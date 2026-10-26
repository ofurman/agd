# euro.com.pl / oleole.pl — promocje koszykowe vs kod 3000 zł (2026-10-25)

Zakres: czy którakolwiek promocja koszykowa („5. produkt za 1 zł”, „drugi produkt −40%”, progi, „X za Y”) bije rabat **3 000 zł** z kodu `RKPROGAGD1026` i czy da się ją z nim połączyć oraz z cashbackami producentów.
Koszyk wzorcowy: 9 pozycji, **17 293,99 zł** brutto (ceny z 25.10.2026, statusy jak w `euro.com.pl.md`), cashbacki **750 zł Whirlpool + 400 zł Samsung = 1 150 zł**.

## 0. Test koszyka na żywo (26.10.2026, Arc) — nadpisuje wnioski z 25.10

Koszyk został realnie zbudowany w Arc (9 pozycji), a kod wpisany w polu „Wpisz kod rabatowy”. Wynik:

| Krok | Obserwacja |
|---|---|
| Koszyk 9 poz. z ADF0, bez promocji | **19 533,25 zł** |
| „Piąty produkt za 1 zł” (auto) | 19 316,95 zł (−216,30) |
| **`RKPROGAGD1026`** | modal „promocje nie łączą się”; po aktywacji **−3 000,00 → 16 533,25 zł** |
| Cashback | Whirlpool 750 + Samsung 700 (200+200+300 ADF0) = **1 450 zł** |
| **Netto** | **15 083,25 zł** |

- Kod **działa** i nadal daje pełne −3 000 (baza ≥16 000), ale **zastępuje** BLACK FRIDAY / EURO WJECHAŁO / „Piąty produkt za 1 zł”. Nie da się ich sumować — mechanika z pkt II.8.1 potwierdzona empirycznie.
- Na koszyku z BES0 auto-promocje dawały 17 440,27 zł (z „Piątym” 17 266,43), a kod 15 933,25 zł. Realna przewaga kodu: **1 507,02 / 1 333,18 zł**, a nie 3 000 zł.
- Koszyk bez lodówki (8 poz.) = **13 333,26 zł** przy bazie 16 333,26 zł — próg 16 000 nadal trzyma, ale z zapasem tylko 333,26 zł.
- Wnioski z sekcji 1–9 (ceny z 25.10, brak testu koszyka) są historyczne. Nie planuj wariantów (h)/(i) — nie są osiągalne.


## Jak zdobyto dane (i czego nie udało się zrobić)

| Źródło | Status dostępu |
|---|---|
| Regulamin **WIEL** `…/upload_regulaminy/05_2026/Regulamin_Programu_Wielosztuki_30_55_80_1zl.pdf` (6 str.) | ✅ pobrany i przeczytany w całości (25.10.2026) |
| Regulamin **`RKPROGAGD1026`** `…/10_2026/Regulamin_promocja_progowa_AGD_7-31.10.2026.pdf` (93 str. z Załącznikiem nr 1) | ✅ pobrany i przeczytany w całości |
| **„Zasady stosowania kodów rabatowych…”** (brzmienie od 16.03.2026) | ✅ pełny tekst z archiwum Wayback (snapshot 18.06.2026); wersja live na euro.com.pl zwraca 403 |
| Strona **/cms/promocje.bhtml** (indeks wszystkich aktualnych akcji) | ✅ archiwum Wayback, snapshot **24.10.2026** — to najlepsze „live” źródło listy promocji |
| Strona **/cms/piaty-za-1-zl.bhtml** | ✅ odczytana na żywo (25.10.2026) przed blokadą |
| Karty produktów, koszyk, strona 50/500, Whirlpool Days | ❌ HTTP 403 (Akamai, blokada na IP). **Nie obchodziłem zabezpieczenia** — brak testu koszyka |

Konsekwencja: **nie udało się empirycznie sprawdzić, czy koszyk przyjmie dwa kody naraz.** Poniżej rozdzielam to, co wynika z regulaminów (twarde), od tego, co wymaga kliknięcia w koszyku.

