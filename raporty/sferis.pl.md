# sferis.pl – raport (2026-10-25)

## Jak zebrano ceny

- **Ceny sprawdzone na żywo: 25.10.2026, ok. 23:00–23:55 czasu polskiego** (CEST), przez prawdziwą przeglądarkę (Chromium), na stronach listingów kategorii i kartach produktów sferis.pl. Każda cena w tym raporcie pochodzi z karty produktu lub listingu odczytanego w tej sesji — nie ze snippetów.
- **Sklep nie blokuje botów w rozumieniu captcha**: brak 403/DataDome, brak captchy. Warunki techniczne: (a) strona wymaga JavaScript (listing i paginacja `?p=N` renderowane po stronie klienta), (b) samo `curl`/żądanie bez przeglądarki jest zrywane na TLS (połączenie resetowane) — dlatego użyłem przeglądarki, **nie obchodziłem żadnego zabezpieczenia**, tylko czytałem stronę jak użytkownik, (c) przed pierwszym wejściem trzeba zaakceptować cookies (Cookiebot) — zrobiłem to raz, w trybie „zezwól na wszystkie”.
- **Zakres sprawdzenia** (liczby ofert z nagłówków kategorii, stan 25.10.2026): piekarniki 71, lodówki 111 (w tym 14 do zabudowy), płyty grzewcze 134 (w tym 59 indukcyjnych, z tego 30 o szer. 59–60 cm), okapy 131 (w tym 10 teleskopowych), kuchenki mikrofalowe 27 (9 do zabudowy), zmywarki 77 (w tym 60 cm i 45 cm do zabudowy), pralki 63, suszarki 10.
- Dodatkowo przeczytałem na żywo: `/kody-rabatowe`, `/dostawa`, `/dostawa/zadbano`, `/formy-platnosci`, `/promocje-bosch`, `/newsletter`, oraz sitemap produktów (24 586 URL) do sprawdzenia, czy dany model w ogóle występuje w katalogu.
- **Dostępność**: każda pozycja w koszyku miała status „Produkt Dostępny” i „Zamów teraz aby otrzymać: **2026-10-27**” (następny dzień roboczy).
- **Sprzedaż**: sferis.pl to sklep **Action S.A.** — **sprzedaż własna, bez marketplace’u**. Gwarancja producenta 24 mies. (tak podane w kartach dla AGD), faktura VAT.
- Ceny zewnętrzne (whirlpool.pl, Refunder, strony producentów) podaję wyłącznie jako punkt odniesienia i oznaczam.

> **Pułapka katalogowa:** sferis.pl **nie ma w ofercie żadnego z 7 modeli wzorcowych** ani głównych alternatyw z wymagań (Samsung BRB70F30BES0EO, Whirlpool WOI7A8FHT2SBA, Whirlpool WB S2560 NE, Whirlpool W7 MD440 NB, Whirlpool W7I HT58 T, Samsung WW90CGC04DAE / DV9MDG52A0AE, Bosch WGG244ZEPL / WQG245DEPL / WTZ27400). Asortyment AGD do zabudowy jest wąski i zdominowany przez **Bosch, Electrolux, Beko, Amica, Gorenje** — Whirlpool jest reprezentowany szczątkowo (21 adresów produktowych w indeksie sklepu), a **Samsung AGD praktycznie nie istnieje** (0 lodówek, 0 pralek Samsung — jest tylko pralko-suszarka WD90DG5G34BBEO).

---

## Promocje / kupony

