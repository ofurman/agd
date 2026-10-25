# avans.pl – raport (2026-10-25)

## Jak zebrano ceny

- **Ceny sprawdzone na żywo:** 25.10.2026, godz. **22:10–23:00 CET**. Avans.pl **nie blokuje botów** – karty produktów i listingi renderują się poprawnie (SSR + JS), żadnej captchy ani 403.
- Metoda: wyszukiwarka sklepu (`/search?query[querystring]=…`) → karta produktu → odczyt ceny, „ceny z kodem”, dostępności, najszybszej dostawy i tabeli specyfikacji. Dodatkowo przejrzane całe listingi kategorii (piekarniki 366 szt., lodówki do zabudowy 176, płyty 629, okapy 1343, mikrofalówki 121, zmywarki 60 cm 220, pralki 381, suszarki 166), żeby nie przeoczyć modeli spoza wyszukiwarki.
- **Sprzedaż:** wyłącznie sprzedaż własna Avans (TERG S.A., Złotów). **Brak marketplace** – każda cena to oferta sklepu, z polską gwarancją producenta.
- Ograniczenie: **nie dodawałem produktów do koszyka**, więc nie potwierdziłem, czy kod rabatowy (RWE…) nalicza się automatycznie czy trzeba go wpisać. Cena „z kodem” jest ceną wyświetlaną przez sklep przy produkcie – traktuję ją jako obowiązującą do 31.10.2026 do 21:59.
- „Najszybsza dostawa: **W PONIEDZIAŁEK**” = 26.10.2026 – taki komunikat miały wszystkie sprawdzone karty.

---

## Promocje / kupony