---

**KOREKTA (25.10, 23:50):** lista Whirlpool Days „−40%” **nie obejmuje** WOI7A8FHT2SBA, W7I HT58 T ani WMD7O4TX — kwalifikuje się tylko płyta WB S2560 NE. Na naszym koszyku rabat = **0 zł** (brak drugiego produktu z listy). Wiersz poniżej pokazuje wariant teoretyczny, nie nasz koszyk.

## 1. Tabela promocji

| Promocja | Mechanika (dokładnie) | Rabat na naszym koszyku | Łączenie z 3000 zł | Łączenie z cashbackiem | Ważność | Źródło | Werdykt |
|---|---|---|---|---|---|---|---|
| **`RKPROGAGD1026`** „Nawet do 3000 zł rabatu” | Min. **2 produkty** z Zał. 1, wartość ≥1 000 zł; progi: 1 000→100 · 2 000→250 · 3 000→400 · 5 000→750 · 9 000→1 400 · 12 000→1 900 · **16 000+→3 000**. Max 2 szt. tego samego produktu. Rabat rozkładany proporcjonalnie na produkty. | **−3 000,00** | — (to baza) | Tak | 07.10.2026 16:00 – **31.10.2026 23:45** | regulamin PDF, pkt II.2 + Tabela nr 1 | **Wygrywa** |
| **`WIEL`** „5. produkt za 1 zł” / Wielosztuki 30-55-80-1 | **2 prod. → −30% tańszego · 3 → −55% najtańszego · 4 → −80% najtańszego · 5+ → najtańszy za 1 zł.** Rabat na **jeden** produkt, max **1 szt.**, jedna transakcja, min. **2 różne** produkty. Program można powtarzać w kolejnych zamówieniach. | 1 transakcja: **−612,00** (lub −248,00 — patrz §3). Podział 4+3+2: **−2 656,09** | ❌ regulaminowo nie (dwa kody koszykowe na te same produkty) | Tak (regulamin nie wyklucza) | od 31.05.2026 **do odwołania** (min. 3 dni wypowiedzenia) | regulamin PDF pkt II.2, II.1; strona live | **Przegrywa z 3 000** |
| **„50 zł za każde wydane 500 zł”** (rabat progowy) | Min. **2 różne produkty** objęte promocją, zakupy ≥500 zł; **50 zł za każde 500 zł**, drabinka do **2 000 zł od 20 000 zł**; implementacja: **kod produktowy naliczany automatycznie** w koszyku | ~**−1 700,00** (17 293,99 → przedział 17 000–17 499,99) | ❌ **nie** — pkt II.8.1 Zasad: przy aktywnym kodzie koszykowym produkty warunkujące go nie mogą dostać kodu produktowego (patrz §5) | Tak | **do 03.11.2026** (wg indeksu promocji) | indeks promocji 24.10.2026 + archiwum strony (edycja 12.2025) | **Solo przegrywa z 3 000** (1 700 < 3 000); łączenie wykluczone |
| **Whirlpool Days „Drugi tańszy 40% taniej”** | Min. **2 różne produkty Whirlpool** z listy, **−40% ceny tańszego**; kod koszykowy (w edycji majowej `RKWHIRL40PR0526`) | **0 zł na naszym koszyku** — lista obejmuje tylko płytę WB S2560 NE; WOI7A8FHT2SBA, W7I HT58 T i WMD7O4TX są poza listą. Teoretycznie, gdyby wszystkie 4 były objęte: −1 459,20 | ❌ kod koszykowe na te same produkty | Tak | **do 26.10.2026** | indeks promocji 24.10.2026 (tekst oficjalny; lista modeli) + archiwum strony Whirlpool Days (mechanika) | **Nie dotyczy / przegrywa** |
| **Whirlpool Days „Płyta 50% taniej przy piekarniku”** | Wybrany piekarnik Whirlpool + wybrana płyta → **−50% ceny płyty** | **−674,00** (1 348 × 50%) | ❌ | Tak | **do 26.10.2026** | indeks promocji 24.10.2026; mechanika analogiczna do archiwalnej edycji | **Przegrywa** |
| Whirlpool Days „Pralka 50% taniej przy suszarce” | pralka + suszarka **Whirlpool** | 0 — nasza pralka i suszarka to Samsung | — | — | do 26.10.2026 | indeks promocji | **Nie dotyczy** |
| Samsung „Płyta do zabudowy za 1 zł” | piekarnik **Samsung** + zmywarka **Samsung** → płyta za 1 zł | 0 — nie mamy piekarnika ani zmywarki Samsunga | — | — | do 31.10.2026 | indeks promocji | **Nie dotyczy** |
| „Nawet do 7 500 zł rabatu” / „do 7 000 zł” (drabinka ogólna) | Min. 500 zł → 35 zł, **max 7 500 zł przy 50 000 zł** (drabinka „kupuj więcej”) | progi nieodczytane — przy 17,3 tys. **< 3 000** | ⚠️ nieustalone | Tak | wg indeksu: akcja bieżąca (bez twardej daty w snippecie) | snippet euro.com.pl `/cms/nawet-do-7500zl-rabatu.bhtml` | **Nie bije** (do potwierdzenia) |
| Codebacki („100 zł za 1000 zł”, „50 zł na kolejne zakupy”) | **Voucher na przyszłe zakupy**, nie rabat na ten koszyk | 0 zł na tym koszyku | nie dotyczy | — | różne | regulaminy euro | **Nie na ten koszyk** |

