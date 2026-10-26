# morele.net – raport (2026-10-25)

> **Snapshot sprzed decyzji 26.10.2026.** Aktualny wybór: płyta Electrolux CIV634 (2 099, euro) + okap Electrolux LFG716R (1 348,99, euro); koszyk netto 16 193,25 / 15 663,44 — patrz `README.md`. Modele WBS2560NE/LFP326FW w tym raporcie są historyczne.

## Jak zebrano ceny

- **morele.net nie blokuje bota.** Wszystkie strony (kategoria, karta produktu) zwróciły HTTP 200 z pełną treścią SSR. Nie było captchy, DataDome ani 403.
- **Ceny sprawdzone na żywo: 25.10.2026, godz. 21:19–22:20 CET.** Każda cena pochodzi z danych strukturalnych oferty (`offers.price`, waluta PLN) albo z atrybutu `data-default-price-gross` na karcie produktu. Kafelki w listingach miały znacznik `data-updated-at="2026-10-25 21:19:49"` / `21:20:23`, czyli były świeże w chwili pobrania.
- **Stan magazynowy** czytany z `offers.availability` (`InStock` / `OutOfStock`), nie z tekstu marketingowego.
- **Koszt dostawy** czytany z `offers.shippingDetails.shippingRate` (dla AGD wychodzi 0–25,99 zł). Faktyczną cenę dla kodu pocztowego morele pokazuje po wpisaniu kodu — **niepodana z góry**.
- **Specyfikacje** z zakładki „Informacje podstawowe / Dane techniczne” na karcie morele. Tam, gdzie karta milczy, sprawdzałem u producenta (whirlpool.pl, karta PDF Boscha) — zaznaczone w tabelach. Pozycje niepotwierdzone mają status `niepotwierdzone`.
- Sklep rozróżnia **sprzedaż własną (Morele.net Sp. z o.o.)** od marketplace — kolumna „Sprzedawca”. Marketplace w tym zestawie trafił się raz (piekarnik Amica, sprzedawca WorldAGD).
- Ceny z innych sklepów podaję tylko jako odniesienie (whirlpool.pl, euro.com.pl z dokumentu wymagań) — nie są sprawdzane przeze mnie na żywo.

**Legenda statusów:** `[live]` = sprawdzone na żywo na morele.net 25.10.2026 · `[prod]` = dane producenta (whirlpool.pl / PDF Boscha / instrukcja) · `niepotwierdzone` = brak źródła, wymaga weryfikacji przed zakupem.

---

## Promocje / kupony

