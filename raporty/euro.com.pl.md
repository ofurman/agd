# euro.com.pl – raport (25.10.2026; ceny koszyka zweryfikowane 26.10.2026)

> **Aktualizacja 26.10.2026 — decyzja użytkownika: płyta Electrolux CIV634 (2 099,00) + okap Electrolux LFG716R (1 348,99).** Poniższe tabele są snapshotem rynku z 25.10 (WBS2560NE, LFP326FW); wiersze wybranych modeli są oznaczone. Aktualny koszyk: baza **20 843,25**, kod −3 000, netto **16 193,25** / podział **15 663,44** — patrz `README.md` i `zakup-optimal.md` §0.

**Źródło wszystkich cen:** strona sklepu euro.com.pl (REST API sklepu `/rest/api/products…`, te same dane co karta produktu), stan na 25.10.2026. **Uzupełnienie 26.10.2026:** ceny 10 pozycji oraz zachowanie koszyka i kodu `RKPROGAGD1026` sprawdzone na żywo w Arc — patrz `zakup-optimal.md` §0 i `koszyk-euro.md` §0. Ceny „z kodem” to kody produktowe pokazane przy produkcie (naliczają się automatycznie w koszyku). Ceneo blokuje boty (captcha), więc ceneo nie było źródłem.
Legenda MUST: ✓ = spełnia wg karty sklepu, ✗ = nie spełnia, ? = karta sklepu nie podaje / do sprawdzenia w instrukcji.
Linki: `https://www.euro.com.pl/<kategoria>/<produkt>.bhtml`.

## Promocje sklepowe

