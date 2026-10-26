# Koszyk przez kanały oficjalne i Allegro — czy coś bije 3000 zł z euro.com.pl (2026-10-25)

> **Snapshot sprzed decyzji 26.10.2026 (WBS2560NE + LFP326FW).** Aktualny wybór: CIV634 + LFG716R; koszyk netto 16 193,25 / 15 663,44 — patrz `README.md`. Poniższe sumy są historyczne.

**Pytanie:** czy promocja koszykowa „5. produkt za 1 zł / darmo”, „drugi produkt −40%” albo inna akcja w **whirlpool.pl**, **samsung.pl** lub na **Allegro** daje więcej niż **−3000 zł** z kodu `RKPROGAGD1026`, i czy da się ją połączyć z tym kodem oraz cashbackami producentów.

**Odpowiedź w jednym zdaniu:** **nie.** Żadna sprawdzona promocja w tych trzech kanałach nie przekracza 3000 zł, a każda, która wymaga rozbicia koszyka, **kasuje próg 16 000 zł** w euro — czyli traci się 3000 zł, żeby zyskać 100–678 zł.

**Punkt odniesienia (potwierdzony w `euro.com.pl.md`):** brutto 17 293,99 zł − 3000 zł (kod) − 1150 zł (cashback Whirlpool 750 + Samsung 400) = **13 143,99 zł netto**, jedna transakcja, kod ważny do **31.10.2026 23:45**.

**Jak sprawdzałem:** whirpool.pl i samsung.pl czytane na żywo (ceny z API katalogowego i stron produktowych), Allegro — tylko strony `/pomoc` i `help.allegro.com` (listingi i karty produktów nadal **HTTP 403 DataDome**; nie obchodziłem zabezpieczenia). Ceny Allegro pochodzą z migawek i są oznaczone `niepotwierdzone (snippet)`.

---

## 1. Tabela zbiorcza