| Promocja | Warunki | Ważność | Czy działa na te modele | Źródło |
|---|---|---|---|---|
| **Kod RWE0110-3110** (kampanijny, podany wprost przy produkcie) | Kod wyświetlany jako „Cena z kodem: RWE0110-3110”. Rabat jest **kwotowy i różny per produkt** (np. zmywarka Beko 2799,99 → 2496,96; Whirlpool WH8IA15AM3TUS0 3519,99 → 3197,96; mikrofalówka Hisense 1599,99 → 1296,88). Nie jest to stały % | **do 31.10.2026, godz. 21:59** | Tak: Beko MEDIN3755A, Whirlpool WH8IA15AM3TUS0, Hisense BIM325G62BG2, okap VDB Vector ME 60, okap Gö&J TH600KT. **Nie** na: WOI7P8FHT1SBA, WOI7A8HT2SBA (inny kod), BRB70/80F30 (brak kodu), W7IHT58T, WMD54MB, WW90CGC04DAH, DV90DG52A0AEEO, SKK-DD | [karta Beko MEDIN3755A](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-beko-medin3755a) |
| **Kod RWE1310-311026** | Drugi kod kampanijny – tylko część piekarników. WOI7A8HT2SBA: **4429,99 → 3849,98 zł** (−580,01) | **do 31.10.2026, godz. 21:59** | Tak: piekarnik WOI7A8HT2SBA | [karta WOI7A8HT2SBA](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi7a8ht2sba-elektryczny-parowy-czarny-a) |
| **Darmowy transport** | Koszt dostawy 0 zł dla zamówień **od 99 zł**, przy płatności przelewem, pobraniem, e‑przelewem lub kartą. Nie obejmuje dodatkowych opłat za wybrane usługi | bez terminu | Tak – cały koszyk objęty | [avans.pl/darmowa-dostawa-w-avans](https://www.avans.pl/darmowa-dostawa-w-avans) |
| **Do 20 rat 0% / RRSO 0%** | Akcja 01.10–02.11.2026, tylko produkty z emblematem. Przykład: 2408 zł na 20 rat = 120,40 zł/mies., koszt kredytu 0 zł. Alior Bank / Credit Agricole | **do 02.11.2026** | Tak – przy wszystkich sprawdzonych kartach widnieje „x N rat 0%, RRSO 0%” (np. 169,95 zł × 20 dla WOI7P8FHT1SBA) | [avans.pl/lp,raty-0-procent](https://www.avans.pl/lp,raty-0-procent) |
| **Cashback Whirlpool „Spokój zaczyna się od mądrych decyzji”** | Trzeba kupić **piekarnik** + min. 1 inny sprzęt AGD Whirlpool z listy. Rejestracja na whirlpool-promocja.pl **do 14.01.2027, najpóźniej 14 dni od zakupu piekarnika** + opinia z hasztagiem #PromocjaZyskajSpokój. Produkty nie muszą być na jednym paragonie | zakupy **do 31.12.2026** | **Częściowo.** Na liście piekarników jest **WOI7A8HT2SBA** (ale on nie ma termosondy). **WOI7P8FHT1SBA i WOI11P8FHT2SBAF nie występują w widocznej części listy.** Na liście płyt: **WLS7260NE, WLS2760BFS, WBS0060NE, WBB3960BF**. Na liście mikrofal: **WMD54MB, WMD54MBG, WMD54MW, WMD54MX**. Zmywarki nie biorą udziału | [avans.pl/lp,31964-whirlpool-cashback](https://www.avans.pl/lp,31964-whirlpool-cashback) |
| **Cashback Samsung AGD (producenta)** | Zakup 1.10–30.11.2026, rejestracja do 21.12.2026 na cashbackagd.samsung.pl, paragon/faktura bez NIP, sprzęt z polskiej dystrybucji. Kwoty z listy: **WW90CGC04DAEEO 200 zł, DV9MDG52A0AEEO 200 zł** | do 30.11.2026 lub wyczerpania puli | **Niepotwierdzone.** Avans nie ma modeli o tych kodach – sprzedaje **WW90CGC04DAH** i **DV90DG52A0AE**. Regulamin dopuszcza dowolny sklep w Polsce, ale lista modeli wskazuje na końcówki DAE/EO. **Avans nie prowadzi własnej strony cashbacku Samsung AGD** (strona `/lp,32421-samsung-zyskaj-nawet-4999-zl` to promocja tabletów, `/lp,17109-samsung-zyskaj-nawet-400-zl-zwrotu` jest pusta) | [avans.pl – promocje AGD](https://www.avans.pl/lp,aktualne-promocje) |
| **Bosch – zwrot do 1000 zł za suszarkę/pralko‑suszarkę** | Zakup do 31.12.2026, opinia, rejestracja. Kwota zależna od ceny końcowej | do 31.12.2026 | **Niepotwierdzone** dla WQG244CSPL – na liście Bosch znam WQG245DEPL/WQH245B0PL, modelu z Avans nie zweryfikowałem | [avans.pl – promocje AGD](https://www.avans.pl/lp,aktualne-promocje) |
| **Siemens / Electrolux‑AEG** (zwroty do 6500 zł / „płaci rachunki”) | Osobne akcje producenckie – nie dotyczą wybranych tu modeli | do 31.12.2026 | Nie | [Siemens](https://www.avans.pl/lp,32274-siemens-zyskaj-do-6500-zl-zwrotu-na-konto), [Electrolux](https://www.avans.pl/lp,31189-electrolux-aeg-placi-twoje-rachunki) |
| **Odbiór zużytego sprzętu** | **Bezpłatny** odbiór i recykling starego sprzętu w miejscu dostawy, w ilości i rodzaju równym zamawianemu. **Nie obejmuje demontażu** | bez terminu | Tak, dla każdego urządzenia | Karta produktu → sekcja „Usługi” |
| **Wniesienie / montaż (płatne usługi w koszyku)** | **Wniesienie: 99,99 zł** (lodówka 109,99 zł). **Montaż w miejscu zabudowy: 319,99 zł** (piekarnik, lodówka, zmywarka, pralka; przy płycie indukcyjnej sklep **nie oferuje** montażu – tylko wniesienie 99,99 zł). Rozpakowanie 99,99–174,99 zł. Usługi wybiera się przy produkcie | bez terminu | Tak | Karta produktu → „Usługi”; [avans.pl/lp,montaz-instalacja](https://www.avans.pl/lp,montaz-instalacja) |
| **Kody z newslettera / „P‑xxxxx”** | Na `/lp,kody-rabatowe` są tylko 3 kody: P‑32213 (trzonek gratis, do 31.10), P‑31795 (Cold Brew, do 31.12), P‑32511 (oczyszczacz za 1 zł, do 31.12). **Żaden nie dotyczy AGD** | – | Nie | [avans.pl/lp,kody-rabatowe](https://www.avans.pl/lp,kody-rabatowe) |
| **Gwarancja lepszej ceny** (price match) | Sklep deklaruje „Gwarancję lepszej ceny”; szczegóły w regulaminie (nie sprawdzałem procedury) | – | Tak | nagłówek serwisu |
| **Zestawy / rabaty za kilka sztuk** | **Brak** rabatu za komplet. Zestawów pralka+suszarka Avans nie sprzedaje – tylko osobne urządzenia + łącznik | – | – | listing pralek/suszarek |

---

## 1. Piekarnik do zabudowy

MUST: para · szuflada/zbiornik na wodę · termosonda · hydroliza · teleskopy na 2 poziomach · termoobieg

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WOI7A8FHT2SBA** | wzorzec | **brak oferty** (wyszukiwarka nie zna tego kodu) | – | – | – | – | – |
| **Whirlpool WOI11P8FHT2SBAF** | alternatywa (pełny MUST) | **4597,99 zł** | darmowa (od 99 zł) | dostępny, dostawa pon. 26.10 | ✓ para (parowy) · szuflada na wodę ✓ · **termosonda Tak** · czyszczenie **SmartClean** (hydroliza/para) ✓ · **teleskopy 2 poziomy** ✓ · termoobieg ✓ | Jedyny piekarnik w Avans z **kompletem MUST**. Droższy o ok. 1600 zł od wzorca. A++, 73 l | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi11p8fht2sbaf-elektryczny-parowy-czarny-a-termosonda) |
| **Whirlpool WOI7P8FHT1SBA** | alternatywa (najbliżej wzorca) | **3399,00 zł** (bez kodu) | darmowa | dostępny, pon. 26.10 | para **SteamSense+ (do 100%)** ✓ · szuflada na wodę ✓ · **termosonda ✓** · czyszczenie **„Para”** ✓ · **teleskopy tylko na 1 poziomie** ✗ · termoobieg ✓ | **A++**, Pizza 310 °C, SousVide, 6. Zmysł. Lepiej: klasa i funkcje. Gorzej: prowadnice tylko 1 poziom → **nie spełnia jednego MUST** | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi7p8fht1sba-elektryczny-czarny-a-termosonda) |
| Whirlpool WOI7A8HT2SBA | odpowiednik (tańszy w promo) | **3849,98 zł z kodem RWE1310-311026** (4429,99 zł bez kodu) | darmowa | dostępny, pon. 26.10 | para **SteamSense (do 75%)** ✓ · szuflada na wodę ✓ · **termosonda: NIE** ✗ · hydroliza + SmartClean ✓ · **teleskopy 2 poziomy** ✓ · termoobieg ✓ | A+, 73 l. Najtańszy z teleskopami 2 poz., **ale bez termosondy** → nie spełnia MUST. Jest na liście cashbacku Whirlpool | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi7a8ht2sba-elektryczny-parowy-czarny-a) |
| **Hisense BSA6633PBG8** | alternatywa (najlepszy stosunek ceny) | **2499,99 zł** (było 2799,99) | darmowa | dostępny, pon. 26.10 | para **Steam Add Plus** + **zbiornik na wodę przy panelu** ✓ · **termosonda Tak** ✓ · **teleskopy 2 poziomy** ✓ · termoobieg ✓ · czyszczenie **Pyroliza**, nie hydroliza ✗ | **−900 zł vs WOI7P8FHT1SBA**. 77 l (większy niż wzorzec 73 l), A+. Gorsze: inna marka, brak hydrolizy (jest pyroliza + Steam Clean) | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-hisense-bsa6633pbg8-elektryczny-parowy-czarny-a) |
| ⚠ Amica ED975396BA+ X‑TYPE Steam P | odrzucone (niepełne MUST) | 2099,99 zł | darmowa | dostępny | para **SoftSteam**, ale woda wlewa się **w zagłębienie na dnie komory** – **brak szuflady/zbiornika** ✗ · termosonda Tak ✓ · czyszczenie **Pyroliza** ✗ · teleskopy 2 poz. ✓ | Najtańszy z teleskopami 2 poz., ale **nie spełnia MUST „szuflada/zbiornik na wodę”** ani hydrolizy | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-amica-ed975396ba-x-type-steam-p-elektryczny-parowy-czarny-a) |
| Samsung NV7B5685BAK U2 Dual Cook | odpowiednik | 3609,00 zł | darmowa | dostępny | **termosonda: Nie** ✗ · czyszczenie katalityczne/parowe ✗ · teleskopy 2 poz. ✓ | Droższy i bez termosondy – odrzucony | [karta](https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-samsung-nv7b5685bak-u2-dual-cook-elektryczny-parowy-czarny-a) |

**Wniosek:** w Avans nie ma piekarnika, który spełnia **wszystkie** MUST w rozsądnej cenie – jest tylko **WOI11P8FHT2SBAF za 4597,99 zł**. Najlepszy kompromis: **Hisense BSA6633PBG8 2499,99 zł** – para ze zbiornikiem na wodę, termosonda, teleskopy 2 poziomy (jedyne odstępstwo: pyroliza zamiast hydrolizy, czyli czyszczenie o klasę wyżej). Drugi wariant: **WOI7P8FHT1SBA 3399 zł** (wszystko poza teleskopami na 2 poziomach). **Amica ED975396BA+ (2099,99 zł) odpada** – nie ma szuflady/zbiornika na wodę, tylko wgłębienie w dnie komory.

---

## 2. Lodówka do zabudowy

MUST: zabudowa ~193,5 cm, zawiasy ślizgowe · pełny No Frost · 2 obiegi · ~298 l · ≤35 dB

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Samsung BRB70F30BES0EO** | **wzorzec (dokładnie ten kod)** | **3299,00 zł** | darmowa | dostępny, pon. 26.10 | ✓ 193,5 × 54 × 55 cm · **zawiasy ślizgowe** ✓ · **pełny No Frost** ✓ · **Twin Cooling (2 obiegi)** ✓ · 224 + 74 = 298 l ✓ · **35 dB** ✓ · alarm drzwi, Optimal Fresh+, Cool Select+, LED | – | [karta](https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb70f30bes0eo-ai) |
| **Samsung BRB80F30BES0EO** | alternatywa | **3499,99 zł** (było 3999,99) | darmowa | dostępny | ✓ te same parametry + **Metal Cooling** | +201 zł za Metal Cooling. 229 kWh/rok, klasa E. **Uwaga:** wersje BRB80F30**ADS0EO/ADF0EO** mają cashback Samsung 300 zł – BES0EO nie jest potwierdzone | [karta](https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb80f30bes0eo-ai) |
| Samsung BRB80F30BEF0EO | alternatywa | 3589,00 zł | darmowa | dostępny | ✓ | +290 zł, bez wyraźnej korzyści | [karta](https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb80f30bef0eo-ai) |
| Samsung BRB80F30BDS0EO | alternatywa | 3997,96 zł | darmowa | dostępny | ✓ | +699 zł – nieopłacalne | [karta](https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb80f30bds0eo-ai) |
| Samsung BRB80F30ADF0EO | alternatywa (wariant A) | 4299,00 zł | darmowa | dostępny | ✓ | +1000 zł – nieopłacalne, mimo potencjalnego cashbacku 300 zł | [karta](https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb80f30adf0eo-ai) |
| Samsung BRB70F30**A**ES0EO | wariant | **brak oferty** | – | – | – | – | – |

Alternatywy innej marki spełniającej komplet MUST w Avans **nie ma** (lodówki do zabudowy 193,5 cm z dwoma obiegami to praktycznie tylko Samsung).

---

## 3. Płyta indukcyjna

MUST: 59–60 cm · strefa łączona · 4 pola · Booster · osobny suwak na strefę · **błyszczące** czarne szkło · blokada dzieci · ciepło resztkowe

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WB S2560 NE** | wzorzec (bez matu) | **brak oferty** | – | – | – | Wyszukiwarka podstawia WBS0060NE – to **inny model** | – |
| **Whirlpool WBS0060NE** | alternatywa (najtańsza) | **1199,00 zł** | darmowa | dostępny, pon. 26.10 | ✓ 59 × 51 cm · **łączenie pól Tak** · **4 pola** (1200/1600, 1800/2100, 1800/2100, **2100/3000 W**) · **Booster** ✓ · sterowanie dotykowe (osobny suwak na strefę **?**) · **czarne szkło bez szlifu (błyszczące)** ✓ · **zabezpieczenie przed dziećmi** ✓ · ciepło resztkowe ✓ | **−400 do −700 zł vs typowa cena wzorca.** Ma też **6. Zmysł** i Timer. Brak potwierdzenia „Direct Access” (osobny suwak per strefa) | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-whirlpool-wb-s0060-ne) |
| **Whirlpool WLS7260NE** | alternatywa (FlexiCook) | **1899,99 zł** | darmowa | dostępny | ✓ 59 × 51 · **FlexiCook – łączenie pól** ✓ · **4 pola** (4 × 1750/2200 W) · Booster ✓ (2200 W, nie 3 kW) · elektronika dotykowa · czarne szkło ceramiczne ✓ · ciepło resztkowe ✓ · **blokada dzieci – tylko „wyłącznik bezpieczeństwa”** ✗/? | Wersja „nowsza” z FlexiCook i automatyką (rozpuszczanie, podtrzymywanie, wolne gotowanie, timer). Jest na liście cashbacku Whirlpool. **Nie ma MattProtect** | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-indukcyjna-whirlpool-wl-s7260-ne) |
| ⚠ Whirlpool WLS5360BFW | odrzucone | 1698,98 zł | darmowa | dostępny | kolor **biały** ✗ | Nie pasuje do czarnej reszty | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-indukcyjna-whirlpool-wl-s5360-bf-w) |
| ⚠ Whirlpool WLS2760BFS | odrzucone | 1799,00 zł | darmowa | dostępny | kolor **szampański** ✗ | Nie pasuje kolorystycznie | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-indukcyjna-whirlpool-wl-s2760-bf-s) |
| ⚠ Whirlpool MWS2260PCPNEBM | odrzucone | 1999,99 zł | darmowa | dostępny | **MattProtect** (mat) ✗ | Wprost odrzucone w wymaganiach | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-whirlpool-mws2260pcpnebm-mattprotect-flexispace-hob-to-hood-59cm) |
| Whirlpool WBB3960BF | alternatywa | 1439,99 zł | darmowa | dostępny | ConnexionZone, 9 poziomów; FlexiCook ? | Środek między 1199 a 1899 zł | [karta](https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-indukcyjna-whirlpool-wbb3960bf-connexionzone-9-poziomow-mocy) |