| Promocja | Warunki | Ważność | Łączenie |
|---|---|---|---|
| **Nawet 3000 zł rabatu** (kod koszykowy **RKPROGAGD1026**) | Min. 2 produkty promocyjne o łącznej wartości ≥ 1000 zł. Rabat: 100 zł (od 1000 zł), 250 zł (od 2000), 400 zł (od 3000), **750 zł (od 5000)**, **1400 zł (od 9000)**, 1900 zł (od 12 000), 3000 zł (od 16 000). Maks. 2 szt. tego samego modelu. Obejmuje prawie wszystkie produkty z tego raportu (plakietka na karcie). | 07.10–**31.10.2026 23:45** | To kod koszykowy. Produkt objęty kodem koszykowym **nie dostaje już kodu produktowego**. Opłaca się więc dla produktów **bez** kodu produktowego (wzorce: piekarnik, zmywarka, okap LFP326FW, łącznik). [cms/agd-nawet-3000zl-rabatu](https://www.euro.com.pl/cms/agd-nawet-3000zl-rabatu.bhtml) |
| **Wielosztuki / 5. produkt za 1 zł** (kod **WIEL**) | Przy 2 różnych produktach tańszy −30%, przy 3 najtańszy −55%, przy 4 −80%, przy 5+ **najtańszy za 1 zł**. Na naszym koszyku: jedna transakcja 9 pozycji = **−612 zł** (okap), podział **4+3+2 = −2 656,09 zł**. | Bezterminowo (od 31.05.2026; Pepper ~05.11.2026) | Kod koszykowy. **Nie łączy się** z `RKPROGAGD1026` na tych samych produktach; przegrywa o 343,91 zł. [cms/piaty-za-1-zl](https://www.euro.com.pl/cms/piaty-za-1-zl.bhtml) |
| **50 zł za każde wydane 500 zł** (kod **50ZA500201026**) | To **kod na kolejne zakupy (codeback)**, nie rabat od razu. Przykłady z kart: lodówka Samsung 350 zł, Candy 300 zł, Amica 200 zł. Kod ważny 3 miesiące. Kod obniża zakup maks. o 50%. Maks. 2000 zł. | 20.10–**03.11.2026** | Wykorzystanie kodu nie łączy się z kodami produktowymi i koszykowymi. To, czy zakup z kodem produktowym daje prawo do codebacku: **niepotwierdzone** (regulamin). [cms/50-za-500](https://www.euro.com.pl/cms/50-za-500.bhtml) |
| **Whirlpool Days – drugi tańszy −40%** (kod **RKWHIRLPOOLDAYS40PR1026**) | Min. 2 różne produkty Whirlpool z promocji, tańszy −40%. Objęte m.in.: płyta WBS2560NE, lodówka WHC20T573P, zmywarki WIO3O540PELG i W7IHP40L, mikrofalówki AMW6440FB, WMD54MB i WMD7O4TB. **Wzorce WOI7A8FHT2SBA i W7IHT58T nie są objęte.** | 13.10–**26.10.2026 23:45 (jutro!)** | Kod koszykowy (zastępuje kody produktowe). [cms/whirlpool-days-najtanszy-40proc](https://www.euro.com.pl/cms/whirlpool-days-najtanszy-40proc.bhtml) |
| Whirlpool Days – płyta −50% przy piekarniku (RKWHIRLPOOLDAYSPLYTA50PR) | Tylko wybrane piekarniki. Plakietkę ma WOI98FPT2SBA (bez pary, ✗ MUST). Wzorzec WOI7A8FHT2SBA **jej nie ma**. | 13.10–26.10.2026 | [cms/whirlpool-days-plyta-50proc](https://www.euro.com.pl/cms/whirlpool-days-plyta-50proc.bhtml) |
| Whirlpool Days – zmywarka: pakiet usług za 1 zł i kapsułki Fairy za 1 zł | Wybrane zmywarki Whirlpool (np. WIO3O540PELG, W7IHP40L). Wzorzec W7IHT58T nie ma tej plakietki. | 13.10–26.10.2026 | [cms/whirlpool-days-zmywarka-uslugi-1zl](https://www.euro.com.pl/cms/whirlpool-days-zmywarka-uslugi-1zl.bhtml) |
| Samsung „płyta za 1 zł przy piekarniku i zmywarce” (RKSAMSPLYTA1ZL) | Wybrane modele Samsung | 15.10–31.10.2026 | Nieopłacalne, bo piekarnik Samsung NV7B5685AAK nie ma hydrolizy. |
| Samsung Cashback AGD „do 4500 zł” (organizator Samsung) | Zwrot na konto po zakupie i **opublikowaniu opinii**: pralki 200–700 zł, suszarki 200–700 zł, lodówki 200–1200 zł. Plakietkę mają pralka WW90CGC04DAE i suszarka DV9MDG52A0AEEO. Dokładna kwota dla tych modeli: **niepotwierdzone** (załącznik 1 na cashbackagd.samsung.pl). | 01.10–**30.11.2026** | Cashback producenta, więc łączy się z ceną sklepu. [cms/samsung-cashback-agd](https://www.euro.com.pl/cms/samsung-cashback-agd.bhtml) |
| Whirlpool Cashback „do 3000 zł”, Haier „do 5000 zł”, Siemens „do 6500 zł” | Plakietki na kartach (Whirlpool: piekarnik wzorcowy; Haier: lodówki i zmywarka XI 6B0S3FSB). Kwoty dla modeli: **niepotwierdzone**. | – | Cashbacki producentów |
| Beko – kod 300 zł na kolejne zakupy przy zmywarce Beko | Np. BDIN37541WP | 13.10–26.10.2026 | codeback |
| „Kasa za opinię” | Karta podarunkowa 150 zł za opinię (plakietka na piekarniku WOI7A8FHT2SBA) | – | – |
| **Raty** | „2 raty gratis! 30 rat 0% RRSO 0%” (kredyt 300–30 000 zł, obejmuje też usługi). Na stronach widoczne też „aż 50 rat 0%” dla wybranych produktów. | 13.10–31.10.2026 | Łączy się z kodami (zasady kodów, pkt o produktach ratalnych) |
| **Dostawa** | Duże AGD: **darmowa** od 99 zł, na 2. dzień roboczy i później. Na jutro 24,99 zł, ten sam dzień 29,99 zł, przedziały godzinowe 24,99–49,99 zł. Odbiór w sklepie 0 zł. | stałe | [cms/darmowy-transport](https://www.euro.com.pl/cms/darmowy-transport.bhtml) |
| **Odbiór zużytego sprzętu** | **Bezpłatnie** przy dostawie do domu: zabierają sprzęt tego samego rodzaju (opcja „Mam zużyty sprzęt do oddania”). | stałe | – |
| **Wniesienie i montaż** (cennik) | Wniesienie: okap i mikrofala 49,99 zł, płyta 79,99 zł, piekarnik, zmywarka, pralka i suszarka 89,99 zł, lodówka do zabudowy 99,99 zł. **Montaż w zabudowie:** zmywarka 299,99 zł, lodówka 299,99 zł, piekarnik 299,99 zł, płyta 249,99 zł, **zestaw płyta + piekarnik 369,99 zł**. Pralka z instalacją 159,99 zł, suszarka 159,99 zł, **montaż słupka pralka + suszarka 299,99 zł**. Wersje z demontażem starego sprzętu: +20–30 zł. | stałe | [cms/cennik-uslug-dodatkowych](https://www.euro.com.pl/cms/cennik-uslug-dodatkowych.bhtml) |

**Zasady łączenia kodów** ([cms/aktualne-kody-rabatowe](https://www.euro.com.pl/cms/aktualne-kody-rabatowe.bhtml)):
- Jeden produkt może dostać tylko jeden kod: produktowy **albo** koszykowy.
- W jednym zamówieniu może być kilka kodów produktowych i koszykowych, jeśli obejmują różne produkty.
- Produkty, które warunkują kod koszykowy, tracą kod produktowy.
- Kody produktowe działają automatycznie. Jeśli w koszyku jest aktywny kod koszykowy, kod produktowy trzeba zaznaczyć ręcznie.
- Większość kodów produktowych w raporcie (REW…/RGEW…/RGBF…) jest ważna do **31.10.2026 23:45**.

## 1. Piekarnik do zabudowy

MUST: para / szuflada na wodę / termosonda / hydroliza / teleskopy na 2 poziomach / termoobieg.

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| Whirlpool WOI7A8FHT2SBA | wzorzec | 3499 zł | 3499 zł (brak kodu). Wchodzi do „Nawet 3000” i „Piąty za 1 zł”. | – | ✓✓✓✓✓✓ (SteamSense, termosonda, hydroliza, teleskopy 2 poz.). Szuflada na wodę wg wymagań: ✓ | 73 l, A+, 30–310°C, 4,9★/33. Dostępność: do 7 dni. Najniższa cena z 30 dni: brak informacji. | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/whirlpool-woi7a8fht2sba-termoobieg-termosonda-airfry-czarny.bhtml) |
| Haier ID2P5B5EYTB (seria ID2 H6) | odpowiednik (najtańszy) | 2199 zł | 2199 zł | – | para ✓ (Easy Steam), szuflada na wodę ?, termosonda ✓ (nazwa), hydroliza ✓ (piroliza + hydroliza), teleskopy ✓ (liczba poziomów ?), termoobieg ✓ | −1300 zł. A++, 78 l, ma też pirolizę i tacę AirFry. Szczegóły karty niepotwierdzone (API sklepu zablokowało ponowny odczyt). | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/haier-seria-id2-h6-id2p5b5eytb-taca-air-fry-termosonda-termoobieg-czarny.bhtml) |
| Amica ED975398BA+ X-Type Steam P | odpowiednik | 2219,99 zł | 2219,99 zł (codeback 200 zł w 50-za-500) | – | para ✓ (SoftSteam), szuflada ?, termosonda ✓, **hydroliza ✗ (piroliza)**, teleskopy 2 poz. ✓, termoobieg ✓ | −1279 zł. 77 l, maks. 280°C, „programy parowe: nie”. Piroliza zamiast hydrolizy. | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/amica-ed975398ba-x-type-steam.bhtml) |
| Gorenje BPSA6747A36DBG | odpowiednik | 2799 zł | **2398 zł** | REW1610311026C1 do 31.10.2026 23:45 | para ✓, zbiornik ?, termosonda ✓, **hydroliza ✗ (piroliza)**, teleskopy 2 poz. ✓, termoobieg ✓ | −1101 zł. 77 l, 300°C, Wi-Fi. | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/gorenje-bpsa6747a36dbg-termosonda-zdalne-sterowanie-czarny.bhtml) |
| Whirlpool WOI11P8FHT2SBAF | alternatywa+ | 4699,99 zł | **4598 zł** | REW1610311026C1 do 31.10.2026 | ✓ wszystkie | +1099 zł vs wzorzec. Wyższa seria W11 (lepszy panel i wykończenie). Niewielki zysk za tę dopłatę. | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/whirlpool-woi11p8fht2sbaf-termoobieg-termosonda-airfry-czarny.bhtml) |
| Samsung NV7B5685AAK Dual Cook | alternatywa | 4399,99 zł | 4399,99 zł | – (Samsung cashback) | para ✓ (Steam Assist), termosonda ✓, **hydroliza ✗ (czyszczenie parą + kataliza)**, teleskopy 2 poz. ✓ | Dual Cook, 76 l, ale tylko 250°C | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/samsung-nv7b5685aak-dual-cook.bhtml) |
| Whirlpool WOI98FPT2SBA | ✗ | 3599 zł | 2899 zł | kod produktowy do 31.10 | **para ✗** | Odrzucony. Ma promocję „płyta −50%”. | [link](https://www.euro.com.pl/piekarniki-do-zabudowy/whirlpool-woi98fpt2sba-termoobieg-termosonda-airfry-czarny.bhtml) |

Uwaga: piekarniki parowe Electrolux (np. EOD6P77WZ, 2298 zł) mają teleskopy tylko na 1 poziomie (✗).

## 2. Lodówka do zabudowy

MUST: ok. 193,5 cm i zawiasy ślizgowe / pełny No Frost / 2 niezależne obiegi / ok. 298 l / ≤35 dB.

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| Samsung BRB70F30**BES0**EO | wzorzec | 3699,99 zł | **3299 zł** (najniższa cena z 30 dni: 3699,99) | **REW041026311026C1**, 04.10–31.10.2026 23:45 | ✓ wszystkie (193,5×54×55, zawiasy ślizgowe, 224/74 l, 35 dB, Twin Cooling) | Klasa E, 229 kWh, Wi-Fi. Codeback 350 zł w akcji 50-za-500. | [link](https://www.euro.com.pl/lodowki-do-zabudowy/samsung-brb70f30bes0eo-pelny-no-frost-193-5cm-komora-swiezosci-zdalne-sterowanie.bhtml) |
| **Samsung BRB80F30ADF0EO** | baseline (D) | 4 549 zł (sugerowana) | **4 299,99 zł** — live 26.10; + cashback Samsung **300 zł** | – (kod 3000) | ✓ 298 l (224+74), D 183 kWh, 35 dB, Twin Cooling Plus, No Frost, Optimal Fresh+ | **Cena wzrosła** z 3 971,69 (Morele, 25.10) do 4 299,99 w euro. Po cashbacku 3 999,99. Zawiasy nożycowe. | [link](https://www.euro.com.pl/lodowki-do-zabudowy/samsung-brb80f30adf0eo-pelny-no-frost-193-5cm-komora-swiezosci-zdalne-sterowanie.bhtml) |
| Samsung BRB70F30BE**F**0EO | wariant | 3599,99 zł | 3599,99 zł | – | ✓ | Inny wariant (uwaga na pełny kod). Drożej o 300 zł. | – |
| Candy CNBQT5519DW | odpowiednik (najtańszy) | 3499,99 zł | **2799 zł** | REW2010311026C1 do 31.10.2026 | wys./zawiasy ✓, NF ✓, **2 obiegi ?** (2 termostaty), 211/73 l ≈ 284 l ✓, 33 dB ✓ | −500 zł. Klasa D, 183 kWh (oszczędniejsza). Codeback 300 zł. | [link](https://www.euro.com.pl/lodowki-do-zabudowy/candy-cnbqt5519dw-panorama-light-total-no-frost-circle-fresh-szuflada-humidity-zone-kompresor-inwerterowy.bhtml) |
| Whirlpool WHC20T573P | odpowiednik / alternatywa+ | 3499 zł | **2899 zł** | RGEWICP0510311026, 05.10–31.10.2026 | zawiasy ✓, NF ✓, **2 obiegi ?** (2 termostaty, 1 sprężarka), 212/68 l = 280 l ✓, **32 dB** ✓ | −400 zł vs wzorzec. **Cichsza (32 dB) i klasa D (177 kWh)**. Ma promocje Whirlpool Days. | [link](https://www.euro.com.pl/lodowki-do-zabudowy/whirlpool-whc20-t573-p.bhtml) |
| Haier EHBQW5519ECM | odpowiednik | 3399 zł | 2999 zł | RGEW0710311026C3, 07.10–31.10.2026 | NF ✓, 2 obiegi ?, 211/73 l ✓, 35 dB ✓ | −300 zł. Klasa E. Haier cashback do 5000 zł. | [link](https://www.euro.com.pl/lodowki-do-zabudowy/haier-ehbqw5519ecm-total-no-frost-kompresor-inwerterowy-szuflada-humidity-zone.bhtml) |
| Whirlpool WHC20T352 | odpowiednik | 2599,99 zł | 2599 zł | kod produktowy do 31.10 | 32 dB ✓, 212/68 l, 2 obiegi ?, klasa E | Dostępność UNDEFINED (prawdopodobnie brak) | [link](https://www.euro.com.pl/lodowki-do-zabudowy/whirlpool-whc20-t352.bhtml) |

Odrzucone: Beko BCNA306E4ZSN (37 dB ✗), Whirlpool WHK25323B5E1 (37 dB ✗), modele 69 cm szerokości (nie pasują do wnęki).

## 3. Płyta indukcyjna

MUST: 59–60 cm / strefa łączona / 4 pola / booster / suwak na strefę / błyszczące szkło / blokada + wskaźnik ciepła.

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Electrolux CIV634** | **WYBÓR 26.10.2026** | 2 099 zł | 2 099 zł | – (kod koszykowy) | 59 cm ✓, Bridge ✓, 4 pola ✓, Booster 3,2 kW ✓, **suwak: jeden pasek + wybór pola (7/8)** | 44 mm, H2H, czarne błyszczące; para z LFG716R 3 447,99 → cashback Electrolux 400. **H2H — główny powód.** | [link](https://www.euro.com.pl/plyty-do-zabudowy/electrolux-civ634.bhtml) |
| Whirlpool WB S2560 NE (bez matu) | wzorzec | 1499 zł | **1348 zł** | **REW2010311026C**, do 31.10.2026 23:45 | ✓ wszystkie (FlexiCook, suwak, szkło ceramiczne, 4 programy 6. Zmysł, blokada, wskaźnik) | 7,2 kW. W Whirlpool Days (−40% jako tańszy produkt do 26.10). | [link](https://www.euro.com.pl/plyty-do-zabudowy/whirlpool-wb-s2560-ne.bhtml) |
| Whirlpool WBS2560NEBM MattProtect | – | 2249 zł | – | – | ✗ (mat) | niechciany | – |
| Indesit IS35Q60NE | odpowiednik (najtańszy) | 899 zł | **697 zł** | REW1610311026C1 do 31.10.2026 | 59 cm ✓, łączenie stref ✓ (filtr sklepu), 4 pola ✓, booster ✓, **suwak ✓ (osobny na strefę ?)**, szkło ✓, blokada i wskaźnik ✓ | −651 zł. Brak programów automatycznych (NICE). | [link](https://www.euro.com.pl/plyty-do-zabudowy/indesit-is35q60ne-59cm-czarny.bhtml) |
| Sharp KH-6I35NS0K-EU | odpowiednik | 1069,99 zł | 699 zł | REW1510311026C do 31.10.2026 | strefa brytfanna ✓, suwak ✓, **blokada / wskaźnik ?** (karta podaje tylko auto-wyłączenie) | −649 zł | [link](https://www.euro.com.pl/plyty-do-zabudowy/sharp-kh-6i35ns0k-eu-59cm.bhtml) |
| Midea MIH744BE325GK | odpowiednik | 999 zł | 849 zł | kod produktowy do 31.10 | mostek ✓, suwak ✓, booster ✓, wskaźnik ✓, **blokada ?** | −499 zł. 7,4 kW. Codeback 50 zł. | [link](https://www.euro.com.pl/plyty-do-zabudowy/midea-mih744be325gk-59cm.bhtml) |
| Beko HII64700UFT bPro500 | alternatywa (tańsza od wzorca) | 1599,99 zł | **1297 zł** | kod produktowy do 31.10 | suwak ✓, IndyFlex ✓, booster ✓, blokada / wskaźnik ? | −51 zł vs wzorzec. Ma HobToHood. Brak 6. Zmysłu. | [link](https://www.euro.com.pl/plyty-do-zabudowy/beko-hii64700uft-bpro500.bhtml) |
| Candy CIES64MCA | ✗ | 999,99 zł | 848 zł | – | **suwak ✗** | – | [link](https://www.euro.com.pl/plyty-do-zabudowy/candy-cies64mca-59cm.bhtml) |

Odrzucone: Beko HII64200SFMT (1146 zł, brak suwaka) i Electrolux LIV63431BK (1448 zł, brak suwaka).

## 4. Okap — wkład (wybór) + teleskopy (historia)

Karty sklepu podają **tylko maksymalną głośność i wydajność**. Nie podają głośności na biegu codziennym, klapy zwrotnej, silnika BLDC ani minimalnej głębokości szafki, więc te MUST są „?” dla wszystkich. **Wybrany LFG716R to wkład 54 cm; pozostałe wiersze to historyczne teleskopy 60 cm.**

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze | Link |
|---|---|---|---|---|---|---|---|
| **Electrolux LFG716R** | **WYBÓR 26.10.2026 (wkład)** | 1 348,99 zł | 1 348,99 zł | – (kod koszykowy) | wkład 54 cm ✓, 580/700 m³/h ✓, 67/54 dB ✓, Ø150 ✓, H2H ✓, klapa ? | 30 cm głębokości (przednie pola poza obrysem); para z CIV634 3 447,99 → 400 zł. | [link](https://www.euro.com.pl/okapy/electrolux-lfg716r.bhtml) |
| **Electrolux LFP326FW (biały)** | historyczny (zastąpiony przez LFG716R) | 789 zł | **638,99 zł promo** (wchodzi do „Nawet 3000”) | – | fi150 ✓, **410 m³/h maks.**, **57 dB LwA min. / 69 maks.**, filtry alu ✓, gł. 28,4 cm ✓; **2 MUST niepełne**; klapa ? | biały teleskop, 3 biegi, 100 W, klasa C, bez timera. **Nieaktualny wybór.** | [karta ME](https://www.mediaexpert.pl/agd-do-zabudowy/okapy-do-zabudowy/okap-electrolux-lfp326fw-bialy-410m3-h-69db-klasa-c) (euro: szukaj LFP326FW) |
| Elica Elite 26 IX/A/60 | alternatywa (najcichsza) | 638,99 zł | 638,99 zł (wchodzi do „Nawet 3000”) | – | fi150 ✓, 581 m³/h maks. (bieg zwykły 480–496), filtry alu ✓, głośność 44–61 dB, klapa ?, gł. 28 cm ✓ | booster, wybieg, timer. Listwa stalowa (nie biała). | [link](https://www.euro.com.pl/okapy/elica-26-ix-a-60-stalowy.bhtml) |
| Maan Corona BIS G 60 | odpowiednik | 699 zł | 627 zł | RGBF18311026 do 31.10.2026 | 615 m³/h, 66 dB maks., reszta ? | czarny | [link](https://www.euro.com.pl/okapy/maan-corona-bis-g-60-czarny.bhtml) |
| VDB Ideal Pro 60 Black | odpowiednik | 749 zł | 749 zł | – | 670 m³/h, 62 dB maks., timer | czarny | [link](https://www.euro.com.pl/okapy/vdb-ideal-pro-60-black.bhtml) |
| Whirlpool WAHTT 64 LM K | odpowiednik | 879 zł | 879 zł | – | 581 m³/h, 65 dB, filtry stalowe | czarny, Whirlpool (spójny z piekarnikiem) | [link](https://www.euro.com.pl/okapy/whirlpool-wahtt-64-lm-k-czarny.bhtml) |
| VDB Vector PRO 60 | alternatywa+ | 999,99 zł | 999,99 zł | – | 788 m³/h, 62 dB | większy zapas wydajności, czarny | [link](https://www.euro.com.pl/okapy/vdb-vector-pro-60-czarny.bhtml) |
| Electrolux LFP626AK | alternatywa | 1199 zł | 1199 zł | – | 600 m³/h, klasa A, 68 dB | – | [link](https://www.euro.com.pl/okapy/electrolux-okap-lfp626ak-electrolux.bhtml) |
| Akpo WK-7 Light Glass Touch | odpowiednik | 599,96 zł | 599,96 zł | – | 719 m³/h, **69 dB**, silnik indukcyjny | najtańszy, ale najgłośniejszy | [link](https://www.euro.com.pl/okapy/akpo-wk-7-light-glass-touch-60-czarny-60cm.bhtml) |

Odrzucone: Faber Flexa NG (wylot fi 120 ✗) i Electrolux LFP336K (669 zł, tylko 410 m³/h). Globalo Teslo 60.1 (1059 zł, 575 m³/h) – bez przewagi.

## 5. Mikrofalówka do zabudowy

MUST: talerz ≥ ok. 31–32 cm / 60 cm / wys. ok. 38 cm. Whirlpool W7 MD440 NB **nie występuje** w euro.com.pl. W6 MD440 BSS kosztuje 1949,99 zł, ale ma dostępność UNDEFINED.

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze | Link |
|---|---|---|---|---|---|---|---|
| Candy CA38FL7N25WXB | odpowiednik (najtańszy) | 1099 zł | **799 zł** | REW1610311026C1 do 31.10.2026 | talerz 31,5 cm ✓ (na granicy), 60 cm ✓, wys. 38,5 cm ✓ | 26 l, czarne szkło, grill | [link](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/candy-ca38fl7n25wxb-.bhtml) |
| Gorenje BM251M2BG | odpowiednik | 949 zł | 949 zł | – | talerz 31,5 ✓, wysokość ? | 25 l, bez grilla | [link](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/gorenje-bm251m2bg.bhtml) |
| Amica AMMB25E4SGB | odpowiednik | 1359 zł | 949 zł | kod produktowy do 31.10 | talerz 31,5 ✓, wysokość ? | – | [link](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/amica-ammb25e4sgb.bhtml) |
| Beko BMGB31443B | alternatywa | 1849 zł | 1397 zł | kod produktowy do 31.10 | 31 l, talerz 31,5 ✓, wysokość ? | większa komora. Codeback 150 zł. | [link](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/beko-b300-bmgb31443b-grill.bhtml) |
| **Whirlpool AMW6440FB** | alternatywa+ | 2039 zł | **1742 zł** | REW1610311026C1 do 31.10.2026 | 31 l, **talerz 32,5 cm** ✓, wysokość ? | Najbliżej W7 MD440: ta sama marka, czarne szkło. +943 zł vs Candy. W parze z inną rzeczą Whirlpool z akcji Days −40% (do 26.10). | [link](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/whirlpool-amw-6440-fb-grill.bhtml) |
| Whirlpool WMD54MB / WMD7O4TB | alternatywa | 1849,99 / 2119,99 zł | bez kodu | – | talerz 32,5 ✓ | – | [WMD54MB](https://www.euro.com.pl/kuchenki-mikrofalowe-do-zabudowy/whirlpool-wmd54mb-grill.bhtml) |

## 6. Zmywarka do zabudowy

MUST: 60 cm, pełna zabudowa / ≥14–15 kpl. / szuflada na sztućce / ≤40 dB / auto-otwieranie drzwi / dodatkowe dysze na garnki / regulowane kosze, stalowa komora. Wszystkie poniżej spełniają: 60 cm, szufladę i auto-otwieranie (filtr sklepu).

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Co lepsze / gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| Whirlpool W7I HT58 T MaxiSpace | wzorzec | 2299,99 zł | 2299,99 zł (brak kodu). Wchodzi do „Nawet 3000”. | – | 15 kpl. ✓, szuflada ✓, **38 dB** ✓, auto-otwieranie ✓, PowerClean / strefa intensywna ✓, kosze Lift-Up ✓, stalowa komora ? | Klasa B (0,654 kWh). Projekcja na podłodze ✓. Zawiasy zwykłe. Ochrona przed zalaniem: „wąż dopływowy z zabezpieczeniem” (AquaStop ?). Dostawa: pojutrze. | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/whirlpool-w7i-ht58-t-60cm-automatyczne-otwieranie-drzwi-szuflada-na-sztucce.bhtml) |
| Haier XI 6B0S3FSB Washlens Plus | odpowiednik (najtańszy) | 2229,99 zł | **1978 zł** (najniższa z 30 dni: 1988) | REW041026311026C3, 04.10–31.10.2026 | 16 kpl. ✓, 40 dB ✓ (na granicy), strefa intensywna ✓, Lift-Up ✓, stalowa komora ? | −322 zł. Oświetlenie wnętrza. Bez projekcji na podłodze. Klasa B. Haier cashback. | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/haier-xi-6b0s3fsb-automatyczne-otwieranie-drzwi-59-7cm-szuflada-na-sztucce.bhtml) |
| Beko bPro500 BDIN37541WP | odpowiednik | 2219,99 zł | **1989 zł** (live 26.10, Arc) | wg wcześniejszego odczytu REW041026311026C3 do 31.10.2026 | 15 kpl. ✓, **40 dB ✓**, **PowerIntense ✓**, TrayWash ✓, MaxiDry, kosze 3-poziomowe ✓ | −311 zł. Silnik inwerterowy, WaterSafe+. Klasa C, 0,76 kWh, 8,9 l. Codeback Beko 300 zł (do 26.10). | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/beko-bpro500-bdin37541wp-powerintense-59-8cm-automatyczne-otwieranie-drzwi-szuflada-na-sztucce.bhtml) |
| ⚠ Beko BDIN37540WP (link użytkownika) | odrzucona | **2035 zł** (Ceneo 25.10, najniższa z 90 dni) | – | – | 15 kpl. ✓, szuflada ✓, auto-otwieranie ✓, PowerIntense ✓, **42 dB ✗** (karta Beko) | **Nie spełnia ≤40 dB** (oficjalna karta: 42 dBA). 5,9 l — oszczędna woda, ale klasa C 0,76 kWh. **Wybrać 37541WP: 40 dB i 46 zł taniej.** | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/beko-bpro500-bdin37540wp-powerintense-savewater-59-8cm-automatyczne-otwieranie-drzwi-szuflada-na-sztucce.bhtml) |
| Gorenje G600 GV663B65 | odpowiednik | 2269 zł | 1999 zł | RGEW0510311026C7, 05.10–31.10.2026 | 16 kpl. ✓, **38 dB** ✓, szuflada ✓, strefa intensywna ? | −301 zł. **Dostępność: UNDEFINED** (prawdopodobnie brak). | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/gorenje-g600-gv663b65-59-8cm-automatyczne-otwieranie-drzwi.bhtml) |
| Whirlpool WIO3O540PELG | odpowiednik | 2199,99 zł | 2199,99 zł (Whirlpool Days: pakiet usług za 1 zł, kapsułki za 1 zł, −40% w parze) | – | 14 kpl. ✓, 40 dB ✓, strefa intensywna ✓, Lift-Up ✓ | −100 zł. Klasa B, tryb cichy. | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/whirlpool-wio3o540pelg.bhtml) |
| Haier SXI 6B0S3FSBV | odpowiednik | 2559 zł | 2189 zł | REW041026311026C3 do 31.10 | 16 kpl., 40 dB | wersja z zawiasami przesuwnymi (SXI; ?) | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/haier-sxi-6b0s3fsbv-59-7cm-automatyczne-otwieranie-drzwi-szuflada-na-sztucce.bhtml) |
| Whirlpool WH7IA15AM3LS0 | alternatywa+ | 3599 zł | 3059 zł | RGEW0510311026C7 do 31.10 | 15 kpl., 38 dB ✓ | +759 zł. Nowsza seria. Klasa A i AquaStop: niepotwierdzone. | (search: WH7IA15AM3LS0) |
| Whirlpool W7IHP40L | – | 2399 zł | 2399 zł | – | 15 kpl., 40 dB | gorsza od wzorca (klasa C) i droższa | [link](https://www.euro.com.pl/zmywarki-do-zabudowy/whirlpool-w7i-hp40-l-automatyczne-otwieranie-drzwi-60cm-szuflada-na-sztucce.bhtml) |

Brak w sklepie: Whirlpool WH8IA15AM3TUS0 i Beko MEDIN3755A. Odrzucone z powodu hałasu (41–43 dB ✗): Beko BDIN38555 (1679 zł), Gorenje GV673C65 (1599 zł), Midea MDWEB1403MB-WA, Candy CH 5B3F1B, Whirlpool WIC3C33PFE.

## 7. Pralka + suszarka (słupek)

| Model | Typ | Cena reg. | Cena promo / z kodem | Kod + ważność | MUST ok? | Uwagi | Link |
|---|---|---|---|---|---|---|---|
| Samsung WW90CGC04DAE (pralka) | wybrana | 2299 zł | **1799 zł** (najniższa z 30 dni: 2299) | **RBF2310071226C**, 23.10.2026 15:15 – **07.12.2026 23:45** | 9 kg / 1400 / A / inwerter ✓. Dokładanie prania ? | 4,9★/374. Dostawa: pojutrze. Samsung cashback (kwota ?). | [link](https://www.euro.com.pl/pralki/samsung-pralka-ww90cgc04dae-ecobubble-9-kg-biala.bhtml) |
| Samsung DV9MDG52A0AEEO (suszarka) | wybrana | 2929,99 zł | **2489 zł** (najniższa z 30 dni: 2499) | **REW1410311026C2**, 14.10 – **31.10.2026 23:45** | pompa ciepła 9 kg ✓, 64 dB ✓, klasa C (105 kWh) ✓. Czujnik wilgotności ? Wąż ? | Samsung cashback (kwota ?) | [link](https://www.euro.com.pl/suszarki/samsung-dv9mdg52a0aeeo-funkcje-ai-60cm-9kg-zdalne-sterowanie.bhtml) |
| Łącznik Samsung SKK-DD | łącznik | 217,30 zł | 217,30 zł (wchodzi do „Nawet 3000” i „Piąty za 1 zł”) | – | z półką (15 kg), biały. Zgodność z WW90CGC04DAE: **?** | Dostawa: do 3 dni | (search: SKK-DD; link sklepu: …/bosch-skk-dd.bhtml) |
| Łącznik Samsung SKK-UDW | łącznik | 359,99 zł | 359,99 zł | – | z półką. Karta: „Pralki z panelem AI Control, kolor biały (bez Bespoke)”, więc **prawdopodobnie pasuje** do WW90CGC04DAE (panel AI Control) | – | (search: SKK-UDW) |
| **Para Samsung osobno** | – | 5228,99 zł | **4288 zł** (+ łącznik 217,30 lub 359,99 zł) | j.w. | – | Taniej niż gotowy zestaw | – |
| Zestaw Samsung WW90CGC04DAEEO + DV9MDG52A0AE | zestaw | 5299 zł | 5299 zł (codeback 500 zł w akcji 50-za-500, 2 raty gratis) | – | – | **o 1011 zł drożej** niż osobno | [link](https://www.euro.com.pl/zestawy-pralka-i-suszarka/samsung-pralka-ww90cgc04daeeo-9kg-1400obr-min-suszarka-dv9mdg52a0ae-60cm-9kg.bhtml) |
| Bosch Serie 6 WGG244ZEPL (pralka) | alternatywa | 2849 zł | 2399 zł | REW051026311026C do 31.10.2026 | ✓ | – | [link](https://www.euro.com.pl/pralki/bosch-wgg244zepl-9kg-1400obr-min.bhtml) |
| Bosch Serie 6 WQG245DEPL (suszarka) | alternatywa | 3699 zł | 3199 zł | REW051026311026C do 31.10.2026 | ✓ (samoczyszczący skraplacz, AutoDry) | – | [link](https://www.euro.com.pl/suszarki/bosch-wqg245depl-61-3cm-9kg.bhtml) |
| **Zestaw Bosch WGG244ZEPL + WQG245DEPL** | alternatywa+ | 6299 zł | **5299 zł** | REW051026311026C do 31.10.2026 | ✓ | Taniej niż osobno (5598 zł). **+1011 zł vs para Samsung.** | (search: WGG244ZEPL; zestawy-pralka-i-suszarka) |
| Łącznik Bosch WTZ27410 / WTZ27400 | łącznik | 119,99 / 314,97 zł | j.w. | – | WTZ27400 ma szufladę | Dostawa: jutro | [WTZ27410](https://www.euro.com.pl/laczniki-do-pralek-i-suszarek/bosch-wtz27410.bhtml) (ścieżka kategorii ?) |
| Bosch WGG244F1PL (i-DOS) | NICE | 3149 zł | 2599 zł | REW051026311026C do 31.10 | ✓ | +200 zł vs WGG244ZEPL, czyli i-DOS mieści się w progu 300 zł | (search) |
| Bosch WGH24409PL (AquaStop) | alternatywa | 3699 zł | 3099 zł | REW0910311026C4 do 31.10 | ✓ | +700 zł vs WGG244ZEPL | (search) |

Inne suszarki (z kodem): Electrolux EW6D297GP 2299 zł (gł. 63,6 cm), Gorenje DG69CPS/PL 2599 zł, Bosch WQG1417EPL 2379 zł, Bosch WQG243DEPL 2879 zł. Tych modeli nie weryfikowano pod MUST.

## Najtańszy koszyk w tym sklepie

**Wariant A – maksymalnie dużo MUST potwierdzonych (okap LFP326FW ma 2 niepełne), z optymalnym użyciem kodów.** Do „Nawet 3000 zł rabatu” (RKPROGAGD1026) wkładamy produkty **bez** kodu produktowego i lodówkę Samsung. Lodówka bez kodu kosztuje 3699,99 zł, ale podnosi koszyk do progu 9000 zł, a próg daje rabat 1400 zł zamiast 750 zł. Zysk netto ok. 250 zł względem kodu produktowego.

| Pozycja | Model | Cena |
|---|---|---|
| Grupa „Nawet 3000”: piekarnik | Whirlpool WOI7A8FHT2SBA | 3499,00 |
| Grupa „Nawet 3000”: zmywarka | Whirlpool W7IHT58T | 2299,99 |
| Grupa „Nawet 3000”: lodówka | Samsung BRB70F30BES0EO (cena bez kodu) | 3699,99 |
| Grupa „Nawet 3000”: okap | Electrolux LFP326FW (biały) | 638,99 |
| Grupa „Nawet 3000”: łącznik | Samsung SKK-DD | 217,30 |
| **Rabat RKPROGAGD1026** (10 355,27 zł ≥ 9000 zł) | | **−1400,00** |
| Płyta (kod) | Whirlpool WB S2560 NE | 1348,00 |
| Mikrofala (kod) | Candy CA38FL7N25WXB | 799,00 |
| Pralka (kod do 07.12) | Samsung WW90CGC04DAE | 1799,00 |
| Suszarka (kod do 31.10) | Samsung DV9MDG52A0AEEO | 2489,00 |
| **RAZEM** | | **≈ 15 390 zł** |

- Bez tej optymalizacji (wszystkie kody produktowe, a „Nawet 3000” tylko dla piekarnika, zmywarki, okapu i łącznika: −750 zł) koszyk kosztuje ≈ 15 639 zł.
- Bez żadnych rabatów koszykowych: ≈ 16 390 zł.
- Rabat koszykowy jest wyliczony z tabeli progów. **W koszyku go nie sprawdzono**. Kolejność i wybór kodów trzeba zrobić ręcznie w polu „Dostępne promocje i kody”.
- Do tego: dostawa 0 zł, odbiór starego sprzętu 0 zł. Opcjonalnie montaż: płyta + piekarnik 369,99 zł, zmywarka 299,99 zł, lodówka 299,99 zł, słupek pralka + suszarka 299,99 zł.
- Dodatkowe korzyści, nieodliczone od sumy: Samsung cashback za pralkę i suszarkę (200–700 zł każda, wymaga opinii, kwota ?), codeback z akcji 50-za-500 (?), 150 zł za opinię o piekarniku.

**Wariant A′ – jeszcze taniej, ale z „?” w MUST** (do weryfikacji w instrukcjach):
- Indesit IS35Q60NE zamiast WBS2560NE: −651 zł (osobny suwak na strefę ?).
- Haier ID2P5B5EYTB zamiast wzorca piekarnika: ok. −1300 zł przed rabatem. Grupa „Nawet 3000” spada wtedy do 9055 zł i nadal mieści się w progu 1400 zł, o ile Haier jest w promocji (?). Nie potwierdzono teleskopów na 2 poziomach ani szuflady na wodę.
- Razem ok. **13 440 zł**.

**Wariant B – „lepszy za niewiele więcej”** (wariant A plus poniższe zmiany):
- Zestaw Bosch Serie 6 WGG244ZEPL + WQG245DEPL za 5299 zł z kodem do 31.10 i łącznik WTZ27410 za 119,99 zł, zamiast pary Samsung i SKK-DD: **+≈ 914 zł**. Grupa „Nawet 3000” nadal ≥ 9000 zł. Zyskujesz samoczyszczący skraplacz, AutoDry, wspólny łącznik z półką i zgodność potwierdzoną przez producenta.
- Mikrofala Whirlpool AMW6440FB za 1742 zł zamiast Candy: **+943 zł**. Zyskujesz talerz 32,5 cm, 31 l i spójny wygląd z piekarnikiem Whirlpool.
- Razem ok. **17 250 zł** (+≈ 1857 zł vs A).
- Tańsza opcja „lepsza”: lodówka Whirlpool WHC20T573P za 2899 zł z kodem jest cichsza (32 dB) i ma klasę D. Obieg 2 ?. Jest −400 zł vs Samsung z kodem, ale wypada wtedy z grupy „Nawet 3000”, więc realnie ok. +250 zł vs wariant A.

## Uwagi / niepewności

- **Terminy:**
  - Większość kodów produktowych i „Nawet 3000” wygasa **31.10.2026 23:45**.
  - Whirlpool Days (−40%, płyta −50%, usługi za 1 zł) wygasa **26.10.2026**.
  - Kod na pralkę Samsung jest ważny do 07.12.2026, a 50-za-500 do 03.11.2026.
- Rabaty koszykowe są wyliczone z regulaminu i plakietek na kartach. **Nie są sprawdzone w koszyku**: zakaz logowania i dodawania do koszyka (formularze), a koszyk może inaczej przypisać kody.
- Pod koniec pracy API sklepu zaczęło zwracać 403 (limit). Dlatego szczegóły karty Haier ID2P5B5EYTB (poziomy teleskopów, szuflada na wodę) i jego udział w „Nawet 3000” są **niepotwierdzone**.
- Lodówki Candy, Whirlpool i Haier: karta podaje „2 termostaty”, co nie potwierdza dwóch niezależnych obiegów (MUST). Potwierdzony jest tylko Samsung (Twin Cooling).
- Okapy: karta sklepu nie podaje hałasu na biegu codziennym, klapy zwrotnej, BLDC ani minimalnej głębokości szafki. Trzeba sprawdzić w instrukcji producenta.
- Mikrofalówki: wysokość potwierdzona tylko dla Candy (38,5 cm). Dla pozostałych trzeba sprawdzić wymiar wnęki w instrukcji.
- Łączniki Samsung: zgodność SKK-DD i SKK-UDW z WW90CGC04DAE i DV9MDG52A0AE **niepotwierdzona** (lista zgodności Samsunga). SKK-UDW z opisu pasuje do pralek „AI Control białych”.
- Samsung cashback (do 30.11.2026) wymaga opinii. Dokładne kwoty dla modeli są w załączniku na cashbackagd.samsung.pl (nie sprawdzano).
- Linki oznaczone „(search …)” lub „ścieżka kategorii ?” nie mają pełnego, potwierdzonego URL. Szukaj ich po kodzie modelu na euro.com.pl.
- Wzorzec zmywarki W7IHT58T: AquaStop niepotwierdzony (karta: „wąż dopływowy z zabezpieczeniem przed zalaniem”). Klasa B.