---

## 2. `RKPROGAGD1026` — potwierdzone na dziś

- Okres: **07.10.2026 16:00 → 31.10.2026 23:45** (zostało 6 dni). Rabat „od razu w koszyku”.
- Próg **16 000 zł → 3 000 zł** jest progiem maksymalnym; **maks. rabat na jedną transakcję to 3 000 zł**.
- Załącznik nr 1 (93-stronicowy PDF) — **wszystkie 9 pozycji jest na liście** (sprawdzone po nazwie modelu):
  piekarnik WOI7A8FHT2SBA (PLU 1342663), lodówka BRB70F30BES0EO (1339341), płyta WB S2560 NE (1214156), okap OTP6651BG, mikrofalówka WMD7O4TX, zmywarka W7I HT58 T, pralka WW90CGC04DAE, suszarka DV9MDG52A0AEEO, łącznik SKK-DD (1113133).
- Wykluczenia: Outlet, Annopol, towary uszkodzone/niepełne; max 2 szt. tego samego modelu.

**Zasada łączenia (pkt IV.6 regulaminu):** kod „może się połączyć z innymi kodami rabatowymi […] **na zasadach określonych w „Zasadach stosowania kodów rabatowych”**”.

---

## 3. `WIEL` — mechanika bez marketingu

Cytat z regulaminu (pkt II.2), dokładnie:

- 2 produkty → „obniżkę ceny jednego, **tańszego** nabywanego Produktu o **30 %**”
- 3 produkty → „obniżkę ceny jednego, **najtańszego** […] o **55 %**”
- 4 produkty → „o **80 %**”
- **5 i więcej** → „obniżkę ceny jednego, **najtańszego** nabywanego Produktu **do kwoty 1 zł brutto**”

Czyli **nie ma „piątego najtańszego”** — rabat idzie na **najtańszy produkt w koszyku**. Strona euro potwierdza: *„Rabat naliczy się na najtańszy produkt w programie”*. Nazwa „piąty najtańszy za 1 zł” to marketing; dla koszyka 9-pozycyjnego różnica jest kolosalna (249–613 zł zamiast ~1 348 zł).

Pozostałe warunki: **1 produkt z rabatem, max 1 szt.**, jedna transakcja, min. **2 różne** produkty, wykluczone Outlet / Annopol / towary uszkodzone. Program działa też w salonach i przez COK. **WIEL jest „koszykowym kodem rabatowym”** (tak nazwany w pkt II.2 regulaminu) — to kluczowe dla łączenia.

