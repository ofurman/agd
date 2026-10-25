# V5 – weryfikacja okazji poza euro.com.pl (runda 2, 25.10.2026, ok. 23:00–23:30)

Metoda: karty produktów i strony/regulaminy promocji odczytane u źródła (curl z UA, r.jina.ai jako proxy, PDF-y regulaminów przez pdftotext). Niczego nie dodawano do koszyka, bez logowania.
Ograniczenie: **mediaexpert.pl zwraca 403 (Cloudflare) dla curl, r.jina.ai i WebFetch** — ani kart produktów, ani stron `lp,k-52xx` nie dało się odczytać. Dla ME mam tylko pośrednie źródła (e-katalog.pl – ceny ofert ME; fragment indeksu wyszukiwarki ze strony `lp,kody-rabatowe`).

Legenda: ✅ potwierdzone u źródła · ⚠️ częściowo / nie do potwierdzenia u źródła · ❌ teza nieprawdziwa

## 1. Neonet

| Oferta | Teza z raportu | Stan zweryfikowany | Status | Źródło |
|---|---|---|---|---|
| „Pralka za pół ceny przy zakupie suszarki” – mechanizm | −50% na pralkę przy zakupie suszarki, kody SAMSUNG50/BOSCH50/ELECTROLUX50/GORENJE50, 15.10–31.10 | Regulamin §2: od 15.10.2026 9:00 do **31.10.2026 23:59** lub do wyczerpania zapasów; rabat 50% na pralkę (produkt promocyjny) przy zakupie suszarki (produkt główny); kod wpisywany w koszyku. Na stronie: „pralkę i suszarkę … **tego samego producenta**” — wymóg jednej marki jest więc zapisany wprost, nie jest wnioskiem | ✅ | [lp/pralka-za-pol-ceny](https://www.neonet.pl/lp/pralka-za-pol-ceny), [regulamin PDF](https://cdn-prod.neonet.pl/static-pages-assets/244/onlineregulaminpromocjipralkazapcenyprzyzakupiesuszarki.pdf) |
| – łączenie | nie łączy się z innymi kodami | §2 ust. 9: nie łączy się z innymi akcjami i rabatami **Organizatora** (Neonet): newsletter, bony, inne kody. Raty 0% dozwolone (ust. 10). Zakup hurtowy wykluczony: >1 szt. modelu lub >1 szt. z kategorii (ust. 8) | ✅ | regulamin j.w. |
| – cashback Samsung | (raport Neonet: nie badał; koszyk-4-sklepy: „para zastępcza 500”) | Karty pralki i suszarki mają plakietkę „Samsung cashback”. Załącznik 1 regulaminu Samsunga: **WW90CGC04DAHEO 200 zł, DV90DG52A0AEEO 200 zł** → 400 zł. Cashback organizuje Samsung, nie Neonet, więc §2 ust. 9 go formalnie nie wyklucza. Warunki: zakup 1.10–30.11.2026, jeden sprzedawca i jeden zakup, paragon/faktura **bez NIP**, opinia, rejestracja do 21.12.2026 | ✅ (kwoty) / ⚠️ (łączenie wynika z interpretacji) | [lp/samsung-cashback-agd](https://www.neonet.pl/lp/samsung-cashback-agd), [regulamin Samsung PDF](https://cdn-prod.neonet.pl/static-pages-assets/225/regulaminpromocjicashbackda_110-30112026_15092026.pdf) |
| Samsung WW90CGC04DAH z SAMSUNG50 | 2299 → 1149,50 | Karta: **2299,00 zł**, „Dostępny”, plakietka „Pralka o połowę taniej” → z kodem **1149,50 zł** | ✅ | [p/1358760](https://www.neonet.pl/p/1358760.html) |
| Samsung DV90DG52A0AEEO (produkt główny) | 2499 | Karta: **2499,00 zł**, „Dostępny”, plakietka „Pralka o połowę taniej” | ✅ | [p/1351760](https://www.neonet.pl/p/1351760.html) |
| Para Samsung razem | 3648,50 zł | **3648,50 zł**; po cashbacku 3248,50 zł. Łącznika nie ma w tej cenie (gotowy zestaw z łącznikiem [p/1570569](https://www.neonet.pl/p/1570569.html), 4525 zł, „Chwilowo niedostępny”) | ✅ | j.w. |
| Bosch WGG244Z0PL z BOSCH50 + WQG243DKPL | 1449,50 + 2999 | Pralka **2899 zł**, z OKAZJE107 2599 zł (do 31.10), plakietka „Pralka o połowę taniej” → z BOSCH50 1449,50 zł. Suszarka **2999 zł**, dostępna, z plakietką. Para: **4448,50 zł** + łącznik | ✅ | [p/1354937](https://www.neonet.pl/p/1354937.html), [p/1323598](https://www.neonet.pl/p/1323598.html) |
| OKAZJE114 – Gorenje NRKI519D61WF | 2696,96 do 31.10, maks. 1 szt. | Karta: **2696,96 zł z kodem OKAZJE114** (bez kodu 3199 zł), „maks. 1 szt.”, „do 31.10.2026 lub do wcześniejszego wyczerpania limitów”, Dostępny. Uwaga do wymagań: 284 l, a MUST to ok. 298 l (−14 l) | ✅ (cena) / ⚠️ (MUST) | [p/1329793](https://www.neonet.pl/p/1329793.html) |
| BLACKWEEKS1 | kod produktowy, do 09.11, maks. 1 szt. | Np. Electrolux LOC8H39X: **2499 zł z BLACKWEEKS1** (bez kodu 2629 zł), „maks. 1 szt.”, „do 09.11.2026 lub do wyczerpania limitów”, Dostępny | ✅ | [p/1333362](https://www.neonet.pl/p/1333362.html) |
| BLACKWEEKS1 + OKAZJE114 w jednym zamówieniu | raport zakłada jedno zamówienie B | Nie ma tego na żadnej stronie. Bezpieczniej złożyć osobne zamówienia (dostawa jest darmowa) | ⚠️ | – |
| Multirabaty | 2. −35%, 3. −55%, 4. −80%, 5. za 1 zł; do 04–08.11 | Lista promocji podaje „Multirabaty – W zestawie kupisz taniej”, **do 4.11.2026**. Progów rabatu nie ma na stronie akcji (sama lista produktów), regulaminu nie znalazłem. Plakietki są na pralce, suszarce i Gorenje | ⚠️ (data ✅, progi i łączenie niepotwierdzone) | [promocje](https://www.neonet.pl/promocje), [lp/multirabaty-w-zestawie-kupisz-taniej](https://www.neonet.pl/lp/multirabaty-w-zestawie-kupisz-taniej) |
| Neonet: karta pralki „System AquaStop” | (raport neonet: „AquaStop ?”) | Według samsung.com/pl: „Wąż Aquastop: **Nie**”, „Czujnik wycieku: Nie”. Opis na Neonecie jest mylący. AquaStop to tylko NICE | ❌ (AquaStop) | spec. samsung.com/pl (pkt 5) |

## 2. Media Expert (źródło niedostępne – 403)

| Oferta | Teza z raportu | Stan zweryfikowany | Status | Źródło |
|---|---|---|---|---|
| K-5247 „drugi tańszy −45%” | tańszy z 2 produktów AGD −45%, do 01.11, bez Outlet/Marketplace | Indeks wyszukiwarki potwierdza mechanizm (2 różne produkty z akcji, kod w koszyku, −45% na tańszy; bez OUTLET i sprzedawców zewnętrznych) i termin do 01.11.2026. **Których modeli dotyczy, nie da się sprawdzić** | ⚠️ | [lp,k-5247…](https://www.mediaexpert.pl/lp,k-5247-drugi-tanszy-45proc-taniej) (403), [lp,kody-rabatowe](https://www.mediaexpert.pl/lp,kody-rabatowe) (403, tylko indeks wyszukiwarki) |
| K-5239 płyta za 1 zł (z piekarnikiem i zmywarką) | do 31.10 | Indeks: „płyta za 1 zł przy zakupie piekarnika i zmywarki”, do 31.10.2026. Lista modeli nieznana | ⚠️ | j.w. |
| K-5213 do −3000 zł | progi 100/250/400 … 3000 zł od 16 000 zł, do 31.10 | Strony nie odczytałem, a wyszukiwarka nie zwraca jej treści. Progi i termin są **niepotwierdzone** | ⚠️ | [lp,k-5213…](https://www.mediaexpert.pl/lp,k-5213-zyskaj-nawet-3000zl-rabatu) (403) |
| K-5241 | (raport ME: brak) | Indeks: **pralka −50% przy zakupie z suszarką**, do 31.10.2026. To odpowiednik SAMSUNG50 w ME. Lista modeli nieznana | ⚠️ (nowa informacja) | lp,kody-rabatowe (indeks) |
| K-5244 | płyta −50% z piekarnikiem, do 09.11 | Indeks potwierdza: płyta −50% z piekarnikiem, do 09.11.2026 | ⚠️ | j.w. |
| K-5252 | −200 zł od 1500 zł (2 różne produkty), do 27.10 | Indeks potwierdza: do 27.10.2026 | ⚠️ | j.w. |
| WW90CGC04DAH + DV90DG52A0TEEO objęte K-5247/K-5241 | „niepotwierdzone” | Nie da się tego sprawdzić. Ceny ofert ME wg e-katalogu: pralka **1800 zł**, suszarka **2499 zł**. Gdyby kody obejmowały ten model: K-5241 daje 900 + 2499 = 3399 zł, K-5247 daje 990 + 2499 = 3489 zł. Cashback Samsung: DAHEO 200 + DV90DG52A0TEEO 200 | ⚠️ | [e-katalog WW90CGC04DAH](https://e-katalog.pl/SAMSUNG-WW90CGC04DAH.htm), [e-katalog DV90DG52A0TEEO](https://e-katalog.pl/SAMSUNG-DV90DG52A0TEEO.htm) |
| Samsung BRB80F30BES0EO 3099 | 3099 zł | e-katalog: oferta ME **3099 zł**, ale karty ME nie odczytałem. **Cashbacku Samsunga nie ma**: na liście są BRB80F30BDS0EO, ADS0EO i ADF0EO, a BES0EO nie | ⚠️ cena / ❌ cashback | [e-katalog](https://e-katalog.pl/SAMSUNG-BRB80F30BES0EO.htm), regulamin Samsung (zał. 1) |
| Whirlpool W7I HT58 T 2299 | 2299 zł | e-katalog: ME 2299 zł (karty ME nie odczytałem) | ⚠️ | [e-katalog](https://e-katalog.pl/WHIRLPOOL-W7I-HT58-T.htm) |
| Whirlpool WBB8360NE 1287 | 1287 zł | e-katalog: ME 1287 zł (karty ME nie odczytałem) | ⚠️ | [e-katalog](https://e-katalog.pl/WHIRLPOOL-WBB8360NE.htm) |

Wniosek ME: koszyki z raportów ME (13 985,99 / ≈13 793 zł) **nie przechodzą weryfikacji**, bo nie da się potwierdzić, które modele obejmują kody. Sprawdzić może je tylko człowiek w przeglądarce: wpisać kod w koszyku albo otworzyć listę „produkty w akcji” na stronie lp.

## 3. MediaMarkt

| Oferta | Teza z raportu | Stan zweryfikowany | Status | Źródło |
|---|---|---|---|---|
| ZestawoMania | do 25.10.2026 23:59:59 | Regulamin (czas trwania, ust. 3): sklep internetowy od 19.10.2026 16:00:01 do **25.10.2026 23:59:59** lub do wyczerpania zapasów. Aneks nr 1 z 20.10 tylko usuwa produkty z zał. 2 i nie przedłuża akcji | ✅ (o 23:24 akcja praktycznie się skończyła) | [regulamin + aneks](https://cms-assets.mmst.eu/4lyxhctxrf55/6Lgm1bZporP3kkYUwDGYAP/3c21999069752ec0ea01765ed7f70c0f/0c95b915-9dd3-4ef1-831a-aa0d78ae3408.pdf) |
| Urodziny (−28% www / −36% aplikacja) | do 25.10.2026 23:59:59 | Regulamin (aplikacja, aneks z 22.10): 19.10.2026 13:00 do **25.10.2026 23:59:59**. Aneks nie przedłuża terminu | ✅ | [regulamin + aneks](https://assets.ctfassets.net/4lyxhctxrf55/4QuRhSf8R6z9YvY2f1H08z/64e11aebda3e899d260f970846eff231/71df22c4-5dbd-436d-b486-599df0423b38.pdf) |
| „Jutro następna akcja?” | raport: nie znaleziono | Na stronie głównej i w `/pl/campaign/promocje` (23:24) **nie ma zapowiedzi akcji zestawowej od 26.10**. Trwają akcje producentów **do 31.10.2026**: „Bosch – −30% wartości pralki w zestawie z suszarką” oraz „Samsung – kup piekarnik i zmywarkę, zgarnij płytę w zestawie”. Akcji ogólnej od jutra nie da się potwierdzić | ⚠️ | [mediamarkt.pl/pl/campaign/promocje](https://mediamarkt.pl/pl/campaign/promocje), [bosch-suszarka-pralka-zestaw-taniej](https://mediamarkt.pl/pl/specials/bosch-suszarka-pralka-zestaw-taniej), [samsung-z-plyta-w-zestawie](https://mediamarkt.pl/pl/specials/samsung-z-plyta-w-zestawie) |

## 4. Morele / Avans / Sferis

| Oferta | Teza z raportu | Stan zweryfikowany | Status | Źródło |
|---|---|---|---|---|
| Morele Samsung BRB70F30BES0EO 3119 | 3119 zł (ceneo-i-producenci); raport morele: „brak oferty” | Karta: **3119 zł**, MPN BRB70F30BES0EO, EAN 8806097060673. Sprzedaje i wysyła **Morele.net**, InStock, ale z dopiskiem **„Ostatnie sztuki”**. Raport morele.net.md („brak oferty”) się mylił. **Bez cashbacku Samsunga**: model nie ma go na liście | ✅ (ryzyko: niski stan) | [morele …-14761798](https://www.morele.net/lodowka-samsung-chlodziarko-zamrazarka-do-zabudowy-brb70f30bes0-14761798/) |
| Morele Whirlpool WB S2560 NE 1298 | 1298 zł | Karta (ld+json): **1298 zł**, InStock | ✅ | [morele …-13484603](https://www.morele.net/plyta-grzewcza-whirlpool-hob-induction-wb-s2560-ne-whp-13484603/) |
| Avans Whirlpool W7I HT58 T | 2299 zł, bez kodu | Stan strony: `price_gross` **2299,00 zł**, `promoPrice: null` (kod RWE nie obejmuje tego produktu), InStock, „Dostawa jutro” | ✅ | [avans W7I HT58 T](https://www.avans.pl/agd-do-zabudowy/zmywarki-do-zabudowy/zmywarka-whirlpool-w7i-ht58-t) |
| Sferis Gorenje GV663B65 2399 | 2399 zł | Teraz **2239 zł** (przekreślone 2399; najniższa cena z 30 dni 2399), Produkt Dostępny, dostawa 27.10 gratis. **O 160 zł taniej niż w raporcie**. Terminu obniżki strona nie podaje | ✅ (lepiej niż w raporcie) | [sferis i652768](https://www.sferis.pl/zmywarka-do-zabudowy-60-cm-gorenje-gv663b65-klasa-b-16-kpl-aquastop-totaldry-speedwash-i652768) |
| Sferis Electrolux LFP326FB 659 | 659 zł | **659 zł**, Produkt Dostępny | ✅ | [sferis i297104](https://www.sferis.pl/okap-teleskopowy-electrolux-lfp326fb-60-cm-300-m3-h-led-czarny-i297104) |

## 5. WW90CGC04DAH vs WW90CGC04DAE (samsung.com/pl)

Porównałem obie karty na samsung.com/pl (URL-e z `da-sitemap.xml`). **Tabela „Specyfikacja” jest identyczna co do linii** (160 linii, diff pusty): 9 kg, 1400 obr., A, 44 kWh/100 cykli, 50 l, wirowanie 72 dB, klasa wirowania B, emisja hałasu A, 600×850×550 mm, 65 kg, silnik DIT, Higieniczna para, Pranie szybkie 15, Wełna/Delikatne, **dodawanie ubrań w trakcie programu: Tak**, StayClean, Wi-Fi/SmartThings, Wąż Aquastop: Nie. Różnią się tylko teksty marketingowe: karta DAE ma dodatkowy przypis o AutoCycle Link (funkcja SmartThings w parze z suszarką), a ocena i liczba opinii są inne. Oba modele są na samsung.com „niedostępne”. Oba są na liście cashbacku Samsunga (po 200 zł).
**Wniosek: DAH to wariant kanałowy (inny kod sprzedażowy) tej samej pralki, nie inna funkcjonalność. ✅**
Źródła: [WW90CGC04DAEEO](https://www.samsung.com/pl/washers-and-dryers/washing-machines/ww5000c-front-loading-eco-bubble-a-10percent-extra-energy-saving-smartthings-ai-energy-mode-9kg-white-ww90cgc04daeeo/), [WW90CGC04DAHEO](https://www.samsung.com/pl/washers-and-dryers/washing-machines/ww5000c-front-loading-eco-bubble-a-10percent-extra-energy-saving-smartthings-ai-energy-mode-9kg-white-ww90cgc04daheo/)

## 6. Najtańszy wariant, który przechodzi weryfikację (bez euro.com.pl i bez ME)

Do wariantu weszły tylko pozycje potwierdzone u źródła w tej rundzie. Mikrofalówka i łącznik pralka–suszarka nie były w zakresie V5, więc trzeba je dodać z innych weryfikacji.

| Kategoria | Sklep | Model | Cena | Kod / termin | Uwagi |
|---|---|---|---|---|---|
| Piekarnik | Neonet | Electrolux LOC8H39X | 2499,00 | BLACKWEEKS1, do 09.11, maks. 1 szt. | odpowiednik, nie wzorzec |
| Lodówka | Morele | Samsung BRB70F30BES0EO (wzorzec) | 3119,00 | – | „ostatnie sztuki”; bez cashbacku |
| Płyta | Morele | Whirlpool WB S2560 NE (wzorzec) | 1298,00 | – | dostawa 0–25,99 zł |
| Okap | Sferis | Electrolux LFP326FB | 659,00 | – | klapa zwrotna niepotwierdzona (raport sferis) |
| Zmywarka | Sferis | Gorenje GV663B65 | 2239,00 | obniżka bez podanego terminu | 16 kpl, 38 dB |
| Pralka | Neonet | Samsung WW90CGC04DAH | 1149,50 | SAMSUNG50, do 31.10 23:59 | osobne zamówienie (nie łączy się z innymi rabatami Neonetu) |
| Suszarka | Neonet | Samsung DV90DG52A0AEEO | 2499,00 | produkt główny SAMSUNG50 | w tym samym zamówieniu co pralka |
| **Razem (7 pozycji)** | | | **13 462,50 zł** | | + dostawa Morele ≤ 52 zł |
| Cashback Samsung | | pralka 200 + suszarka 200 | **−400 zł** | zakup do 30.11, rejestracja do 21.12, bez NIP | netto **13 062,50 zł** |

Podział na sklepy: **Neonet 6147,50 zł** (zamówienie A: pralka + suszarka z SAMSUNG50; zamówienie B: piekarnik z BLACKWEEKS1) · **Morele 4417,00 zł** · **Sferis 2898,00 zł**.

Warianty:
- Lodówka Gorenje NRKI519D61WF z Neonetu (2696,96 zł, OKAZJE114 do 31.10, osobne zamówienie) zamiast Samsunga z Morele daje razem **13 040,46 zł**, netto 12 640,46 zł (−422 zł). Ten model ma 284 l, a MUST to ok. 298 l, więc jest na granicy wymagań.
- Zmywarka wzorcowa Whirlpool W7I HT58 T z Avansu (2299 zł) kosztuje 60 zł więcej niż Gorenje w Sferisie.
- Media Expert z K-5241 (para Samsung ok. 3399 zł) mógłby być o ok. 250 zł tańszy od Neonetu w pralni, **ale nie przechodzi weryfikacji**: nie da się potwierdzić, które modele obejmuje kod.
- Termin krytyczny: **31.10.2026 23:59** dla SAMSUNG50 i OKAZJE114.