| Promocja | Warunki | Ważność | Czy działa na te modele | Źródło |
|---|---|---|---|---|
| **Kod newslettera −20 zł** | Zapisy do newslettera; kod przychodzi mailem („kod powitalny na pierwsze zakupy”). Zwykle jednorazowy, na zakupy w sklepie, nie na outlet | bez daty na stronie | **Prawdopodobnie tak** na AGD, ale kwota 20 zł jest symboliczna przy koszyku ~18 tys. zł | [lp.morele.net/newsletter](https://lp.morele.net/newsletter/) `[live]` |
| **Brand Club: 10 zł rabatu za każde 100 zł** | Trzeba mieć konto, zapisać się do newslettera i zrobić zakupy ≥100 zł. Kod przychodzi mailem do 14 dni **po** odbiorze zamówienia, ważny 3 miesiące, jednorazowy, **nie łączy się** z innymi kodami ani outletem | bezterminowo | **Nie na ten zakup** — kod dostajesz po pierwszym zamówieniu, czyli na kolejne. Przy koszyku ok. 17,8 tys. zł realny rabat do ok. 30% w strefie Brand Club, ale na przyszłe zakupy | [tech.morele.net/kody-rabatowe](https://tech.morele.net/kody-rabatowe/) `[live]` |
| **Kod `SALE`** | Wymieniony na liście kodów jako bezterminowy, kategorie: „Elektronika i IT • **AGD i dom** • ogród i narzędzia • sport turystyka i hobby • uroda, zdrowie, dziecko”. Wysokości rabatu strona nie podaje | bezterminowy | **Prawdopodobnie tak** (AGD jest w kategoriach), ale **wysokość rabatu niepotwierdzona** — trzeba wpisać w koszyku i sprawdzić | [tech.morele.net/kody-rabatowe](https://tech.morele.net/kody-rabatowe/) `[live]` |
| Kod `GAME26` | Laptopy, podzespoły, akcesoria gamingowe, fotele, monitory | **do 25.10.2026** (czyli dziś) | Nie — nie dotyczy AGD | tamże `[live]` |
| Kody `CLEAN26`, `JESIEN26`, `SCHOOL26`, `GARDEN26`, `SUMMER26`, `BDAY26`, `DEAL26`, `TATA26` | – | **wygasły** | Nie | tamże `[live]` |
| **Morele MAX (abonament, darmowa dostawa)** | Jednorazowa opłata 19,98 / 35,94 / 48,60 zł za 3 / 6 / 12 mies. Darmowa dostawa dla produktów oznaczonych symbolem, min. 39,99 zł od jednego sprzedawcy. **Nie dotyczy outletu** ani wybranych kategorii. Wydłuża zwrot do 30 dni | bezterminowo | **Tak, i to najbardziej opłacalny „kupon” w tym koszyku** — 9 przesyłek AGD po 25,99 zł = 233,91 zł, abonament 12 mies. kosztuje 48,60 zł. Oszczędność ok. **185 zł** | tamże `[live]` |
| **Raty 10×0%** (banner w sklepie) / **Santander do 60 rat** | Raty od Morele (produkty sprzedawane bezpośrednio): RRSO 22,31%. Marketplace: kredyt celowy RRSO 19,09%. Kwoty 200–50 000 zł | bezterminowo | Tak, dla produktów sprzedawanych przez Morele.net. **Uwaga:** przy kredycie Santandera kody rabatowe sklepu zwykle nie działają łącznie — potwierdź w koszyku, zanim wybierzesz raty | [lp.morele.net/raty-santander](https://lp.morele.net/raty-santander/) `[live]` |
| **Usługi AGD (ceny z kart produktów)** | Wniesienie **99 zł**, wniesienie + recykling **99 zł**, montaż płyty indukcyjnej KOMFORT **229 zł**, montaż piekarnika KOMFORT (cena nieodczytana), montaż lodówki w zabudowie + zmiana kierunku drzwi **389 zł**, zmiana kierunku drzwi **249 zł** | bezterminowo | Tak — to jedyny sposób na wniesienie „pod drzwi mieszkania”; dostawa kurierem to zwykle tylko próg | karty produktów `[live]` |
| **Cashback Samsung AGD (do 4500 zł)** | Zakup 1.10–30.11.2026, rejestracja do 21.12.2026 na cashbackagd.samsung.pl. Wymagany sprzęt z polskiej dystrybucji Samsunga (kody **EO**). Wg raportu allegro.pl: WW90CGC04DAE**EO** 200 zł, DV9MDG52A0AE**EO** 200 zł; BRB70F30BES0EO **nie ma na liście** | do 30.11.2026 | **Wątpliwe na morele.** Modele Samsunga na morele mają końcówkę **LE**, nie EO: `WW90CGC04DAELE`, `DV90DG52A0AELE`, `WW90DG5G34AELE`. To inny kod sprzedażowy niż wymagany w regulaminie → **ryzyko odrzucenia wniosku**. Przed zakupem zapytaj morele o kod EO na fakturze | [cashbackagd.samsung.pl](https://cashbackagd.samsung.pl/) (regulamin — `niepotwierdzone` w tej sesji) |
| **Cashback Whirlpool (do 3000 zł)** | 1.09–31.12.2026, zestaw min. 2 urządzeń, piekarnik obowiązkowo. morele sprzedaje Whirlpool (WB S2560 NE, WOI78PT1SBA, W8I HT40 T) | do 31.12.2026 | **Niepotwierdzone** — regulamin na whirlpool-promocja.pl jest renderowany JS (strona odrzuca stare UA, treści nie odczytałem). Dodatkowo w tym koszyku **nie ma piekarnika Whirlpool**, więc warunek „piekarnik obowiązkowo” nie jest spełniony | [whirlpool-promocja.pl](https://whirlpool-promocja.pl/) (strona niedostępna dla bota) |
| **Cashback Bosch – suszarki (do 1000 zł)** | Zakup **1.10–31.12.2026**, zgłoszenie do 30.01.2027. Premia zależy od ceny końcowej na dowodzie zakupu: 400 / 500 / 600 zł w progach cenowych. **Regulamin wprost dopuszcza każdy legalny „Punkt Sprzedaży” w Polsce** i wyklucza tylko sklepy prowadzone bezpośrednio przez Boscha. Na liście modeli jest **WQG145APPL** (dostępny na morele) oraz WQG245DEPL | do 31.12.2026 lub do wyczerpania puli | **Tak, morele się kwalifikuje** (regulamin PDF, pkt 2.x — „punkt sprzedaży prowadzący zgodnie z prawem sprzedaż na terytorium RP”). Warunek: paragon/faktura **bez NIP**, opinia z hashtagiem | [Regulamin PDF Bosch](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) (przeczytany) `[live]` |
| **Rabat „Kup taniej w zestawie”** | Na kartach AGD wyświetla się sekcja „Kup taniej w zestawie”, ale po rozwinięciu zawiera **wyłącznie usługi** (wniesienie 99 zł, wniesienie+recykling 99 zł, montaż 229 zł) — nie ma realnego rabatu za zestaw urządzeń | – | Nie daje rabatu na sprzęt | karta WB S2560 NE `[live]` |
| Wyprzedaż ostatnich sztuk / outlet | Osobne sekcje sklepu; outlet **nie łączy się** z kodami ani Brand Club | bezterminowo | W tym zestawie nie znalazłem modeli z listy w outlecie | [lp.morele.net/wyprzedaz-ostatnich-sztuk](https://lp.morele.net/wyprzedaz-ostatnich-sztuk/) `[live]` |

**Podsumowanie promocji:** jedyne realne obniżki to Morele MAX (≈185 zł na dostawach) i ewentualnie kod `SALE`/newsletter (20 zł). Rabaty producentów (Samsung) są na morele **ryzykowne z powodu końcówki LE**. Boschowski cashback na suszarkę działa i jest policzalny.

---

## 1. Piekarnik

MUST: para · szuflada/zbiornik na wodę · termosonda · hydroliza · teleskopy na 2 poziomach · termoobieg

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|---|
| **Whirlpool WOI7A8FHT2SBA** | wzorzec | **brak oferty** (wyszukiwarka: 0 wyników na „WOI7A8”, „WOI7A8FHT2SBA”; brak też w indeksie Google `site:morele.net`) | – | – | – | – | morele w ogóle nie ma piekarników z linii W Collection | – |
| **Electrolux LOD8P39Z** | alternatywa (najbliżej MUST) | **2 628,99 zł** `[live]` | Morele.net | 0–25,99 zł (Morele MAX: 0 zł) | InStock | **częściowo**: para ✓ (SteamBake), termosonda ✓, teleskopy ✓, termoobieg ✓, 300°C ✓ · **zbiornik/szuflada na wodę ✗** · hydroliza ✗ (ma **pirolizę** — mocniejsze czyszczenie) | Lepsze: piroliza zamiast hydrolizy, 15 programów auto, wyświetlacz TFT EXCite, 72 l. Gorsze: brak szuflady na wodę (para tylko „na starcie pieczenia”), teleskopy prawdopodobnie na 1 poziomie | [morele.net](https://www.morele.net/piekarnik-electrolux-lod8p39z-15092782/) |
| **Electrolux EOD6F77WZ** | alternatywa (budżet) | **1 639,00 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **częściowo**: para ✓ (SteamBake), termosonda ✓, teleskopy ✓, termoobieg ✓, 300°C ✓ · zbiornik ✗ · **hydroliza ✗** (emalia łatwoczyszcząca) | −990 zł vs LOD8P39Z. Brak pirolizy i hydrolizy — czyszczenie ręczne | [morele.net](https://www.morele.net/piekarnik-electrolux-eod6f77wz-15451072/) |
| **Bosch HBG578EB3** | alternatywa | **2 398,00 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **częściowo**: teleskopy ✓, **hydroliza ✓ (czyszczenie parowe)**, piroliza ✓, termoobieg ✓, 30 programów ✓, 71 l · termosonda **nie wykazana w karcie** · zbiornik ✗ | Lepsze: hydroliza + piroliza, 30 programów. Gorsze: 71 l, brak potwierdzonej sondy (trzeba sprawdzić HBG578E**S**3 — wersja z sondą) | [morele.net](https://www.morele.net/piekarnik-bosch-bosch-hbg578eb3-14940851/) |
| **Whirlpool WOI6A8FPT1SBA** | alternatywa (Whirlpool, czarny) | **3 791,04 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **częściowo**: termosonda ✓, **hydroliza ✓ + piroliza ✓**, termoobieg ✓, 73 l · **prowadnice drabinkowe ✗** (teleskopy tylko jako akcesorium) · para ✗ | Lepsze: ta sama marka/linia co płyta Whirlpool, hydroliza + piroliza. Gorsze: brak pary, brak teleskopów w standardzie, cena jak wzorzec | [morele.net](https://www.morele.net/piekarnik-whirlpool-73-l-czarny-piekarnik-pirolityczny-wbudowany-elektryczny-piekarnik-woi6a8fpt1sba-8003437836398-15604582/) |
| Whirlpool WOI78PT1SBA | alternatywa | 2 013,05 zł `[live]` | Morele.net | 0–25,99 zł | **OutOfStock** | teleskopy ✓, hydroliza ✓, piroliza ✓, 73 l · termosonda nie wykazana · para ✗ | Czarny Whirlpool, ale **niedostępny** | [morele.net](https://www.morele.net/piekarnik-whirlpool-woi78pt1sba-15665461/) |
| Whirlpool WOI6A8HT1SBA | alternatywa | 2 999,00 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 73 l, grill + termoobieg w karcie; **para, termosonda, hydroliza, teleskopy — nie wykazane** | Karta morele jest uboga (tylko 4 pola) — nie da się potwierdzić MUST | [morele.net](https://www.morele.net/piekarnik-whirlpool-built-in-oven-woi6a8ht1sba-whirpool-15081927/) |
| Amica ED97619VBA+ X-TYPE Steam | alternatywa (odrzucona) | 1 499,00 zł `[live]` | **WorldAGD (marketplace)** | nieustalona | InStock | teleskopy ✓, termoobieg ✓, 77 l, SoftSteam ✓ · **termosonda ✗** (brak w karcie) · hydroliza ✗ (katalityczne) | Największa pojemność w zestawieniu, ale bez sondy i bez hydrolizy; marketplace = inna gwarancja/zwrot | [morele.net](https://www.morele.net/piekarnik-amica-piekarnik-ed97619vba-x-type-steam-13116888/) |

**Wniosek dla piekarnika: na morele nie ma modelu, który spełnia wszystkie MUST** (para + zbiornik na wodę + termosonda + hydroliza + teleskopy 2 poz.). Whirlpool WOI7A8FHT2SBA i WOI7P8FHT1SBA nie są w ofercie. Najbliżej: **Electrolux LOD8P39Z** (2 629 zł; brakuje tylko szuflady na wodę i hydrolizy, ma za to pirolizę, sondę i teleskopy) oraz **Bosch HBG578EB3** (2 398 zł; ma hydrolizę i teleskopy, ale nie ma potwierdzonej sondy). Piekarnik trzeba kupić w innym sklepie.

---

## 2. Lodówka do zabudowy

MUST: zabudowa ~193,5 cm · zawiasy ślizgowe · pełny No Frost · 2 niezależne obiegi · ~298 l · ≤35 dB

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|---|
| **Samsung BRB70F30BES0EO** | wzorzec | **brak oferty** (0 wyników na „BRB70F30”, „BRB70”) | – | – | – | – | Sklep ma tylko warianty **AEF0EO** (224 l) i serię **BRB80** | – |
| **Samsung BRB80F30BES0EO** | **najbliższy wzorcowi (faktycznie ten sam sprzęt)** | **3 499,99 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **✓ wszystkie**: 193,5 cm, 298 l (224 l chłodziarka + 74 l zamrażarka), No Frost (obie komory automatyczne), **Twin Cooling — dwa osobne obiegi**, 35 dBA, klasa E, 229 kWh/rok, Wi-Fi **SmartThings**, komora zero, szybkie chłodzenie/zamrażanie | Identyczna specyfikacja jak wzorzec (te same 229 kWh, 298 l, 35 dB), dodatkowo potwierdzone Wi-Fi i Metal Cooling. Różnica: inny kod (80 vs 70) — sprawdź tylko wymiar wnęki | [morele.net](https://www.morele.net/lodowka-samsung-brb80f30bes0eo-14860286/) |
| Samsung BRB80F30**AEF**0EO | alternatywa (tańsza, mniejsza) | **3 292,96 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **✗ pojemność**: 224 l netto (nie 298 l). Reszta OK: 193,5 cm, 35 dB, No Frost, klasa E, 229 kWh | −207 zł, ale chłodziarka jest wyraźnie mniejsza. **Uwaga na pułapkę:** cyfra „80” w kodzie **nie** oznacza 298 l — 298 l ma dopiero wariant z „BES0” | [morele.net](https://www.morele.net/lodowka-samsung-brb80f30aef0eo-14906913/) |
| Samsung BRB70F30**AEF**0EO | alternatywa | 3 248,99 zł `[live]` | Morele.net | 0–25,99 zł | InStock | **✗ pojemność**: 224 l, 2 pojemniki zamrażarki, 35 dB, 193,5 cm | To wariant 224 l — nie ten wzorzec | [morele.net](https://www.morele.net/lodowka-samsung-brb70f30aef0eo-14870052/) |
| Samsung BRB80F30**ADF**0EO | alternatywa (klasa D) | 3 971,69 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 193,5 cm, No Frost, 35 dB, **klasa D** · karta podaje **1 agregat / 2 termostaty** — brak potwierdzenia „2 niezależnych obiegów” | **+472 zł** za oszczędniejszą klasę D. Drożej bez pewności co do drugiego obiegu | [morele.net](https://www.morele.net/lodowka-samsung-brb80f30adf0eo-14906911/) |
| Whirlpool WHC20 T352 | alternatywa (budżet) | 2 994,00 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 193,5 cm ✓, No Frost ✓, 280 l, klasa E, 222 kWh/rok · **2 obiegi niepotwierdzone** · 35 dB nie wykazane | **−506 zł**, ale to chłodziarko-zamrażarka z jednym obiegiem — nie spełnia MUST „dwa niezależne obiegi” | [morele.net](https://www.morele.net/lodowka-whirlpool-whc20-t352-8648523/) |

**Usługi dodatkowe dla lodówki (morele):** zmiana kierunku otwierania drzwi **249 zł**, montaż w zabudowie + zmiana kierunku **389 zł** `[live]`.

**Wniosek:** kupuj **Samsung BRB80F30BES0EO za 3 499,99 zł** — to funkcjonalnie wzorzec (298 l, Twin Cooling, 35 dB, 193,5 cm, Wi-Fi). Uważaj na tańsze warianty AEF0EO: mają 224 l.

---

## 3. Płyta indukcyjna

MUST: 59–60 cm · strefa łączona · 4 pola · Booster ~3 kW · osobny suwak na strefę · **błyszczące** czarne szkło · blokada dzieci · ciepło resztkowe

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|---|
| **Whirlpool WB S2560 NE** | **wzorzec (bez matu)** | **1 298,00 zł** `[live]` (whirlpool.pl: 1 429 zł `[prod]`) | Morele.net | 0–25,99 zł | InStock | 59 × 51 cm ✓, 4 pola ✓, **FlexiCook — łączenie pól potwierdzone u producenta** ✓, Booster ✓, 7,2 kW ✓, wskaźnik ciepła resztkowego ✓, timer ✓, szkło błyszczące (brak powłoki MattProtect) ✓ · **osobny suwak na strefę — niepotwierdzone** (opis producenta mówi ogólnie o sterowaniu dotykowym/„intuicyjnym pokrętle”) · blokada dzieci nie wykazana w karcie | **−131 zł taniej niż u producenta.** To dokładnie wersja bez matu, której szukasz | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-hob-induction-wb-s2560-ne-whp-13484603/) · [whirlpool.pl](https://www.whirlpool.pl/plyta-indukcyjna-szklanoceramiczna-whirlpool-wb-s2560-ne-869991579680/p) |
| **Whirlpool WL B3360 NE** | alternatywa | **1 284,99 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | 4 pola ✓, **łączenie pól grzewczych: Tak** ✓, Booster ✓, 7,2 kW ✓, 59 × 51 ✓, ciepło resztkowe ✓, czarna ceramika ✓ · suwak/blokada dzieci nie wykazane | **−13 zł** vs wzorzec, ta sama klasa. Uwaga: karta podaje „Wykończenie: prosta krawędź”, więc estetyka inna niż S2560 | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-wl-b3360-ne-6747478/) |
| Whirlpool WL S7960 NE | alternatywa | 1 563,99 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 4 pola ✓, **łączenie pól: Tak** ✓, Booster ✓, 7,2 kW ✓, 59 × 51 ✓, czarna ✓ | **+266 zł** — nowsza linia S, więcej funkcji; suwaki niepotwierdzone | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-hob-induction-wl-s7960-ne-whp-13484600/) |
| Whirlpool WBB 8360NEBM | **odrzucona** | 1 933,55 zł `[live]` | Morele.net | 0–25,99 zł | InStock | – | Oznaczenie **„netnet” / BM** = wersja **MattProtect (matowa)** — wprost odrzucona w wymaganiach | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-plyta-indukcyjna-whirlpool-wbb-8360nebm-netnet-15791731/) |
| Whirlpool WS Q4860 NE | odrzucona | 1 170,98 zł `[live]` | Morele.net | – | InStock | **łączenie pól: Nie** ✗ | Najtańsza indukcja Whirlpool, ale bez strefy łączonej | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-ws-q4860-ne-6780716/) |
| Bosch PIE631HB1E | odrzucona | 1 379,00 zł `[live]` | Morele.net | – | InStock | 4 pola, 59,2 cm, 7,4 kW · **łączenie pól: Nie** ✗ · **Booster: Nie** ✗ | Odpada na dwóch MUST | [morele.net](https://www.morele.net/plyta-grzewcza-bosch-pie631hb1e-13219713/) |
| Whirlpool WL B4560 NE/W | odrzucona | 1 548,00 zł `[live]` | Morele.net | – | InStock | łączenie pól ✓, Booster ✓ · **kolor: biały** ✗ | Odpada na kolorze | [morele.net](https://www.morele.net/plyta-grzewcza-whirlpool-wl-b4560-ne-w-7333370/) |

**Wniosek:** **WB S2560 NE za 1 298 zł** to trafienie — dokładnie wersja bez MattProtect, z potwierdzonym FlexiCook i ceną niższą niż u producenta. Jedyne niewiadome: czy sterowanie ma osobny suwak na każdą strefę (MUST) i czy jest blokada dzieci — **potwierdź w instrukcji PDF z whirlpool.pl przed zakupem**.

---

## 4. Okap teleskopowy

MUST: teleskop 60 cm · mieści się w szafce 35 cm · wylot fi 150 · 400–600 m³/h na zwykłym biegu · ≤~55 dB · metalowe filtry do zmywarki · klapa zwrotna

**Uwaga metodologiczna:** morele podaje „Poziom hałasu” bez informacji, czy to moc akustyczna (dB(A) re 1 pW), czy ciśnienie. Wartości 57–72 dB wskazują na **moc akustyczną** — czyli o ok. 10–12 dB więcej niż to, co słychać w kuchni. Dlatego kolumna „≤55 dB” jest w praktyce nie do potwierdzenia na podstawie karty sklepu.

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze | Link |
|---|---|---|---|---|---|---|---|---|
| **Electrolux LFP326FW (biały)** | historyczny (zastąpiony przez LFG716R) | **665,00 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | teleskop ✓ 59,8 cm ✓, gł. **28,4 cm** (szafka 35 → ✓), **410 m³/h maks.** ✓/? (bieg codzienny niżej), filtr **aluminiowy** ✓ (mycie w zmywarce — do potwierdzenia), **57 dB LwA** (48 dB wg instrukcji, prawdopodobnie LpA), **fi 150 ✓** (ME) · klapa zwrotna niepotwierdzona | Biały, 3 prędkości, klasa C, bez timera. W euro 638,99 promo — taniej o 26,01 zł | [Morele FW](https://www.morele.net/okap-electrolux-lfp326fw-10588020/) |
| **Electrolux LFP326FB** | najlepszy kompromis (czarny) | **619,00 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | teleskop ✓ 59,8 cm ✓, gł. **28,4 cm** (szafka 35 → ✓), **410 m³/h** ✓ (max), filtr **aluminiowy** ✓ (mycie w zmywarce — do potwierdzenia), **57 dB** (moc akustyczna — granica) · **fi 150 niepotwierdzone** · klapa zwrotna niepotwierdzona | Czarny (pasuje do czarnego AGD), 3 prędkości, klasa C. Najtańszy, który w ogóle wchodzi w 400–600 m³/h i w 35 cm szafki | [morele.net](https://www.morele.net/okap-electrolux-lfp326fb-10613455/) |
| **Electrolux LFP616X** | alternatywa (mocniejsza) | **871,81 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | teleskop ✓ 59,8 cm ✓, gł. **30 cm** ✓, **600 m³/h** ✓, filtr aluminiowy ✓, klasa **A**, 3 prędkości · **68 dB** ✗ (najprawdopodobniej moc akustyczna = ok. 56–58 dB w kuchni) · fi 150 niepotwierdzone | Stal (nie czarny). Wydajność 600 m³/h jak w wymaganiach, ale głośniejszy na papierze niż LFP326FB | [morele.net](https://www.morele.net/okap-electrolux-lfp616x-11714037/) |
| Gorenje BHP623E8X | alternatywa | 590,62 zł `[live]` | Morele.net | 0–25,99 zł | InStock | teleskop ✓ 60 cm ✓, gł. 30,5 cm ✓, **578 m³/h** ✓, filtr aluminiowy ✓, 3 prędkości · **72 dB** ✗ | Najtańszy z wydajnością ~580 m³/h, ale najgłośniejszy w zestawieniu. Srebrny | [morele.net](https://www.morele.net/okap-gorenje-bhp623e8x-6039063/) |
| Bosch DFM064W55 | alternatywa | 998,00 zł `[live]` | Morele.net | 0–25,99 zł | InStock | teleskop ✓ 59,8 cm ✓, gł. **29 cm** ✓, 3 prędkości · **68 dB** · **wydajność m³/h nie podana** | BSH — jakość i serwis, ale karta nie podaje wydajności ani fi wylotu; nie da się potwierdzić MUST | [morele.net](https://www.morele.net/okap-bosch-dfm064w55-600336544/) |
| Teka CNL 6415 Plus | odrzucony | 639,42 zł `[live]` | Morele.net | – | InStock | **293 m³/h** ✗ (za mało), 64 dB | Odpada na wydajności | [morele.net](https://www.morele.net/okap-teka-cnl-6415-plus-6205609/) |
| Amica OTP6651BG, Bosch DFS067K51 | kandydaci z wymagań | **brak oferty** (0 wyników na „OTP6651”, „DFS067”) | – | – | – | – | Nie ma ich na morele | – |

**Wniosek:** na morele **nie ma okapu z potwierdzonym ≤55 dB** przy 400–600 m³/h. Najrozsądniejszy zakup: **Electrolux LFP326FB (619 zł)** — mieści się w szafce 35 cm, ma 410 m³/h i czarny front. Klapę zwrotną fi 150 i potwierdzenie fi 150 trzeba dokupić/sprawdzić osobno. Bosch DFS067K51 (cichy, 41–53 dB) trzeba kupić w innym sklepie.

---

## 5. Mikrofalówka do zabudowy

MUST: talerz ≥31–32 cm · zabudowa 60 cm · wysokość urządzenia ~38 cm

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze | Link |
|---|---|---|---|---|---|---|---|---|
| **Whirlpool W7 MD440 NB** | kandydat z wymagań | **brak oferty** (0 wyników na „W7 MD440”, „W7MD440”) | – | – | – | – | Sklep nie ma tej mikrofalówki | – |
| **Bosch BFL554MB0** (Serie 6) | **alternatywa — najlepsza** | **1 406,74 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **✓**: 594 × 382 × 388 mm (wys. **38,2 cm** ✓), 25 l, **900 W**, czarne szkło bez ramki, **bez grilla** ✓, AutoPilot 7 programów `[prod: karta PDF]` · talerz: wymiar wnęki **328 mm szerokości** — odpowiada talerzowi **ok. 31,5 cm** (spójne z wymaganiem; dokładnej średnicy karta PDF nie podaje — `niepotwierdzone`) | Dokładnie ta alternatywa z wymagań. Czarne, ta sama wysokość wnęki co Whirlpool, bez zbędnego grilla | [morele.net](https://www.morele.net/kuchenka-mikrofalowa-bosch-bfl554mb0-7563525/) · [karta PDF](https://media3.bosch-home.com/Documents/specsheet/en-GB/BFL554MB0B.pdf) |
| **Beko BMGB 25333 BG** | alternatywa (budżet) | **962,59 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | 25 l, **595 × 388 × 392 mm** (wys. 38,8 cm ✓), czarne ✓, 900 W + grill 1000 W · talerz niepotwierdzony (przy 25 l zwykle 27–31,5 cm — **sprawdź w karcie**) | **−444 zł**. Ma grill, którego nie potrzebujesz. Ryzyko: mniejszy talerz niż 31 cm = niespełniony MUST | [morele.net](https://www.morele.net/kuchenka-mikrofalowa-beko-bmgb-25333-bg-9612748/) |
| Whirlpool WMD44MW | alternatywa (Whirlpool) | 1 844,80 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 31 l ✓, 595 × 385 × 468 mm (38,5 cm ✓), 1000 W, bez ramki · **kolor: biały** ✗ (nie pasuje do czarnego piekarnika) | Duża pojemność, ale biała. Wersja WMD44M**E** (beżowa) też nie pasuje | [morele.net](https://www.morele.net/kuchenka-mikrofalowa-whirlpool-wmd44mw-15516545/) |
| Bosch BFL553MS0 | alternatywa | **1 480,99 zł** `[live]` (cena z listingu; karta kategorii pokazała samą ocenę bez ceny) | Morele.net | 0–25,99 zł | InStock | 25 l, 900 W, bez grilla, wysokość niepodana w karcie · wykończenie **srebrne (MS0)** | +74 zł vs BFL554MB0 i srebrne — nie pasuje do czarnej reszty | [morele.net](https://www.morele.net/kuchenka-mikrofalowa-bosch-bfl553ms0-4151077/) |
| Bosch BFL554MS0 | alternatywa | cena nieodczytana (karta bez ceny w danych strukturalnych) | Morele.net | – | InStock | parametry jak BFL554MB0, ale **srebrne (MS0)** | Nie brałbym: kolor nie pasuje | [morele.net](https://www.morele.net/kuchenka-mikrofalowa-bosch-bfl554ms0-9541733/) |

**Wniosek:** **Bosch BFL554MB0 za 1 406,74 zł** — spełnia wysokość 38 cm i brak grilla, jest czarna. Przed zakupem potwierdź średnicę talerza (mają być ≥31 cm) — karta morele i PDF Boscha jej nie podają wprost.

---

## 6. Zmywarka do zabudowy

MUST: pełna zabudowa 60 cm · 14–15 kpl · 3. kosz · ≤40 dB · auto-uchylanie drzwi · dysze na garnki · regulowane kosze · stal

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|---|
| **Whirlpool W7I HT58 T** | wzorzec | **brak oferty** (0 wyników na „W7I HT58”, „W7IHT58”) | – | – | – | – | Brak wzorca na morele | – |
| **Whirlpool W8I HT40 T** | **alternatywa — najlepsza** | **2 409,88 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | **✓ prawie wszystkie**: 60 cm pełna zabudowa (ukryty panel) ✓, **14 kpl** ✓, **3. kosz SpaceClean** ✓, **40 dB** ✓ (granica MUST), **automatyczne otwieranie drzwi** ✓ (potwierdzone w opisie), **dysze wodne w 3. koszu** ✓, stal nierdzewna ✓, silnik inwerterowy ✓, **AquaStop** ✓ („zabezpieczenie przeciwwypływowe”), **projekcja czasu na podłodze** ✓ · klasa C, 8 programów, 9,5 l/cykl | **+0 zł vs wzorzec cenowy (2,3–2,4 tys.)**, a dostajesz **AquaStop + projekcję**, których wzorzec nie ma. Gorsze: 14 kpl zamiast 15, 40 dB zamiast 38, klasa C zamiast B | [morele.net](https://www.morele.net/zmywarka-whirlpool-w8i-ht40-t-14794528/) |
| Whirlpool W8I HT58 TS | alternatywa (bliżej wzorca) | 2 473,00 zł `[live]` | Morele.net | 0–25,99 zł | **OutOfStock** | **38 dB** ✓, 14 kpl ✓, koszyk na sztućce (nie szuflada — **3. kosz ?**), AquaStop ✓, projekcja ✓, klasa B, silnik inwerterowy | To najbliższy krewny wzorca (58 = 38 dB). **Niedostępna** — można zamówić z powiadomieniem | [morele.net](https://www.morele.net/zmywarka-whirlpool-w8i-ht58-ts-13134616/) |
| Whirlpool W7I HP42 L | alternatywa | 3 134,99 zł `[live]` | Morele.net | 0–25,99 zł | InStock | **15 kpl** ✓, **szuflada** na sztućce ✓, 42 dB ✗ (powyżej 40), AquaStop ✓, projekcja ✓, 10 programów | **+725 zł** i **głośniejsza** — nie warto | [morele.net](https://www.morele.net/zmywarka-whirlpool-w7i-hp42-l-12968076/) |
| Bosch SMD8TCX04E | alternatywa (premium) | 5 669,75 zł `[live]` | Morele.net | 0–25,99 zł | InStock | 14 kpl ✓, 42 dB ✗, szuflada ✓, klasa **A**, AquaStop ✓, sterowanie aplikacją | **+3 260 zł** — poza budżetem | [morele.net](https://www.morele.net/zmywarka-bosch-smd8tcx04e-14946314/) |
| Beko BDFN26530X | odrzucona (budżet) | **1 670,99 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | 15 kpl ✓, szuflada ✓, 60 cm ✓ · **44 dB** ✗ · **bez AquaStop** | **−739 zł**, ale głośna i bez zabezpieczenia przed zalaniem — odpada na MUST | [morele.net](https://www.morele.net/zmywarka-beko-zmywarka-bdfn26530x-60cm-15-kpl-3-kosz-13134605/) |
| Beko MEDIN3755A, Whirlpool WH8IA15AM3TUS0 | alternatywy z wymagań | **brak oferty** (0 wyników) | – | – | – | – | Nie ma ich na morele | – |

**Wniosek:** **Whirlpool W8I HT40 T (2 409,88 zł)** to najlepszy wybór w tym sklepie — jedyna zmywarka na morele, która łączy ≤40 dB, 3. kosz, auto-uchylanie i AquaStop w cenie wzorca. Brakuje jej tylko 15. kompletu i 2 dB ciszy.

---

## 7. Pralka + suszarka (słupek)

MUST pralki: 9 kg · 1400 obr. · klasa A · inwerter · gł. ≤60 cm · krótki program, dokładanie prania, wełna
MUST suszarki: pompa ciepła 9 kg · czujnik wilgotności · odprowadzenie wody · ≤65 dB · klasa min. C (nowa etykieta)

| Model | Typ | Cena | Sprzedawca | Dostawa | Dostępność | MUST ok? | Lepsze/gorsze | Link |
|---|---|---|---|---|---|---|---|---|
| **Samsung WW90CGC04DAE** (na morele: **WW90CGC04DAELE**) | wybrana pralka | **2 553,90 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | 9 kg ✓, 1400 ✓, klasa **A** ✓, inwerter ✓, gł. 55 cm ✓, para ✓, 14 programów, 44 kWh/100 cykli, wirowanie 72 dB · dokładanie prania niepotwierdzone | **+755 zł vs euro.com.pl (1 799 zł z kodem)** — wyraźnie drogo. Kod kończy się **LE**, nie EO → ryzyko dla cashbacku Samsunga | [morele.net](https://www.morele.net/pralka-samsung-ww90cgc04daele-14875904/) |
| **Samsung WW90DG5G34AELE** | **alternatywa — wygrywa ceną** | **1 758,13 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | 9 kg ✓, **1400 obr.** ✓, klasa **A** ✓, inwerter ✓, para ✓, **gł. 48 cm** ✓ (najpłytsza), 72 dB | **−796 zł vs WW90CGC04DAE i −41 zł vs euro (1 799 zł)**. Nowsza generacja (seria DG). To najlepszy stosunek ceny do funkcji w całym zestawieniu pralek | [morele.net](https://www.morele.net/pralka-samsung-pralka-ww90dg5g34aele-samsung-15280352/) |
| Bosch WGG244Z0PL (Serie 6) | alternatywa (pralka) | 2 479,00 zł `[live]` (WGG244Z0SN: 2 376,34 zł) | Morele.net | 0–25,99 zł | InStock | 9 kg ✓, 1400 ✓, klasa A ✓, SilentPower Drive ✓ | **+721 zł** vs Samsung DG5G34. Zamiennik dla niedostępnego WGG244ZEPL — ta sama seria | [morele.net](https://www.morele.net/pralka-bosch-wgg244z0pl-15389200/) |
| **Samsung DV9MDG52A0AE** | wybrana suszarka | **brak oferty** (0 wyników na „DV9MDG”, „DV9MDG52”) | – | – | – | – | Sklep ma nowszą wersję: DV90DG52A0AELE | – |
| **Samsung DV90DG52A0AELE** | **alternatywa (następca wybranej)** | **3 013,72 zł** `[live]` | Morele.net | 0–25,99 zł | InStock | pompa ciepła ✓, **9 kg** ✓, **64 dB** ✓, 60 × 60 × 85 cm ✓, 192 kWh/rok, klasa A+++ (stara etykieta) · czujnik wilgotności i wąż do kanalizacji **niepotwierdzone** w karcie · montaż na pralce nie wykazany | **+525 zł vs euro.com.pl (2 489 zł z kodem do 31.10)**. Sensowna tylko jeśli kod na euro wygaśnie | [morele.net](https://www.morele.net/suszarka-do-ubran-samsung-dryer-dv90dg52a0aele-samsung-14856691/) |
| Beko BM3T49249W | alternatywa (suszarka) | 2 976,50 zł `[live]` | Morele.net | 0–25,99 zł | InStock | pompa ciepła ✓, 9 kg ✓, **63 dB** ✓, **58,6 cm głęb.** (najpłytsza), 194 kWh/rok, silnik inwerterowy ✓ | **−37 zł** vs Samsung, ciszej o 1 dB i płycej. Minus: inna marka niż pralka → **inny łącznik** (SKK-DD nie pasuje) | [morele.net](https://www.morele.net/suszarka-do-ubran-beko-beko-suszarka-bm3t49249w-15904607/) |
| Bosch WQG145APPL | alternatywa (suszarka + cashback) | 3 064,99 zł `[live]` | Morele.net | 0–25,99 zł | InStock | pompa ciepła, 9 kg · **na liście cashbacku Bosch** — przy cenie 3 064,99 zł wpada w próg **2 999–3 498,99 zł → 500 zł zwrotu** (progi wg raportu allegro.pl; PDF potwierdza kwoty 400/500/600 zł) | **+51 zł** vs Samsung, ale po cashbacku Boscha **2 564,99 zł**, czyli **−449 zł vs Samsung** i −248 zł vs cena euro. Wymaga łącznika Bosch WTZ27400 (309 zł), nie SKK-DD | [morele.net](https://www.morele.net/suszarka-do-ubran-bosch-suszarka-wqg145appl-15557922/) · [regulamin](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) |
| Electrolux EW6D295GP | odrzucona | 2 579,00 zł `[live]` | Morele.net | – | InStock | 9 kg, 64 dB · **„Możliwość montażu na pralce: Nie”** ✗ | Najtańsza 9 kg z pompą ciepła, ale **nie da się postawić w słupku** — odpada na MUST | [morele.net](https://www.morele.net/suszarka-do-ubran-electrolux-ew6d295gp-13811472/) |
| **Samsung SKK-DD** (łącznik) | akcesorium | **379,55 zł** `[live]` (Allegro: 227 zł) | Morele.net | – | InStock | Zgodność z parą WW90CGC04DAE + DV9MDG52A0AE **niepotwierdzona** (Samsung nie publikuje aktualnej listy) | **+152 zł vs Allegro** — na morele łącznik jest drogi | [morele.net](https://www.morele.net/samsung-lacznik-skk-dd-169785-6275814/) |
| Bosch WTZ27400 (łącznik) | akcesorium | 309,00 zł `[live]` | Morele.net | – | InStock | Do par Bosch (WGG244*/WQG*), z półką | +81 zł vs Allegro (227–260 zł) | [morele.net](https://www.morele.net/bosch-lacznik-pralki-z-suszarka-wtz27400-6358173/) |

**Bilans pary (ceny morele, brutto):**
- Samsung: 2 553,90 + 3 013,72 + 379,55 = **5 947,17 zł** (euro.com.pl: ok. 4 288 + łącznik ≈ 4 638 zł → **morele +1 309 zł**)
- Samsung „value”: 1 758,13 + 3 013,72 + 379,55 = **5 151,40 zł**
- Bosch: 2 479,00 + 3 064,99 + 309,00 = **5 852,99 zł**, po cashbacku suszarki (−500 zł) → **5 352,99 zł**

**Wniosek:** pralnię na morele opłaca się kupić **tylko** w wariancie „value” (WW90DG5G34AELE 1 758 zł) lub **Bosch z cashbackiem**. Wybrana para Samsung jest na morele o ok. 1,3 tys. zł droższa niż na euro.com.pl.

---

## Koszyk w tym sklepie

Wariant „najbliżej wymagań, sprzedaż własna Morele.net, wszystko na stanie”:

| Kategoria | Model | Cena | Dostawa | Dostępność |
|---|---|---|---|---|
| 1. Piekarnik | Electrolux LOD8P39Z | 2 628,99 zł | 0–25,99 zł | InStock |
| 2. Lodówka | Samsung BRB80F30BES0EO | 3 499,99 zł | 0–25,99 zł | InStock |
| 3. Płyta | Whirlpool WB S2560 NE | 1 298,00 zł | 0–25,99 zł | InStock |
| 4. Okap | Electrolux LFP326FB | 619,00 zł | 0–25,99 zł | InStock |
| 5. Mikrofalówka | Bosch BFL554MB0 | 1 406,74 zł | 0–25,99 zł | InStock |
| 6. Zmywarka | Whirlpool W8I HT40 T | 2 409,88 zł | 0–25,99 zł | InStock |
| 7a. Pralka | Samsung WW90CGC04DAELE | 2 553,90 zł | 0–25,99 zł | InStock |
| 7b. Suszarka | Samsung DV90DG52A0AELE | 3 013,72 zł | 0–25,99 zł | InStock |
| 7c. Łącznik | Samsung SKK-DD | 379,55 zł | 0–25,99 zł | InStock |
| **Razem sprzęt** | | **17 809,77 zł** | | |

- Dostawa: 9 przesyłek × do 25,99 zł = **do 233,91 zł** (z Morele MAX 12 mies. za 48,60 zł → **0 zł**).
- Wniesienie „pod mieszkanie”: 8 urządzeń × 99 zł = **792 zł** (opcjonalnie; z recyklingiem starocia ta sama cena 99 zł).
- Montaż płyty indukcyjnej: **229 zł**; montaż lodówki w zabudowie + zmiana kierunku drzwi: **389 zł** (opcjonalnie).
- **Razem z wniesieniem i Morele MAX: ok. 18 650 zł.**
- **Po cashbackach: 0 zł** — Samsung odpada z powodu kodu LE, Whirlpool wymaga piekarnika Whirlpool (nie ma), Bosch nie dotyczy tego koszyka.

**Braki w koszyku:** brak piekarnika spełniającego wszystkie MUST (Whirlpool WOI7A8FHT2SBA nie ma w ofercie), brak okapu ≤55 dB, brak mikrofalówki Whirlpool W7 MD440 NB, brak zmywarki 15 kpl przy ≤40 dB.

**Wariant „value” (te same kategorie, taniej):** piekarnik Electrolux EOD6F77WZ (1 639 zł) + pralka Samsung WW90DG5G34AELE (1 758,13 zł) → koszyk **16 024,01 zł** (−1 785,76 zł), ale piekarnik traci pirolizę, a pralka jest innej generacji.

**Czy opłaca się kupować całość tutaj?** **Nie.** morele wygrywa tylko w trzech pozycjach: płyta WB S2560 NE (1 298 zł, taniej niż u producenta), zmywarka W8I HT40 T (2 409,88 zł, z AquaStop i projekcją) i mikrofalówka BFL554MB0 (1 406,74 zł). Przegrywa wyraźnie na pralni Samsung (+1,3 tys. zł vs euro.com.pl) i nie ma piekarnika ani okapu z MUST.

---

## Tabela do porównania

Ceny brutto PLN, stan na 25.10.2026 21:19–22:20 CET, sprzedaż własna Morele.net (chyba że zaznaczono).

| kategoria | model | cena | dostawa | promocja netto | MUST | url |
|---|---|---|---|---|---|---|
| piekarnik | Electrolux LOD8P39Z | 2628.99 | 0–25.99 | 0 (Morele MAX: 0 zł) | częściowo: para ✓, sonda ✓, teleskopy ✓, piroliza zamiast hydrolizy, brak zbiornika | https://www.morele.net/piekarnik-electrolux-lod8p39z-15092782/ |
| piekarnik | Electrolux EOD6F77WZ | 1639.00 | 0–25.99 | 0 | częściowo: para ✓, sonda ✓, teleskopy ✓, brak hydrolizy i zbiornika | https://www.morele.net/piekarnik-electrolux-eod6f77wz-15451072/ |
| piekarnik | Bosch HBG578EB3 | 2398.00 | 0–25.99 | 0 | częściowo: hydroliza ✓, piroliza ✓, teleskopy ✓; sonda niepotwierdzona, brak pary | https://www.morele.net/piekarnik-bosch-bosch-hbg578eb3-14940851/ |
| piekarnik | Whirlpool WOI6A8FPT1SBA | 3791.04 | 0–25.99 | 0 | częściowo: sonda ✓, hydroliza+piroliza ✓; drabinkowe, brak pary | https://www.morele.net/piekarnik-whirlpool-73-l-czarny-piekarnik-pirolityczny-wbudowany-elektryczny-piekarnik-woi6a8fpt1sba-8003437836398-15604582/ |
| piekarnik | Whirlpool WOI7A8FHT2SBA (wzorzec) | brak oferty | – | – | – | – |
| lodówka | Samsung BRB80F30BES0EO | 3499.99 | 0–25.99 | 0 | TAK (298 l, Twin Cooling, 35 dB, 193.5 cm, NoFrost, Wi-Fi) | https://www.morele.net/lodowka-samsung-brb80f30bes0eo-14860286/ |
| lodówka | Samsung BRB80F30AEF0EO | 3292.96 | 0–25.99 | 0 | NIE (224 l) | https://www.morele.net/lodowka-samsung-brb80f30aef0eo-14906913/ |
| lodówka | Samsung BRB70F30AEF0EO | 3248.99 | 0–25.99 | 0 | NIE (224 l) | https://www.morele.net/lodowka-samsung-brb70f30aef0eo-14870052/ |
| płyta | Whirlpool WB S2560 NE | 1298.00 | 0–25.99 | 0 | TAK poza suwakiem/blokadą (niepotwierdzone); FlexiCook ✓, błyszczące ✓ | https://www.morele.net/plyta-grzewcza-whirlpool-hob-induction-wb-s2560-ne-whp-13484603/ |
| płyta | Whirlpool WL B3360 NE | 1284.99 | 0–25.99 | 0 | łączenie pól ✓, Booster ✓; suwak/blokada niepotwierdzone | https://www.morele.net/plyta-grzewcza-whirlpool-wl-b3360-ne-6747478/ |
| płyta | Whirlpool WL S7960 NE | 1563.99 | 0–25.99 | 0 | łączenie pól ✓, Booster ✓; suwak/blokada niepotwierdzone | https://www.morele.net/plyta-grzewcza-whirlpool-hob-induction-wl-s7960-ne-whp-13484600/ |
| okap | Electrolux LFP326FB | 619.00 | 0–25.99 | 0 | częściowo: 410 m³/h ✓, 28.4 cm ✓, 57 dB (~55 w kuchni); fi 150 i klapa niepotwierdzone | https://www.morele.net/okap-electrolux-lfp326fb-10613455/ |
| okap | Electrolux LFP616X | 871.81 | 0–25.99 | 0 | częściowo: 600 m³/h ✓, 30 cm ✓, klasa A, 68 dB | https://www.morele.net/okap-electrolux-lfp616x-11714037/ |
| okap | Gorenje BHP623E8X | 590.62 | 0–25.99 | 0 | częściowo: 578 m³/h ✓, 30.5 cm ✓, 72 dB | https://www.morele.net/okap-gorenje-bhp623e8x-6039063/ |
| mikrofalówka | Bosch BFL554MB0 | 1406.74 | 0–25.99 | 0 | TAK (38.2 cm, 594 mm, czarne, bez grilla); talerz ~31.5 cm niepotwierdzony | https://www.morele.net/kuchenka-mikrofalowa-bosch-bfl554mb0-7563525/ |
| mikrofalówka | Beko BMGB 25333 BG | 962.59 | 0–25.99 | 0 | częściowo: 38.8 cm, czarne, 25 l; talerz niepotwierdzony | https://www.morele.net/kuchenka-mikrofalowa-beko-bmgb-25333-bg-9612748/ |
| zmywarka | Whirlpool W8I HT40 T | 2409.88 | 0–25.99 | 0 | TAK: 14 kpl, 40 dB, 3. kosz, auto-drzwi, AquaStop, projekcja | https://www.morele.net/zmywarka-whirlpool-w8i-ht40-t-14794528/ |
| zmywarka | Whirlpool W8I HT58 TS | 2473.00 | 0–25.99 | 0 | 38 dB ✓, 14 kpl ✓; OutOfStock | https://www.morele.net/zmywarka-whirlpool-w8i-ht58-ts-13134616/ |
| zmywarka | Beko BDFN26530X | 1670.99 | 0–25.99 | 0 | NIE (44 dB, brak AquaStop) | https://www.morele.net/zmywarka-beko-zmywarka-bdfn26530x-60cm-15-kpl-3-kosz-13134605/ |
| pralka | Samsung WW90DG5G34AELE | 1758.13 | 0–25.99 | 0 (cashback Samsung niepewny: kod LE) | TAK (9 kg, 1400, A, inwerter, 48 cm) | https://www.morele.net/pralka-samsung-pralka-ww90dg5g34aele-samsung-15280352/ |
| pralka | Samsung WW90CGC04DAELE | 2553.90 | 0–25.99 | 0 (kod LE) | TAK (9 kg, 1400, A, inwerter, 55 cm) | https://www.morele.net/pralka-samsung-ww90cgc04daele-14875904/ |
| pralka | Bosch WGG244Z0PL | 2479.00 | 0–25.99 | 0 | TAK (9 kg, 1400, A) | https://www.morele.net/pralka-bosch-wgg244z0pl-15389200/ |
| suszarka | Samsung DV90DG52A0AELE | 3013.72 | 0–25.99 | 0 | TAK poza czujnikiem/wężem (niepotwierdzone); 9 kg, 64 dB | https://www.morele.net/suszarka-do-ubran-samsung-dryer-dv90dg52a0aele-samsung-14856691/ |
| suszarka | Beko BM3T49249W | 2976.50 | 0–25.99 | 0 | częściowo: 9 kg, 63 dB, 58.6 cm; brak potwierdzenia czujnika i węża | https://www.morele.net/suszarka-do-ubran-beko-beko-suszarka-bm3t49249w-15904607/ |
| suszarka | Bosch WQG145APPL | 3064.99 | 0–25.99 | **≈ −500 zł (cashback Bosch, próg 2999–3498,99)** | TAK | https://www.morele.net/suszarka-do-ubran-bosch-suszarka-wqg145appl-15557922/ |
| akcesorium | Samsung SKK-DD | 379.55 | 0–25.99 | 0 | zgodność niepotwierdzona | https://www.morele.net/samsung-lacznik-skk-dd-169785-6275814/ |
| akcesorium | Bosch WTZ27400 | 309.00 | 0–25.99 | 0 | TAK dla par Bosch | https://www.morele.net/bosch-lacznik-pralki-z-suszarka-wtz27400-6358173/ |

---

## Wnioski

1. **morele.net nie jest sklepem, w którym da się skompletować całą listę.** Brakuje czterech kluczowych modeli: piekarnika Whirlpool WOI7A8FHT2SBA (cała linia W Collection), mikrofalówki W7 MD440 NB, zmywarki W7I HT58 T i suszarki DV9MDG52A0AE. Sklep ma wąską ofertę AGD do zabudowy — głównie Electrolux, Bosch i tańsze Whirlpool.
2. **Trzy pozycje naprawdę warto kupić tutaj:** płyta **WB S2560 NE za 1 298 zł** (taniej niż u producenta 1 429 zł, potwierdzony FlexiCook, wersja bez matu), zmywarka **W8I HT40 T za 2 409,88 zł** (jedyna ≤40 dB z AquaStop i projekcją w cenie wzorca) oraz mikrofalówka **Bosch BFL554MB0 za 1 406,74 zł**.
3. **Lodówka: uważaj na pułapkę kodów.** BRB70F30BES0EO nie ma, ale **BRB80F30BES0EO za 3 499,99 zł** to funkcjonalnie ten sam sprzęt (298 l, Twin Cooling, 35 dB, 193,5 cm, Wi-Fi). Warianty „AEF0EO” za 3 249–3 293 zł mają tylko **224 l** — nie kupuj ich w przekonaniu, że to 298 l.
4. **Pralnia: morele jest drogie.** Wybrana para Samsung kosztuje tu 5 947 zł z łącznikiem, czyli **+1,3 tys. zł vs euro.com.pl**. Zamiast tego: pralka **WW90DG5G34AELE za 1 758,13 zł** (9 kg, 1400, klasa A, 48 cm) albo **Bosch WQG145APPL z cashbackiem 400–600 zł** (morele kwalifikuje się do akcji Boscha wprost z regulaminu).
5. **Cashback Samsunga na morele jest ryzykowny** — modele mają końcówkę **LE**, a regulamin wymaga kodów **EO** z polskiej dystrybucji. Przed zakupem poproś sklep o potwierdzenie kodu na fakturze; bez tego nie licz na 200 zł.
6. **Największa realna oszczędność to Morele MAX** (48,60 zł za 12 mies. zamiast 233,91 zł za 9 przesyłek) i wniesienie po 99 zł za urządzenie. Kody `SALE` i newsletter (20 zł) są pomijalne przy tym koszyku. **Żadna z promocji nie wygasa 31.10** — jedyny termin to cashback Samsunga (30.11) i fakt, że kod `GAME26` kończy się dziś, ale nie dotyczy AGD.
