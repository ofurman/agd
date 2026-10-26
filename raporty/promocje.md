# promocje (cashbacki, kody, raty) – raport (2026-10-25)

> **Snapshot sprzed decyzji 26.10.2026.** Aktualny wybór: płyta Electrolux CIV634 (2 099, euro) + okap Electrolux LFG716R (1 348,99, euro); para 3 447,99 → cashback Electrolux 400. Koszyk netto 16 193,25 / 15 663,44 — patrz `README.md`.

## Jak zebrano dane

**Sprawdzone na żywo (25.10.2026, 21:35–22:10):**

| Źródło | Co | Status |
|---|---|---|
| `samsung.com/pl/offer/cashback/promo/agd/2026` | strona promocji + **regulamin PDF** (`Regulamin_promocji_Cashback_DA_1.10-30.11.2026_15.09.2026.pdf`) z **Załącznikiem nr 1 = pełna lista modeli i kwot** | ✅ pobrane, przeczytane |
| `whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spokój_zaczyna_się_od_mądrych_decyzji-2.pdf` | regulamin + **Załącznik nr 1 = pełna lista modeli i kwot** | ✅ pobrane, przeczytane. Strona główna promocji to SPA (bez JS pokazuje tylko „zaktualizuj przeglądarkę”), ale PDF regulaminu leży na tym samym serwerze → promocja działa |
| `media3.bosch-home.com/...Promocja_suszarek_pralko-suszarek...pdf` | regulamin + Załącznik nr 1 | ✅ pobrane, przeczytane |
| `mediamarkt.pl/pl/campaign/promocje`, `/specials/zestawomania`, `/specials/bosch-suszarka-pralka-zestaw-taniej`, `/specials/samsung-z-plyta-w-zestawie`, `/specials/zakupy-na-raty`, `/campaign/urodziny-mediamarkt` | opisy akcji + **regulaminy PDF z listami produktów** | ✅ pobrane, przeczytane |
| `mediaexpert.pl/lp,k-5239-plyta-za-1-zl`, `/lp,k-5234-nawet-400zl-na-kolejne-zakupy`, `/lp,k-4449-pralka-50-proc-taniej`, `/lp,27514-bosch-pralka-50proc-taniej` | opisy akcji + listy kodów „cena z kodem” | ✅ pobrane, przeczytane (dwie ostatnie strony okazały się **wygasłe**) |
| `cdn-prod.neonet.pl/.../onlineregulaminpromocjipralkazapolcenyprzyzakupiesuszarki.pdf` (wersja `/244/`) | regulamin „pralka za pół ceny” 15.10–31.10.2026, kody `SAMSUNG50`/`BOSCH50`/… | ✅ pobrane, przeczytane (samego listingu modeli nie – `neonet.pl` zwraca 403 na wszystkie ścieżki) |
| `avans.pl/lp,kody-rabatowe` | kody i gratisy | ✅ pobrane, przeczytane (brak kodu % na AGD) |
| `amica.pl/200za1500-promocja`, `amica.pl/wielorabaty-promocja` | warunki i terminy | ✅ pobrane, przeczytane |
| `payback.pl/sklepy-online` (+ karty EURO / mediaexpert / media-markt / OLEOLE) | lista partnerów, stawka naliczania | ✅ pobrane, przeczytane |
| `x-kom.pl/promocje` | raty 0%, newsletter | ✅ pobrane |

**Blokady (nie obchodziłem, zgodnie z zasadami):**

- **euro.com.pl i oleole.pl** – HTTP **403** przy każdym żądaniu (także na `cms/*.bhtml`). Wszystko o euro/oleole poniżej ma status `niepotwierdzone (snippet)` albo pochodzi z `wymagania-AGD.md`.
- **neonet.pl** – HTTP **403**. **sferis.pl** – brak połączenia (000). **mediaexpert.pl** – `curl` dostaje 403 (antybot), ale strony akcji dały się odczytać przez czytnik; ceny z listingu Media Expert mam tylko ze snippetów.
- **morele.net, avans.pl** – strony akcji niedostępne pod zgadywanymi adresami (404); kodów nie potwierdziłem → oznaczone „nie zweryfikowano”.

**Ceny w tym raporcie:** to raport *promocji*, nie cen. Kwoty bazowe biorę z innych raportów/`wymagania-AGD.md` i **zawsze** oznaczam źródło. Kwoty cashbacków i warunki są **potwierdzone w regulaminach** (pewność wysoka), same ceny – nie.

---

## Promocje / kupony

### A. Cashbacki producentów