### Co jest w programie
Lista to linki per kategoria (piekarniki do zabudowy, płyty, okapy, mikrofalówki do zabudowy, zmywarki, pralki, suszarki, lodówki do zabudowy itd.). Kategorii **„łączniki / akcesoria”** na liście **nie ma** — dlatego łącznik SKK-DD (249 zł) traktuję jako **prawdopodobnie poza programem** (⚠️ niepotwierdzone bezpośrednio).
Potwierdzone oznaczenie „PIĄTY PRODUKT ZA 1 ZŁ!” ma **lodówka BRB70F30BES0EO** (migawka listingu euro). Dla pozostałych 7 modeli obecności w programie **nie potwierdziłem** (karty produktów 403).

### Rabat WIEL na naszym koszyku (17 293,99 zł)

| Scenariusz | Rabat | Brutto po rabacie | Netto po cashbacku 1 150 zł |
|---|---|---|---|
| 1 transakcja, łącznik **poza** programem (najtańszy = okap 613) | **−612,00** | 16 681,99 | 15 531,99 |
| 1 transakcja, łącznik **w** programie (najtańszy = 249) | **−248,00** | 17 045,99 | 15 895,99 |
| **Podział 4+3+2** (9/9 w programie): 80%×2 299,99 + 55%×1 348 + 30%×249 | **−2 656,09** | 14 637,90 | 13 487,90 |
| **Podział 4+2+2** (8 pozycji bez łącznika) | **−2 533,29** | 14 760,70 | 13 610,70 |

Podział jest dozwolony w sensie programowym („podczas składania kolejnego Zamówienia Uczestnik może ponownie skorzystać z Programu”), ale **każde zamówienie to osobna transakcja**, więc traci się kod 3000 zł (wymaga 16 000 zł w jednej transakcji).

**Najlepszy wynik WIEL = 2 656,09 zł < 3 000 zł.**

---

## 4. „Drugi produkt −40%” — istnieje, ale nie u nas

- **Tak, jest taka promocja**: **Whirlpool Days – „Drugi tańszy 40% taniej”**, euro.com.pl `/cms/whirlpool-days-najtanszy-40proc.bhtml`, **do 26.10.2026** (czyli jutro). Opis oficjalny: *„Kup min 2 produkty a na tańszy otrzymasz 40% rabat”*.
- Mechanika (z archiwalnej, bliźniaczej edycji tej samej akcji): min. **2 różne produkty Whirlpool** objęte promocją w jednym koszyku, **−40% ceny najtańszego z nich**, realizowane **kodem koszykowym** (`RKWHIRL40PR…`; w edycji majowej `RKWHIRL40PR0526` — kod bieżącej edycji **niepotwierdzony**).
- **Lista modeli:** akcja **nie obejmuje** WOI7A8FHT2SBA, W7I HT58 T ani WMD7O4TX; kwalifikuje się **tylko płyta WB S2560 NE**. Potrzeba 2 produktów → **na naszym koszyku rabat = 0 zł**.
- Teoretycznie, gdyby wszystkie 4 były objęte: jedna transakcja → 539,20 (40% z płyty, bo najtańsza); dwie transakcje (piekarnik+zmywarka → 920,00; płyta+mikrofalówka → 539,20) → **1 459,20**. To **nie jest nasz koszyk**.
- Równolegle trwa (do 26.10) **„Płyta 50% taniej przy zakupie piekarnika Whirlpool”** → **−674,00** — dla nas korzystniejsze od pary −40%.
- W euro i OleOle **nie ma** ogólnokoszykowej akcji „drugi produkt −40%”. Historycznie były inne warianty (np. „drugi −25% / trzeci −40% / czwarty −70%” w starych edycjach, „drugi produkt za 1 zł” do 2025 r.) — dziś zastąpił je WIEL 30/55/80/1 zł.

---

## 5. Czy da się połączyć WIEL (lub 40%) z kodem 3000 zł?

**Regulaminowo: nie na tym koszyku.** „Zasady stosowania kodów rabatowych” (brzmienie od 16.03.2026), pkt II.8.1:

