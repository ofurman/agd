# V1 – weryfikacja mechaniki kodu RKPROGAGD1026 (euro.com.pl / OleOle!)

**Weryfikator, runda 2. Stan: 25.10.2026, wieczór.**

**Jak sprawdzałem:**
- Regulamin PDF promocji przeczytałem przez r.jina.ai (93 strony). Euro blokuje curl, ale przez proxy działa.
- „Zasady stosowania kodów rabatowych” czytałem przez translate.goog. To pełny tekst z `cms/aktualne-kody-rabatowe`.
- Karty produktów euro i OleOle też czytałem przez translate.goog. Brałem z nich JSON strony: `prices.mainPrice`, `voucherDiscountedPrice`, `lowestPrice` i `voucherDetails` (kod, ważność).
- Dla kontroli porównałem ceny ze skapiec.pl (feed euro/OleOle).
- Niczego nie dodawałem do koszyka i nie logowałem się. **Rabatu w koszyku nie sprawdziłem.**

---

## 1. Regulamin promocji „Nawet do 3000 zł rabatu” (RKPROGAGD1026)

Źródło: [Regulamin_promocja_progowa_AGD_7-31.10.2026.pdf](https://www.euro.com.pl/si_upload/upload_regulaminy/10_2026/Regulamin_promocja_progowa_AGD_7-31.10.2026.pdf)

| # | Teza | Status | Dowód (cytat ≤ 15 słów) |
|---|---|---|---|
| 1.1 | Progi: 1000→100, 2000→250, 3000→400, 5000→750, 9000→1400, 12 000→1900, 16 000+→3000 zł | ✅ | Tabela nr 1: „16 000,00 zł i powyżej 3 000,00 zł” |
| 1.2 | Warunek: min. 2 Produkty Promocyjne, łącznie ≥ 1000 zł, jedno zamówienie | ✅ | pkt I.11: „co najmniej dwóch lub większej liczby wybranych Produktów Promocyjnych w łącznej cenie co najmniej 1000” |
| 1.3 | Maks. 2 szt. tego samego produktu, maks. rabat 3000 zł na transakcję | ✅ | pkt I.10–I.11 |
| 1.4 | Ważność: 07.10.2026 16:00 – **31.10.2026 23:45** (online) | ✅ | pkt I.6.1 |
| 1.5 | Można złożyć kolejne zamówienie i znowu użyć kodu (2 zamówienia = 2 progi) | ✅ | pkt I.10: „Podczas składania kolejnego Zamówienia … Uczestnik może ponownie skorzystać z Promocji” |
| 1.6 | Próg liczony od **aktualnej ceny** produktu (z przeceną, jeśli jest) | ✅ | pkt IV.3: „Rabat naliczany jest od ceny danego Produktu Promocyjnego obowiązującej … w chwili zawarcia umowy” |
| 1.7 | Łączy się z **przecenami** (cena promocyjna bez kodu) | ✅ | pkt IV.6: „Promocja łączy się z aktualnie obowiązującymi u Organizatora przecenami” |
| 1.8 | Łączy się z **innymi kodami** tylko wg „Zasad stosowania kodów” | ✅ | pkt IV.6: „na zasadach określonych w ‘Zasadach stosowania kodów rabatowych…’” |
| 1.9 | Rabat jest rozkładany proporcjonalnie. Zwrot części produktów zmniejsza zwrot pieniędzy | ✅ | pkt IV.2: „Rabat rozkładany jest proporcjonalnie na wszystkie Produkty Promocyjne” |
| 1.10 | Promocja obejmuje tylko euro.com.pl (z COK) i sklepy RTV EURO AGD. **Nie obejmuje OleOle!** | ✅ | pkt I.3: „Promocja organizowana jest w Sklepie Internetowym Organizatora … https://www.euro.com.pl” |

### Załącznik nr 1 – czy obejmuje 9 pozycji

| Pozycja | Indeks euro | W Załączniku 1? |
|---|---|---|
| Piekarnik Whirlpool WOI7A8FHT2SBA | 1342663 | ✅ „PIEKARNIK WOI7A8FHT2SBA WHIRLPOOL” |
| Lodówka Samsung BRB70F30BES0EO | 1339341 | ✅ |
| Płyta Whirlpool WB S2560 NE | 1214156 | ✅ |
| Mikrofala Whirlpool WMD7O4TX | 1342671 | ✅ (na liście są też WMD7O4TB, AMW6440FB, Candy CA38FL7N25WXB) |
| Zmywarka Whirlpool W7I HT58 T | 1292095 | ✅ |
| Okap Amica OTP6651BG | 1208008 | ✅ (Elica Elite 26 IX/A/60, 1353289, też jest) |
| Pralka Samsung WW90CGC04DAE | 1301864 | ✅ |
| Suszarka Samsung DV9MDG52A0AEEO | 1379330 | ✅ |
| Łącznik Samsung SKK-DD | 1113133 | ✅ |
| Łącznik „z panelem LED WW\*\*CG\*\*” = **Samsung SKK-5EW** | 1318804 | ✅ |

**Wynik: ✅ wszystkie 9 pozycji (oba warianty łącznika) są Produktami Promocyjnymi.** Tu `zakup-optimal.md` ma rację.

---

## 2. Mechanika: kod produktowy a kod koszykowy

Źródło: [Zasady stosowania kodów rabatowych (cms/aktualne-kody-rabatowe)](https://www.euro.com.pl/cms/aktualne-kody-rabatowe.bhtml), wersja od 16.03.2026.

| # | Teza | Status | Dowód |
|---|---|---|---|
| 2.1 | Jeden produkt dostaje **jeden** kod: produktowy albo koszykowy | ✅ | „zastosowanie będzie mógł znaleźć tylko jeden z nich tj. jeden wybrany kod” |
| 2.2 | Produkty, które budują próg kodu koszykowego, **nie dostają** kodu produktowego | ✅ | „produkty warunkujące zastosowanie takiego kodu koszykowego … nie będą mogły zostać objęte kodem produktowym” |
| 2.3 | W jednym zamówieniu mogą być kody produktowe i koszykowe, jeśli dotyczą **innych** produktów | ✅ | „kilka kodów produktowych oraz kilka kodów koszykowych o ile obejmują one inne Produkty” |
| 2.4 | Przy aktywnym kodzie koszykowym kod produktowy trzeba **zaznaczyć ręcznie** | ✅ | „naliczenie kodu produktowego wymaga manualnego wprowadzenia, zaznaczenia lub aktywowania” |
| 2.5 | Ceny 1799 / 2489 / 3299 / 1348 / 1698 / 613 zł to ceny **z kodem produktowym**, nie przeceny | ✅ | JSON kart euro: `promotionalPrice: null`, a `voucherDiscountedPrice` ma te kwoty (tabela 3) |
| 2.6 | `zakup-optimal.md`: kod koszykowy od sumy 17 293,99 zł (ceny z kodami) → 14 293,99 zł | ❌ **obalone** | Pkt 2.2 + 2.5. W koszyku z RKPROG produkty mają cenę bez kodu. 9 pozycji kosztuje wtedy 19 293,26 zł, po rabacie **16 293,26 zł**, nie 14 293,99 |
| 2.7 | `euro.com.pl.md`: do kodu koszykowego warto dawać głównie produkty bez kodu produktowego | ⚠️ zasada dobra, wniosek nieoptymalny | Ten raport liczył inny zestaw (Candy + Elica) i wybrał próg 9000 zł (−1400). Dla tego samego zestawu optimum to 14 882,26 zł, nie 15 390 zł (pkt 4) |

---

## 3. Ceny 25.10.2026 (karty produktów, JSON strony)

`main` = cena bez kodu (tę liczy się do progu). `z kodem` = `voucherDiscountedPrice`.

| Pozycja | euro: bez kodu | euro: z kodem | Kod produktowy, ważność | Zysk z kodu | OleOle!: cena | Kod w OleOle |
|---|---|---|---|---|---|---|
| Piekarnik WOI7A8FHT2SBA | 3499,00 | – | – | 0 | 3499,00 | – |
| Lodówka BRB70F30BES0EO | 3699,99 | 3299,00 | REW041026311026C1, do 31.10 23:45 | 400,99 | 3299,00 | – |
| Płyta WB S2560 NE | 1499,00 | 1348,00 | REW2010311026C, do 31.10 | 151,00 | 1348,00 | – |
| Mikrofala WMD7O4TX | **2149,00** | 1698,00 | REW1610311026C1, do 31.10 | 451,00 | 1698,00 | – |
| Zmywarka W7I HT58 T | 2299,99 | – | – | 0 | 2299,00 | – |
| Okap Amica OTP6651BG | **699,99** | 613,00 | RGBF18311026, do 31.10 | 86,99 | 613,00 | – |
| Pralka WW90CGC04DAE | 2299,00 | 1799,00 | RBF2310071226C, **do 07.12.2026** | 500,00 | 1799,00 | – |
| Suszarka DV9MDG52A0AEEO | 2929,99 | 2489,00 | REW1410311026C2, do 31.10 | 440,99 | 2489,00 | – |
| Łącznik SKK-DD | 217,30 | – | – | 0 | 217,30 | – |
| Łącznik SKK-5EW (1318804) | 229,00 | – | – | 0 | 229,00 | – |
| *(wariant) Okap Elica Elite 26 IX/A/60* | 638,99 | – | – | 0 | 638,99 (skapiec) | – |
| *(wariant) Mikrofala Candy CA38FL7N25WXB* | 1099,00 | 799,00 | REW1610311026C1 | 300,00 | – | – |

Źródła (karty): [piekarnik](https://www.euro.com.pl/piekarniki-do-zabudowy/whirlpool-woi7a8fht2sba-termoobieg-termosonda-airfry-czarny.bhtml), [lodówka](https://www.euro.com.pl/lodowki-do-zabudowy/samsung-brb70f30bes0eo-pelny-no-frost-193-5cm-komora-swiezosci-zdalne-sterowanie.bhtml), [płyta](https://www.euro.com.pl/plyty-do-zabudowy/whirlpool-wb-s2560-ne.bhtml), [mikrofala](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/whirlpool-wmd7o4tx-grill.bhtml), [zmywarka](https://www.euro.com.pl/zmywarki-do-zabudowy/whirlpool-w7i-ht58-t-60cm-automatyczne-otwieranie-drzwi-szuflada-na-sztucce.bhtml), [okap Amica](https://www.euro.com.pl/okapy/amica-otp6651bg.bhtml), [pralka](https://www.euro.com.pl/pralki/samsung-pralka-ww90cgc04dae-ecobubble-9-kg-biala.bhtml), [suszarka](https://www.euro.com.pl/suszarki/samsung-dv9mdg52a0aeeo-funkcje-ai-60cm-9kg-zdalne-sterowanie.bhtml), [SKK-DD](https://www.euro.com.pl/laczniki-do-pralek-i-suszarek/bosch-skk-dd.bhtml), [SKK-5EW](https://www.euro.com.pl/laczniki-do-pralek-i-suszarek/samsung-skk-5ew.bhtml). Pod tymi samymi ścieżkami są karty na oleole.pl.
Przykład z karty pralki: „Najniższa cena z 30 dni przed obniżką: 2 299 zł”, kod RBF2310071226C, „Cena z kodem”.

Poprawki do raportów rundy 1:
- ❌ `zakup-optimal.md`: SKK-DD za 249 zł. Na euro i OleOle kosztuje **217,30 zł**.
- ⚠️ `zakup-optimal.md`: cena łącznika 1318804 była „nieznana”. Teraz jest znana: to **SKK-5EW, 229 zł**.
- ✅ Ceny „z kodem” w `euro.com.pl.md` się zgadzają (lodówka, płyta, pralka, suszarka, Candy).

---

## 4. Najtańsza kombinacja w euro.com.pl (pełny przegląd wariantów)

Policzyłem wszystkie 4^9 przypisań. Każda pozycja: kod produktowy albo zamówienie 1, 2 lub 3 z RKPROG.

**Koszyk docelowy** (zestaw z `zakup-optimal.md`: Amica OTP6651BG, WMD7O4TX, SKK-DD):

| Strategia | Suma |
|---|---|
| Tylko kody produktowe (bez RKPROG) | 17 262,29 |
| Wszystkie 9 w RKPROG (19 293,26 − 3000) | 16 293,26 |
| **Optimum: 7 pozycji w RKPROG + 2 z kodem produktowym** | **15 706,27** |
| 2 lub 3 zamówienia | nie są tańsze (najlepsze też 15 706,27) |

### ✅ Poprawny koszyk euro.com.pl (jedno zamówienie)

| Grupa | Pozycja | Cena liczona |
|---|---|---|
| RKPROGAGD1026 | Piekarnik Whirlpool WOI7A8FHT2SBA | 3499,00 |
| RKPROGAGD1026 | Lodówka Samsung BRB70F30BES0EO (bez kodu) | 3699,99 |
| RKPROGAGD1026 | Płyta Whirlpool WB S2560 NE (bez kodu) | 1499,00 |
| RKPROGAGD1026 | Mikrofala Whirlpool WMD7O4TX (bez kodu) | 2149,00 |
| RKPROGAGD1026 | Zmywarka Whirlpool W7I HT58 T | 2299,99 |
| RKPROGAGD1026 | Suszarka Samsung DV9MDG52A0AEEO (bez kodu) | 2929,99 |
| RKPROGAGD1026 | Łącznik Samsung SKK-DD | 217,30 |
| | **Wartość Produktów Promocyjnych** | **16 294,27** (≥ 16 000) |
| | **Rabat RKPROGAGD1026** | **−3000,00** |
| | Po rabacie | 13 294,27 |
| Kod produktowy RBF2310071226C (zaznaczyć ręcznie) | Pralka Samsung WW90CGC04DAE | 1799,00 |
| Kod produktowy RGBF18311026 (zaznaczyć ręcznie) | Okap Amica OTP6651BG | 613,00 |
| | **DO ZAPŁATY** | **15 706,27 zł** |

- Łącznik może być w grupie RKPROG albo osobno, cena ta sama. **Zostaw go w grupie.** Zapas nad progiem rośnie wtedy z 76,97 do 294,27 zł. Bez łącznika wystarczy, że jedna cena spadnie o 77 zł, i rabat spada do 1900 zł.
- Z łącznikiem SKK-5EW (1318804) zamiast SKK-DD: **15 717,97 zł** (+11,70).
- Dlaczego pralka i okap są poza grupą: kod produktowy daje na nich 500 i 87 zł. Na pozostałych pozycjach kod produktowy daje mniej niż wynosi rabat z progu. Bez nich grupa spadłaby poniżej 16 000 zł.
- Cashbacki producentów (Whirlpool 750 zł, Samsung 400 zł wg `zakup-optimal.md`) **nie były tu weryfikowane**. Jeśli są prawdziwe, netto wynosi ok. **14 556 zł**, a nie 13 144 zł.
- Wariant z `euro.com.pl.md` (Candy zamiast WMD7O4TX, Elica zamiast Amica) przy tej samej metodzie kosztuje **14 882,26 zł**. Grupa RKPROG = piekarnik, lodówka, płyta, zmywarka, pralka, suszarka (16 226,97). Kod produktowy na Candy 799, Elica 638,99 i SKK-DD 217,30. To o 508 zł mniej niż 15 390 zł z tamtego raportu. Zmiana dotyczy jednak innych produktów (MUST mikrofali i okapu do oceny gdzie indziej).

---

## 5. OleOle!

| # | Teza | Status | Dowód |
|---|---|---|---|
| 5.1 | RKPROGAGD1026 działa w OleOle! | ❌ | Regulamin pkt I.3 wskazuje tylko euro.com.pl i sklepy RTV EURO AGD. Na kartach OleOle brak plakietki „Nawet 3000 zł rabatu” (sprawdzone na 10 kartach) |
| 5.2 | OleOle! ma własną, podobną promocję progową AGD | ❌ (nie znaleziono) | [oleole.pl/cms/promocje](https://www.oleole.pl/cms/promocje.bhtml) pokazuje tylko cashbacki producentów („Do 3000 zł zwrotu” to Whirlpool i Bosch). `cms/aktualne-kody-rabatowe` zwraca 404. PDF regulaminu pod ścieżką OleOle zwraca 404 |
| 5.3 | Ceny w OleOle! = ceny euro z kodem, bez żadnego kodu | ✅ | JSON kart OleOle: `mainPrice` 3299 / 1348 / 1698 / 613 / 1799 / 2489, `voucherDetails: null` |
| 5.4 | Koszyk 9 pozycji w OleOle! | ✅ wyliczone | 3499 + 3299 + 1348 + 1698 + 2299 + 613 + 1799 + 2489 + 217,30 = **17 261,30 zł**, o 1555 zł drożej niż euro z optymalnym RKPROG |

---

## 6. Ryzyka i co sprawdzić w koszyku

1. **Rabatu nie sprawdzono w koszyku.** Wyliczenie opiera się na regulaminie, „Zasadach” i JSON kart.
   - Po wpisaniu RKPROGAGD1026 musisz zobaczyć **−3000 zł** na 7 pozycjach.
   - Potem ręcznie zaznacz kody produktowe na pralce i okapie.
   - Kontrolna suma: **15 706,27 zł**.
2. Kody produktowe na lodówce, płycie, mikrofali, suszarce i okapie oraz RKPROG wygasają **31.10.2026 23:45**. Kod na pralkę działa do 07.12.
3. Zapas nad progiem to 294,27 zł. Jeśli przed zakupem coś stanieje (przecena), sprawdź, czy suma grupy nadal wynosi co najmniej 16 000 zł.
4. Zwrot jednej pozycji z grupy RKPROG zwraca jej cenę pomniejszoną o proporcjonalną część rabatu (pkt IV.9).