---

## 4. Okap teleskopowy

MUST: teleskop 60 cm · mieści się w szafce gł. 35 cm · wylot **fi 150** · 400–600 m³/h na zwykłym biegu · ≤~55 dB · metalowe filtry do zmywarki · klapa zwrotna

Uwaga: podane dB to **moc akustyczna** (LwA) – realnie w kuchni jest o ok. 7–10 dB ciszej. Filtr „klapa zwrotna” – sklep nie podaje jej w karcie żadnego modelu; kupuje się osobno (Avans ma akcesoria do okapów).

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Amica OTP6651BG** | najlepszy kandydat (z wymagań) | **613,00 zł** | darmowa | dostępny, pon. 26.10 | ✓ teleskopowy 60 cm · **głębokość 30 cm** (szafka 35) ✓ · **wylot fi 15 cm** ✓ · **508 m³/h** na biegu standardowym ✓ · 63 dB (moc akust.) — granica ✓/? · **2 filtry aluminiowe** (zmywarka) ✓ · klapa zwrotna **?** (brak w karcie) | Czarne szkło, sterowanie sensorowe, **Timer (wybieg)** ✓, klasa **B**, silnik 154 W. BLDC niepotwierdzony | [karta](https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-amica-otp6651bg-czarne-szklo-508m3-h-63db-klasa-b-timer) |
| **VDB Vector ME 60** | alternatywa (mocniejsza) | **797,79 zł z kodem RWE0110-3110** (889,99 zł bez) | darmowa | dostępny | ✓ teleskopowy 60 cm · gł. **29 cm** ✓ · **fi 15 cm** ✓ · **526 m³/h std / 788 turbo** ✓ · **62 dB** · 2 filtry aluminiowe ✓ | klasa B, sterowanie dotykowe, funkcja czasowego wyłączenia. +185 zł, ale więcej mocy i ciszej o 1 dB | [karta](https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-vdb-vector-me-60-czarny) |
| **Götze & Jensen TH600KT** | alternatywa | **799,54 zł z kodem** (889,99 zł bez) | darmowa | dostępny | ✓ teleskopowy 60 · gł. 28,5 cm ✓ · **fi 15 cm** ✓ · **470 m³/h std / 635 turbo** ✓ · **60 dB** (najciszej z tanich) · 2 filtry aluminiowe ✓ | klasa B, Timer. Najcichszy z porównywanych | [karta](https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-gotze-jensen-th600kt-czarny-470m3-h-60db-klasa-b-timer) |
| Elica Elite 26 IX/A/60 | alternatywa | 638,99 zł | darmowa | dostępny | ✓ teleskop 60 · gł. 28 cm · **fi 15 cm** ✓ · **480/581 m³/h** · **61 dB** · 2 filtry alu ✓ | Inox (nie czarny), klasa C. Można osadzić front szafki | [karta](https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-elica-elite-26-ix-a-60-inox-581m3-h-61db-klasa-c) |
| ⚠ Amica OTP6641BG | odrzucone | 523,00 zł | darmowa | dostępny | **wylot fi 12 cm** ✗ (wymagałby redukcji) | Odrzucone wprost przez MUST | [karta](https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-amica-otp6641bg-czarny-389m3-h-65db-klasa-c-funkcja-czasowego-wylaczenia) |
| Bosch DFS067K51 | alternatywa z wymagań | **brak oferty** | – | – | – | – | – |