> „…można zastosować **kilka kodów produktowych oraz kilka kodów koszykowych o ile obejmują one inne Produkty**; w przypadku gdy dany Produkt objęty jest więcej niż jednym kodem […] zastosowanie będzie mógł znaleźć **tylko jeden z nich** […]; **jeżeli został zastosowany kod koszykowy, to również produkty warunkujące zastosowanie takiego kodu koszykowego […] nie będą mogły zostać objęte kodem produktowym**”.

- `RKPROGAGD1026` i `WIEL` to **oba kody koszykowe** i oba obejmują **te same 9 produktów** (kod 3000 rozkłada rabat proporcjonalnie na wszystkie produkty promocyjne — pkt IV.2). Zgodnie z II.8.1 na jednym produkcie może zadziałać tylko jeden z nich.
- To samo dotyczy kodu Whirlpool Days −40% i „płyty −50%”.
- **Zastrzeżenie:** to wykładnia regulaminu, a nie test koszyka. **Nie mogłem sprawdzić zachowania koszyka** (403). Jeśli koszyk pozwoli wpisać drugi kod, sprawdź, czy rabat 3000 nie spadnie z progu (po WIEL koszyk 16 681,99 zł — próg 16 000 nadal trzyma).

### „50 zł za każde wydane 500 zł” — dlaczego **nie** dołoży się do 3 000 zł

**Nazwa i mechanika (potwierdzone).** Indeks promocji euro (snapshot **24.10.2026**): *„50 zł za każde wydane 500 zł — Rabat naliczamy od razu!”*, ważne **do 03.11.2026**. Pełna, identycznie opisana edycja tej akcji (strona archiwalna **02.12.2025**, tekst „rabat od razu”):

- min. **2 różne produkty objęte promocją**, wartość zakupów **≥ 500 zł**;
- drabinka: **50 zł** (500–999,99) · 100 zł (1 000–1 499,99) · 150 zł (1 500–1 999,99) · … · **2 000 zł od 20 000 zł**;
- *„Kod rabatowy naliczy się **automatycznie** w koszyku”*;
- lista „produktów objętych promocją” jest **produktowa** (badge na karcie: „50 zł za każde wydane 500 zł — Na produkty objęte promocją”), nie koszykowa.

Na naszym koszyku 17 293,99 zł → przedział 17 000–17 499,99 → **1 700 zł**.

**Dlaczego się nie sumuje.** To **kod produktowy naliczany automatycznie** — Zasady, pkt I.1.1: *„kod produktowy zastosuje się automatycznie w Sklepie Internetowym…”*. Wtedy działa pkt **II.8.1, zdanie ostatnie**:

> „…**jeżeli został zastosowany kod koszykowy, to również produkty warunkujące zastosowanie takiego kodu koszykowego, na które nie został udzielony rabat, nie będą mogły zostać objęte kodem produktowym**”.

`RKPROGAGD1026` jest kodem koszykowym, a **wszystkie 9 pozycji warunkuje jego zastosowanie** (próg 16 000 zł i min. 2 produkty liczone z tych właśnie pozycji). Po jego wpisaniu **żadna z tych 9 pozycji nie może dostać automatycznego rabatu 50/500**. Wynik: w jednej transakcji dostajesz **albo 3 000 zł, albo ~1 700 zł** — nigdy oba.

**Test koszyka: niewykonalny.** Od ≈23:00 cała domena euro.com.pl zwraca 403 na to IP — sprawdzone na `/cms/50-za-500.bhtml`, `/api/`, `/api/v1/products`, `/robots.txt`, `/sitemap.xml`, `/energy-label.ltr` (wszystkie 403; wcześniej działały tylko pliki PDF i to okno się zamknęło). Zabezpieczenia **nie obchodziłem** — zgodnie z poleceniem.

---

## 6. Warianty — pełne wyliczenie

