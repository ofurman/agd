# x-kom.pl – raport (2026-10-25)

## Jak zebrano ceny

- **Wszystkie ceny w tym raporcie pobrano na żywo z x-kom.pl 25.10.2026, między 21:50 a 22:15 CET** (bezpośrednie zapytania HTTP do stron wyszukiwania i kart produktów). Nie ma tu ani jednej ceny „ze snippetu”.
- **Blokada:** x-kom ma zabezpieczenie antybotowe („Performing security verification”). Część prób przez pośrednika (render tekstu) trafiła na ten ekran. **Nie obchodziłem zabezpieczenia** – powtórzyłem zwykłe zapytanie do publicznej strony, które zwróciło normalny HTML (HTTP 200). Żadnego captcha nie rozwiązywałem.
- **Najważniejsze ustalenie:** **x-kom.pl nie prowadzi sprzedaży grubego AGD ani AGD do zabudowy.** Nie ma piekarników do zabudowy, lodówek, płyt indukcyjnych, zmywarek, pralek, suszarek ani mikrofalówek do zabudowy. Asortyment „domowy” to drobne AGD (odkurzacze, ekspresy, czajniki, szczoteczki) plus 6 okapów Akpo (przyścienne/podszafkowe, w większości wycofane).
- x-kom sam kieruje kupujących AGD do **Neonetu**, w którym ma 51% udziałów: artykuł [„Szukasz AGD – sprawdź ofertę Neonetu”](https://www.x-kom.pl/aktualnosci/9545-szukasz-agd-sprawdz-oferte-neonetu.html) (aktualizacja 09.12.2024) oraz [„Przejęliśmy 51% udziałów w Neonecie”](https://www.x-kom.pl/aktualnosci/9617-przejelismy-51-udzialow-w-neonecie.html) (aktualizacja 03.02.2025). Wyszukiwarka x-kom przy hasłach AGD wyświetla baner reklamowy prowadzący do kategorii na neonet.pl.
- Wyszukiwania wykonane na żywo (liczba trafień x-kom, 25.10.2026):

| Hasło | Wynik | Co faktycznie znaleziono |
|---|---|---|
| `BRB70F30BES0EO`, `WB S2560 NE`, `W7I HT58 T`, `WW90CGC04DAE`, `DV9MDG52A0AE`, `BFL554MB0`, `W7 MD440 NB`, `OTP6651BG`, `DFS067K51`, `SKK-DD`, `WTZ27400` | **0 – „Nie znaleźliśmy wyników”** (każde osobno) | brak jakiejkolwiek oferty tych modeli i akcesoriów |
| `piekarnik` | 3 | 2 minipiekarniki Blaupunkt (EOM501 499 zł, EOM601 599 zł), myjka parowa Sencor 329 zł |
| `piekarnik do zabudowy`, `piekarnik parowy`, `mikrofalowka do zabudowy`, `whirlpool` | **0** | brak kategorii |
| `lodowka` | 6 | wyłącznie lodówki turystyczne (Yolco, Ninja, EcoFlow Glacier) |
| `lodowko-zamrazarka`, `zamrazarka` | 6 / 6 | te same lodówki turystyczne |
| `plyta indukcyjna` | 3 | 2 płyty stołowe Rommelsbacher (349/419 zł) + biurko gamingowe (trafienie przypadkowe) |
| `okap` | 9 | 6 okapów Akpo + 3 parownice Kärcher (trafienia przypadkowe) |
| `okap teleskopowy`, `teleskopowy` | 0 okapów | wyłącznie uchwyty/wysięgniki teleskopowe (Silver Monkey, DJI) |
| `zmywarka` | 3 | brak zmywarek; trafienia niepowiązane (kubek x-kom, ekspres DeLonghi) |
| `pralka`, `pralko-suszarka`, `suszarka do prania` | 1 / 2 / 2 | tylko akcesoria (siatki Meliconi) i „suszarki” do włosów/sierści |
| `agd` / `duze agd` | 29 / 8 | drobnica (golarki, szczoteczki, ciśnieniomierze) / telewizory |
| `whirlpool piekarnik`, `samsung pralka`, `bosch pralka`, `beko zmywarka`, `amica okap` | **0** | brak oferty tych marek w AGD |

---

## Promocje / kupony

| Promocja | Warunki | Ważność | Czy działa na te modele | Źródło |
|---|---|---|---|---|
| **Bon 20 zł za zapis do newslettera** | Jednorazowy kod z maila po potwierdzeniu zapisu; **zamówienie min. 200 zł**; zakres wyłączeń wg regulaminu newslettera | do **30.11.2026 23:59** | **Nie dotyczy** – nie ma czego kupić z listy | [lp/newsletter-promocje](https://www.x-kom.pl/lp/newsletter-promocje) (odczytane na żywo) |
| **Raty 0%** | Zamówienia **300–4 000 zł** oraz wybrane produkty; RRSO 0% | stała oferta | Nie dotyczy (brak produktów). Limit 4 000 zł i tak objąłby piekarnik/płytę, gdyby były | [x-kom.pl/raty](https://www.x-kom.pl/raty) |
| Raty oprocentowane do 50 rat | 300–30 000 zł; banki: Alior, Santander Consumer, Credit Agricole | stała oferta | Nie dotyczy | [x-kom.pl/raty](https://www.x-kom.pl/raty) |
| **Darmowy odbiór w salonie** | „Salon x-kom i Neonet **0 zł**”, do 3 dni roboczych; **do salonów nie doręczają szczególnie dużych urządzeń** (wybrane TV, niektóre desktop) | stała oferta | Nie dotyczy – brak towaru; przy AGD gabarytowym odbiór w salonie i tak nie wchodzi w grę | [x-kom.pl/dostawa](https://www.x-kom.pl/dostawa) |
| Kurier / Paczkomat / punkt | Kurier przedpłata **14,99–129,99 zł**, pobranie 19,99–134,99 zł; Paczkomat **10,99–45,99 zł**; punkt odbioru 10,99 zł; „wybrane produkty mogą mieć darmową dostawę” | stała oferta | Nie dotyczy | [x-kom.pl/dostawa](https://www.x-kom.pl/dostawa) |
| Leasing / Tax Free / zakupy dla firm | Dostępne | stała oferta | Nie dotyczy | [x-kom.pl/dostawa](https://www.x-kom.pl/dostawa) |
| **Cashback Samsung AGD (do 4500 zł)** | Zakup 1.10–30.11.2026, rejestracja do 21.12.2026; sprzęt z polskiej dystrybucji (kod …EO) | do 30.11.2026 | **Nie dotyczy** – x-kom nie ma ani jednego modelu Samsung AGD (0 wyników na `BRB70F30BES0EO`, `WW90CGC04DAE`, `DV9MDG52A0AE`) | [cashbackagd.samsung.pl](https://cashbackagd.samsung.pl/) |
| **Cashback Whirlpool (do 3000 zł)** | Zestaw min. 2 urządzeń, piekarnik obowiązkowo; 1.09–31.12.2026 | do 31.12.2026 | **Nie dotyczy** – 0 wyników na `whirlpool`, `WOI7A8FHT2SBA`, `WB S2560 NE`, `W7 MD440 NB`, `W7I HT58 T` | [whirlpool-promocja.pl](https://whirlpool-promocja.pl/) |
| **Cashback Bosch – suszarki (do 600 zł)** | Zakup 1.10–31.12.2026, zgłoszenie do 30.01.2027 | do 31.12.2026 | **Nie dotyczy** – x-kom nie sprzedaje suszarek (marka Bosch tylko w odkurzaczach) | [regulamin Bosch](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) |
| Akcje x-kom (38 banerów na /promocje) | m.in. „Black Weeks” (do 25.10.2026 23:59), „Gorący Strzał” (codziennie 10:00 i 22:00), un.Box, Samsung cashback **na telefony Galaxy** (do 25.10.2026), odkup smartfonów (do 500 zł), Canon cashback (do 15.11.2026), meble Silver Monkey w ratach 0% (do 31.10.2026) | różne | **Żadna nie dotyczy AGD** – wszystkie 38 banerów to IT/telefony/TV/meble | [x-kom.pl/promocje](https://www.x-kom.pl/promocje) (odczytane na żywo) |
| Wniesienie / montaż AGD | **Brak usługi.** Strona [x-kom.pl/montaz](https://www.x-kom.pl/montaz) obejmuje wyłącznie komputery (montaż desktopa 249–349 zł, rozbudowa laptopa 99–249 zł, BIOS 69 zł) | – | Nie dotyczy | [x-kom.pl/montaz](https://www.x-kom.pl/montaz) |

**Uwaga o pułapce cenowej:** x-kom ma własną stronę „Samsung cashback”, ale dotyczy ona **telefonów Galaxy** – nie AGD. Nie przenoś zasad ani kwot cashbacku Samsung AGD na zakupy w x-kom.

---

## 1. Piekarnik

**Brak oferty.** x-kom nie sprzedaje piekarników do zabudowy w ogóle (`piekarnik do zabudowy` → 0 wyników, `piekarnik parowy` → 0). Wzorzec Whirlpool WOI7A8FHT2SBA → 0 wyników.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `piekarnik do zabudowy`](https://www.x-kom.pl/szukaj?q=piekarnik%20do%20zabudowy) |

Najbliższe (nie są zamiennikiem, nie spełniają żadnego MUST): minipiekarnik Blaupunkt EOM501 – 499 zł (dostępny), EOM601 – 599 zł (niedostępny); to urządzenia wolnostojące, nie do zabudowy 60 cm, bez pary, termosondy i hydrolizy.

## 2. Lodówka do zabudowy

**Brak oferty.** `lodowka` → 6 wyników, wszystkie to **lodówki turystyczne/kompresorowe** (Yolco QL40 2699 zł, Ninja FrostVault 47 l 999,99 zł, EcoFlow Glacier 2999–3999 zł). Wzorzec Samsung BRB70F30BES0EO → 0 wyników; warianty A/F/BE również nie występują.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `lodowka do zabudowy`](https://www.x-kom.pl/szukaj?q=lodowka%20do%20zabudowy) |

## 3. Płyta indukcyjna

**Brak oferty.** `płyta indukcyjna` → 3 wyniki: dwie **płyty stołowe** Rommelsbacher CT 2002/IN 349 zł i CTA 1800/IN 419 zł (jednopolowe, przenośne) oraz przypadkowe biurko Huzaro. Wzorzec Whirlpool WB S2560 NE → 0 wyników. Wersji matowej/MattProtect też nie ma, więc pułapka „mat vs błyszczące” tu nie występuje.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `płyta indukcyjna`](https://www.x-kom.pl/szukaj?q=plyta%20indukcyjna) |

## 4. Okap teleskopowy

**Brak oferty.** `okap teleskopowy` → 0 wyników. Jedyne okapy w x-kom to 6 modeli **Akpo**: 4 przyścienne (kominowe/skośne) i 2 podszafkowe. **Typ „teleskopowy” nie występuje** – a podszafkowy i przyścienny są w wymaganiach wykluczone (przy szafkach 35 cm nie obejmują przednich pól płyty). Dodatkowo **wylot to 12 cm** (nie fi 150 bez redukcji) – tak podają karty wszystkich modeli poza WK-9 K50 (15 cm + redukcja do 12) i WK-9 K60 (brak danych) – a karty produktów pokazują **„Wycofany”/„Czasowo niedostępny”**, więc kupić praktycznie nie ma czego.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty teleskopowego** | — | — | **nie** | brak typu teleskopowego w ofercie | [wyszukiwarka `okap teleskopowy`](https://www.x-kom.pl/szukaj?q=okap%20teleskopowy) |
| Akpo WK-7 Light Glass Touch 60 inox-czarny | podszafkowy (nie teleskop) | 579 zł | — | **Wycofany** | **nie**: typ ✗, wylot 12 cm ✗, wydajność brak w karcie, głębokość brak w karcie | 60 cm ✓, hałas 60 dB (karta), sterowanie elektroniczne, czarno-inox | [karta](https://www.x-kom.pl/p/230940-okap-podszafkowy-akpo-wk-7lightglasstouch60-inox-czarny.html) |
| Akpo WK-4 Grand Eco 60 czarny | przyścienny skośny | 439 zł | — | **Wycofany** | **nie**: typ ✗, 297 m³/h ✗ (za mało i to max), 61 dB ✗, wylot 12 cm ✗ | głębokość 34,7 cm (zmieściłby się w szafce 35 cm), klasa E, 118 kWh/rok, filtr aluminiowy | [karta](https://www.x-kom.pl/p/231660-okap-przyscienny-akpo-wk-4-grand-eco-60-czarny.html) |
| Akpo WK-9 K60 Inox + czarna szyba | przyścienny kominowy | 599 zł | — | **Czasowo niedostępny** | **nie**: typ ✗, 253 m³/h ✗, wylot brak danych | 60 cm ✓, 56 dB (karta), sterowanie sensorowe | [karta](https://www.x-kom.pl/p/1025440-okap-przyscienny-akpo-okap-akpo-wk-9-k60-inox-czarna-szyba.html) |
| Akpo WK-4 Grand Eco 50 / WK-9 K50 / WK-7 LGT 50 | przyścienny / podszafkowy | 408 / 599 / 699 zł | — | wycofany / czasowo niedostępny / czasowo niedostępny | **nie**: dodatkowo zła szerokość (50 cm) | – | [WK-4 50](https://www.x-kom.pl/p/231669-okap-przyscienny-akpo-wk-4-grand-eco-50.html) |

## 5. Mikrofalówka do zabudowy

**Brak oferty.** `mikrofalowka`, `mikrofala`, `mikrofalowka do zabudowy` → 0 wyników. Wzorzec Whirlpool W7 MD440 NB i alternatywa Bosch BFL554MB0 → 0 wyników. x-kom nie ma mikrofal w żadnej formie (do zabudowy ani wolnostojących).

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `mikrofalowka do zabudowy`](https://www.x-kom.pl/szukaj?q=mikrofalowka%20do%20zabudowy) |

## 6. Zmywarka do zabudowy

**Brak oferty.** `zmywarka` → 3 wyniki, w tym kubek firmowy x-kom i ekspres DeLonghi – **zero zmywarek**. Wzorzec Whirlpool W7I HT58 T, Beko MEDIN3755A, Whirlpool WH8IA15AM3TUS0 → 0 wyników.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `zmywarka`](https://www.x-kom.pl/szukaj?q=zmywarka) |

## 7. Pralka + suszarka

**Brak oferty.** `pralka` → 1 wynik (siatki do prania Meliconi 11,24 zł). `suszarka do prania` → 2 wyniki (suszarki do włosów/sierści). `pralko-suszarka` → tylko akcesoria.
Modele: Samsung WW90CGC04DAE – 0, DV9MDG52A0AE – 0, łącznik SKK-DD – 0, Bosch WGG244ZEPL/WQG245DEPL – 0, łącznik WTZ27400 – 0.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| — | — | **brak oferty** (pralka, suszarka, łącznik) | — | — | **nie** | brak kategorii w sklepie | [wyszukiwarka `pralka`](https://www.x-kom.pl/szukaj?q=pralka) |

---

## Alternatywy obowiązkowo

**W x-kom nie ma ani jednej alternatywy spełniającej wszystkie MUST – w żadnej z 7 kategorii.** Nie da się tego obejść „podobnym sprzętem”, bo sklep nie prowadzi sprzedaży tych kategorii:

- **Piekarnik, lodówka, płyta, mikrofalówka, zmywarka, pralka, suszarka:** 0 ofert w kategorii. Nie ma wariantu „podobny/lepszy w promocji” – nie ma nawet tańszego modelu bez części funkcji.
- **Okap:** 3 modele 60 cm istnieją (2 przyścienne, 1 podszafkowy) plus 3 modele 50 cm, ale **każdy łamie co najmniej 3 MUST** (typ nie-teleskopowy, wylot 12 cm zamiast 150, wydajność 253–297 m³/h tam, gdzie karta ją podaje, przy 56–61 dB). Trzy z nich są wycofane, trzy „czasowo niedostępne”, więc kupić nie ma czego. Żaden nie jest alternatywą – to nie jest kwestia ceny, tylko konstrukcji.
- **Akcesoria:** łączniki słupkowe Samsung SKK-DD / SKK-DF / SKK-DDX i Bosch WTZ27400 – **brak w ofercie** (0 wyników).
- Gdzie szukać alternatyw: w Neonecie (ta sama grupa, x-kom sam tam odsyła) oraz w raportach pozostałych sklepów.

## Koszyk w tym sklepie

| Kategoria | Model | Cena | Dostawa | Status |
|---|---|---|---|---|
| 1. Piekarnik | — | — | — | brak oferty |
| 2. Lodówka do zabudowy | — | — | — | brak oferty |
| 3. Płyta indukcyjna | — | — | — | brak oferty |
| 4. Okap teleskopowy | — | — | — | brak oferty (tylko przyścienne/podszafkowe, wycofane) |
| 5. Mikrofalówka do zabudowy | — | — | — | brak oferty |
| 6. Zmywarka | — | — | — | brak oferty |
| 7. Pralka + suszarka + łącznik | — | — | — | brak oferty |
| **Razem** | **0 z 8 pozycji** | **0 zł** | **0 zł** | **Koszyk pusty** |

**Nie opłaca się kupować tutaj całości – ani żadnej pozycji.** x-kom pokrywa 0% listy. Jedyny scenariusz, w którym x-kom ma sens: gdyby któraś pozycja nie była AGD (np. sprzęt IT do domu), albo gdyby chodziło o drobne AGD spoza tej listy. Dla tej listy x-kom jest sklepem **nieprzydatnym** i nie generuje ani jednej linii koszyka do porównania.

## Tabela do porównania

| kategoria | model | cena | dostawa | promocja netto | MUST | url |
|---|---|---|---|---|---|---|
| 1. Piekarnik | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=piekarnik%20do%20zabudowy |
| 2. Lodówka do zabudowy | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=lodowka%20do%20zabudowy |
| 3. Płyta indukcyjna | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=plyta%20indukcyjna |
| 4. Okap teleskopowy | brak oferty (0 teleskopowych) | — | — | — | nie | https://www.x-kom.pl/szukaj?q=okap%20teleskopowy |
| 4a. Okap (poza MUST) | Akpo WK-4 Grand Eco 60 czarny (przyścienny, wycofany) | 439 | — | brak | nie | https://www.x-kom.pl/p/231660-okap-przyscienny-akpo-wk-4-grand-eco-60-czarny.html |
| 4b. Okap (poza MUST) | Akpo WK-7 Light Glass Touch 60 (podszafkowy, wycofany) | 579 | — | brak | nie | https://www.x-kom.pl/p/230940-okap-podszafkowy-akpo-wk-7lightglasstouch60-inox-czarny.html |
| 5. Mikrofalówka do zabudowy | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=mikrofalowka%20do%20zabudowy |
| 6. Zmywarka | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=zmywarka |
| 7a. Pralka | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=pralka |
| 7b. Suszarka | brak oferty | — | — | — | nie | https://www.x-kom.pl/szukaj?q=suszarka%20do%20prania |
| 7c. Łącznik słupkowy | brak oferty (SKK-DD, WTZ27400) | — | — | — | nie | https://www.x-kom.pl/szukaj?q=lacz%C4%85cznik%20SKK-DD |
| — | Warunki dostawy x-kom (dla orientacji optymalizatora) | — | kurier 14,99–129,99 zł; Paczkomat 10,99–45,99 zł; punkt 10,99 zł; salon 0 zł | bon newsletter 20 zł od 200 zł (do 30.11.2026) | — | https://www.x-kom.pl/dostawa |

Ceny brutto w PLN, stan na 25.10.2026 22:00–22:15 CET, odczytane z kart produktów x-kom.

## Wnioski

1. **x-kom odpada z optymalizacji koszyka w całości – 0 z 8 pozycji.** To nie kwestia cen czy promocji: sklep nie prowadzi sprzedaży grubego AGD ani AGD do zabudowy. Każde pytanie „ile u nich kosztuje X” ma odpowiedź „brak oferty”, nie „drożej”.
2. **To świadoma polityka grupy, nie luka w asortymencie.** x-kom ma 51% udziałów w Neonecie (komunikat z 03.02.2025) i sam publikuje artykuł odsyłający po AGD do Neonetu (09.12.2024); wyszukiwarka przy hasłach AGD pokazuje baner do neonet.pl, a odbiór w salonie jest wspólny („Salon x-kom i Neonet 0 zł”). Praktycznie: **AGD z tej listy kupuj w Neonecie**, a nie w x-kom – ale to osobny sklep, osobny koszyk i osobne promocje (bon 20 zł, raty 0%, newsletter nie przechodzą między markami).
3. **Pułapka na cashback:** promocje Samsung/Whirlpool/Bosch AGD formalnie nie wymagają konkretnego sklepu, ale u x-kom nie ma czego rejestrować – modeli AGD tych marek nie ma w ofercie. Strona „Samsung cashback” na x-kom dotyczy wyłącznie telefonów Galaxy (do 25.10.2026). Nie licz na zwrot 200 zł za pralkę Samsunga kupioną w x-kom.
4. **Okap: nie ma nawet „prawie dobrego” wariantu.** Wszystkie 6 okapów to Akpo przyścienne/podszafkowe, wylot 12 cm (nie fi 150), wydajność 253–297 m³/h przy 56–61 dB – czyli poniżej minimum 400 m³/h i powyżej progu głośności. Cztery z sześciu są wycofane, dwa „czasowo niedostępne”. Nawet gdyby cena kusiła (439–699 zł), nie da się tego zamontować zgodnie z wymaganiami.
5. **Warunki zakupowe x-kom (gdyby coś było):** raty 0% tylko do 4 000 zł, odbiór w salonie 0 zł (ale nie dla gabarytów), kurier 14,99–129,99 zł, brak usługi wniesienia/montażu AGD (montaż dotyczy wyłącznie komputerów). Jedyny realny rabat to bon 20 zł przy zamówieniu od 200 zł (do 30.11.2026).
6. **Terminy:** dziś (25.10.2026) o 23:59 wygasają banery „Black Weeks” i akcje Galaxy – bez znaczenia dla AGD. Istotne daty dla całego projektu pozostają przy innych sklepach: kod na suszarkę Samsung do 31.10.2026, cashback Samsung AGD do 30.11.2026, cashback Bosch do 31.12.2026, Whirlpool do 31.12.2026.