---

## 5. Mikrofalówka do zabudowy

MUST: talerz ≥ ~31–32 cm · do zabudowy 60 cm · wysokość urządzenia ~38 cm

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WMD54MB** | najlepszy kandydat | **1849,00 zł** | darmowa | **dostępny**, pon. 26.10 | ✓ **talerz 32,5 cm**, 31 l · 59,5 × 38,5 cm, „Rodzaj: Do zabudowy” ✓ · czarny · 1000 W, 6. Zmysł, Jet Defrost | Ta sama linia co piekarnik Whirlpool (czarne szkło). Ma grill (moc mikrofali 1000 W) – niepotrzebny. **Jest na liście cashbacku Whirlpool** | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-whirlpool-wmd54mb-1000w-srednica-32-5-cm-pojemnosc-31l-szosty-zmysl-jet-defrost-czarny) |
| Whirlpool WMD7O4TX | alternatywa (taniej) | **1698,00 zł** | darmowa | dostępny | ✓ talerz 32,5 cm, 31 l, 59,5 × 38,5 cm | −151 zł vs WMD54MB; 1000 W, 6. Zmysł | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-whirlpool-wmd7o4tx-1000w-srednica-32-5-cm-pojemnosc-31l-szosty-zmysl-jet-defrost-czarny) |
| **Bosch BEL554MB0 Serie 6** | alternatywa (inna marka) | **1898,00 zł** | darmowa | dostępny | ✓ **talerz 31,5 cm** (granica „ok. 31–32”), 25 l · 38,8 cm wys. · czarny + hydroliza | Inna marka niż piekarnik, ale czarne szkło. Autopilot, Auto Defrost | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-bosch-bel554mb0-serie-6-900w-srednica-31-5-pojemnosc-25l-auto-defrost-hydroliza-czarny) |
| **Hisense BIM325G62BG2** | alternatywa (najtaniej) | **1296,88 zł z kodem RWE0110-3110** (1599,99 zł bez) | darmowa | dostępny | ✓ talerz **31,5 cm**, 25 l · 59,5 × 38,8 cm · czarny | −552 zł vs WMD54MB, ale 25 l zamiast 31 l (mniejsza wnęka) | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchnia-mikrofalowa-hisense-bim325g6bg2) |
| Whirlpool W6MD440NB | kandydat z wymagań | 1949,00 zł | – | **produkt chwilowo niedostępny** | ✓ (31 l, 32,5 cm) | Nie da się kupić | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchnia-mikrofalowa-whirlpool-w6-md-440-nb) |
| Whirlpool WMD7O4TB | alternatywa | 1949,00 zł | – | **chwilowo niedostępny** | ✓ (31 l, 32,5 cm, talerz Crisp) | – | [karta](https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchnia-mikrofalowa-whirlpool-wmd7o4tb-wcollection-poj-31-czarna) |
| Whirlpool W7 MD440 NB | kandydat z wymagań | **brak oferty** (podstawia W6MD440NB) | – | – | – | – | – |
| Bosch BFL554MB0 | alternatywa z wymagań | **brak oferty** (są BFL553MS0 1549 zł, BEL554MB0 1898 zł) | – | – | – | – | – |