| Wariant | Rabat | Brutto | Netto po cashbacku | vs 13 143,99 |
|---|---|---|---|---|
| **(a) tylko `RKPROGAGD1026`** | −3 000,00 | **14 293,99** | **13 143,99** | **baza** |
| (b) tylko WIEL, 1 transakcja (okap najtańszy) | −612,00 | 16 681,99 | 15 531,99 | +2 388,00 |
| (b′) tylko WIEL, 1 transakcja (łącznik w programie) | −248,00 | 17 045,99 | 15 895,99 | +2 752,00 |
| (c) tylko WIEL, podział 4+3+2 | −2 656,09 | 14 637,90 | 13 487,90 | +343,91 |
| (c′) tylko WIEL, podział 4+2+2 (bez łącznika) | −2 533,29 | 14 760,70 | 13 610,70 | +466,71 |
| (d) 3000 + WIEL (gdyby koszyk przyjął; okap) | −3 612,00 | 13 681,99 | **12 531,99** | −612,00 |
| (d′) 3000 + WIEL (łącznik) | −3 248,00 | 14 045,99 | 12 895,99 | −248,00 |
| (e) Whirlpool −40% — **na naszym koszyku 0** (tylko płyta na liście); teoretycznie 2 transakcje | 0 / −1 459,20 | — | — | nie dotyczy |
| (f) tylko Whirlpool „płyta −50%” | −674,00 | 16 619,99 | 15 469,99 | +2 326,00 |
| (g) tylko 50/500 (drabinka 50 zł/500 zł) | −1 700,00 | 15 593,99 | 14 443,99 | +1 300,00 |
| (h) 3000 + 50/500 ❌ **regulaminowo wykluczone** (rachunek kontrolny) | −4 700,00 | 12 593,99 | 11 443,99 | −1 700,00 |
| (i) 3000 + WIEL + 50/500 ❌ **wykluczone** (rachunek kontrolny) | −5 312,00 | 11 981,99 | 10 831,99 | −2 312,00 |

Warianty (h) i (i) **nie są osiągalne**: Zasady, pkt II.8.1 wykluczają automatyczny rabat produktowy na produktach warunkujących kod koszykowe 3000. Podaję je wyłącznie jako rachunek kontrolny („co by było, gdyby”). **Realny najlepszy wynik to 13 143,99 zł netto.**

---

## 7. Werdykt

1. **Żadna promocja koszykowa nie bije 3 000 zł na tym koszyku.** Maksima: WIEL **2 656,09 zł** (tylko przy dzieleniu na 3 transakcje), Whirlpool Days **0 zł na naszym koszyku** (teoretycznie 1 459,20 przy hipotetycznym zestawie 4 objętych produktów), „50/500” **~1 700 zł**, drabinka „do 7 500” przy 17,3 tys. zł — poniżej 3 000.
2. **`WIEL` jest wyraźnie gorszy, niż sugeruje nazwa** — rabat idzie na *najtańszy* produkt (249–613 zł), a nie na „piąty najtańszy” (1 348 zł). W jednej transakcji z 9 pozycjami daje **612 zł** (lub 248 zł, jeśli łącznik jest w programie).
3. **Łączenie z kodem 3000 zł: regulaminowo nie** — oba są kodami koszykowymi obejmującymi te same produkty (Zasady, pkt II.8.1). To samo dotyczy −40% Whirlpool.
4. **Cashbacki są niezależne od kodów** — Whirlpool wprost „łączy się z kodami sklepowymi”, Samsung rozlicza kwoty modelowe (200 + 200), a BRB70F30BES0EO w ogóle nie ma cashbacku. Rabaty nie zmniejszają kwot zwrotu. Jedyne zastrzeżenie: nagroda Whirlpool > 2 000 zł w jednym zgłoszeniu → 10% podatku (nas nie dotyczy: 350 + 200 + 200).
5. **„50 zł za 500 zł” (do 03.11) NIE dołoży się do kodu 3000.** To kod produktowy naliczany automatycznie („Kod rabatowy naliczy się automatycznie w koszyku”), a Zasady pkt II.8.1 zabraniają objęcia kodem produktowym produktów warunkujących aktywny kod koszykowe — u nas warunkuje go wszystkie 9 pozycji. Arytmetyka „17 293,99 − 3 000 − 1 700 − 1 150 = **11 443,99 zł**” jest więc **nieosiągalna**; to wyłącznie rachunek kontrolny. Solo 50/500 daje 15 593,99 zł brutto i **14 443,99 zł netto** — o 1 300 zł gorzej niż kod 3000.
6. **Werdykt jednoznaczny: kupuj jednym koszykiem z `RKPROGAGD1026`. 13 143,99 zł netto to najlepszy dostępny wynik w euro.com.pl / OleOle!** Żadna kombinacja promocji koszykowych go nie poprawia.