| Akcja | Modele / kwoty (dla naszej listy) | Warunki | Ważność | Łączenie | Źródło | Pewność |
|---|---|---|---|---|---|---|
| **Samsung cashback AGD** (do 4500 zł) | **WW90CGC04DAEEO → 200 zł** · **DV9MDG52A0AEEO → 200 zł** · **BRB80F30ADS0EO → 300 zł** · BRB80F30ADF0EO → 300 zł · BRB80F26ACS0EO/ADS0EO/ACF0EO/ADF0EO/BDF0EO → 300 zł · NZ64B5066GK/U2 → 200 zł · NZ64B5066FK/U2 → 200 zł · **BRB70F30BES0EO → NIE MA NA LIŚCIE** · zmywarka/piekarnik Samsunga: NV7B* 300–600 zł, DW* 200–500 zł | Zakup **1.10–30.11.2026** u jednego sprzedawcy = „Punkt Handlowy” (sklep stacjonarny **lub internetowy**; marketplace’owy sprzedawca też jest sklepem, ale musi to być sprzęt wprowadzony do obrotu przez Samsung PL, czyli kod **…EO**). Rejestracja na `cashbackagd.samsung.pl` **do 21.12.2026**, konto Samsung Account, **opinia ≥200 znaków** z `#OpiniaZaCashbackwPromocji` i `#PromocjaSamsungUrzadzeniaAGDQ42026`, zdjęcia tabliczek znamionowych, paragon/faktura imienna **bez NIP kupującego** (NIP sprzedawcy musi być widoczny). Max **4 zgłoszenia**, max 5 produktów w zgłoszeniu. | 30.11.2026 lub wyczerpanie puli **2 480 000 zł**; wypłata do 8.02.2027 | Łączy się z kodami sklepowymi, ratami i innymi cashbackami (różne marki). **Nie** z innym zgłoszeniem tego samego numeru seryjnego. Zwrot towaru = utrata prawa. Podatek: nagroda jest powiększana o 11,11% → **nie pomniejsza wypłaty** | [samsung.com/pl/offer/cashback/promo/agd/2026](https://www.samsung.com/pl/offer/cashback/promo/agd/2026/) + [regulamin PDF](https://images.samsung.com/is/content/samsung/assets/pl/regulaminy_2026/Regulamin_promocji_Cashback_DA_1.10-30.11.2026_15.09.2026.pdf) | **wysoka** (regulamin, zał. 1) |
| **Whirlpool „Spokój zaczyna się od mądrych decyzji”** (do 3000 zł) | **WOI7A8FHT2SBA → 350 zł** · **WOI7P8FHT1SBA → 750 zł** · WOI11P8FHT2SBAF → 750 zł · WOI9P8HT2SBA/WOI9A8PT2SBA → 750 zł · **WBS2560NE → 200 zł** · WLS2760BF/S → 200 zł · WLB6860NES/WLB3360NE → 200 zł · lodówki do zabudowy WHK25324B6E/B6E1 → 750 zł · mikrofalówki WMD7O4TB / WMD54MB / WMW57* → 200–300 zł · **W7 MD440 NB → NIE MA NA LIŚCIE** · **W7I HT58 T (zmywarka) → promocja nie obejmuje zmywarek** | **Minimum 2 produkty, w tym obowiązkowo piekarnik** (2–4 produkty; po jednym z kategorii piekarnik / płyta / mikrofalówka / lodówka). Zakup **1.09–31.12.2026**, dowody mogą być z różnych transakcji i różnych sklepów. **Piekarnik rejestrujesz ≤14 dni od zakupu**, pozostałe produkty **≤3 dni od rejestracji piekarnika** (dostajesz kod). Opinia **osobno dla każdego produktu** z `#PromocjaZyskajSpokój`. Paragon/faktura bez NIP kupującego. Max 3 zgłoszenia. | Zgłoszenia **do 14.01.2027**, pula **1 500 000 zł**, wypłata do 31.03.2027 | Łączy się z kodami sklepowymi i cashbackiem innej marki. **Nie** z innymi równoległymi akcjami Beko/Whirlpool na te same kategorie (pkt 8.6). **Pułapka podatkowa:** nagroda >2000 zł w jednym zgłoszeniu → 10% podatku potrącane z nagrody (3000 zł → 2700 zł na konto) | [regulamin PDF](https://whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spok%C3%B3j-zaczyna-si%C4%99-od-m%C4%85drych-decyzji-2.pdf) | **wysoka** (regulamin, zał. 1) |
| **Bosch – suszarki i pralko-suszarki** (do 1000 zł) | **WQG245DEPL → 500 zł** przy cenie 2999–3498,99 zł · **WQH245B0PL** – ta sama tabela progowa · **WGG244ZEPL (pralka) → NIE OBJĘTA** (lista = tylko suszarki i pralko-suszarki) | Progi od **ceny końcowej na dowodzie zakupu po wszystkich rabatach**: 1999–2498,99 → 200; 2499–2998,99 → 400; **2999–3498,99 → 500**; 3499–3998,99 → 600; 3999–4998,99 → 750; ≥4999 → 1000. Zakup **1.10–31.12.2026**, zgłoszenie **do 30.01.2027**, opinia z `#opiniamotywowanapromocją`, paragon bez NIP, zdjęcie tabliczki. Wyłączone: zakup bezpośrednio u BSH. | do 31.12.2026, pula **2 500 000 zł**, wypłata 60 dni | Łączy się z kodami sklepowymi – **ale kod obniżający cenę poniżej 2999 zł zmniejsza zwrot z 500 na 400 zł**. Podatek: gross-up (dostajesz pełną kwotę) | [regulamin PDF](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) | **wysoka** (regulamin, zał. 1) |
| Bosch – zmywarki (do 700 zł) | dotyczy zmywarek Bosch (nasze typy to Whirlpool/Beko) | Zakup **1.09–15.11.2026** | do 15.11.2026 | – | [bosch-home.pl](https://www.bosch-home.pl/pl) (baner), [regulamin zmywarek](https://media3.bosch-home.com/Documents/29219642_REGULAMIN_CB_Zmywarki_Bosch_Tekst_Jednolity.pdf) | wysoka (regulamin istnieje; kwot progowych nie czytałem) |
| Beko – 5 lat ochrony serwisowej | dotyczy wybranych modeli Beko (m.in. zmywarki), **przy zakupie z meblami kuchennymi** | 1.04–31.12.2026, rejestracja na `register.beko.com/pl-pl` | do 31.12.2026 | – | [programatorbeko.pl](https://www.programatorbeko.pl/) | średnia (strona promocji; lista modeli w PDF nie sprawdzona) |
| Electrolux – cashback pralnictwo (do 500 zł) | nie dotyczy naszej listy (brak Electrolux w koszyku) | akcja euro.com.pl | – | – | snippet euro.com.pl | **niepotwierdzone (snippet)** |

### B. Kody i akcje sklepowe

| Akcja | Modele / kwoty | Warunki | Ważność | Łączenie | Źródło | Pewność |
|---|---|---|---|---|---|---|
| **MediaMarkt „Urodziny – w zestawie taniej”** (aplikacja) | **36% ceny drugiego tańszego produktu** z zestawu 2–6 różnych produktów. W liście zał. 1 są m.in. **WOI7P8FHT1SBA**, **W7I HT58 T**, **BRB80F30ADS0EO**. **NIE ma:** WOI7A8FHT2SBA, WBS2560NE, BRB70F30BES0EO, WW90CGC04DAE, DV9MDG52A0AE, MEDIN3755A, OTP6651BG, BFL554MB0, WQG245DEPL, WGG244ZEPL | Tylko **aplikacja MediaMarkt** (myMediaMarkt, zalogowane konto), jedna transakcja, różne modele. Nie łączy się z innymi akcjami „zestawowymi”. | **kończy się dziś 25.10.2026, 23:59:59** | Nie łączy się z ZestawoManią ani z zestawami Bosch/Samsung | [mediamarkt.pl/pl/campaign/urodziny-mediamarkt](https://mediamarkt.pl/pl/campaign/urodziny-mediamarkt) + [regulamin z aneksem 22.10](https://assets.ctfassets.net/4lyxhctxrf55/4QuRhSf8R6z9YvY2f1H08z/64e11aebda3e899d260f970846eff231/71df22c4-5dbd-436d-b486-599df0423b38.pdf) | **wysoka** |
| **MediaMarkt „ZestawoMania”** | 2 produkty → **−30% najtańszego**, 3 → −55%, 4 → −80%, 5 → **5. najtańszy za 1 zł**. W liście (zał. 2 po aneksie 20.10) są m.in. **WOI7P8FHT1SBA**, **W7I HT58 T**, **BRB80F30ADS0EO**; reszty naszych modeli **nie ma** | Jedna transakcja, różne modele, dowolne mieszanie dużego AGD / AGD do zabudowy / RTV. Nie obejmuje Outletu i Marketplace. Nie łączy się z innymi zestawami. | **kończy się dziś 25.10.2026, 23:59:59** | Nie z urodzinami, nie z zestawami Bosch/Samsung | [mediamarkt.pl/pl/specials/zestawomania](https://mediamarkt.pl/pl/specials/zestawomania) + [regulamin](https://cms-assets.mmst.eu/4lyxhctxrf55/6Lgm1bZporP3kkYUwDGYAP/3c21999069752ec0ea01765ed7f70c0f/0c95b915-9dd3-4ef1-831a-aa0d78ae3408.pdf) | **wysoka** |
| **MediaMarkt – pralka + suszarka Bosch −30% wartości pralki** | **Tylko 5 sztywnych par:** WGG242ZKPL+WQG241ALPL · WGG256ZTPL+WQG244CSPL · WAN2425MPL+WTH85V9FPL · WAN2827LPL+WTH85V9FPL · WGH2460XPL+WQH246CNPL. **Nasza para WGG244ZEPL + WQG245DEPL NIE jest objęta** | Jedna transakcja, nie Outlet, nie „za pobraniem”, nie Marketplace | 14.10–**31.10.2026** | Nie z ZestawoManią | [regulamin PDF](https://cms-assets.mmst.eu/4lyxhctxrf55/4sQlrfGzwFmch9xqGeIfA3/4d9bc82ff783ef16f755032df6af05c3/7955_Regulamin_Pralka_i_suszarka_Bosch_w_zestawie_taniej_o_30-_wartosci_pralki.pdf) | **wysoka** |
| MediaMarkt – „Kup piekarnik i zmywarkę, płyta w zestawie” | Samsung: piekarnik + zmywarka → płyta w cenie | Wybrane produkty Samsung (lista w regulaminie) | do **31.10.2026** | – | [mediamarkt.pl/pl/specials/samsung-z-plyta-w-zestawie](https://mediamarkt.pl/pl/specials/samsung-z-plyta-w-zestawie) | wysoka (opis), lista nie sprawdzona |
| MediaMarkt – pakiet usług „Wniesienie, montaż, odbiór starego + 3 lata gwarancji” | usługa dodawana do koszyka, cena pakietu zmienia się automatycznie | – | do **31.10.2026** | – | [mediamarkt.pl/pl/promo-list/koenic_peaq_wniesienie_montaz_odbior_taniej](https://mediamarkt.pl/pl/promo-list/koenic_peaq_wniesienie_montaz_odbior_taniej) | wysoka (opis); ceny pakietu nie sprawdziłem |
| **MediaMarkt – raty 0% (BNP Paribas)** | RRSO **0%**, kwota 300–20 000 zł, 3–50 rat, opcja odroczenia do 6 mies. („Urodzinowa Rata GRATIS” – bank płaci 1 ratę) | wniosek online, decyzja w 60 s | akcja urodzinowa do 25.10.2026; oferta ratalna „odwołalna” | – | [mediamarkt.pl/pl/specials/zakupy-na-raty](https://mediamarkt.pl/pl/specials/zakupy-na-raty) | wysoka |
| **Media Expert – kody „cena z kodem”** | **ME0410-311026, ME0510-311026, ME0610-311026, ME0910-311026, ME1210-311026, ME1510-311026, ME1610-311026, ME2010-311026, ME2210-311026** → do **31.10.2026 23:59**; **ME0410-311026G14** → 31.10 do 13:59; **RW0110-3110** → 31.10 do 21:59 (produkty Whirlpool); **RW0910-311026** → 31.10 do 21:59; **R0110-311026** → 31.10 23:59; **AK2410-2510** → **25.10** (dziś!); **AK2510-2610, PAZ2310, RS2410-261026** → 26.10 23:59; **BW1610-0112** → 01.12.2026; **R0810-071226, R1710-071226** → 07.12.2026; **R2309-311226** → 31.12.2026 | Rabat dotyczy **konkretnych produktów oznaczonych „cena z kodem: …”** w listingu/karcie. Kod nie łączy się z innym kodem. Wyłączone: Outlet i sprzedawcy inni niż Media Expert (marketplace). | jak wyżej | **Nie łączy się z innymi kodami**, ale łączy z cashbackiem producenta | [lp,k-5239-plyta-za-1-zl](https://www.mediaexpert.pl/lp,k-5239-plyta-za-1-zl), [lp,k-5234…](https://www.mediaexpert.pl/lp,k-5234-nawet-400zl-na-kolejne-zakupy), [lp,k-4449 (przypisy z kodami)](https://www.mediaexpert.pl/lp,k-4449-pralka-50-proc-taniej) | **wysoka** (listy kodów na stronach akcji) |
| Media Expert – „Płyta za 1 zł” (kod **K-5239**) | piekarnik Samsung + zmywarka Samsung + płyta Samsung → płyta za 1 zł | zestaw 3 produktów z listy Samsunga, kod **K-5239** | do **31.10.2026 23:59** | nie z innymi kodami | [lp,k-5239-plyta-za-1-zl](https://www.mediaexpert.pl/lp,k-5239-plyta-za-1-zl) | wysoka |
| Media Expert – voucher **K-5234** (Electrolux) | „nawet 400 zł na kolejne zakupy” przy zakupie AGD do kuchni Electrolux | kod **K-5234**, kod-voucher wysyłany **1–3.12.2026**, ważny 90 dni, nie na produkty z listy wykluczeń | akcja do **26.10.2026 23:59** | – | [lp,k-5234…](https://www.mediaexpert.pl/lp,k-5234-nawet-400zl-na-kolejne-zakupy) | wysoka |
| **Neonet – „PRALKA ZA PÓŁ CENY PRZY ZAKUPIE SUSZARKI”** | **−50% ceny pralki** przy zakupie suszarki. Kody zależne od marki: **`ELECTROLUX50`, `GORENJE50`, `SAMSUNG50`, `BOSCH50`** | Tylko sklep internetowy neonet.pl, jedna transakcja: suszarka („Produkt Główny”) + pralka oznaczona znakiem „PRALKA ZA PÓŁ CENY”. Wyłączone zakupy hurtowe (max 1 szt. modelu / 1 szt. z kategorii). **Nie łączy się** z innymi rabatami i bonami Neonetu (w tym bonem za newsletter), **łączy się z ratami 0%**. Regulamin nie wyklucza cashbacku producenta. | **15.10.2026 09:00 – 31.10.2026 23:59** | tak: cashback Samsung/Bosch, raty 0%. Nie: inne kody Neonetu | [regulamin PDF](https://cdn-prod.neonet.pl/static-pages-assets/244/onlineregulaminpromocjipralkazapcenyprzyzakupiesuszarki.pdf) | **wysoka** (regulamin); **lista modeli niepotwierdzona** – `neonet.pl/lp/pralka-za-pol-ceny` zwraca 403 |
| euro.com.pl – „pralka 50% przy zakupie suszarki” | analogiczna akcja (osobna strona `cms/pralka-50-pr-do-suszarek.bhtml`) | euro zwraca 403 – nie zweryfikowałem warunków ani modeli | ? | ? | snippet euro.com.pl | **niepotwierdzone (snippet)** |
| Avans – kody rabatowe | **brak kodu % na AGD** – tylko gratisy: „trzonek gratis” (do 31.10.2026), „napój Cold Brew gratis” (do 31.12.2026), „oczyszczacz za 1 zł”; poza tym newsletter | Avans nie publikuje kodu procentowego na duże AGD | jw. | – | [avans.pl/lp,kody-rabatowe](https://www.avans.pl/lp,kody-rabatowe) | wysoka (strona odczytana 25.10) |
| Neonet – „Multirabaty w zestawie” | brak dostępu (403) – nie potwierdzam kwot | – | ? | – | [neonet.pl/lp/multirabaty…](https://www.neonet.pl/lp/multirabaty-w-zestawie-kupisz-taniej) | **niepotwierdzone** |
| Sferis, Morele | **nie zweryfikowano**: sferis.pl nie odpowiada (brak połączenia), morele.net – strony akcji 404 | – | – | – | – | brak danych |
| Media Expert – „Nawet 3000 zł rabatu” przy 2 produktach TV/AGD/AGD do zabudowy | rabat na drugi produkt z pary | lista produktów w regulaminie (strona `lp,k-5213-…` zwracała 403 przy próbie odczytu) | do **31.10.2026** | – | snippet mediaexpert.pl (`/lp,promocja-zakonczona`, strona główna) | **niepotwierdzone (snippet)** |
| Media Expert – Konto Plus | darmowa dostawa od 40 zł, −50% na usługi (wniesienie/montaż), „odbiór za godzinę” | konto w programie | – | – | [lp,konto-plus](https://www.mediaexpert.pl/lp,konto-plus) | wysoka (opis) |
| Media Expert – raty | **0%, RRSO 0%**, „do 40 rat, do marca nie płacisz” | – | – | – | mediaexpert.pl (nawigacja) | średnia (opis bez regulaminu) |
| **Amica – kod `Amica200`** („200 za 1500”) | **−200 zł za każde 1500 zł** w koszyku, maks. 1800 zł. Okap **OTP6651BG 679 zł** kwalifikuje się, ale próg 1500 zł wymaga drugiego produktu Amica z innej kategorii | min. **2 produkty z różnych kategorii**, min. 1500 zł, **od cen regularnych**, tylko sklep **amica.pl** | **23–27.10.2026** | nie z „Wielorabatami” (oba od cen regularnych, inne kody) | [amica.pl/200za1500-promocja](https://www.amica.pl/200za1500-promocja) | **wysoka** |
| Amica – „Wielorabaty” | 2 produkty → −30% najtańszego, 3 → −55%, 4 → −80%, 5 → **−99%** | min. 2 produkty z różnych kategorii, od cen regularnych, sklep amica.pl | **21.10–03.11.2026** | nie z Amica200 | [amica.pl/wielorabaty-promocja](https://www.amica.pl/wielorabaty-promocja) | **wysoka** |
| Amica – test 60 dni / zwrot | piekarnik i/lub płyta: 100% satysfakcji albo zwrot pieniędzy | – | – | – | [amica.pl/satysfakcja](https://www.amica.pl/satysfakcja) | wysoka (opis) |
| Amica – raty | 10 rat 0% RRSO 0% (na amica.pl) | – | – | – | amica.pl (karty produktów) | wysoka |
| **Samsung.pl – kod `MULTI` (Multirabaty)** | −30% na 2. produkt, −55% na 3., −80% na 4., **5. za 1 zł** (rabat na najtańszy), produkty z **różnych grup** | tylko sklep **samsung.pl**, wyłączone przedsprzedaże/premiery | „do wypowiedzenia przez Organizatora” | – | [samsung.com/pl/offer/promocja-agd](https://www.samsung.com/pl/offer/promocja-agd/) (przypis 2 na stronie cashbacku) | średnia (opis bez regulaminu) |
| Samsung.pl – `INSTALACJA` + `OdZysk` | darmowa instalacja (kod `INSTALACJA`); **do 500 zł zniżki** za oddanie starego urządzenia | tylko sklep samsung.pl | – | – | [samsung.com/pl/offer/cashback/promo/agd/2026](https://www.samsung.com/pl/offer/cashback/promo/agd/2026/), [odkup-agd](https://www.samsung.com/pl/offer/odkup-agd/) | średnia (opis) |
| **PAYBACK** | **MediaMarkt: 1 °P za każde 3 zł**. Partnerami są też **mediaexpert.pl, euro.com.pl, oleole.pl** (stawki na ich kartach to „°Punkt podstawowy” – nie odczytałem wartości) | trzeba wejść do sklepu **przez link z PAYBACK**, zalogowany użytkownik, akceptacja wszystkich cookies, punkty blokowane do ~30 dni | – | nie koliduje z cashbackiem producenta | [payback.pl/sklepy-online](https://www.payback.pl/sklepy-online), [media-markt](https://www.payback.pl/sklepy-online/media-markt) | wysoka (stawka MM), wartość punktu **niepotwierdzona** |
| euro.com.pl / OleOle! – kody AGD | wg `wymagania-AGD.md`: **pralka WW90CGC04DAE 1799 zł (kod do 07.12)**, **suszarka DV9MDG52A0AE 2489 zł (kod do 31.10)**; snippet: „kod 500 zł na kolejne zakupy”, „kod do 300 zł przy pralce/suszarce Beko” (wygasło 21.09.2026) | euro **blokuje boty (403)** – nie zweryfikowałem | 31.10 / 07.12.2026 | – | `wymagania-AGD.md` + snippety euro.com.pl | **niepotwierdzone (snippet)** |
| x-kom | raty **0% do 30 rat**, newsletter (kod po zapisie), „darmowa dostawa do salonów” | brak akcji AGD producenta w naszym zakresie | – | – | [x-kom.pl/promocje](https://www.x-kom.pl/promocje) | wysoka (opis) |
| Morele / Avans / Neonet / Sferis | **nie zweryfikowano** – brak dostępu do stron akcji (404 / 403 / brak połączenia) | – | – | – | – | brak danych |

### C. Czego NIE ma (żeby nie szukać drugi raz)

- **Whirlpool nie obejmuje:** zmywarek (W7I HT58 T), mikrofalówki **W7 MD440 NB** (nie ma jej w załączniku 1), lodówek Samsunga. Piekarnik **WOI7A8FHT2SBA** jest w promocji, ale tylko **350 zł** (a WOI7P8FHT1SBA – 750 zł).
- **Samsung nie obejmuje lodówki BRB70F30BES0EO** (wzorzec!). Obejmuje BRB80F30ADS0EO/ADF0EO i BRB80F26*.
- **Bosch nie obejmuje pralek** – tylko suszarki i pralko-suszarki. Czyli za WGG244ZEPL nie ma żadnego zwrotu.
- **MediaMarkt nie ma w zestawach** ani wzorcowego piekarnika (WOI7A8FHT2SBA), ani płyty WBS2560NE, ani pary Samsung, ani okapu Amica, ani zmywarki Beko – czyli „duży” zestaw w MediaMarkcie da się zbudować tylko na WOI7P8FHT1SBA + W7I HT58 T + BRB80F30ADS0EO.
- **Kupon Allegro −100 zł na AGD klasy A** (z raportu allegro.pl) – ważność niepewna, może kończyć się **26.10**. Nie łączy się z Allegro Pay.
- **UWAGA – wygasłe, nie próbuj:** Media Expert `lp,k-4449-pralka-50-proc-taniej` (kod `K-4449`, „Promocja zakończona”, akcja do 04.10.**2025**) i `lp,27514-bosch-pralka-50proc-taniej` (kod `P-27514`, zakończona 30.10.2025). Strony nadal są w Google i wyglądają na aktualne — **nie działają**. Aktywny odpowiednik to **Neonet** (kod `SAMSUNG50`/`BOSCH50`, do 31.10.2026).

---

## 1. Piekarnik

MUST: para · szuflada/zbiornik na wodę · termosonda · hydroliza · teleskopy na 2 poziomach · termoobieg

| Model | Typ | Cena (źródło) | Akcja producenta | Kody sklepu | Cena po akcjach (netto) | Lepsze/gorsze vs wzorzec | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WOI7A8FHT2SBA** | wzorzec | 3399 zł (Allegro, `niepotwierdzone`; 3499 zł euro / 3599 zł whirlpool.pl wg raportu Allegro) | **Whirlpool 350 zł** (wymaga 2. produktu Whirlpool, np. płyty) | Media Expert `RW0110-3110` do 31.10 (jeśli produkt oznaczony) | 3399 − 350 = **3049 zł** (z płytą, patrz §3) | – | [regulamin](https://whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spok%C3%B3j-zaczyna-si%C4%99-od-m%C4%85drych-decyzji-2.pdf) |
| **Whirlpool WOI7P8FHT1SBA** | **odrzucona — MUST ✗** | 3399 zł (Allegro `niepotwierdzone`; 3399 euro, 3419 whirlpool.pl) | **Whirlpool 750 zł** | jak wyżej | **NIE — 1 poziom teleskopów** | Klasa **A++**, SousVide, ale **teleskopy tylko na 1 poziomie** (ME/Ceneo) → nie spełnia MUST; nie kupować mimo wyższego cashbacku | [whirlpool.pl](https://www.whirlpool.pl/piekarnik-elektryczny-do-zabudowy-whirlpool-kolor-czarny-woi7p8fht1sba-859991686550/p) |
| Whirlpool WOI11P8FHT2SBAF | alternatywa | brak ceny w tym raporcie | 750 zł | – | – | wyższa półka, ta sama kwota zwrotu | – |
| Samsung NV7B5660RAK/U2 | alternatywa przez zestaw | brak ceny w tym raporcie | **Samsung 300 zł** (NV7B5660* jest na liście) | Media Expert **K-5239** (płyta za 1 zł w zestawie z zmywarką Samsung) | – | MUST **do potwierdzenia** (termosonda, hydroliza, teleskopy) – Samsung zwykle ma pyrolizę, nie hydrolizę | [lp K-5239](https://www.mediaexpert.pl/lp,k-5239-plyta-za-1-zl) |

**Wniosek:** promocje nie zmieniają rankingu MUST. WOI7P8FHT1SBA ma wyższy cashback (750 vs 350 zł), ale **teleskopy tylko na 1 poziomie** → **nie spełnia MUST** i nie może być podstawą koszyka. Zostaje wzorzec WOI7A8FHT2SBA (350 zł) + płyta (200 zł) + mikrofalówka (200 zł) = **750 zł** cashbacku.

## 2. Lodówka do zabudowy

| Model | Typ | Cena (źródło) | Akcja producenta | Kody sklepu | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|---|
| **Samsung BRB70F30BES0EO** | wzorzec | 3105,80 zł (Allegro `niepotwierdzone`; 3279 Ceneo) | **BRAK** – nie ma jej w załączniku 1 Samsunga | `ME1610-311026` / `ME2210-311026` (jeśli produkt jest oznaczony kodem) | **3105,80 zł** | kupując wzorzec **tracisz 300 zł** cashbacku | [samsung cashback](https://cashbackagd.samsung.pl/) |
| **Samsung BRB80F30ADS0EO** | **alternatywa+ (rekomendowana ze względu na cashback)** | 3649–3699 zł (Allegro `niepotwierdzone`) | **Samsung 300 zł** | + ZestawoMania / urodziny MM (do 25.10) | **≈3349–3399 zł** | klasa **D** (183 kWh/rok) vs E (229) → ok. −45 kWh/rok; Power Cool/Freeze. Różnica do wzorca po cashbacku: **+243…+293 zł** | [regulamin](https://images.samsung.com/is/content/samsung/assets/pl/regulaminy_2026/Regulamin_promocji_Cashback_DA_1.10-30.11.2026_15.09.2026.pdf) |
| Samsung BRB80F30ADF0EO | alternatywa | 3673–4298 zł (Allegro `niepotwierdzone`) | 300 zł | – | – | zwykle drożej od ADS0 | – |
| BRB80F26* (ACS0EO/ADS0EO/ACF0EO/ADF0EO/BDF0EO) | alternatywa | brak ceny | 300 zł | – | – | sprawdzić wysokość/pojemność – to inna półka cenowa | – |

## 3. Płyta indukcyjna

| Model | Typ | Cena (źródło) | Akcja producenta | Kody sklepu | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|---|
| **Whirlpool WB S2560 NE / WBS2560NE** | wzorzec (bez matu) | 1179 zł (Allegro `niepotwierdzone`; Ceneo 1298) | **Whirlpool 200 zł** (SKU 869991579680 jest w załączniku) | `RW0110-3110` do 31.10 (jeśli oznaczona) | **979 zł** (w zestawie z piekarnikiem) | Cashback tylko razem z piekarnikiem Whirlpool – czyli „przy okazji” | [regulamin](https://whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spok%C3%B3j-zaczyna-si%C4%99-od-m%C4%85drych-decyzji-2.pdf) |
| Whirlpool WLS2760BF/S | alternatywa | 1694 zł (Allegro `niepotwierdzone`) | 200 zł | – | 1494 zł | drożej; MUST (FlexiCook/Direct Access) do potwierdzenia | – |
| Samsung NZ64B5066GK/U2 | alternatywa | brak ceny | Samsung 200 zł | Media Expert `ME1610-311026`/`ME2210-311026` (do sprawdzenia) | – | nie opłaca się (wg raportu Allegro ~2350 zł) | [mediaexpert listing](https://www.mediaexpert.pl/agd-do-zabudowy/plyty-do-zabudowy/plyty-indukcyjne) |
| Electrolux EIV63440BW | alternatywa | 1725–1949 zł (Allegro `niepotwierdzone`) | **0 zł** (cashback Electrolux dotyczy pralnictwa) | voucher **K-5234** (400 zł na kolejne zakupy, wysyłka 12.2026) | – | voucher to nie rabat na tę płytę – realnie 0 zł | [lp K-5234](https://www.mediaexpert.pl/lp,k-5234-nawet-400zl-na-kolejne-zakupy) |

## 4. Okap teleskopowy

| Model | Typ | Cena (źródło) | Akcja | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|
| **Amica OTP6651BG** | wzorzec/najtańszy kandydat | **679 zł** (amica.pl, snippet; tyle samo Allegro wg raportu) | brak cashbacku producenta; **Amica200** lub **Wielorabaty** tylko przy koszyku ≥1500 zł / ≥2 produktów Amica | **679 zł** solo | 10 rat 0% na amica.pl | [amica.pl](https://www.amica.pl/okap-teleskopowy-60-cm-otp6651bg), [200za1500](https://www.amica.pl/200za1500-promocja) |
| Amica OMC5651B HC (meblowy, nie teleskop) | **nie spełnia MUST** (typ) | 1399 zł (amica.pl) | – | – | pokazany tylko jako element zestawu Amica do progu 1500 zł – **odpada jako okap** | – |
| Bosch DFS067K51 | alternatywa+ | brak ceny w tym raporcie (raport Allegro: 2449 zł) | brak | – | brak promocji producenta | – |

**Wniosek:** okap nie ma żadnego cashbacku. Jedyne realne obniżenie: **Amica200 −200 zł**, ale tylko jeśli dobierzesz drugi produkt Amica z innej kategorii za ≥821 zł (żeby suma ≥1500 i nie zmienił się piekarnik/płyta Whirlpool — bo wtedy tracisz 750/200 zł cashbacku Whirlpool). Realnie: **nie opłaca się**, chyba że i tak wybierzesz całą kuchnię Amica.

## 5. Mikrofalówka do zabudowy

| Model | Typ | Cena (źródło) | Akcja | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|
| **Whirlpool W7 MD440 NB** | kandydat | 1550 zł + dostawa od 199 zł = 1749 zł (Allegro `niepotwierdzone`; 2085 Ronat) | **BRAK** – nie ma jej w załączniku 1 Whirlpoola | **1749 zł** | nie łapie się na Whirlpool cashback; nie ma jej też w zestawach MM | [regulamin Whirlpool](https://whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spok%C3%B3j-zaczyna-si%C4%99-od-m%C4%85drych-decyzji-2.pdf) |
| **Whirlpool WMD7O4TB** | **alternatywa z cashbackiem** | ok. 2169 zł (agdmaniak, `niepotwierdzone`) | **Whirlpool 200 zł** (jest w załączniku) | **≈1969 zł** | droższa, ale 200 zł zwrotu; inne otwieranie (do dołu) | [agdmaniak](https://www.agdmaniak.pl/139054/uwaga-cashback-nawet-3000-zl-zwrotu-za-zakup-zestawu-whirlpool/) |
| **Bosch BFL554MB0** | alternatywa | 1435 zł (Allegro `niepotwierdzone`) | brak | **1435 zł** | talerz 31,5 cm (granica), czarne szkło, bez grilla. Nadal **najtańsza** opcja | – |

**Wniosek:** promocje nie pomagają w tej kategorii – W7 MD440 NB nie jest objęty niczym. Bosch BFL554MB0 zostaje najtańszy (o ok. 300 zł taniej niż Whirlpool po cashbacku).

## 6. Zmywarka do zabudowy

| Model | Typ | Cena (źródło) | Akcja | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|
| **Whirlpool W7I HT58 T** | wzorzec | 2297 zł (Allegro `niepotwierdzone`; 2438 z darmową dostawą) | **Whirlpool NIE obejmuje zmywarek**; **jest** w ZestawoMani i w urodzinach MediaMarktu (do 25.10) | **2297 zł** solo; **−36% / −30% w zestawie MM** | 10 lat na silnik po rejestracji (osobny program Whirlpoola) | [zestawomania](https://mediamarkt.pl/pl/specials/zestawomania) |
| **Beko MEDIN3755A** | alternatywa+ | 2498 zł (Allegro `niepotwierdzone`) | brak cashbacku; jest **5 lat ochrony serwisowej Beko** (1.04–31.12.2026), ale **przy zakupie z meblami kuchennymi** | 2498 zł | AutoDose, zawiasy przesuwne, 40 dB | [programatorbeko.pl](https://www.programatorbeko.pl/) |
| Whirlpool WH8IA15AM3TUS0 | alternatywa+ | 2998–3519,99 zł (Allegro `niepotwierdzone`) | kupon Allegro −100 zł (klasa A, ≥2500 zł) – ważność niepewna | 2898 zł (jeśli kupon działa) | klasa A, AquaStop, zawiasy ślizgowe | [raport allegro.pl](allegro.pl.md) |
| Bosch (np. SMV4EVX00E) | alternatywa | brak ceny | **Bosch cashback zmywarki** (1.09–15.11.2026, do 700 zł) | – | jedyna kategoria, gdzie Bosch daje zwrot na zmywarki | [bosch-home.pl](https://www.bosch-home.pl/pl/mkt-category/zmywanie) |

## 7. Pralka + suszarka

**Ważne:** ta kategoria jest najbardziej „promocyjna” w całym koszyku.

| Model | Typ | Cena (źródło) | Akcja | Netto | Uwagi | Link |
|---|---|---|---|---|---|---|
| **Samsung WW90CGC04DAE (EO)** | wybrana pralka | **1799 zł** (euro, wg `wymagania-AGD.md`, kod do 07.12) / 1899 zł (Allegro `niepotwierdzone`) | **Samsung 200 zł** | **1599 / 1699 zł** | kod musi być na konkretną ofertę | [cashback](https://cashbackagd.samsung.pl/) |
| **Samsung DV9MDG52A0AE (EO)** | wybrana suszarka | **2489 zł** (euro, kod **do 31.10**) / 2479 zł (Allegro) | **Samsung 200 zł** | **2289 / 2279 zł** | jeśli kod euro wygasa 31.10 – decyzja do soboty | – |
| **Razem para Samsung + SKK-DD** | – | 4288 + 227 (łącznik, Allegro `niepotwierdzone`) | **−400 zł** cashback | **≈4115 zł** | Łącznik zwykle nie jest objęty promocjami | – |
| **Samsung para w Neonet (kod `SAMSUNG50`)** | **największa dźwignia w tym koszyku** | ceny Neonetu nieznane (403); licząc na cenach referencyjnych: 2489 + 1799 = 4288 zł | **−50% ceny pralki** = −**899,50 zł** + **−400 zł** cashback Samsunga | **≈2988 zł** (+ łącznik) | Warunek: **oba modele na liście „PRALKA ZA PÓŁ CENY”** na `neonet.pl/lp/pralka-za-pol-ceny` – tego nie potwierdziłem. Regulamin: 15.10–31.10.2026, nie łączy się z innymi rabatami Neonetu | [regulamin](https://cdn-prod.neonet.pl/static-pages-assets/244/onlineregulaminpromocjipralkazapcenyprzyzakupiesuszarki.pdf) |
| Zestaw Samsung (gotowy) | odrzucone | 5299 zł (Allegro) | −400 zł | 4899 zł | **drożej o ~780 zł** niż osobno | [raport allegro](allegro.pl.md) |
| Bosch WGG244ZEPL | alternatywa | 2399 zł (Allegro `niepotwierdzone`) | **0 zł – pralki nie są w promocji Bosch** | 2399 zł | – | [regulamin suszarek](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) |
| **Bosch WQG245DEPL** | alternatywa | **3299 zł** (Allegro `niepotwierdzone`) – **w progu 2999–3498,99** | **Bosch 500 zł** | **2799 zł** | ⚠️ jeśli kod obniży cenę **poniżej 2999 zł → zwrot spada do 400 zł**; poniżej 2499 → 200 zł | – |
| Bosch WQH245B0PL | alternatywa | brak ceny | 500 zł przy cenie 2999–3498,99 | – | AutoDry, samoczyszczący skraplacz | – |
| Bosch zestaw MM −30% pralki | **nie dotyczy** | – | tylko WGG242ZKPL/WGG256ZTPL/WAN2425MPL/WAN2827LPL/WGH2460XPL | – | naszej pary **nie ma** na liście | [regulamin MM](https://cms-assets.mmst.eu/4lyxhctxrf55/4sQlrfGzwFmch9xqGeIfA3/4d9bc82ff783ef16f755032df6af05c3/7955_Regulamin_Pralka_i_suszarka_Bosch_w_zestawie_taniej_o_30-_wartosci_pralki.pdf) |

**Porównanie po promocjach:** Samsung para = **≈4115 zł** (z łącznikiem; w Neonet z `SAMSUNG50` **≈3215 zł** z łącznikiem) · Bosch para = 2399 + 2799 + 260 (WTZ27400) = **5458 zł** (w Neonet z `BOSCH50` **4258,50 zł**). Bez kodu Neonet różnica **≈1343 zł** i cashback Boscha tego nie wyrównuje; z kodem `BOSCH50` różnica spada do **≈143 zł** i wtedy Bosch jest realną opcją (samoczyszczący skraplacz, 61 dB, AutoDry) — **o ile oba modele są na liście Neonetu**.

---

## Koszyk w tym sklepie

Raport dotyczy promocji **ponad sklepami**, więc „koszyk” = koszyk referencyjny z cenami z innych raportów, z nałożonymi cashbackami. **Ceny bazowe są niepotwierdzone na żywo** (patrz kolumna Źródło).

| # | Kategoria | Model | Cena bazowa | Źródło ceny | Promocja | Netto |
|---|---|---|---|---|---|---|
| 1 | Piekarnik | Whirlpool WOI7P8FHT1SBA | 3399 zł | Allegro (snippet) | −750 zł (Whirlpool) | 2649 zł |
| 2 | Lodówka | Samsung BRB80F30ADS0EO | 3649 zł | Allegro (snippet) | −300 zł (Samsung) | 3349 zł |
| 3 | Płyta | Whirlpool WB S2560 NE | 1179 zł | Allegro (snippet) | −200 zł (Whirlpool, w zestawie z piekarnikiem) | 979 zł |
| 4 | Okap | Amica OTP6651BG | 679 zł | amica.pl (snippet) | brak | 679 zł |
| 5 | Mikrofalówka | Bosch BFL554MB0 | 1435 zł | Allegro (snippet) | brak | 1435 zł |
| 6 | Zmywarka | Whirlpool W7I HT58 T | 2297 zł | Allegro (snippet) | brak (Whirlpool nie obejmuje zmywarek) | 2297 zł |
| 7 | Pralka | Samsung WW90CGC04DAE | 1799 zł | euro (wg wymagań, kod) | −200 zł (Samsung) | 1599 zł |
| 8 | Suszarka | Samsung DV9MDG52A0AE | 2489 zł | euro (wg wymagań, kod do 31.10) | −200 zł (Samsung) | 2289 zł |
| 9 | Łącznik | Samsung SKK-DD | 227 zł | Allegro (snippet) | brak | 227 zł |
| | **Razem** | | **17 153 zł** | | **−1650 zł** | **15 503 zł** |

Dostawa: w większości ofert Allegro/Smart! darmowa; euro – zwykle darmowa od progu; mikrofalówka Allegro „od 199 zł” (+199 zł, jeśli ta oferta). **Braki w tym koszyku:** brak informacji o dostawie/wniesieniu w euro (403) i brak kodów dla Media Expert/Morele na konkretne modele.

**Czy opłaca się kupować całość w jednym sklepie?** Nie. Optymalnie: piekarnik+płyta Whirlpool w jednym miejscu (warunek cashbacku Whirlpool – choć regulamin pozwala na różne transakcje, piekarnik musi być zarejestrowany pierwszy, a resztę masz 3 dni), Samsung osobno (dowolne sklepy), reszta tam, gdzie najtaniej. **Uwaga:** Samsung wymaga „jednego zakupu u jednego sprzedawcy” tylko dla *zestawu*; pojedyncze urządzenia możesz kupić w różnych sklepach (kwoty i tak się sumują: 200+200+300).

---

## Tabela do porównania

| kategoria | model | cena | dostawa | promocja netto | MUST | url |
|---|---|---|---|---|---|---|
| piekarnik | Whirlpool WOI7A8FHT2SBA (wzorzec) | 3399 zł* | darmowa* | −350 zł (Whirlpool, z 2. produktem) | ✓ | [whirlpool.pl](https://www.whirlpool.pl/) |
| piekarnik | Whirlpool WOI7P8FHT1SBA | 3399 zł* | darmowa* | **−750 zł** | ✓ (teleskopy do potwierdzenia) | [whirlpool.pl](https://www.whirlpool.pl/piekarnik-elektryczny-do-zabudowy-whirlpool-kolor-czarny-woi7p8fht1sba-859991686550/p) |
| lodówka | Samsung BRB70F30BES0EO (wzorzec) | 3105,80 zł* | darmowa* | **0 zł** (nie w promocji) | ✓ | [samsung.com](https://www.samsung.com/pl/) |
| lodówka | Samsung BRB80F30ADS0EO | 3649 zł* | ? | **−300 zł** | ✓ | [samsung cashback](https://cashbackagd.samsung.pl/) |
| płyta | Whirlpool WB S2560 NE | 1179 zł* | darmowa* | −200 zł (z piekarnikiem) | ✓ | [whirlpool.pl](https://www.whirlpool.pl/) |
| okap | Amica OTP6651BG | 679 zł* | ? | 0 zł (brak akcji) | dB do potwierdzenia | [amica.pl](https://www.amica.pl/okap-teleskopowy-60-cm-otp6651bg) |
| mikrofala | Whirlpool W7 MD440 NB | 1550 zł + 199 dostawa* | od 199 zł* | **0 zł** | ✓ | [whirlpool.pl](https://www.whirlpool.pl/) |
| mikrofala | Bosch BFL554MB0 | 1435 zł* | darmowa* | 0 zł | ✓ (talerz 31,5 cm) | [bosch-home.pl](https://www.bosch-home.pl/) |
| zmywarka | Whirlpool W7I HT58 T | 2297 zł* | darmowa* | 0 zł (Whirlpool nie obejmuje zmywarek) | ✓ | [whirlpool.pl](https://www.whirlpool.pl/) |
| zmywarka | Beko MEDIN3755A | 2498 zł* | darmowa* | 0 zł (5 lat serwisu przy meblach) | ✓ | [beko](https://www.beko.com/pl-pl) |
| pralka | Samsung WW90CGC04DAE | 1799 zł (euro, kod) | darmowa | **−200 zł**; w Neonet dodatkowo do **−50% ceny pralki** przy suszarce (do 31.10) | ✓ | [euro.com.pl](https://www.euro.com.pl/) |
| pralka | Bosch WGG244ZEPL | 2399 zł* | Smart!* | **0 zł** cashbacku; w Neonet `BOSCH50` do **−50% ceny pralki** | ✓ | [bosch-home.pl](https://www.bosch-home.pl/) |
| suszarka | Samsung DV9MDG52A0AE | 2489 zł (euro, kod do 31.10) | darmowa | **−200 zł** (warunek akcji Neonet: zakup w Neonet) | ✓ | [euro.com.pl](https://www.euro.com.pl/) |
| suszarka | Bosch WQG245DEPL | 3299 zł* | darmowa* | **−500 zł** (cena musi zostać ≥2999) | ✓ | [regulamin](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) |
| łącznik | Samsung SKK-DD | 227 zł* | Smart!* | 0 zł | zgodność do potwierdzenia | [samsung](https://www.samsung.com/pl/) |

`*` = cena/dostawa z migawek lub z innych raportów, **niepotwierdzone na żywo**.

---

## Jak maksymalnie obniżyć koszyk (scenariusze, wyliczone)

Podstawa: koszyk referencyjny z tabeli wyżej, **17 153 zł** brutto. Wszystkie kwoty cashbacków są **pewne** (regulaminy), ceny bazowe – nie.

**KOREKTA PO WERYFIKACJI MUST (25.10, 23:30):** scenariusze S2, S4 i S10 opierają się na piekarniku **WOI7P8FHT1SBA**, który ma **teleskopy tylko na 1 poziomie** (potwierdzone w Media Expert i Ceneo) → **nie spełnia MUST**. MediaMarkt nie ma piekarnika WOI7A8FHT2SBA, a jego ceny są wyższe niż w tym raporcie (BRB80F30ADS0EO **4449 zł**, nie 3649). Dlatego S2/S4/S10 są **odrzucone**. Realny najlepszy koszyk to euro.com.pl: 17 294 − 3000 (kod) − 1150 (cashbacki Whirlpool 750 + Samsung 400) = **13 144 zł** (13 082 zł z łącznikiem poza euro). Szczegóły: `zakup-optimal.md`.

**S0 – bez żadnych akcji:** 17 153 zł.

**S1 – same cashbacki producentów (minimalny wysiłek):**
Whirlpool: piekarnik WOI7A8FHT2SBA 350 + płyta 200 = **550 zł**
Samsung: pralka 200 + suszarka 200 = **400 zł**
→ **17 153 − 950 = 16 203 zł**

**S2 – piekarnik WOI7P8FHT1SBA zamiast wzorca (❌ ODRZUCONE — teleskopy 1 poziom):**
Whirlpool: 750 + 200 = **950 zł**; Samsung 400 zł → łącznie **1350 zł**
→ **17 153 − 1350 = 15 803 zł** (cena piekarnika ta sama wg migawek; **−400 zł** względem S1 bez dopłaty)

**S3 – S2 + lodówka z cashbackiem (BRB80F30ADS0EO):**
dopłata **+543 zł** (3649 vs 3105,80), zwrot **+300 zł**
→ **15 803 + 243 = 16 046 zł** → **gorzej o 243 zł** niż S2. Sensowne tylko jeśli chcesz klasę D i −45 kWh/rok.

**S4 – MediaMarkt, tylko dziś (25.10, do 23:59), aplikacja:**
W zestawie są tylko WOI7P8FHT1SBA, W7I HT58 T i BRB80F30ADS0EO.
- para: piekarnik 3399 + zmywarka 2297 → rabat **36% × 2297 = 827,32 zł**
- trójka: lodówka 3649 + piekarnik 3399 + zmywarka 2297 → rabat **36% × 3399 = 1223,64 zł**
  (regulamin: 36% ceny produktu „drugiego w kolejności od najwyższej”, czyli środkowego)
Do tego cashback Whirlpool 750 + 200 (płyta z innego sklepu, zarejestrowana ≤3 dni po piekarniku) i Samsung 300.
Licząc wariant trójki na cenach referencyjnych: 3649+3399+2297 = 9345 − 1223,64 = **8121,36 zł** za trzy sztuki, a po cashbackach (750+200+300 = 1250) **≈6871 zł**.
⚠️ Promocja **wygasa dziś o 23:59:59** i tylko w aplikacji; nie łączy się z ZestawoManią.

**S5 – kody Media Expert (jeśli modele są oznaczone kodem):**
`RW0110-3110` (Whirlpool, do 31.10 21:59) i `ME2210-311026` / `ME1610-311026` (do 31.10 23:59). Rabat jest **produktowy** – w zaobserwowanym przykładzie (lodówka Whirlpool) wynosił ok. **4,5%** ceny. Kod **nie łączy się z innym kodem**, ale **łączy się z cashbackiem producenta**. Kodów `AK2410-2510` (dziś) i `AK2510-2610`/`PAZ2310`/`RS2410-261026` (do 26.10) nie da się już przypisać do modeli bez listingu.

**S6 – Bosch zamiast Samsunga w pralni:**
WGG244ZEPL 2399 + WQG245DEPL 3299 + WTZ27400 260 = **5958 zł**; cashback **500 zł** (vs 400 zł Samsunga) → **5458 zł** vs **4115 zł** Samsunga. Bez kodu: **nie opłaca się** (+1343 zł), a promocja MediaMarktu „−30% pralki” **tej pary nie obejmuje**.
**Ale z kodem `BOSCH50` w Neonet** (50% ceny pralki = 1199,50 zł): 5958 − 1199,50 = 4758,50 − 500 = **4258,50 zł**, czyli tylko **+143 zł** vs Samsung. Przy tej różnicy Bosch (samoczyszczący skraplacz, 61 dB, AutoDry) staje się realną opcją — **pod warunkiem, że oba modele są na liście Neonetu**.

**S7 – Amica (okap) w zestawie:**
Okap 679 zł sam nie łapie progu. `Amica200` wymaga 2 produktów z różnych kategorii za ≥1500 zł. Dobranie płyty Amica w miejsce Whirlpool oznacza utratę 200 zł cashbacku Whirlpoola i zmianę modelu na taki, którego MUST (strefa łączona + suwak na strefę) nie mam potwierdzonego → **nie rekomenduję**.

**S8 – PAYBACK:** MediaMarkt **1 °P za 3 zł** → przy koszyku 9345 zł ok. 3115 °P. Wartości punktu w złotych nie potwierdziłem, więc **nie wliczam** do scenariuszy (rząd wielkości: ułamek procenta).

**S9 – raty 0%:** nie obniżają ceny, tylko rozkładają płatność (MediaMarkt/BNP: 3–50 rat, 300–20 000 zł, RRSO 0%; Media Expert 0% do 40 rat; x-kom do 30 rat; amica.pl 10 rat).

**S10 – scenariusz maksymalny („wszystko, co się da”) – ❌ ODRZUCONY, MUST ✗ – 13 380 zł:**
| Element | Gdzie | Cena | Rabat | Netto |
|---|---|---|---|---|
| lodówka BRB80F30ADS0EO | MediaMarkt, aplikacja | 3649 | −300 cashback | |
| piekarnik WOI7P8FHT1SBA | MediaMarkt, aplikacja | 3399 | −750 cashback | |
| zmywarka W7I HT58 T | MediaMarkt, aplikacja | 2297 | – | |
| *(razem MM)* | | **9345** | **−1223,64** (36% × 3399) | 8121,36 |
| płyta WB S2560 NE | dowolny sklep | 1179 | −200 cashback | 979 |
| okap OTP6651BG | amica.pl | 679 | – | 679 |
| mikrofalówka BFL554MB0 | dowolny sklep | 1435 | – | 1435 |
| pralka WW90CGC04DAE + suszarka DV9MDG52A0AE | Neonet, `SAMSUNG50` | 4288 | −899,50 (50% pralki) −400 cashback | 2988,50 |
| łącznik SKK-DD | Allegro | 227 | – | 227 |
| **RAZEM** | | **17 153** | **−3773,14** | **13 379,86** |

Założenia i ryzyka: (a) promocja MediaMarktu **kończy się dziś 23:59** i wymaga aplikacji + konta myMediaMarkt; (b) rabat 36% liczony od produktu „drugiego od najwyższej ceny” zgodnie z §4 ust. 2 i 4 regulaminu; (c) płyta z innego sklepu – piekarnik rejestrujesz jako pierwszy, płytę w ciągu 3 dni; (d) **lista modeli Neonetu niepotwierdzona (403)** – jeśli pary nie ma, scenariusz spada do 14 279,36 zł; (e) wszystkie ceny bazowe są `niepotwierdzone`.

**Ranking po korekcie MUST (ceny referencyjne):**
1. **euro.com.pl, 9 pozycji + `RKPROGAGD1026`** – **13 144 zł** netto po cashbackach (13 082 zł z łącznikiem poza euro). Termin kodu: 31.10.
2. **Ceneo mix (bez progu)** – **15 922 zł** po cashbackach (17 072 − 1150).
3. **Neonet, pełny MUST na alternatywach** – **15 429 zł** (para LKU4 łapie 500 zł cashbacku: 200+300).
4. **S3** – 16 046 zł (ale S3 bazuje na S2 → odrzucone przez piekarnik).
5. **S1** – 16 203 zł, jeśli nie chcesz rejestrować niczego.
6. **S2 / S4 / S10** – **odrzucone**: WOI7P8FHT1SBA ma teleskopy 1 poziom, a MediaMarkt nie ma zgodnego piekarnika; ceny MM są wyższe niż w S10.

---

## Wnioski

1. **Terminy układają się w drabinkę – decyzje trzeba podejmować natychmiast.** Dziś (25.10, 23:59) kończą się w MediaMarkcie „Urodziny – w zestawie taniej” (36% na drugi tańszy produkt, tylko aplikacja) i „ZestawoMania”; dziś wygasa też kod Media Expert `AK2410-2510`. **31.10** kończą się: kod `SAMSUNG50`/`BOSCH50` w Neonet (−50% ceny pralki), kody Media Expert `RW0110-3110`, `ME*-311026`, `R0110-311026`, zestaw Bosch w MediaMarkcie, płyta za 1 zł (K-5239) i kod na suszarkę Samsunga na euro.com.pl. **30.11** – Samsung cashback (rejestracja do 21.12), **31.12** – Whirlpool cashback (rejestracja do 14.01.2027) i Bosch (do 30.01.2027).
2. **Największa dźwignia to próg 16 000 zł w euro.com.pl** — 3000 zł rabatu plus 1150 zł cashbacków daje **13 144 zł** za komplet MUST. MediaMarkt 36% i Neonet 50% nie wygrywają: MM nie ma zgodnego piekarnika (P8 ma 1 poziom teleskopów, a BRB80 kosztuje 4449 zł, nie 3649 zł), a Neonet nie ma naszej pary Samsunga. Nie rozbijaj koszyka euro.
3. **Piekarnik: nie ma darmowej poprawy.** WOI7P8FHT1SBA ma **750 zł** cashbacku (vs 350 zł za wzorzec), ale **teleskopy tylko na 1 poziomie** → **MUST ✗**. Zostaje wzorzec; jego zestaw z płytą (200 zł) i mikrofalówką (200 zł) daje 750 zł cashbacku.
4. **Wzorce wypadają blado w promocjach.** Lodówka-wzorzec BRB70F30BES0EO **nie jest objęta** cashbackiem Samsunga (jest BRB80F30ADS0EO/ADF0EO za 300 zł), a mikrofalówka W7 MD440 NB **nie jest objęta** Whirlpoolem. Za to zmywarka Whirlpoola nie ma żadnego zwrotu (promocja Whirlpoola nie obejmuje zmywarek).
5. **Pułapki liczbowe:** (a) Whirlpool: nagroda >2000 zł w jednym zgłoszeniu → 10% podatku (3000 zł → 2700 zł na konto), więc duże zestawy lepiej dzielić na zgłoszenia ≤2000 zł; (b) Bosch: próg liczy się od **ceny po rabatach** — kod obniżający suszarkę WQG245DEPL poniżej 2999 zł kosztuje 100 zł cashbacku; (c) kody Media Expert **nie łączą się ze sobą**, ale łączą się z cashbackiem; (d) cashback = paragon/faktura **bez NIP kupującego**; (e) zwrot towaru (14 dni) odbiera prawo do zwrotu pieniędzy.
6. **Dystrybucja i marketplace:** Samsung wymaga kodów z końcówką **EO** (sprzęt wprowadzony do obrotu przez Samsung Polska) — oferty „wersja niemiecka” nie kwalifikują się. Whirlpool i Bosch dopuszczają każdy sklep detaliczny (także sprzedawcę marketplace), ale promocje **samego MediaMarktu i Media Expert wykluczają produkty Marketplace/Outlet** — czyli rabat sklepu i cashback producenta trzeba planować osobno.
7. **Programy lojalnościowe są marginalne:** PAYBACK daje w MediaMarkcie 1 °P za 3 zł (wartość punktu do sprawdzenia), a karty typu Clubcard nie mają tu zastosowania. Jedyne „duże” dodatki to raty 0% (płynność, nie rabat) i usługi: MediaMarkt „wniesienie + montaż + odbiór starego + 3 lata gwarancji” (do 31.10) oraz −50% na usługi w Media Expert Konto Plus.
8. **Promocje koszykowe nie biją 3000:** WIEL/5. za 1 zł (podział 4+3+2) = −2 656,09 zł; drugi −40% (Whirlpool Days) = **0 zł** na naszym koszyku (lista obejmuje tylko płytę; teoret. max −1 459,20 zł); 50/500 = −1 700 zł, ale nie łączy się z kodem 3000; MM 36% = −3 299,76 zł nominalnie, lecz koszyk 16 612,23 zł. Szczegóły: `koszyk-promocje.md`.