---

## 6. Zmywarka do zabudowy

MUST: pełna zabudowa 60 · 14–15 kpl · 3. kosz · ≤40 dB · auto‑uchylanie drzwi · dysze na garnki · regulowane kosze, stal

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool W7IHT58T (W7I HT58 T)** | **wzorzec** | **2299,00 zł** | darmowa | dostępny, pon. 26.10 | ✓ 60 cm, 82 × 55,5 · **15 kpl** · **3. szuflada** · **38 dB** · **auto‑otwieranie drzwi** · **PowerClean** · MaxiSpace/ExtraSpace, komora stal nierdzewna ✓ | Dodatkowo: **AquaStop ✓** (w karcie jest – w wymaganiach było „?”), **wyświetlacz czasu na podłodze ✓**, 8 programów, klasa **B**, 65 kWh, 9,5 l. Zawiasy **zwykłe** (NICE nie spełnione) | [karta](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-w7i-ht58-t) |
| **Whirlpool WH8IA15AM3TUS0** | alternatywa+ | **3197,96 zł z kodem RWE0110-3110** (3519,99 zł bez) | darmowa | dostępny | ✓ 15 kpl · 38 dB · 3. szuflada · auto‑drzwi · PowerClean Pro · **zawiasy ślizgowe** ✓ | **klasa A** (55 kWh vs 65), zawiasy ślizgowe, kosz SpaceClean. +899 zł | [karta](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-wh8ia15am3tus0) |
| **Beko MEDIN3755A** | alternatywa | **2496,96 zł z kodem RWE0110-3110** (2799,99 zł bez) | darmowa | dostępny | ✓ 15 kpl · **40 dB** (granica) · 3. szuflada · auto‑drzwi · **PowerIntense** (dysze) ✓ | **AutoDose** (NICE), HomeWhiz, 8,9 l wody. +198 zł vs wzorzec, głośniejsza o 2 dB | [karta](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-beko-medin3755a) |
| Whirlpool WH8IA15AM3TUCH0 | alternatywa | 3398,99 zł | darmowa | dostępny | ✓ + wyświetlacz czasu na podłodze | +1100 zł – nieopłacalne | [karta](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-wh8ia15am3tuch0-technologia-6-zmysl) |

---

## 7. Pralka + suszarka (słupek)