### Co zrobić w koszyku (5 minut, przed 31.10.2026 23:45)
1. Wrzuć 9 pozycji, wpisz `RKPROGAGD1026` → **musi pokazać −3 000,00** (a nie −1 900).
2. Jeśli zamiast −3 000 widzisz ~−1 700, to znaczy, że koszyk wybrał automatyczne „50 zł za 500 zł” — **wróć do kodu 3000**. Oba rabaty na tych samych produktach nie zadziałają (Zasady, pkt II.8.1).
3. Opcjonalnie sprawdź `WIEL` jako drugi kod — koszyk powinien odmówić albo podmienić rabat. Jeśli każe wybrać jeden — **zostaw 3000**.
4. **Nie dziel koszyka** — podział na 4+3+2 pod WIEL daje 2 656 zł, ale traci 3 000 zł.

## 8. Czego nie potwierdziłem (do domknięcia w koszyku/COK 855 855 855)

- czy wszystkie 9 modeli jest na liście produktów objętych „50 zł za 500 zł” (mechanika, drabinka i limit 2 000 zł — potwierdzone; sama lista produktów — nie),
- czy łącznik SKK-DD i pozostałe 7 modeli są w programie WIEL (potwierdzona tylko lodówka),
- czy koszyk przyjmie `RKPROGAGD1026` + `WIEL` jednocześnie i jak rozliczy próg,
- mechanika i kod bieżącej edycji Whirlpool Days −40% (edycja majowa: `RKWHIRL40PR0526`),
- progi drabinki „Nawet do 7 500 zł rabatu” dla koszyka 17,3 tys. zł.

## 9. Źródła

| Dokument | Link | Status |
|---|---|---|
| Regulamin WIEL (30/55/80/1 zł), 6 str. | `https://www.euro.com.pl/si_upload/upload_regulaminy/05_2026/Regulamin_Programu_Wielosztuki_30_55_80_1zl.pdf` | ✅ odczytany |
| Regulamin `RKPROGAGD1026` + Zał. 1 | `https://www.euro.com.pl/si_upload/upload_regulaminy/10_2026/Regulamin_promocja_progowa_AGD_7-31.10.2026.pdf` | ✅ odczytany |
| Zasady stosowania kodów rabatowych (od 16.03.2026) | `https://www.euro.com.pl/cms/aktualne-kody-rabatowe.bhtml` (treść: Wayback 18.06.2026) | ✅ (archiwum) |
| Indeks promocji euro (data snapshotu 24.10.2026) | `https://www.euro.com.pl/cms/promocje.bhtml` (Wayback 24.10.2026) | ✅ (archiwum) |
| Strona WIEL | `https://www.euro.com.pl/cms/piaty-za-1-zl.bhtml` | ✅ live 25.10.2026 |
| Whirlpool Days −40% | `https://www.euro.com.pl/cms/whirlpool-days-najtanszy-40proc.bhtml` | ⚠️ tylko tytuł/opis z indeksu, mechanika z edycji majowej |
| 50 zł za 500 zł | `https://www.euro.com.pl/cms/50-za-500.bhtml` | ⚠️ indeks promocji 24.10.2026 (nazwa, „rabat od razu”, 03.11) + archiwum edycji 02.12.2025 (drabinka, limit, automatyczne naliczanie); lista produktów niepotwierdzona |
| Drabinka „do 7 500 zł” | `https://www.euro.com.pl/cms/nawet-do-7500zl-rabatu.bhtml` | ⚠️ snippet |