| Promocja | Warunki | Ważność | Czy działa na te modele | Źródło |
|---|---|---|---|---|
| **Newsletter −10 zł / −50 zł** | Kod z zapisu na newsletter: **10 zł przy koszyku ≥ 200 zł** albo **50 zł przy koszyku ≥ 2000 zł**. Kod jednorazowy, wpisywany w koszyku | bez terminu (kod po zapisie) | **Tak, na cały koszyk.** Przy koszyku AGD > 2000 zł realnie działa wariant −50 zł | [sferis.pl/kody-rabatowe](https://www.sferis.pl/kody-rabatowe) — sprawdzone na żywo 25.10.2026 |
| **Kody rabatowe per produkt** | Strona „Kody rabatowe” zbiera produkty z **indywidualnym kodem, zniżką i terminem**; regulamin przy każdej ofercie | różne, „do wyczerpania” | **Żaden z 7 modeli wzorcowych ani żaden produkt z mojego koszyka nie ma kodu** (sprawdziłem karty) | [sferis.pl/kody-rabatowe](https://www.sferis.pl/kody-rabatowe) |
| **Darmowa dostawa AGD** | Na kartach produktów AGD do zabudowy: „**Darmowa dostawa**”, listing: „Dostawa 0zł”. Standardowo (poza AGD): Paczkomat/DPD od 599 zł 0 zł, kurier 17,90–19,90 zł | bieżąca | **Tak dla 7 z 9 pozycji koszyka** (8 urządzeń + łącznik). Wyjątki: **lodówka** — „Dostawa już od **67,90 zł**” (półpaleta), **łącznik** — „Dostawa już od 17,90 zł” | [sferis.pl/dostawa](https://www.sferis.pl/dostawa), karty produktów |
| **Cennik dostaw gabarytowych** | Kurier 19,90 zł (+7 zł pobranie), kurier InPost 17,90 zł, **półpaleta od 67,90 zł, paleta od 147,90 zł**, punkt UPS/FedEx 19,90 zł | bieżący (aktualizacja strony 05.08.2026) | Tak — dotyczy pralek, lodówek, zmywarek | [sferis.pl/dostawa](https://www.sferis.pl/dostawa) |
| **Dostawa z wniesieniem / z instalacją (Zadbano)** | Osobno płatne pakiety: **piekarniki** wniesienie 99 zł / instalacja 319 zł; **płyty** 99 / 249 zł; **okapy** 99 / 169 zł; **mikrofale** 68 / 199 zł; **zmywarki i pralki** 99–139 / 249–319 zł; **lodówki** 139 / 249–319 zł. **Odbiór starego urządzenia to dodatkowo płatna usługa poza pakietem** | bez terminu | Tak, dla wszystkich pozycji koszyka | [sferis.pl/dostawa/zadbano](https://www.sferis.pl/dostawa/zadbano) |
| **Raty 0%** | Badge „Raty 0%” + „Rata już od …” na kartach AGD (np. piekarnik 1739 zł → rata 0% od 39,44 zł; zmywarka 2399 zł → 50,77 zł). Liczba rat/RRSO **nie są podane na stronie** — widać je dopiero w koszyku | bez terminu | Tak (wszystkie pozycje koszyka mają „Raty 0%”) | karty produktów; [sferis.pl/formy-platnosci](https://www.sferis.pl/formy-platnosci) |
| **PayPo – zapłać za 30 dni** | Odroczona płatność, limit wg operatora; na kartach AGD: „Kup teraz, zapłać za 30 dni z PayPo” | bez terminu | Tak | [sferis.pl/formy-platnosci](https://www.sferis.pl/formy-platnosci) |
| **Cashback Bosch – suszarki i pralko-suszarki (do 1000 zł)** | Zakup 01.10–31.12.2026 lub do wyczerpania puli; warunek: **opinia z hasztagiem #opiniąmotywowanąpromocją**, rejestracja do 30.01.2027; kwota zależy od **ceny końcowej** modelu. Organizator BSH | do 31.12.2026 | **Tak dla suszarki Bosch z koszyka wariantu A** (WQG243DRPL, 4199 zł → najprawdopodobniej najwyższy próg; dokładna kwota tylko w regulaminie). **Nie działa** na suszarkę Electrolux | [sferis.pl/promocje-bosch](https://www.sferis.pl/promocje-bosch) — banner + regulamin, sprawdzone 25.10.2026 |
| **Cashback Bosch – zmywarki (do 700 zł)** | Zakup 01.09–15.11.2026, opinia + rejestracja urządzenia | do 15.11.2026 | **Tak dla Bosch SMV4ECX23E** (2899 zł) — o ile model jest na liście Bosch (lista w regulaminie, niepodana na stronie sklepu). **Nie dotyczy** zmywarki Gorenje | [sferis.pl/promocje-bosch](https://www.sferis.pl/promocje-bosch), [sferisrtvagd.pl](https://sferisrtvagd.pl/portfolio/kup-zmywarke-bosch-zyskaj-do-700zl/) |
| **Cashback Whirlpool (do 3000 zł)** | Zestaw: **piekarnik Whirlpool (obowiązkowo)** + płyta indukcyjna / mikrofalówka do zabudowy / lodówka. Rejestracja w 14 dni od zakupu | do 31.12.2026 (lub do wyczerpania puli) | **Prawdopodobnie tak** dla pary piekarnik WOI4S8HM2SBA + mikrofalówka WMD44MX (oba Whirlpool, oba z tej samej transakcji = jeden koszyk). **Kwot dla tych modeli nie potwierdziłem** (regulamin nie podaje listy na stronie sklepu) → `niepotwierdzone` | [whirlpool-promocja.pl](https://whirlpool-promocja.pl/), [agdmaniak.pl](https://www.agdmaniak.pl/139054/uwaga-cashback-nawet-3000-zl-zwrotu-za-zakup-zestawu-whirlpool/) |
| **Cashback Samsung (do 4500 zł)** | Zakup 01.10–30.11.2026, rejestracja do 21.12.2026, sprzęt z polskiej dystrybucji (kod EO) | do 30.11.2026 | **Nie** — sferis.pl nie ma modeli z listy (brak BRB70F30BES0EO, WW90CGC04DAE, DV9MDG52A0AE). Jedyne urządzenie Samsung pralnicze to pralko-suszarka WD90DG5G34BBEO | [samsung.com/pl/offer/cashback/agd/2026](https://www.samsung.com/pl/offer/cashback/agd/2026/) |
| **Cashback portalu Refunder – Sferis 1,5% (AGD)** | Zwrot **1,5% od wartości netto** zamówienia (bez VAT i dostawy); wymagane przejście z Refundera, **zakaz używania obcych kodów rabatowych** (czyli nie łącz z kodem newslettera), wypłata do 100 dni (typowo ~43 dni) | bez terminu | Tak, ale **wyklucza się z kodem newslettera −50 zł** — przy koszyku ~18 tys. zł 1,5% netto (~220 zł) bije kod −50 zł | [refunder.pl/sklepy/sferis-2483](https://www.refunder.pl/sklepy/sferis-2483) |
| **Aktualne przeceny / outlet** | Stała sekcja przecen; w AGD pojedyncze obniżki (np. piekarnik Beko BCBIM17300KSBMPB 1449 → **1349 zł**, −7%) | bieżące | **Żaden model z koszyka nie jest przeceniony** (ceny bez przekreślenia) | [sferis.pl/produkty-przecenione](https://www.sferis.pl/produkty-przecenione) |
| **Ubezpieczenie sprzętu (opcja)** | Pakiety Srebrny/Złoty/Platynowy, np. piekarnik 199/209/344 zł | – | Opcja, nie rabat | karty produktów |

**Czego nie ma:** brak kuponu „−100 zł na AGD”, brak rabatu za odbiór osobisty, brak rabatu za zestaw (kilka sztuk), brak progów „im więcej tym taniej”. Rabaty producenckie rozliczane są **po zakupie** (cashback), nie w koszyku.

---

## 1. Piekarnik do zabudowy

MUST: para · szuflada/zbiornik na wodę · termosonda · hydroliza · teleskopy na 2 poziomach · termoobieg.
Wzorzec **Whirlpool WOI7A8FHT2SBA — brak oferty** (nie ma go w katalogu; brak też WOI7P8FHT1SBA).

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Electrolux EOD4P57H SteamBake** (czarny) | **najlepsze pokrycie MUST** | **2499 zł** | 0 zł (darmowa) | Dostępny, odbiór 27.10.2026 | **5/6 potwierdzone**: para ✓ (SteamBake, „Gotowanie na parze: Tak”), **termosonda ✓** (w nazwie handlowej karty), **teleskopy ✓** („Szyna teleskopowa w zestawie: Tak”), termoobieg ✓, 72 l ✓, A+, 9 programów, pizza ✓. **Czyszczenie: piroliza** („Rodzaj czyszczenia: Pyrolityczne”) — mocniejsze niż wymagana hydroliza. **Szuflada/zbiornik na wodę ✗** | +760 zł vs Whirlpool, ale to **jedyny piekarnik w Sferis, który łączy parę z termosondą**. Piroliza zamiast hydrolizy = mniej pracy przy czyszczeniu. Brak zbiornika (para przez dolanie wody do wnęki) | [karta](https://www.sferis.pl/piekarnik-elektryczny-electrolux-eod4p57h-steambake-72-l-para-steambake-piroliza-termosonda-czarny-i400491) |
| **Electrolux EOB8S39H Steamify** (czarny) | alternatywa (pełna para + sonda + czyszczenie parowe) | **4699 zł** | 0 zł | Dostępny | para ✓ (Steamify — para na każdym programie), **termosonda ✓**, **czyszczenie parowe ✓** (= hydroliza), 70 l ✓; teleskopy **niepodane ?**; zbiornik ✗ | +2200 zł vs EOD4P57H. Najbardziej „parowy” model w ofercie — ale cena nieproporcjonalna do przewagi | [karta](https://www.sferis.pl/piekarnik-parowy-electrolux-eob8s39h-steamify-72-l-steamify-termosonda-szybkie-nagrzewanie-czarny-i511049) |
| **Whirlpool WOI4S8HM2SBA** (czarny) | alternatywa (najtaniej z parą) | **1739 zł** | 0 zł (darmowa) | Dostępny, odbiór 27.10.2026 | **4/6**: para ✓ (Steam+), hydroliza ✓, teleskopy ✓ („Prowadnice teleskopowe” w opisie), termoobieg ✓, 73 l ✓; **termosonda ✗** (brak w karcie, opisie i na whirlpool.pl), **zbiornik ✗** | **−260 zł vs whirlpool.pl (1999 zł)**. AirFry, Pizza 310°C, 6. Zmysł (30 przepisów), A+, SoftClosing. **Bez termosondy** | [karta](https://www.sferis.pl/piekarnik-do-zabudowy-whirlpool-woi4s8hm2sba-czarny-steam-hydroliza-softclosing-airfry-i772505) |
| **Whirlpool WOI4S8PM0SBA** (czarny) | alternatywa (ta sama cena, lepsze czyszczenie) | **1739 zł** | 0 zł | Dostępny, 27.10.2026 | para ✓, **hydroliza + piroliza** ✓, termoobieg ✓, 73 l ✓, A+; teleskopy **niepotwierdzone ?**; **termosonda ✗**, zbiornik ✗ | **Za tę samą cenę dochodzi piroliza** (470°C, popiół) — realnie lepszy od HM2SBA. AirFry, Pizza **310°C**, Cook 4, 6. Zmysł, SoftClosing | [karta](https://www.sferis.pl/piekarnik-elektryczny-do-zabudowy-whirlpool-woi4s8pm0sba-pyroliza-airfry-steam-softclosing-i753729) |
| **Whirlpool AKZ9S 8220 FB** (czarny) | alternatywa (pełna para) | **2129 zł** | 0 zł | Dostępny, 27.10.2026 | para ✓ (SteamSense), hydroliza ✓, termoobieg ✓, 73 l ✓, piekarnik **parowy** (nie tylko wspomaganie) | +390 zł vs WOI4S8. SteamSense = sterowanie parą pod nadzorem; AirFry, Cook3, SoftClosing. **Zbiornik/szuflada na wodę: niepodane ?**, **termosonda ✗** (brak w nazwie/opisie) | [karta](https://www.sferis.pl/piekarnik-parowy-do-zabudowy-whirlpool-akz9s-8220-fb-czarny-steamsense-airfry-softclosing-hydroliza-cook3-i650862) |
| Bosch HRG312BB4 Serie 4, 71 l | alternatywa | **2399 zł** | 0 zł | Dostępny, 27.10.2026 | para ✓ (AddedSteam), hydroliza ✓ („Rodzaj czyszczenia: Hydrolityczne”), termoobieg ✓, 71 l ✓, A+; teleskopy **niepotwierdzone**, termosonda **niepotwierdzona** | +660 zł. Bosch = pewniejsza dostępność części/serwisu, AddSteam (wspomaganie parą), AirFry, SoftClose. Gorsze: 71 l vs 73 l, brak potwierdzonych teleskopów | [karta](https://www.sferis.pl/piekarnik-parowy-bosch-hrg312bb4-serie-4-71-l-airfry-addedsteam-softclose-czarny-i626372) |
| Amica ED47637BA+ X-TYPE STEAM, 77 l | odpowiednik (tańszy, niepełny MUST) | **1639 zł** | 0 zł | Dostępny | para ✓ (SoftSteam), termoobieg ✓, teleskopy ✓, 77 l ✓ — **ale czyszczenie katalityczne, nie hydroliza ✗**; termosonda/zbiornik ? | −100 zł vs Whirlpool, ale **nie spełnia MUST czyszczenia**. Większa komora 77 l | [karta](https://www.sferis.pl/piekarnik-do-zabudowy-amica-ed47637ba-x-type-steam-softsteam-77-l-czarny-i258728) |
| Bosch HBG7341B2 Serie 8, 71 l | odpowiednik (odrzucony na MUST) | 3899 zł | 0 zł | Dostępny | **termosonda ✓, piroliza + hydroliza ✓**, AirFry ✓ — **ale „Gotowanie na parze: Nie” ✗** | Ma sondę i najlepsze czyszczenie, ale **brak pary** → nie spełnia MUST. Analogicznie HBG7722B1 (4399 zł) | [karta](https://www.sferis.pl/piekarnik-elektryczny-bosch-hbg7341b2-serie-8-71-l-airfry-piroliza-termosonda-wifi-home-connect-czarny-i626302) |

**Wniosek do piekarnika:** **żaden piekarnik w Sferis nie ma szuflady ani zbiornika na wodę** — wszystkie funkcje pary (Steam+, SteamBake, Steamify, AddedSteam, ExtraSteam) działają bez wysuwanego zbiornika (woda wlewana do wnęki / system wytwarza parę z komory). Ten jeden MUST jest w tym sklepie **nie do spełnienia**. Poza nim **najlepszy jest Electrolux EOD4P57H SteamBake 2499 zł** — **para + termosonda + teleskopy + termoobieg + 72 l + piroliza** (piroliza zamiast hydrolizy to wyższy standard czyszczenia). Tańsza, ale **bez sondy**, jest para Whirlpool: **WOI4S8HM2SBA / PM0SBA po 1739 zł** (dodatkowo Pizza 310°C, AirFry, 6. Zmysł). Sonda w Whirlpoolu jest wykluczona także przez stronę producenta, więc **nie ma sensu liczyć na „ukrytą” termosondę w tańszym modelu**.

---

## 2. Lodówka do zabudowy

MUST: zabudowa ~193,5 cm · zawiasy ślizgowe · pełny No Frost · 2 niezależne obiegi · ~298 l · ≤35 dB.
Wzorzec **Samsung BRB70F30BES0EO — brak oferty**. W katalogu **nie ma ani jednej lodówki Samsung** (111 pozycji, wszystkie innych marek). **Nie ma też żadnej lodówki o wys. 193,5 cm i szer. 60 cm ani modelu z dwoma obiegami chłodzenia** — więc **żadna pozycja nie spełnia kompletu MUST**.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Bosch KIN86NSE0** (177,2 × 54,1 cm) | najbliżej (cicha) | **3199 zł** | **od 67,90 zł** (półpaleta) | Dostępny, 27.10.2026 | zawias **ślizgowy** ✓, **35 dB** ✓, 260 l (≈), klasa E; **No Frost tylko zamrażarka ✗** (chłodziarka: „No Frost: Nie”), 2 obiegi **niepotwierdzone**, **177,2 cm ✗** (nie 193,5) | Jedyna naprawdę cicha (35 dB). Minusy: wyższa o 16 cm niższa wnęka, brak pełnego No Frost w chłodziarce | [karta](https://www.sferis.pl/lodowka-bosch-kin86nse0-do-zabudowy-z-dolnym-zamrazalnikiem-177-2-x-54-1-cm-zawias-slizgowy-nofrost-i679146) |
| **Amica BK3055.6 NFM(E)** (176,9 cm) | alternatywa (pełny No Frost) | **2039 zł** | 0 zł | Dostępny | **Total No Frost ✓ (chłodziarka i zamrażarka)**, 274 l (≈), inwerter, drzwi dwustronne, alarm ✓, klasa E; **41 dB ✗** (wymóg ≤35), 176,9 cm ✗, 2 obiegi ? | **−1160 zł**. Jedyny pełny No Frost w ofercie. Głośniejszy o 6 dB i niższy o 16 cm od wzorca | [karta](https://www.sferis.pl/lodowka-do-zabudowy-amica-bk3055-6-nfm-e-total-no-frost-176-9-cm-kompresor-inwerterowy-szuflada-vitcontrol-biala-i722376) |
| Bosch KBN96VFE0 (193,5 cm) | odpowiednik wymiarowy — **odrzucony** | 3999 zł | 0 zł | Dostępny, 27.10.2026 | wys. **1935 mm ✓**, 34 dB ✓, 383 l, alarm ✓ — **ale szer. 708 mm ✗** (nie wejdzie w szafkę 60 cm), No Frost tylko zamrażarka ✗ | Jedyny model o wysokości 193,5 cm — bezużyteczny przy szafce 60 cm | [karta](https://www.sferis.pl/lodowka-do-zabudowy-bosch-kbn96vfe0-193-5-cm-szer-70-cm-kompresor-inwerterowy-vitafresh-biala-i384359) |
| Bosch KIS86AFE0 (177,2 cm) | odpowiednik | 3599 zł | 0 zł | Dostępny | 266 l, 36 dB, alarm ✓; **No Frost: Nie (obie komory) ✗** | Droższy i bez No Frost | [karta](https://www.sferis.pl/lodowka-do-zabudowy-bosch-kis86afe0-no-frost-177-2-cm-vitafresh-kompresor-inwerterowy-biala-i259502) |
| Bosch KIV86VFE1 (177,2 cm) | odpowiednik | 2999 zł | 0 zł | Dostępny | 267 l, **38 dB ✗**, No Frost: brak danych w karcie | Brak potwierdzenia No Frost i głośniejszy | [karta](https://www.sferis.pl/lodowka-do-zabudowy-bosch-kiv86vfe1-no-frost-177-2-cm-vitafresh-kompresor-inwerterowy-biala-i265819) |

**Wniosek do lodówki:** **kategoria niezdatna do zakupu w Sferis** przy zachowaniu MUST (wymiar 193,5 cm + 2 obiegi + ≤35 dB + pełny No Frost nie występują razem; brak Samsunga). Sensowne tylko kompromisy: **Amica BK3055.6 NFM 2039 zł** (pełny No Frost, ale 41 dB i 177 cm) albo **Bosch KIN86NSE0 3199 zł** (35 dB, ale No Frost tylko w zamrażarce).

---

## 3. Płyta indukcyjna

MUST: 59–60 cm · strefa łączona · 4 pola · Booster ~3 kW · osobny suwak na każdą strefę · **czarne błyszczące szkło (bez MattProtect/mat)** · blokada dzieci · wskaźnik ciepła resztkowego.
Wzorzec **Whirlpool WB S2560 NE — brak oferty**. Whirlpool w indukcji 60 cm ma tylko: **WF S7560NE BM 1739 zł (czarny MAT, MattProtect) — odrzucony przez MUST**, WL B4560 NE/W 1528 zł (biała) i WLB6860NES 1699 zł (beżowa do zabudowy).

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Amica PIM6540PHTUN 3.0** | alternatywa (najlepszy stosunek w MUST) | **1199 zł** | 0 zł | Dostępny, 27.10.2026 | 60 cm ✓ (592×522), **4 strefy ✓**, **AutoBridge — strefa łączona ✓**, **PowerBoost do 3000 W ✓** (4 boostery), czarna ceramika (ultra płaska) ✓, ciepło resztkowe ✓, 14 poziomów, 7350 W; **blokada dzieci: niepodana w karcie ?**, **typ sterowania (osobny suwak): niepodany ?** | **−~100–400 zł vs konkurencji** i wszystko, co da się potwierdzić z MUST. Brak potwierdzenia „suwaka na strefę” | [karta](https://www.sferis.pl/plyta-indukcyjna-amica-pim6540phtun-3-0-60-cm-powerboost-autobridge-hobcontrol-pro-czarny-ultra-plaska-i603634) |
| **Bosch PIE611BB5E Serie 4** | alternatywa (elastyczna strefa duża) | **1399 zł** | 0 zł | Dostępny, 27.10.2026 | 4 strefy ✓, **FlexInduction 210×380 mm ✓**, PowerBoost 3100/3700 W ✓, czarna ✓, ciepło resztkowe ✓, 7400 W; **sterowanie TouchSelect = jeden pasek na wszystkie pola → MUST „osobny suwak na strefę” ✗/niespełniony** | Pewniejsza marka, strefa łączona jak we wzorcu (FlexiCook), ale sterowanie nie jest „Direct Access”. Brak wyświetlacza | [karta](https://www.sferis.pl/plyta-indukcyjna-bosch-pie611bb5e-serie-4-60-cm-4-pola-powerboost-touchselect-czarny-i296293) |
| **Bosch PIE631HB1E Serie 6** | alternatywa | **1429 zł** | 0 zł | Dostępny | 4 pola ✓, PowerBoost 3100–3700 W ✓, czarna bezramkowa ✓, 17 poziomów, timer; **strefa łączona: brak w karcie ?**, sterowanie ? | +230 zł vs Amica; dochodzi **WiFi / Home Connect** (NICE) | [karta](https://www.sferis.pl/plyta-indukcyjna-bosch-pie631hb1e-serie-6-60-cm-4-pola-powerboost-timer-wifi-home-connect-czarny-bezramkowa-i393803) |
| **Electrolux EIV644** | alternatywa (2 strefy elastyczne) | **2299 zł** | 0 zł | Dostępny | 4 strefy ✓, **2 strefy elastyczne + Bridge/CombiZone ✓**, Boost 3200 W ✓, czarna ✓, ciepło resztkowe ✓, 7350 W | +1100 zł. Najbardziej „elastyczna” płyta w ofercie, ale drogo i timer mechaniczny | [karta](https://www.sferis.pl/plyta-indukcyjna-electrolux-eiv644-60-cm-4-pola-powerboost-timer-czarny-i400482) |
| Electrolux LIV63431BK Slim-fit | odpowiednik | 1399 zł | 0 zł | Dostępny | 4 strefy ✓, **Bridge ✓, PowerBoost ✓**, czarna bezramkowa, 7350 W | Slim-fit — do wąskich blatów; brak potwierdzonego wskaźnika ciepła w karcie | [karta](https://www.sferis.pl/plyta-indukcyjna-electrolux-liv63431bk-slim-fit-60-cm-4-pola-bridge-powerboost-czarny-bezramkowa-i208708) |
| Beko HII64206F2MT | **odrzucony** | 1099 zł | 0 zł | Dostępny, 27.10.2026 | nazwa handlowa: „**czarny mat**” ✗ — dokładnie to, czego wymagania zabraniają; Boost tylko 2300 W ✗ | – | [karta](https://www.sferis.pl/plyta-indukcyjna-beko-hii64206f2mt-60-cm-4-pola-flexzone-powerboost-czarny-mat-i383056) |
| Gorenje GI6421SYB | odrzucony na MUST | 1379 zł | 0 zł | Dostępny | 4 strefy ✓, BigZone, strefa elastyczna ✓ — **Boost max 2000 W ✗** (< 3 kW) | – | [karta](https://www.sferis.pl/plyta-indukcyjna-gorenje-gi6421syb-60-cm-bigzone-23-cm-powerboost-timer-czarny-i671596) |

**Wniosek do płyty:** kupując w Sferis trzeba **zrezygnować z „osobnego suwaka na każdą strefę”** — żadna karta nie potwierdza Direct Access (Bosch TouchSelect = 1 pasek). Pozostałe MUST spełnia **Amica PIM6540PHTUN 1199 zł** (blokadę dzieci potwierdzić przy zakupie).

---

## 4. Okap teleskopowy

MUST: teleskop 60 cm · mieści się w szafce gł. 35 cm · wylot **fi 150** · 400–600 m³/h na zwykłym biegu · ≤~55 dB codziennie · metalowe filtry do zmywarki · klapa zwrotna.
Wzorce z wymagań (**Amica OTP6651BG, Bosch DFS067K51**) — **brak oferty**. W katalogu jest 10 okapów teleskopowych.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Electrolux LFP326FB 60 cm** | alternatywa (najbardziej „potwierdzony”) | **659 zł** | 0 zł | Dostępny, 27.10.2026 | 60 cm ✓ (598), **fi 15 cm ✓**, gł. produktu **284 mm**, gł. przedziału **265 mm ✓** (szafka 35 cm), wydajność **410 m³/h** ✓ (karta), **48 dB niska / 69 dB wysoka**, 2× filtr aluminiowy, mycie ✓, klasa C; **klapa zwrotna: niepodana ?** | Realnie cichy na 1. biegu, mieści się w 35 cm. **Uwaga na sprzeczność:** slug sklepu mówi „300 m³/h”, a nazwa „LEDLights **300**” to nazwa serii Electrolux — parametr 410 m³/h pochodzi z tabeli specyfikacji; potwierdzić na tabliczce/etykiecie UE | [karta](https://www.sferis.pl/okap-teleskopowy-electrolux-lfp326fb-60-cm-300-m3-h-led-czarny-i297104) |
| **MAAN Corona Touch Bis 60** | alternatywa (największy ciąg) | **639 zł** | 0 zł | Dostępny | 60 cm ✓, **635 m³/h ✓**, 48 dB niska / 68 dB wysoka, filtr aluminiowy, sterowanie dotykowe, szkło hartowane + stal, czarny; **fi wylotu i głębokość: niepodane w karcie ?** | −20 zł vs Electrolux, wyraźnie więcej m³/h. Ryzyko: brak potwierdzonego fi 150 i głębokości ≤35 cm → sprawdzić instrukcję przed zakupem | [karta](https://www.sferis.pl/okap-teleskopowy-maan-corona-touch-bis-60-cm-sterowanie-dotykowe-led-czarny-i293624) |
| **MAAN Corona Bis 60** | alternatywa (budżet) | **559 zł** | 0 zł | Dostępny | 60 cm ✓, 635 m³/h ✓, 48/68 dB, filtr Al, sterowanie **mechaniczne**, fi/gł. ? | −100 zł vs Electrolux, ale sterowanie przyciskami (brak „start od wysunięcia”) | [karta](https://www.sferis.pl/okap-teleskopowy-maan-corona-bis-60-cm-led-czarny-i293623) |
| Electrolux LFP226S 60 cm | odrzucony na MUST | 449 zł | 0 zł | Dostępny | fi **150 mm ✓**, gł. przedziału 265 mm ✓, ale **330 m³/h ✗** (poniżej 400) i 64 dB | Za słaby ciąg | [karta](https://www.sferis.pl/okap-teleskopowy-electrolux-lfp226s-60-cm-250-m3-h-led-inox-i297578) |
| Gorenje TH64E3SGB 60 cm | odrzucony na MUST | 469 zł | 0 zł | Dostępny | fi 15 cm ✓, gł. 306 mm, **350 m³/h ✗**, 67 dB ✗, filtr Al/PU zmywarkowy ✓ | Za słaby i za głośny | [karta](https://www.sferis.pl/okap-teleskopowy-gorenje-th64e3sgb-60-cm-sterowanie-dotykowe-led-czarne-szklo-i385585) |
| MAAN Corona 2 / 2 Touch / 2 G (315 m³/h) | odrzucone na MUST | 479–599 zł | 0 zł | Dostępny | **315 m³/h ✗** | – | [Corona 2 G](https://www.sferis.pl/okap-teleskopowy-maan-corona-2-g-60-cm-led-czarny-i293651) |

**Wniosek do okapu:** w Sferis najbliżej wymagań jest **Electrolux LFP326FB 659 zł** (fi 150 + gł. 265 mm potwierdzone) lub **MAAN Corona Touch Bis 639 zł** (635 m³/h, ale bez potwierdzonego fi/głębokości). **Klapa zwrotna (MUST) nie jest potwierdzona w żadnej z tych kart** — trzeba dopytać sprzedawcę; jeśli okapu nie mają w wersji z klapą, dokupić klapę fi 150 osobno.

---

## 5. Mikrofalówka do zabudowy

MUST: talerz ≥ ~31–32 cm (poj. ~25–31 l) · zabudowa 60 cm · wys. urządzenia ~38 cm.
Kandydat z wymagań **Whirlpool W7 MD440 NB — brak oferty**; **Bosch BFL554MB0 — brak oferty** (jest BFL520MB0, ale z talerzem **25,5 cm → nie spełnia MUST**).

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WMD44MX** (czarny) | najlepszy zamiennik wzorca | **1619 zł** | 0 zł | Dostępny, 27.10.2026 | **talerz 32,5 cm ✓**, **31 l ✓**, szer. 595 mm ✓, **wys. 385 mm ✓**, wbudowana ✓ | Ta sama marka co piekarniki Whirlpool w tym sklepie (spójne czarne szkło — istotne, jeśli piekarnik też Whirlpool), Crisp 3D grill (niepotrzebny, ale jest), 1000 W. Minus: głębokość **468 mm** — sprawdzić słupek | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-whirlpool-wmd44mx-31-litrow-crisp-3d-grill-i753728) |
| **Beko BMGB25353B** (czarna) | alternatywa (najtaniej z MUST) | **999 zł** | 0 zł | Dostępny | **talerz 31,5 cm ✓**, 25 l (na granicy „~25–31”), 595×388 mm ✓ | **−620 zł vs Whirlpool.** Mniejsza pojemność, inna marka (gorsza spójność z piekarnikiem) | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-beko-bmgb25353b-czarna-900w-25l-grill-i617718) |
| **Amica AMMB25E3GB** | alternatywa | **1029 zł** | 0 zł | Dostępny | talerz **31,5 cm ✓**, 25 l, 595×388 ✓ | −590 zł, ta sama klasa co Beko | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-amica-ammb25e3gb-i722369) |
| Electrolux LMS4253TBK | alternatywa | 1539 zł | 0 zł | Dostępny | talerz 31,5 ✓, 25 l, 595×388 ✓ | −80 zł vs Whirlpool, ale mniejsza komora (25 l) | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-electrolux-lms4253tbk-i694323) |
| Amica AMMB25E2SGB X-TYPE | odpowiednik | 1259 zł | 0 zł | Dostępny | 25 l, 594×382 ✓, talerz niepodany ? | Brak potwierdzenia talerza | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-amica-ammb25e2sgb-x-type-i134931) |
| MPM-25-KMI-01 | odrzucony na MUST | 679 zł | wg cennika | Dostępny | **talerz 27 cm ✗** | Za mały talerz | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-mpm-25-kmi-01-czarna-poj-25l-900w-czyszczenie-parowe-i267247) |
| Bosch BFL520MB0 | odrzucony na MUST | 1299 zł | 0 zł | Dostępny, 27.10.2026 | **talerz 25,5 cm ✗**, 20 l | – | [karta](https://www.sferis.pl/kuchenka-mikrofalowa-bosch-bfl520mb0-i590166) |

**Wniosek:** **Whirlpool WMD44MX 1619 zł spełnia wszystkie MUST** (talerz 32,5 cm, 31 l, wys. 385 mm) i jest spójny wizualnie z piekarnikami Whirlpool (Steam+ / SteamSense) — jeśli wybierzesz piekarnik Electrolux, spójność marki znika, ale MUST dalej jest spełniony. Budżetowo: Beko BMGB25353B 999 zł.

---

## 6. Zmywarka do zabudowy

MUST: pełna zabudowa 60 cm · 14–15 kpl · trzeci kosz · ≤40 dB · auto-uchylanie drzwi · dysze na garnki · regulowane kosze, stal.
Wzorzec **Whirlpool W7I HT58 T — brak oferty**; **Beko MEDIN3755A — brak**; **Whirlpool WH8IA15AM3TUS0 — brak**.

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Gorenje GV663B65** | **najlepszy w kategorii** | **2399 zł** | 0 zł | Dostępny, 27.10.2026 | **wszystkie MUST ✓**: pełna zabudowa 60 (598×816×555) ✓, **16 kpl ✓**, **3 kosze + szuflada na sztućce ✓**, **38 dB ✓ (klasa A)**, **auto-otwieranie drzwi ✓**, **2 dysze wysokociśnieniowe z tyłu komory = dysze na garnki ✓** (opis), kosz górny regulowany ✓, **komora stal nierdzewna ✓**, AquaStop ✓, klasa B, 9,5 l/cykl, 66 kWh/100, 8 programów, ochrona szkła, opóźniony start 24 h | **Taka sama głośność jak wzorzec (38 dB), ale 16 kpl zamiast 15**, AquaStop ✓ (we wzorcu niepotwierdzony), 66 kWh vs 65 kWh, klasa B. **Brak projekcji na podłodze** (NICE) | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-gorenje-gv663b65-klasa-b-16-kpl-aquastop-totaldry-speedwash-i652768) |
| **Bosch SMV4ECX23E Serie 4** | alternatywa | **2899 zł** | 0 zł | Dostępny, 27.10.2026 | 14 kpl ✓, 3. poziom **Vario3 szuflada ✓**, **40 dB ✓ (granica)**, **EfficientDry = auto-otwieranie drzwi ✓**, AquaStop ✓, regulowany kosz ✓, stal ✓; **dysze na garnki: brak w opisie ?** | +500 zł. Pewniejszy serwis, klasa C, 75 kWh/100. **Głośniejsza o 2 dB** i brak potwierdzonych dysz | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-bosch-smv4ecx23e-serie-4-klasa-c-14-kpl-efficientdry-speedperfect-40-db-i645960) |
| Bosch SMV4HVX11E Serie 4 | odpowiednik (niepełny) | 1999 zł | 0 zł | Dostępny | 14 kpl ✓, szuflada Vario ✓, AquaStop ✓ — **46 dB ✗**, auto-otwieranie ? | −400 zł, ale za głośna na MUST | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-bosch-smv4hvx11e-serie-4-klasa-c-14-kpl-szuflada-na-sztucce-speedperfect-i648497) |
| Bosch SMI4HAS07E Serie 4 | odpowiednik | 2599 zł | 0 zł | Dostępny | **13 kpl ✗**, 42 dB ✗ | – | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-bosch-smi4has07e-serie-4-klasa-c-13-kpl-extradry-speedperfect-i663828) |
| Whirlpool WH7ITD14C6N6 | odpowiednik (inna klasa) | 1949 zł | 0 zł | Dostępny | 14 kpl ✓, 3. kosz ?, **46 dB ✗**, klasa D | Tańsza, ale nie spełnia MUST głośności | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-whirlpool-wh7itd14c6n6-60cm-46db-14kpl-kld-i773059) |
| Electrolux E52LE21OS | odpowiednik | 1999 zł | 0 zł | Dostępny | 14 kpl ✓, **46 dB ✗**, 95 kWh/100 | Za głośna | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-electrolux-e52le21os-i745750) |
| Beko DIN35320 | odrzucony | 1149 zł | 0 zł | Dostępny | **13 kpl ✗, 48 dB ✗** | – | [karta](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-beko-din35320-klasa-e-14-kpl-aquaintense-i236427) |

**Wniosek:** **Gorenje GV663B65 (2399 zł) to najlepsza zmywarka w Sferis i najlepsza relacja ceny do MUST w całym raporcie** — spełnia każdy punkt, w tym dysze na garnki i auto-uchylanie, w cenie zbliżonej do wzorcowego Whirlpoola.

---

## 7. Pralka + suszarka (słupek)

MUST: montaż w słupku (**łącznik dostępny**) · pralka 9 kg / 1400 / A / inwerter · suszarka pompa ciepła 9 kg / czujnik wilgotności / odpływ do kanalizacji / ≤65 dB / **klasa min. C**.
**Brak w ofercie:** WW90CGC04DAE, DV9MDG52A0AE, SKK-DD/DF, WGG244ZEPL, WQG245DEPL, **WTZ27400**. Jedyna pralko-suszarka Samsung: WD90DG5G34BBEO 2999 zł (to nie słupek, tylko 2w1 — nie spełnia wymagania).

### Łączniki dostępne w Sferis (klucz do MUST „słupek”)

| Łącznik | Cena | Dostawa | Kompatybilność | Link |
|---|---|---|---|---|
| **Bosch WTZ2741C** (zestaw do układania) | **319 zł** | **od 17,90 zł** | „Kompatybilność z marką: **Bosch**”, gł. 556 mm, wys. 35 mm, gwarancja 12 mies. — **do pary pralka+suszarka Bosch** | [karta](https://www.sferis.pl/lacznik-pralki-z-suszarka-bosch-wtz2741c-i653975) |
| Bosch WTZ20410 | 119 zł | od 17,90 zł | Bosch (starszy typ) | [karta](https://www.sferis.pl/lacznik-pralki-z-suszarka-bosch-wtz-20410-i282888) |
| Bosch WTZ27500 | 515 zł | od 17,90 zł | Bosch (wersja z półką/wysuwana) | [karta](https://www.sferis.pl/lacznik-pralki-z-suszarka-bosch-wtz27500-i752420) |
| Gorenje SKHNE90W / SKHNE70W | 189 zł | od 17,90 zł | Gorenje | [SKHNE90W](https://www.sferis.pl/lacznik-pralki-z-suszarka-gorenje-skhne90w-i771944) |
| **Samsung SKK-*** | **brak oferty** | – | – | – |

### Pralki (9 kg / 1400 / A)

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Bosch WGG244Z0PL Serie 6** | najlepsza pralka z łącznikiem | **2499 zł** | 0 zł | Dostępny, 27.10.2026 | **9 kg ✓, 1400 ✓, A ✓**, klasa wirowania B ✓, 70 dB, gł. **588 mm ✓**, „Szybki 15 min” ✓, Sport ✓, Iron Assist (para) ✓, ochrona przed dziećmi ✓; **silnik inwerterowy: nieujęty w karcie** (Serie 6 = EcoSilence Drive wg producenta, `niepotwierdzone w karcie`) | Odpowiednik funkcjonalny WGG244ZEPL (bez i-DOS). **Jedyna 9/1400/A, do której jest łącznik w tym sklepie** | [karta](https://www.sferis.pl/pralka-bosch-wgg244z0pl-serie-6-9-kg-1400-obr-min-program-parowy-activewater-plus-wifi-home-connect-i587221) |
| **Beko BM3WFU410415W** | alternatywa (najtaniej, 10 kg) | **1799 zł** | 0 zł | Dostępny, 27.10.2026 | 10 kg ✓, 1400 ✓, **A ✓**, **silnik inwerterowy ✓**, 75 dB, gł. 580 mm, para CoolClean; łącznik Beko **brak w sklepie** | **−700 zł vs Bosch**, większy załadunek. Minus: głośniejsze wirowanie, brak łącznika → nie da się zrobić słupka w Sferis | [karta](https://www.sferis.pl/pralka-wolnostojaca-beko-bm3wfu410415w-10kg-1400obr-para-coolclean-i776049) |
| **Amica WAC914ALISO** | alternatywa (najtaniej 9/1400/A) | **1479 zł** | 0 zł | Dostępny, 27.10.2026 | **9 kg ✓, 1400 ✓, klasa A ✓**, gł. **577 mm ✓**, Express 15' ✓, program Para ✓, antyalergiczny ✓; **76 dB** (głośna), **silnik inwerterowy: niepodany ?**, klasa wirowania C; łącznik Amica **brak w sklepie** | **−1020 zł vs Bosch**, −320 zł vs Beko. Głośna przy wirowaniu i bez potwierdzonego inwertera | [karta](https://www.sferis.pl/pralka-amica-wac914aliso-9-kg-1400-obr-min-steampowerpro-program-anty-alergiczny-cicha-praca-i398086) |
| Bosch WAN2827FPL | alternatywa | 2299 zł | 0 zł | Dostępny | 9 kg ✓, 1400 ✓, A ✓, 72 dB, gł. 590 mm; karta podaje **„automatyczny system dozowania: Tak”** (dla Serie 4 nieoczywiste → do weryfikacji) | −200 zł vs WGG244Z0PL, ale głośniejsza | [karta](https://www.sferis.pl/pralka-bosch-wan2827fpl-9-kg-1400-obr-min-funkcja-pary-ecosilence-drive-wykrywanie-obciazenia-i380042) |
| Bosch WUU28T10PL Serie 6 | alternatywa (premium) | 3159 zł | 0 zł | Dostępny | 9 kg ✓, 1400 ✓, A ✓, 72 dB, SpeedPerfect, Iron Assist | +660 zł, bez wyraźnej przewagi | [karta](https://www.sferis.pl/pralka-wolnostojaca-bosch-wuu28t10pl-serie-6-9-kg-1400-obr-min-speedperfect-ecosilence-drive-iron-assist-i586633) |
| Electrolux EW6F2292P | odrzucony na MUST | 2045 zł | 0 zł | Dostępny | 9 kg ✓, A ✓ — **1200 obr. ✗**, 75 dB, gł. 636 mm ✗ | Nie spełnia wirowania ani głębokości | [karta](https://www.sferis.pl/pralka-electrolux-ew6f2292p-600-9-kg-1200-obr-min-sensicare-speedaction-okocontrol-i394945) |

### Suszarki (pompa ciepła, 9 kg, min. C)

| Model | Typ | Cena | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Bosch WQG243DRPL Serie 6** | **jedyna para „słupek” z łącznikiem** | **4199 zł** | 0 zł | Dostępny, 27.10.2026 | **pompa ciepła ✓, 9 kg ✓ (nagłówek sklepu mówi 10 kg — sprzeczność w karcie), klasa C ✓, 63 dB ✓**, czujnik wilgoci ✓, AutoDry?, drzwi 613 mm | **Najdroższa**, ale dzięki niej słupek Bosch +WTZ2741C jest zgodny z MUST. Uwaga: URL karty mówi „klasa A”, tabela specyfikacji „C” — obowiązuje C (nowa etykieta) | [karta](https://www.sferis.pl/suszarka-wolnostojaca-bosch-wqg243drpl-serie-6-10-kg-klasa-a-pompa-ciepla-autodry-i649437) |
| **Electrolux EW6D295GP** | najlepsza relacja ceny (bez łącznika) | **2569 zł** | 0 zł | Dostępny, 27.10.2026 | **pompa ciepła ✓, 9 kg ✓, klasa C ✓, 64 dB ✓**, **drzwi dwustronne ✓** (zmiana kierunku), gł. 636 mm; czujnik wilgoci/odpływ: **niepodane ?** | **−1630 zł vs Bosch.** Minus MUST: **brak łącznika Bosch/Electrolux w sklepie** → oficjalny słupek nie do zrobienia | [karta](https://www.sferis.pl/suszarka-electrolux-ew6d295gp-z-pompa-ciepla-9kg-klasa-c-65db-sensicare-i619018) |
| Beko BM3T49249W | alternatywa (najtaniej z C) | **2349 zł** | 0 zł | Dostępny | pompa ciepła ✓, 9 kg ✓, **klasa C ✓**, 64 dB ✓, 15 programów, wskaźnik zbiornika ✓; drzwi **niezmieniane ✗** (NICE) | −220 zł vs Electrolux, brak zmiany kierunku drzwi | [karta](https://www.sferis.pl/suszarka-automatyczna-beko-bm3t49249w-9kg-pompa-ciepla-i726568) |
| Whirlpool WPC10XWBSEE | alternatywa | 2689 zł | 0 zł | Dostępny, 27.10.2026 | pompa ciepła ✓, **10 kg ✓**, **klasa C ✓**, 63 dB ✓, program Para | −1490 vs Bosch, ale bez łącznika Whirlpoola w sklepie | [karta](https://www.sferis.pl/suszarka-automatyczna-whirlpool-wpc10xwbsee-10kg-pompa-ciepla-i753730) |
| Bosch WQG145APPL Serie 6 | **odrzucona na MUST** | 3099 zł | 0 zł | Dostępny, 27.10.2026 | 9 kg ✓, 62 dB ✓, ale **klasa D ✗ na nowej etykiecie** (nagłówek karty podaje starą „A+++”) | Mimo SelfCleaning Condenser nie spełnia MUST klasy | [karta](https://www.sferis.pl/suszarka-wolnostojaca-bosch-wqg145appl-serie-6-9-kg-klasa-a-pompa-ciepla-selfcleaning-condenser-i640282) |
| Bosch WQG241ALPL | odrzucona na MUST | 2699 zł | 0 zł | Dostępny | 9 kg ✓, **klasa D ✗**, 62 dB | – | [karta](https://www.sferis.pl/suszarka-bosch-wqg241alpl-z-pompa-ciepla-9kg-klasa-d-64db-autodry-i612465) |

**Porównanie wariantów pary w Sferis**

| Wariant | Pralka | Suszarka | Łącznik | Suma | Uwagi |
|---|---|---|---|---|---|
| **A. Bosch „słupek” (wszystkie MUST)** | WGG244Z0PL 2499 | WQG243DRPL 4199 | Bosch WTZ2741C 319 (+17,90 dost.) | **7017 zł** | Jedyne zestawienie, które ma **oficjalny łącznik w tym sklepie**. Bosch cashback na suszarkę (do 1000 zł, zakup do 31.12.2026) |
| **B. Bosch + Electrolux (najtaniej z sensownych)** | WGG244Z0PL 2499 | EW6D295GP 2569 | **brak w sklepie** | **5068 zł** | −1949 zł vs A, ale słupek trzeba spiąć łącznikiem uniwersalnym z innego źródła → **MUST „łącznik dostępny” niespełniony** |
| C. Beko (najtaniej) | BM3WFU410415W 1799 (10 kg) | BM3T49249W 2349 | brak | **4148 zł** | 10 kg + C + 64 dB; łącznik Beko tylko poza Sferis |

---

## Koszyk w tym sklepie

Wariant **A** — wszystkie kategorie, wszystkie MUST potwierdzone w kartach (poza wyraźnie oznaczonymi „?”):

| # | Kategoria | Model | Cena | Dostawa |
|---|---|---|---|---|
| 1 | Piekarnik | Electrolux EOD4P57H SteamBake (para + termosonda + teleskopy) | 2499 zł | 0 zł |
| 2 | Lodówka | Bosch KIN86NSE0 (kompromis — brak modelu 193,5 cm) | 3199 zł | **67,90 zł** (półpaleta) |
| 3 | Płyta | Amica PIM6540PHTUN 3.0 | 1199 zł | 0 zł |
| 4 | Okap | Electrolux LFP326FB | 659 zł | 0 zł |
| 5 | Mikrofalówka | Whirlpool WMD44MX | 1619 zł | 0 zł |
| 6 | Zmywarka | Gorenje GV663B65 | 2399 zł | 0 zł |
| 7 | Pralka | Bosch WGG244Z0PL | 2499 zł | 0 zł |
| 8 | Suszarka | Bosch WQG243DRPL | 4199 zł | 0 zł |
| 9 | Łącznik | Bosch WTZ2741C | 319 zł | **17,90 zł** |
| | **Suma** | | **18 591 zł** | **85,80 zł** → **razem 18 676,80 zł** |

**Braki w koszyku:** (1) **lodówka** — żaden model nie ma 193,5 cm, 2 obiegów, pełnego No Frost i ≤35 dB jednocześnie; (2) **piekarnik** — brak szuflady/zbiornika na wodę (wada całej oferty Sferis); (3) **płyta** — brak potwierdzonego „osobnego suwaka na strefę”. Reszta (okap, mikrofalówka, zmywarka, pralka, suszarka, łącznik) spełnia MUST według kart produktów — z zastrzeżeniami przy pozycjach oznaczonych „?” (głównie inwerter pralki, czujnik wilgoci w suszarce, klapa zwrotna okapu).

**Wariant taniej (bez suszarki Bosch):** 2499 + 3199 + 1199 + 659 + 1619 + 2399 + 2499 + **2569 (Electrolux EW6D295GP)** = **16 642 zł** + 67,90 dostawy = **16 709,90 zł**, **bez łącznika** (brak w sklepie) — czyli o **1966,90 zł taniej**, kosztem MUST „słupek z łącznikiem”.

**Wariant najtaniej (marki mieszane):** 1739 (Whirlpool) + 2039 (Amica lodówka) + 1199 (Amica płyta) + 659 (Electrolux okap) + 999 (Beko mikrofala) + 2399 (Gorenje zmywarka) + 1799 (Beko pralka) + 2349 (Beko suszarka) = **13 182 zł**, dostawa ~67,90 zł; łącznik tylko poza sklepem.

**Czy kupować całość tutaj?** **Nie.** Sferis wygrywa **zmywarką (Gorenje GV663B65 — 2399 zł, komplet MUST, 38 dB, 16 kpl)**, **mikrofalówką Whirlpoola (1619 zł, talerz 32,5 cm)** i **okapem Electroluxa (659 zł)**; piekarnik Electrolux EOD4P57H (2499 zł) jest jedynym, który łączy parę z termosondą — cenę porównaj z pozostałymi raportami, bo w Sferis nie ma tańszej alternatywy z sondą. Przegrywa **lodówką** (brak jakiegokolwiek modelu ze wzorcowymi parametrami) i **płytą indukcyjną** (brak Whirlpoola w czarnym błyszczącym szkle; brak potwierdzonego „suwaka na strefę”), a w pralni jest o **~3500–7000 zł drożej** niż para Samsung z euro.com.pl (4288 zł) — nawet bez cashbacku.

---

## Tabela do porównania

Ceny brutto w PLN. „Promocja netto” = rabat/kod działający natychmiast w koszyku (bez cashbacków producenckich).

| kategoria | model | cena | dostawa | promocja netto | MUST | url |
|---|---|---|---|---|---|---|
| piekarnik | Electrolux EOD4P57H SteamBake | 2499 | 0 | brak (newsletter −50 zł od 2000 zł koszyka) | 5/6 (brak zbiornika; piroliza zamiast hydrolizy) | https://www.sferis.pl/piekarnik-elektryczny-electrolux-eod4p57h-steambake-72-l-para-steambake-piroliza-termosonda-czarny-i400491 |
| piekarnik | Electrolux EOB8S39H Steamify | 4699 | 0 | brak | 5/6 (teleskopy ?) | https://www.sferis.pl/piekarnik-parowy-electrolux-eob8s39h-steamify-72-l-steamify-termosonda-szybkie-nagrzewanie-czarny-i511049 |
| piekarnik | Whirlpool WOI4S8HM2SBA | 1739 | 0 | brak | 4/6 (termosonda ✗, zbiornik ✗) | https://www.sferis.pl/piekarnik-do-zabudowy-whirlpool-woi4s8hm2sba-czarny-steam-hydroliza-softclosing-airfry-i772505 |
| piekarnik | Whirlpool WOI4S8PM0SBA (pyroliza+hydroliza) | 1739 | 0 | brak | 4/6 (termosonda ✗, teleskopy ?) | https://www.sferis.pl/piekarnik-elektryczny-do-zabudowy-whirlpool-woi4s8pm0sba-pyroliza-airfry-steam-softclosing-i753729 |
| piekarnik | Whirlpool AKZ9S 8220 FB (parowy) | 2129 | 0 | brak | 4/6 (termosonda ✗, zbiornik ?) | https://www.sferis.pl/piekarnik-parowy-do-zabudowy-whirlpool-akz9s-8220-fb-czarny-steamsense-airfry-softclosing-hydroliza-cook3-i650862 |
| piekarnik | Bosch HRG312BB4 | 2399 | 0 | brak | 3/6 (termosonda ✗, teleskopy ?) | https://www.sferis.pl/piekarnik-parowy-bosch-hrg312bb4-serie-4-71-l-airfry-addedsteam-softclose-czarny-i626372 |
| piekarnik | Bosch HBG7341B2 (sonda+piroliza, BEZ pary) | 3899 | 0 | brak | NIE (brak pary) | https://www.sferis.pl/piekarnik-elektryczny-bosch-hbg7341b2-serie-8-71-l-airfry-piroliza-termosonda-wifi-home-connect-czarny-i626302 |
| piekarnik | Amica ED47637BA+ X-TYPE STEAM | 1639 | 0 | brak | NIE (kataliza, nie hydroliza) | https://www.sferis.pl/piekarnik-do-zabudowy-amica-ed47637ba-x-type-steam-softsteam-77-l-czarny-i258728 |
| lodówka | Bosch KIN86NSE0 | 3199 | 67,90 | brak | NIE (177 cm, NoFrost tylko zamrażarka) | https://www.sferis.pl/lodowka-bosch-kin86nse0-do-zabudowy-z-dolnym-zamrazalnikiem-177-2-x-54-1-cm-zawias-slizgowy-nofrost-i679146 |
| lodówka | Amica BK3055.6 NFM(E) | 2039 | 0 | brak | NIE (41 dB, 177 cm) | https://www.sferis.pl/lodowka-do-zabudowy-amica-bk3055-6-nfm-e-total-no-frost-176-9-cm-kompresor-inwerterowy-szuflada-vitcontrol-biala-i722376 |
| płyta | Amica PIM6540PHTUN 3.0 | 1199 | 0 | brak | 6/6 potwierdzone, 2 „?” (suwak, blokada) | https://www.sferis.pl/plyta-indukcyjna-amica-pim6540phtun-3-0-60-cm-powerboost-autobridge-hobcontrol-pro-czarny-ultra-plaska-i603634 |
| płyta | Bosch PIE611BB5E | 1399 | 0 | brak | NIE (TouchSelect, nie suwak per strefa) | https://www.sferis.pl/plyta-indukcyjna-bosch-pie611bb5e-serie-4-60-cm-4-pola-powerboost-touchselect-czarny-i296293 |
| płyta | Electrolux EIV644 | 2299 | 0 | brak | 5/6 (2 strefy flex, timer mechaniczny) | https://www.sferis.pl/plyta-indukcyjna-electrolux-eiv644-60-cm-4-pola-powerboost-timer-czarny-i400482 |
| okap | Electrolux LFP326FB | 659 | 0 | brak | 6/7 (klapa zwrotna ?) | https://www.sferis.pl/okap-teleskopowy-electrolux-lfp326fb-60-cm-300-m3-h-led-czarny-i297104 |
| okap | MAAN Corona Touch Bis 60 | 639 | 0 | brak | 5/7 (fi ?, głębokość ?, klapa ?) | https://www.sferis.pl/okap-teleskopowy-maan-corona-touch-bis-60-cm-sterowanie-dotykowe-led-czarny-i293624 |
| mikrofalówka | Whirlpool WMD44MX | 1619 | 0 | brak | TAK (talerz 32,5 cm, 385 mm) | https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-whirlpool-wmd44mx-31-litrow-crisp-3d-grill-i753728 |
| mikrofalówka | Beko BMGB25353B | 999 | 0 | brak | TAK (talerz 31,5 cm) | https://www.sferis.pl/kuchenka-mikrofalowa-do-zabudowy-beko-bmgb25353b-czarna-900w-25l-grill-i617718 |
| zmywarka | Gorenje GV663B65 | 2399 | 0 | brak | TAK (wszystkie) | https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-gorenje-gv663b65-klasa-b-16-kpl-aquastop-totaldry-speedwash-i652768 |
| zmywarka | Bosch SMV4ECX23E | 2899 | 0 | brak (Bosch cashback zmywarki do 700 zł do 15.11.2026) | 5/6 (dysze ?) | https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-bosch-smv4ecx23e-serie-4-klasa-c-14-kpl-efficientdry-speedperfect-40-db-i645960 |
| pralka | Bosch WGG244Z0PL | 2499 | 0 | brak | TAK (inwerter ?) | https://www.sferis.pl/pralka-bosch-wgg244z0pl-serie-6-9-kg-1400-obr-min-program-parowy-activewater-plus-wifi-home-connect-i587221 |
| pralka | Amica WAC914ALISO | 1479 | 0 | brak | TAK poza inwerterem (?) — 76 dB, brak łącznika | https://www.sferis.pl/pralka-amica-wac914aliso-9-kg-1400-obr-min-steampowerpro-program-anty-alergiczny-cicha-praca-i398086 |
| pralka | Beko BM3WFU410415W (10 kg) | 1799 | 0 | brak | TAK (brak łącznika w sklepie) | https://www.sferis.pl/pralka-wolnostojaca-beko-bm3wfu410415w-10kg-1400obr-para-coolclean-i776049 |
| suszarka | Bosch WQG243DRPL | 4199 | 0 | Bosch cashback (do 1000 zł, do 31.12.2026) | TAK (C, 63 dB) | https://www.sferis.pl/suszarka-wolnostojaca-bosch-wqg243drpl-serie-6-10-kg-klasa-a-pompa-ciepla-autodry-i649437 |
| suszarka | Electrolux EW6D295GP | 2569 | 0 | brak | TAK (czujnik ?, odpływ ?) | https://www.sferis.pl/suszarka-electrolux-ew6d295gp-z-pompa-ciepla-9kg-klasa-c-65db-sensicare-i619018 |
| suszarka | Beko BM3T49249W | 2349 | 0 | brak | TAK (drzwi niezmieniane) | https://www.sferis.pl/suszarka-automatyczna-beko-bm3t49249w-9kg-pompa-ciepla-i726568 |
| łącznik | Bosch WTZ2741C | 319 | 17,90 | brak | TAK dla pary Bosch | https://www.sferis.pl/lacznik-pralki-z-suszarka-bosch-wtz2741c-i653975 |

---

## Wnioski

1. **Kupuj w Sferis tylko wybrane kategorie.** Sklep ma **bardzo mocną zmywarkę, która u mnie wygrywa kategorię** (Gorenje GV663B65, **2399 zł**, 16 kpl, 38 dB, auto-uchylanie drzwi, dysze na garnki, AquaStop — komplet MUST) oraz **piekarnik z parą i termosondą — Electrolux EOD4P57H SteamBake 2499 zł** (72 l, teleskopy, piroliza) plus tani, poprawny okap (Electrolux LFP326FB **659 zł**, fi 150, gł. 265 mm).
2. **Trzy kategorie są w Sferis praktycznie wykluczone:** (a) **lodówka do zabudowy 193,5 cm z 2 obiegami** — brak Samsunga i brak jakiegokolwiek modelu 193,5 × 60 cm; (b) **płyta indukcyjna Whirlpool w błyszczącym czarnym szkle** — jest tylko wariant **MAT** (WF S7560NE BM 1739 zł), którego wymagania zabraniają; (c) **pralnia Samsung** — brak WW90CGC04DAE i DV9MDG52A0AE, brak łącznika SKK. Para Bosch w Sferis kosztuje **7017 zł** (z łącznikiem) wobec **4288 zł** za Samsunga na euro.com.pl — **pralnię kupuj poza Sferis**.
3. **Uważaj na „prawie MUST”:** okapy Gorenje/Electrolux LFP226S mają 330–350 m³/h (za mało), mikrofale Bosch BFL520MB0 ma talerz 25,5 cm, piekarnik Amica ma katalizę zamiast hydrolizy, suszarki Bosch WQG145APPL/WQG241ALPL mają klasę **D**. Wszystkie te pozycje wyglądają tanio, ale nie spełniają wymagań.
4. **Dwie sprzeczności w kartach Sferis do potwierdzenia telefonicznie (22 32 70 888):** okap Electrolux LFP326FB — tabela podaje **410 m³/h**, slug „300 m3/h” (to nazwa serii „LEDLights 300”); suszarka Bosch WQG243DRPL — nagłówek „10 kg / klasa A”, tabela „9 kg / klasa C” (obowiązuje C). Trzecia niepewność jest merytoryczna: **pary „para + termosonda” w jednym piekarniku nie da się w Sferis kupić z szufladą/zbiornikiem na wodę** — wymóg „szuflada na wodę” nie jest spełniony przez żaden model (Electrolux SteamBake/Steamify i Whirlpool Steam+ parują bez wyjmowanego zbiornika).
5. **Rabaty:** najprostszy zysk to **kod newslettera −50 zł (koszyk ≥2000 zł)** — albo, przy koszyku ~18 tys. zł, **cashback Refundera 1,5% netto** (~220 zł), ale **tych dwóch nie łączymy** (Refunder wyklucza obce kody). Cashback **Bosch do 1000 zł** (suszarki, zakup do **31.12.2026**, rejestracja do 30.01.2027) i **Bosch do 700 zł** (zmywarki, do **15.11.2026**) są rozliczane po zakupie — dlatego suszarka Bosch (mimo +1630 zł) może być realnie tylko ~1000–1100 zł droższa od Electroluxa. **Cashback Whirlpool (do 3000 zł, do 31.12.2026)** wymaga piekarnika Whirlpool, więc **wyklucza się z wyborem piekarnika Electrolux** — para „piekarnik WOI4S8HM2SBA + mikrofalówka WMD44MX” to jedyna konfiguracja z potencjalnym zwrotem, ale kwoty dla tych modeli są `niepotwierdzone`.
6. **Terminy i dostawa:** wszystkie pozycje „Dostępny”, odbiór **27.10.2026**; dostawa AGD **0 zł**, ale **lodówka idzie półpaletą od 67,90 zł**, a łącznik od 17,90 zł. Wniesienie/instalacja to **osobne pakiety Zadbano** (piekarnik 99/319 zł, płyta 99/249 zł, okap 99/169 zł, mikrofala 68/199 zł, zmywarka i pralka 99–139/249–319 zł, lodówka 139/249–319 zł) — **odbioru starego sprzętu nie ma w pakiecie**. Przy 8 urządzeniach suma samych instalacji to **ok. 2100–2200 zł** (319 + 249 + 169 + 199 + ~319×2 + ~319 + ~319), a samych wniesień **ok. 850–900 zł** — jeśli chcesz to zlecić sklepowi.