| Promocja | Mechanika (dokładnie) | Rabat na naszym koszyku | Łączenie z kodem 3000 zł | Łączenie z cashbackiem producenta | Ważność | Źródło | Werdykt |
|---|---|---|---|---|---|---|---|
| **Whirlpool.pl „500 zł rabatu za każde 2000 zł zakupu”** (klastry `500za2000`) | Regulamin bieżącej edycji **nie istnieje**. Mechanika z ostatniej edycji (Black Friday 2024): min. **2 różne produkty promocyjne**, kod w koszyku, progi: 2000–3999,99 → −500; 4000–5999,99 → −1000; 6000–7999,99 → −1500; 8000–9999,99 → −2000; 10000–11999,99 → −2500; 12000–13999,99 → −3000; 14000–15999,99 → −3500; **≥16 000 → −4000 (cap)**. Maks. 1 szt./produkt, maks. 3 zamówienia. Rabat **nie łączy się z innymi promocjami cenowymi ani kodami** w whirlpool.pl. | **0 zł** — promocja nie nalicza się (symulacja koszyka: 9066 zł, `rateAndBenefitsIdentifiers: []`). Gdyby działała: −2000 zł przy 4 produktach Whirlpoola; **−500 zł**, gdyby liczyły się tylko 2 produkty z klastrem (płyta 1429 + zmywarka 2319 = 3748). | Nie (inny sklep; kod euro wymaga jednej transakcji ≥16 000 zł) | Whirlpool TAK (regulamin cashbacku nie wyklucza rabatów sklepu, liczy się dowód zakupu) | Brak bieżącego regulaminu; lista regulaminów kończy się na **2024**, wszystkie „Promocja zakończona” | [whirlpool.pl/regulaminy-promocji](https://www.whirlpool.pl/regulaminy-promocji) (live) + [PDF BF 2024](https://whirlpool.pl/assets/vtex.file-manager-graphql/images/04ba4a18-5623-4e43-9631-846000e3027f___48c36c415ef4e52acb9053d85a7ca45c.pdf) + symulacja koszyka 25.10.2026 | **NIEAKTYWNA** — nie liczyć w koszyku. Klaster `500za2000` to pozostałość po 2024 r. |
| **Samsung.pl „Multirabaty” — kod `MULTI`** | Rabat **na najtańszy produkt**, zależy od liczby **różnych grup produktowych**: 2 grupy → **−30% tańszego**, 3 → **−55% najtańszego**, 4 → **−80% najtańszego**, 5 → **najtańszy za 1 zł**. Maks. **1 szt. z jednej grupy** (pralka i suszarka to **jedna** grupa „Pralki i Suszarki”!). Jedno obniżenie na zamówienie. Łączy się **wyłącznie** z kodem `INSTALACJA`. | **−677,70 zł** (30% × pralka 2259 zł) na podzbiorze Samsunga, ale **tylko po rozbiciu** na osobne zamówienie lodówka+pralka. Przy całym koszyku w euro: **0 zł**. | Nie — inny sklep, a rozbicie zabija próg 16 000 zł | **Formalnie NIE** — §3.5: „w pozostałym zakresie Program nie łączy się z innymi programami, promocjami…”. Regulamin cashbacku Samsunga tego nie zakazuje, więc praktyka niepewna | Od **12.05.2026 do odwołania** (2 tyg. wypowiedzenia) | [samsung.com/pl/offer/promocja-agd](https://www.samsung.com/pl/offer/promocja-agd/) (live) + [PDF regulaminu](https://images.samsung.com/is/content/samsung/assets/pl/regulaminy_2026/Program_Multirabaty_na_tanszy_Produkt_w_Sklepie_Samsung.pdf) (przeczytany) | **Za słaba** — maks. 678 zł i tylko na części koszyka |
| **Allegro — kampania „Electro AGD”, kod `AGD100`** | **−100 zł** przy zamówieniu **≥2500 zł**, na wybrane produkty **klasy energetycznej A** z kategorii: lodówki, pralki, pralko-suszarki, suszarki, zamrażarki, zmywarki (wolnostojące i do zabudowy). Kod **przyznawany w osobnej komunikacji** (nie jest publiczny). Rabat finansuje Allegro. | **−100 zł** — w koszyku jest pralka Samsung klasy A, a zamówienie >2500 zł | Nie (inny sklep) | Tak — to kod Allegro, cashback producenta jest zewnętrzny | Kampania **do 1.11.2026**, tylko allegro.pl (komunikat z 19.10.2026) | [help.allegro.com — Electro AGD](https://help.allegro.com/pl/sell/a/juz-dzis-startujemy-z-kampania-electro-agd-Bv35gx9d9fj) (live, przeczytane) | **−100 zł** — 30× mniej niż kod euro |
| **Allegro — kupon −100 zł na duże AGD (Picodi/Pepper)** | To **ten sam mechanizm** co `AGD100`: min. 2500 zł, klasa A, wybrane lodówki/pralki/suszarki/zmywarki. Kupony Allegro są **personalizowane i przypisane do konta** — nie ma publicznego kodu do wpisania. | **−100 zł** (jeśli kupon zostanie przyznany) | Nie | Tak | „do 26.10.2026” wg Picodi — **niepotwierdzone** | [picodi.com/pl/allegro](https://www.picodi.com/pl/allegro), [pepper.pl](https://www.pepper.pl/kupony/allegro.pl) + [zasady kuponów Allegro](https://allegro.pl/pomoc/dla-kupujacych/kupony-punkty-i-programy-znizkowe/jak-dzialaja-kupony-allegro-i-kody-rabatowe-rjOA7am7MU6) | **Nie gwarantowany** — zależy od konta; nie planować na nim koszyka |
| **Allegro — „drugi produkt −40%”, „5. za 1 zł”, „kup 2 −X%”** | **Nie istnieją jako promocja platformowa Allegro.** Allegro ma tylko: (a) **rabaty ilościowe sprzedawcy** (reguły ustawiane przez sprzedającego, w jego ofertach), (b) **zestawy** w ramach jednej oferty, (c) **kupony** (personalizowane), (d) **kody rabatowe sprzedawcy** w wybranych ofertach. | **0 zł** | — | — | — | [Allegro: zestawy](https://allegro.pl/pomoc/dla-kupujacych/wyszukiwanie-i-ulubione/czym-sa-zestawy-i-jak-je-kupowac-jDejgymbBCw), [kupony](https://allegro.pl/pomoc/dla-kupujacych/kupony-punkty-i-programy-znizkowe/jak-dzialaja-kupony-allegro-i-kody-rabatowe-rjOA7am7MU6), [rabaty ilościowe (API)](https://developer.allegro.pl/news/rabaty-ilosciowe-dla-zakupow-w-wielu-ofertach-sprzedajacego-8dmljVEOyfM); 0 trafień na „5. za 1 zł”/„drugi −40%” w promocjach Allegro | **Nie ma czego liczyć** — te mechaniki to Media Expert / MediaMarkt / Amica / euro, nie Allegro |
| **Allegro Pay — 2×50 zł** | Kupony dla kont **bez aktywowanego Allegro Pay**: aktywacja + zakup ≥30 zł w 14 dni. **Nie łączą się** z innymi kuponami Allegro ani w jednej transakcji. | **−100 zł** (dwa osobne zakupy), tylko nowi użytkownicy | Nie | Tak | do **31.10.2026** | [jakdorobic.pl](https://jakdorobic.pl/allegro-pay-kupon-2026) | Nieistotne — max 100 zł i wymaga nowego konta |

---

## 2. Whirlpool.pl — „500 za 2000”: klaster jest, promocji nie ma

Trzy niezależne dowody, wszystkie z 25.10.2026:

1. **Brak regulaminu.** Na [`whirlpool.pl/regulaminy-promocji`](https://www.whirlpool.pl/regulaminy-promocji) lista kończy się na **grudniu 2024**; wszystkie pozycje mają dopisek „Promocja zakończona dnia…”. Ostatnia edycja „500 zł rabatu za każde 2000 zł zakupu” to **Black Friday 2024**.
2. **Klaster został tylko na 2 z 4 produktów** (odczyt HTML kart produktu):
   - płyta **WB S2560 NE** → `500za2000 temporary (customer claim)`
   - zmywarka **W7I HT58 T** → `500za2000 zestaw_2`
   - piekarnik **WOI7A8FHT2SBA** → **brak** klastra
   - mikrofalówka **WMD7O4TX** → **brak** klastra
3. **Koszyk nie nalicza rabatu.** Symulacja koszyka przez publiczny endpoint checkout whirlpool.pl (`POST /api/checkout/pub/orderForms/simulation`) dla czterech konfiguracji — **za każdym razem 0 promocji** (`rateAndBenefitsIdentifiers: []`, `campaigns: []`):
   - wszystkie 4 produkty: **9066,00 zł**, rabat 0
   - płyta + zmywarka: 3748,00 zł, rabat 0
   - zmywarka ×2: 4638,00 zł, rabat 0
   - wszystkie 4 ×2: 18 132,00 zł, rabat 0

**Werdykt:** `500za2000` to **nieaktywna pozostałość konfiguracji katalogu**. Oznaczam jako **niepotwierdzone (klaster bez regulaminu i bez naliczania w koszyku)** i **nie uwzględniam w koszyku**.

**Mechika, gdyby działała (z PDF 2024 — jedyny dostępny dokument):**

| Wartość produktów promocyjnych | Rabat |
|---|---|
| do 1999,99 | 0 |
| 2000,00–3999,99 | 500 |
| 4000,00–5999,99 | 1000 |
| 6000,00–7999,99 | 1500 |
| 8000,00–9999,99 | 2000 |
| 10000,00–11999,99 | 2500 |
| 12000,00–13999,99 | 3000 |
| 14000,00–15999,99 | 3500 |
| ≥16000,00 | **4000 (maks.)** |

Warunki towarzyszące (2024): tylko whirlpool.pl, min. **2 różne** produkty promocyjne, kod rabatowy, maks. 1 szt. tego samego produktu, maks. 3 zamówienia, rabat od ceny przed innymi rabatami, **nie łączy się z innymi promocjami cenowymi ani kodami sklepu**, usługi (dostawa/instalacja) nie wchodzą do progu.

### Koszyk Whirlpoola na naszych cenach (live, 25.10.2026)

| Model | whirlpool.pl | euro.com.pl (nasz koszyk) |
|---|---|---|
| Piekarnik WOI7A8FHT2SBA | **3599,00** (stan 10 szt.) | 3499,00 |
| Płyta WB S2560 NE | **1429,00** (stan 10 szt.) | 1348,00 |
| Mikrofalówka WMD7O4TX | **1719,00** (stan 10 szt.) | 1698,00 |
| Zmywarka W7I HT58 T | **2319,00** (stan 100 szt.) | 2299,99 |
| **Razem** | **9066,00** | **8844,99** |
| Cashback Whirlpool (350 + 200 + 200) | −750,00 | −750,00 |
| **Netto** | **8316,00** | **8094,99** |

Whirlpool.pl jest **+221,01 zł droższy** od euro na tych czterech pozycjach. Gdyby `500za2000` działało i obejmowało wszystkie 4 produkty: 9066 − 2000 − 750 = **6316 zł** (to jedyny scenariusz, w którym kanał oficjalny wygląda atrakcyjnie) — ale promocja **nie nalicza się**, a przy liczeniu tylko produktów z klastrem dałaby zaledwie −500 zł (8566 − 750 = 7816 zł).

---

## 3. Samsung.pl — `MULTI`: rabat na najtańszy, ale grupa „Pralki i Suszarki” psuje układ

**Potwierdzone na żywo** ([strona promocji](https://www.samsung.com/pl/offer/promocja-agd/) + [regulamin PDF](https://images.samsung.com/is/content/samsung/assets/pl/regulaminy_2026/Program_Multirabaty_na_tanszy_Produkt_w_Sklepie_Samsung.pdf), §3.2):

| Liczba produktów z **różnych grup** | Rabat |
|---|---|
| 2 | **−30%** ceny **tańszego** produktu |
| 3 | **−55%** ceny **najtańszego** |
| 4 | **−80%** ceny **najtańszego** |
| 5 | **najtańszy za 1 zł** |

Zasady dodatkowe: **maks. 1 szt. produktu z jednej grupy** (§3.3); rabat nalicza się **tylko na jeden** produkt; pozostałe produkty w zamówieniu bez rabatu (§3.6); wyłączone przedsprzedaże i premiery; program **łączy się wyłącznie z kodem `INSTALACJA`** (darmowa instalacja), a „w pozostałym zakresie nie łączy się z innymi programami, promocjami oraz programami aktywowanymi kodem promocyjnym” (§3.5).

**Kluczowa pułapka:** w §1.6 lit. d grupa AGD to **„Pralki i Suszarki” jako JEDNA podkategoria**. Pralka i suszarka **nie mogą** liczyć się jako dwie grupy — a zakup dwóch produktów z tej samej grupy w programie może skończyć się anulowaniem zamówienia albo sprzedażą w cenie regularnej (§3.4).

### Ceny Samsunga na żywo (samsung.pl, 25.10.2026)

| Model | samsung.pl | euro.com.pl | Różnica |
|---|---|---|---|
| Lodówka BRB70F30BES0EO | **3299,00** (list 4049) | 3299,00 | 0 |
| Pralka WW90CGC04DAE | **2259,00** (list 2499) | 1799,00 | **+460** |
| Suszarka DV9MDG52A0AE | **2499,00** (list 3499) | 2489,00 | +10 |
| Łącznik SKK-DD | **249,00** (list 349) | 249,00 | 0 |
| **Razem** | **8306,00** | **7836,00** | **+470** |

### Co realnie da się ugrać

- **Lodówka + pralka** (2 grupy: Lodówki, Pralki i Suszarki), jedno zamówienie: −30% × 2259 = **−677,70 zł** → 7628,30 zł. Suszarkę i łącznik trzeba kupić osobno (ta sama grupa / brak klastra).
- **Wszystkie 4 w jednym koszyku**: formalnie 3 grupy, ale pralka i suszarka z jednej grupy → ryzyko §3.4; a „najtańszy” to łącznik 249 zł, więc −55% = **−136,95 zł**. Czyli **im więcej drobnicy, tym mniejszy rabat** — mechanika karze dokładanie tanich pozycji.
- **Pełna kuchnia Samsunga (5 grup)**: rabat = cena najtańszego urządzenia („za 1 zł”), czyli rząd **1,5–2,5 tys. zł**, ale wymaga porzucenia piekarnika/płyty/zmywarki Whirlpoola → traci się **750 zł cashbacku Whirlpoola** i wzorce MUST. Nieopłacalne.

**Cashback Samsunga a `MULTI`:** regulamin cashbacku (1.10–30.11.2026) **nie zakazuje** rabatów ani kodów — liczy się model i dowód zakupu bez NIP. Ale §3.5 regulaminu `MULTI` mówi, że program nie łączy się z innymi programami. Przy `MULTI` licz więc **bez** cashbacku (7628,30 zł), a 400 zł traktuj jako niepewne. Dla porównania: ten sam podzbiór w euro to 7836 − 400 = **7436 zł** — **euro jest tańsze**, mimo braku jakiegokolwiek kodu.

---

## 4. Allegro — jest tylko `AGD100` (−100 zł), nie ma „5. za 1 zł” ani „drugiego −40%”

**Potwierdzone** na help.allegro.com (komunikat z 19.10.2026, kampania **do 1.11.2026**, tylko allegro.pl):

- kod **`AGD100`**, obniża zamówienie o **100 zł** przy zakupach **≥2500 zł**,
- dotyczy **wybranych produktów klasy energetycznej A** z kategorii: lodówki, pralki, pralko-suszarki, suszarki, zamrażarki, zmywarki (wolnostojące i do zabudowy),
- kod jest **przyznawany kupującemu w osobnej komunikacji** — nie jest publiczny, więc nie ma gwarancji, że go dostaniesz,
- **piekarniki, płyty, okapy i mikrofalówki są poza listą kategorii**.

W naszym koszyku warunek „klasa A + kategoria z listy + zamówienie ≥2500” spełnia **pralka Samsung WW90CGC04DAE** (klasa A) — więc **−100 zł** na całe zamówienie jest realne, jeśli kod zostanie przyznany.

**Czego Allegro nie ma (sprawdzone):**

- **„5. produkt za 1 zł”** — brak jakiejkolwiek promocji platformowej; mechanika występuje u Media Expert, MediaMarkt, Amica i w euro (`WIEL`), nie na Allegro.
- **„drugi produkt −40%” / „kup 2 −X%”** — Allegro ma wyłącznie **rabaty ilościowe ustawiane przez sprzedawcę** (w jego ofertach) oraz **zestawy** w jednej ofercie. Nie ma reguły „drugi produkt −40%” na poziomie platformy.
- **Kupony** są **personalizowane i przypisane do konta**; nie łączą się z innymi promocjami Allegro (Smart! Monety, karty podarunkowe, Allegro Pay Business, inne kupony) i nie działają przy ratach ani płatności przy odbiorze.

### Koszyk Allegro (ceny `niepotwierdzone (snippet)`, z `allegro.pl.md`)

| Pozycja | Wartość |
|---|---|
| 9 pozycji, najtańsza sensowna konfiguracja | **16 842,00** |
| `AGD100` | −100,00 |
| Cashback Samsung (pralka + suszarka) | −400,00 |
| Cashback Whirlpool (piekarnik + płyta + mikrofalówka) | −750,00 (warunkowo — Allegro nie jest wykluczone, ale niepotwierdzone) |
| **Netto (wszystko działa)** | **15 592,00** |
| **Netto (bez cashbacku Whirlpoola)** | **16 342,00** |

Nawet w najlepszym wariancie Allegro jest **+2 448 zł droższe** od euro (13 143,99). Powód nie leży w promocjach, tylko w cenie bazowej: euro po kodzie 3000 zł jest po prostu tańsze.

---

## 5. Najlepszy wariant i porównanie z 13 143,99 zł

| Wariant | Brutto | Rabaty koszykowe | Cashbacki | **Netto** | Różnica vs euro |
|---|---|---|---|---|---|
| **EURO — jeden koszyk, kod `RKPROGAGD1026`** | 17 293,99 | −3000,00 | −1150,00 | **13 143,99** | **0 (wzorzec)** |
| Whirlpool.pl (4 szt.) + Samsung.pl (4 szt.) + okap w euro | 17 985,00 | −677,70 (`MULTI`) | −1150,00 | **16 157,30** | **+3 013,31** |
| ↑ ten sam podział, gdyby `500za2000` działało (−2000) | 17 985,00 | −2677,70 | −1150,00 | **14 157,30** | +1 013,31 |
| Allegro (9 pozycji) | 16 842,00 | −100,00 | −1150,00 | **15 592,00** | +2 448,01 |
| Wszystko w whirlpool.pl z `500za2000` (hipotetycznie, gdyby sprzedawali Samsunga i Amicę) | 17 293,99 | −4000,00 (cap) | −750,00 | 12 543,99 | −600,00 — **niewykonalne** (brak modeli w ofercie) |

*Uwaga do wierszy z `MULTI`: cashback Samsunga (400 zł) przy `MULTI` jest niepewny (§3.5 regulaminu `MULTI`). Bez niego wariant „Whirlpool.pl + Samsung.pl + okap” to 16 557,30 zł, a z hipotetycznym `500za2000` — 14 557,30 zł. Wniosek się nie zmienia.*

**Dlaczego podział zawsze przegrywa:** kod euro daje **3000 zł tylko przy jednej transakcji ≥16 000 zł**. Rozbicie koszyka, żeby złapać `MULTI` (−678 zł) albo `AGD100` (−100 zł), obniża wartość transakcji w euro poniżej progu i **traci całe 3000 zł**. Nawet hipotetyczne `500za2000` (−2000 zł) jest mniejsze niż 3000 zł, więc i ono nie uzasadnia podziału.

**Wniosek:** **kupujemy całość w euro.com.pl, jednym zamówieniem, z kodem `RKPROGAGD1026`, do 31.10.2026 23:45.** Promocje w whirlpool.pl, samsung.pl i na Allegro należy traktować jako ciekawostkę rynkową, nie jako alternatywę dla tego koszyka.

**Zastrzeżenia i ryzyka:**
1. `500za2000` — **niepotwierdzone**: klaster na 2 kartach produktu, brak regulaminu po 2024 r., zero rabatu w symulacji koszyka. Jeśli chcesz mieć pewność, wrzuć 4 produkty Whirlpoola do koszyka whirlpool.pl i sprawdź, czy pojawi się rabat — dziś nie pojawia się.
2. `MULTI` — mechanika i kwoty **potwierdzone regulaminem**, ale załącznik nr 2 wymienia tylko produkty AV, mimo że §1.5 odsyła do niego także dla AGD (błąd redakcyjny regulaminu). To potencjalna podstawa odmowy; nie opieraj na tym planu.
3. Ceny Allegro — **niepotwierdzone (snippet)**, bo listingi zwracają 403. Wartość 16 842 zł pochodzi z wcześniejszego raportu.
4. Cashback Whirlpoola (750 zł) poza euro — **tylko jeśli sprzęt jest z polskiej dystrybucji i dowód zakupu jest bez NIP**; w euro kwoty są potwierdzone w załączniku regulaminu (WOI7A8FHT2SBA 350, WBS2560NE 200, WMD7O4TX 200).