| Model | Typ | Cena (brutto) | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Samsung WW90CGC04DAE** | pralka wzorcowa | **brak oferty** – Avans ma inne końcówki: **DAH / DAB / DTH** | – | – | – | – | – |
| **Samsung WW90CGC04DAH** | pralka (najbliższa wzorcowi) | **1799,00 zł** (było 1899) | darmowa | dostępny, pon. 26.10 | ✓ wolnostojąca, 60 cm, **gł. 55 cm** (63,5 z drzwiami) · **9 kg** · **1400 obr.** · **klasa A** (44 kWh/100) · **silnik inwerterowy** ✓ · funkcje parowe, AI Energy, SmartThings | Klasa wirowania B, 72 dB. **Ta sama cena jak w euro.com.pl** (1799 zł). Zgodność z łącznikiem potwierdzona kartą SKK‑DD | [karta](https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-samsung-ww90cgc04dah-9kg-1400-obr) |
| Samsung WW90CGC04DTH | pralka (alternatywa) | 1999,00 zł | darmowa | dostępny | ✓ (te same parametry) | +200 zł, bez korzyści | [karta](https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-samsung-ww90cgc04dth-9kg-1400-obr) |
| Samsung WW90CGC04DAB | pralka (alternatywa) | 2399,99 zł | darmowa | dostępny | ✓ | +601 zł – nieopłacalne | [karta](https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-samsung-ww90cgc04dab-9kg-1400-obr) |
| **Samsung DV9MDG52A0AE** | suszarka wzorcowa | **brak oferty** (wyszukiwarka: „nie udało się znaleźć”) | – | – | – | – | – |
| **Samsung DV90DG52A0AEEO** | suszarka (najbliższa wzorcowi) | **2499,00 zł** | darmowa | dostępny, pon. 26.10 | ✓ pompa ciepła, **9 kg** · **klasa C** (105 kWh/100) · **64 dB** · **wąż odpływowy w zestawie ✓** · **możliwość montażu na pralce** ✓ · funkcje AI/SmartThings | Sensorem wilgotności jest OptimalDry/AI; samoczyszczącego skraplacza **nie ma**. Zgodna z SKK‑DD wg karty łącznika | [karta](https://www.avans.pl/agd/pralki-i-suszarki/suszarki/suszarka-samsung-dv5000d-dv90dg52a0ae-z-pompa-ciepla-optimal-dry) |
| Samsung DV90DG52A0AHEO | suszarka (alternatywa) | 2799,00 zł | darmowa | dostępny | ✓ | +300 zł, bez wyraźnej korzyści | [karta](https://www.avans.pl/agd/pralki-i-suszarki/suszarki/suszarka-samsung-dv5000d-dv90dg52a0ah-z-pompa-ciepla-optimal-dry) |
| **Samsung SKK‑DD** (łącznik z półką) | akcesorium | **223,02 zł** | darmowa | dostępny | ✓ **karta podaje przeznaczenie: DV90DG52A0AEEO, DV90DG52A0AHEO, DV90DG52A0TEEO, WW90CGC04DAHEO, WW90CGC04DTHEO** | Zgodność z tą parą **potwierdzona przez sklep** (mocna strona Avansu – na Allegro to było „?”) | [karta](https://www.avans.pl/agd/pralki-i-suszarki/laczniki-pralek-i-suszarek/lacznik-samsung-skk-dd) |
| **Bosch WGG244FRPL** | alternatywa (pralka) | 3399,99 zł | darmowa | dostępny | ✓ 9 kg, 1400, A (49 kWh), inwerter, 71 dB | +1601 zł vs Samsung | [karta](https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-bosch-wgg244frpl-9kg-1400-obr) |
| ⚠ Bosch WGG244F8PL | odrzucone | 2999,00 zł | – | **chwilowo niedostępny** | ✓ | – | [karta](https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-bosch-wgg244f8pl-9kg-1400-obr) |
| Bosch WGG244ZEPL | alternatywa z wymagań | **brak oferty** | – | – | – | – | – |
| **Bosch WQG244CSPL Serie 6** | alternatywa (suszarka) | 2999,00 zł | darmowa | dostępny | ✓ pompa ciepła **9 kg** · **61 dB** · 110 kWh (klasa C) · **SelfCleaning Condenser** ✓ · **DrainSet + wąż w zestawie** ✓ · **AutoDry** + czujnik wilgotności ✓ · montaż na pralce ✓ | **+500 zł vs Samsung**, ale: samoczyszczący skraplacz, ciszej (61 vs 64 dB), pełny DrainSet. Potencjalny zwrot Bosch **do 1000 zł** (niepotwierdzone dla tego modelu) | [karta](https://www.avans.pl/agd/pralki-i-suszarki/suszarki/suszarka-bosch-wqg244cspl-serie-6-z-pompa-ciepla) |
| Bosch WQG245DEPL | alternatywa z wymagań | **brak oferty** („nie udało się znaleźć”) | – | – | – | – | – |
| Bosch WTZ27400 (łącznik) | akcesorium | **brak oferty** – Avans ma tylko SKK‑DD/SSW/SSV/UDW, WPRO KCL103 (179,99), Meliconi (139,99) | – | – | – | Kupując Boscha trzeba dokupić łącznik poza Avansem (ok. 260–400 zł) | [łączniki](https://www.avans.pl/agd/pralki-i-suszarki/laczniki-pralek-i-suszarek) |

**Para Samsung w Avans:** pralka 1799,00 + suszarka 2499,00 + SKK‑DD 223,02 = **4521,02 zł** (dostawa 0 zł).
**Para Bosch w Avans:** 3399,99 + 2999,00 = **6398,99 zł**, plus łącznik, którego Avans nie sprzedaje (ok. 260–400 zł poza sklepem) → **ok. 6660–6800 zł**. Różnica ok. 2,1–2,3 tys. zł.

---

## Koszyk w tym sklepie

Wariant „najtańszy sensowny” (wszystkie kategorie obsłużone; MUST spełnione poza zaznaczonymi wyjątkami):

| # | Kategoria | Model | Cena | Dostawa | Uwaga o MUST |
|---|---|---|---|---|---|
| 1 | Piekarnik | Hisense BSA6633PBG8 | 2499,99 zł | 0 zł | para + zbiornik na wodę ✓, termosonda ✓, teleskopy 2 poz. ✓; pyroliza zamiast hydrolizy |
| 2 | Lodówka | Samsung BRB70F30BES0EO | 3299,00 zł | 0 zł | komplet MUST ✓ |
| 3 | Płyta | Whirlpool WBS0060NE | 1199,00 zł | 0 zł | suwak per strefa niepotwierdzony |
| 4 | Okap | Amica OTP6651BG | 613,00 zł | 0 zł | klapa zwrotna do dokupienia |
| 5 | Mikrofalówka | Whirlpool WMD54MB | 1849,00 zł | 0 zł | komplet MUST ✓ |
| 6 | Zmywarka | Whirlpool W7IHT58T | 2299,00 zł | 0 zł | komplet MUST ✓ (+AquaStop) |
| 7 | Pralka | Samsung WW90CGC04DAH | 1799,00 zł | 0 zł | komplet MUST ✓ |
| 8 | Suszarka | Samsung DV90DG52A0AEEO | 2499,00 zł | 0 zł | komplet MUST ✓ |
| 9 | Łącznik | Samsung SKK‑DD | 223,02 zł | 0 zł | zgodność potwierdzona |
| | **SUMA** | | **16 280,01 zł** | **0 zł** | |

**Braki w sklepie:** piekarnik wzorcowy (WOI7A8FHT2SBA), płyta wzorcowa (WB S2560 NE), mikrofalówka W7 MD440 NB, pralka DAE, suszarka DV9MDG52A0AE, okap Bosch DFS067K51, pralka/suszarka Bosch ZEPL/DEPL. **Wszystko zastąpione odpowiednikami** – koszyk jest kompletny.

**Warianty koszyka:**

| Wariant | Zmiana | Cena koszyka | Komentarz |
|---|---|---|---|
| Bazowy (wyżej) | – | **16 280,01 zł** | najtańszy sensowny |
| Piekarnik → Whirlpool WOI7P8FHT1SBA | +899,01 zł | 17 179,02 zł | lepsza klasa A++, Pizza 310, ale teleskopy 1 poz. |
| Piekarnik → Whirlpool WOI11P8FHT2SBAF | +2098,00 zł | 18 378,01 zł | **jedyny z pełnym MUST** |
| Piekarnik → Whirlpool WOI7A8HT2SBA (3849,98 z kodem) | +1350,00 zł | 17 630,00 zł | teleskopy 2 poz. + hydroliza, ale **bez termosondy** |
| Piekarnik → Amica ED975396BA+ (2099,99) | −400,00 zł | 15 880,01 zł | **taniej, ale bez zbiornika na wodę i bez hydrolizy** |
| Płyta → Whirlpool WLS7260NE | +700,99 zł | 16 981,00 zł | potwierdzony FlexiCook + 6. Zmysł |
| Mikrofalówka → Hisense BIM325G62BG2 | −552,12 zł | 15 727,89 zł | 25 l zamiast 31 l |
| Zmywarka → Beko MEDIN3755A | +197,96 zł | 16 477,97 zł | AutoDose, 40 dB |
| Pralnia → Bosch (WGG244FRPL + WQG244CSPL + łącznik ~260 zł) | +2137,97 zł | 18 417,98 zł | samoczyszczący skraplacz, ciszej, ale łącznika Bosch **nie ma w Avans** |

Dodatki opcjonalne: wniesienie 99,99 zł/szt. (lodówka 109,99), montaż w zabudowie 319,99 zł/szt. (piekarnik, lodówka, zmywarka, pralka; płyta – tylko wniesienie 99,99 zł), odbiór starego sprzętu **0 zł**.

**Czy opłaca się kupować całość tutaj?** Tak – dostawa 0 zł przy całym koszyku, ceny wzorca lodówki (3299 zł) i zmywarki (2299 zł) są na poziomie najtańszych ofert rynkowych, a łącznik SKK‑DD jest tu tańszy niż na Allegro (223 zł vs 227–250 zł) i **z potwierdzoną zgodnością**. Słabe punkty: piekarnik (brak modelu z pełnym MUST w dobrej cenie), płyta (brak wzorca) i pralnia (tylko warianty DAH/DAB/DTH, brak DAE).

---

## Tabela do porównania

`kategoria | model | cena brutto | dostawa | promocja netto | MUST | url`

```
piekarnik | Whirlpool WOI11P8FHT2SBAF | 4597.99 | 0 | brak | TAK (pełne) | https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi11p8fht2sbaf-elektryczny-parowy-czarny-a-termosonda
piekarnik | Whirlpool WOI7P8FHT1SBA | 3399.00 | 0 | brak | NIE (teleskopy 1 poziom) | https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi7p8fht1sba-elektryczny-czarny-a-termosonda
piekarnik | Whirlpool WOI7A8HT2SBA | 3849.98 (4429.99 bez kodu RWE1310-311026) | 0 | -580.01 | NIE (brak termosondy) | https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-whirlpool-woi7a8ht2sba-elektryczny-parowy-czarny-a
piekarnik | Amica ED975396BA+ X-TYPE Steam P | 2099.99 | 0 | brak | NIE (brak zbiornika na wode, pyroliza zamiast hydrolizy) | https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-amica-ed975396ba-x-type-steam-p-elektryczny-parowy-czarny-a
piekarnik | Hisense BSA6633PBG8 | 2499.99 | 0 | brak | PRAWIE (zbiornik + termosonda + teleskopy 2 poz., pyroliza zamiast hydrolizy) | https://www.avans.pl/agd-do-zabudowy/piekarniki-do-zabudowy/piekarnik-hisense-bsa6633pbg8-elektryczny-parowy-czarny-a
lodowka | Samsung BRB70F30BES0EO | 3299.00 | 0 | brak | TAK | https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb70f30bes0eo-ai
lodowka | Samsung BRB80F30BES0EO | 3499.99 | 0 | brak | TAK | https://www.avans.pl/agd-do-zabudowy/lodowki-i-zamrazarki-do-zabudowy/lodowki-do-zabudowy/lodowka-samsung-brb80f30bes0eo-ai
plyta | Whirlpool WBS0060NE | 1199.00 | 0 | brak | TAK/? (suwak per strefa ?) | https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-whirlpool-wb-s0060-ne
plyta | Whirlpool WLS7260NE | 1899.99 | 0 | brak | TAK/? (brak potwierdzonej blokady dzieci) | https://www.avans.pl/agd-do-zabudowy/plyty-do-zabudowy/plyta-indukcyjna-whirlpool-wl-s7260-ne
okap | Amica OTP6651BG | 613.00 | 0 | brak | TAK/? (klapa zwrotna do dokupienia) | https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-amica-otp6651bg-czarne-szklo-508m3-h-63db-klasa-b-timer
okap | VDB Vector ME 60 | 797.79 | 0 | -92.20 (kod RWE0110-3110) | TAK/? | https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-vdb-vector-me-60-czarny
okap | Gotze & Jensen TH600KT | 799.54 | 0 | -90.45 (kod RWE0110-3110) | TAK/? | https://www.avans.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-gotze-jensen-th600kt-czarny-470m3-h-60db-klasa-b-timer
mikrofala | Whirlpool WMD54MB | 1849.00 | 0 | brak | TAK | https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-whirlpool-wmd54mb-1000w-srednica-32-5-cm-pojemnosc-31l-szosty-zmysl-jet-defrost-czarny
mikrofala | Whirlpool WMD7O4TX | 1698.00 | 0 | brak | TAK | https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-whirlpool-wmd7o4tx-1000w-srednica-32-5-cm-pojemnosc-31l-szosty-zmysl-jet-defrost-czarny
mikrofala | Bosch BEL554MB0 | 1898.00 | 0 | brak | TAK (talerz 31.5 cm - granica) | https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchenka-mikrofalowa-bosch-bel554mb0-serie-6-900w-srednica-31-5-pojemnosc-25l-auto-defrost-hydroliza-czarny
mikrofala | Hisense BIM325G62BG2 | 1296.88 | 0 | -303.11 (kod RWE0110-3110) | TAK (25 l) | https://www.avans.pl/agd-do-zabudowy/kuchnie-mikrofalowe-do-zabudowy/kuchnia-mikrofalowa-hisense-bim325g6bg2
zmywarka | Whirlpool W7IHT58T | 2299.00 | 0 | brak | TAK (+AquaStop, projekcja) | https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-w7i-ht58-t
zmywarka | Whirlpool WH8IA15AM3TUS0 | 3197.96 | 0 | -322.03 (kod RWE0110-3110) | TAK (klasa A, zawiasy slizgowe) | https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-wh8ia15am3tus0
zmywarka | Beko MEDIN3755A | 2496.96 | 0 | -303.03 (kod RWE0110-3110) | TAK (40 dB, AutoDose) | https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-beko-medin3755a
pralka | Samsung WW90CGC04DAH | 1799.00 | 0 | brak | TAK | https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-samsung-ww90cgc04dah-9kg-1400-obr
pralka | Samsung WW90CGC04DTH | 1999.00 | 0 | brak | TAK | https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-samsung-ww90cgc04dth-9kg-1400-obr
pralka | Bosch WGG244FRPL | 3399.99 | 0 | brak | TAK | https://www.avans.pl/agd/pralki-i-suszarki/pralki/pralka-bosch-wgg244frpl-9kg-1400-obr
suszarka | Samsung DV90DG52A0AEEO | 2499.00 | 0 | brak | TAK (waz w zestawie) | https://www.avans.pl/agd/pralki-i-suszarki/suszarki/suszarka-samsung-dv5000d-dv90dg52a0ae-z-pompa-ciepla-optimal-dry
suszarka | Bosch WQG244CSPL | 2999.00 | 0 | brak (mozliwy zwrot Bosch do 1000 zl - niepotwierdzone) | TAK (SelfCleaning, DrainSet) | https://www.avans.pl/agd/pralki-i-suszarki/suszarki/suszarka-bosch-wqg244cspl-serie-6-z-pompa-ciepla
lacznik | Samsung SKK-DD | 223.02 | 0 | brak | TAK (zgodnosc potwierdzona) | https://www.avans.pl/agd/pralki-i-suszarki/laczniki-pralek-i-suszarek/lacznik-samsung-skk-dd
```

---

## Wnioski

1. **Najtańsza sensowna konfiguracja: 16 280,01 zł** (piekarnik Hisense BSA6633PBG8 2499,99 + lodówka BRB70F30BES0EO 3299 + płyta WBS0060NE 1199 + okap OTP6651BG 613 + mikrofalówka WMD54MB 1849 + zmywarka W7IHT58T 2299 + pralka WW90CGC04DAH 1799 + suszarka DV90DG52A0AEEO 2499 + łącznik SKK‑DD 223,02). Dostawa 0 zł, bo zamówienie >99 zł. Zejście do 15 880 zł możliwe tylko przez piekarnik Amica (2099,99), ale on **nie ma szuflady/zbiornika na wodę**.
2. **Piekarnik to jedyny prawdziwy problem tego sklepu.** Nie ma wzorca WOI7A8FHT2SBA, a jedyny model z kompletem MUST (**WOI11P8FHT2SBAF**) kosztuje 4597,99 zł. Kompromisy: **Hisense 2499,99** (zbiornik + termosonda + 2 poziomy teleskopów, pyroliza zamiast hydrolizy) lub WOI7P8FHT1SBA 3399 (teleskopy na 1 poziomie). **Uważaj na WOI7A8HT2SBA** – wygląda jak wzorzec, ale ma **„Termosonda: Nie”**.
3. **Lodówka wzorcowa jest tu w dobrej cenie (3299 zł) i z pewnym kodem BRB70F30BES0EO**, z potwierdzonymi zawiasami ślizgowymi, Twin Cooling i 35 dB. Wersje BRB80F30 różnią się literą (B/A/D/F) – nie płacisz za nie więcej niż 200 zł.
4. **Pralnia: kupuj tu, ale w wersji DAH.** Zamiast DAE jest **WW90CGC04DAH za 1799 zł** – ta sama specyfikacja (9 kg, 1400, A, inwerter) i **dokładnie ta sama cena co w euro.com.pl**. Do tego suszarka **DV90DG52A0AEEO 2499 zł** (9 kg, C, wąż w zestawie) i **SKK‑DD 223,02 zł z potwierdzoną listą zgodności** (DAHEO + DV90DG52A0AEEO). Para Bosch wypada ok. 2,1–2,3 tys. zł drożej, m.in. dlatego, że łącznika WTZ27400 tu nie ma.
5. **Terminy:** kody **RWE0110-3110 i RWE1310-311026 wygasają 31.10.2026 o 21:59** (działają m.in. na zmywarkę Beko, Whirlpool WH8IA15AM3TUS0, mikrofalówkę Hisense i okapy VDB/Gö&J – łącznie do ok. 1 tys. zł oszczędności, jeśli wybierzesz te modele). **Raty 0% do 02.11.2026.** Cashback Whirlpool (rejestracja do 14.01.2027) obejmuje piekarnik WOI7A8HT2SBA + płytę WLS7260NE/WBS0060NE + mikrofalówkę WMD54MB – ale ten piekarnik nie ma termosondy. Cashback Samsung dla pary DAH/DV90DGG… **niepotwierdzony** (lista producenta zawiera modele DAE).
6. **Pułapki:** (a) Avans nie ma marketplace'u – wszystkie ceny są własne, z polską gwarancją, ale wybór modeli jest węższy niż na Allegro; (b) płyty Whirlpool z „MattProtect” (MWS2260PCPNEBM) i białe/szampańskie wersje WLS są w ofercie obok – łatwo pomylić; (c) okap Amica OTP6641BG (523 zł) jest tańszy, ale ma **wylot fi 120** i wymagałby redukcji; (d) montaż w zabudowie to **319,99 zł za urządzenie** – przy 4 urządzeniach do zabudowy to prawie 1,3 tys. zł dodatkowo, a wniesienie 99,99–109,99 zł/szt.
