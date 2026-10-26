# Skan promocji koszykowych AGD — 25.10.2026

> **Snapshot sprzed decyzji 26.10.2026 (WBS2560NE + LFP326FW).** Aktualny wybór: CIV634 + LFG716R; koszyk netto 16 193,25 / 15 663,44 — patrz `README.md`. Poniższe sumy są historyczne.

**KOREKTA (25.10, 23:55):** Whirlpool Days „−40%” **nie obejmuje** WOI7A8FHT2SBA, W7I HT58 T ani WMD7O4TX — na naszym koszyku rabat = **0 zł** (kwalifikuje się tylko płyta, brak drugiego produktu). ME `K-5227` ma listę 40 produktów Whirlpoola bez naszych modeli → **0 zł**. Kwoty −920 / −479,60 w tabeli są teoretyczne; nie dotyczą naszego koszyka. Aktualny ranking: `koszyk-promocje.md`.

Zakres: „drugi produkt −40%”, „drugi −50%”, „3. −55%”, „4. −80%”, „5. produkt za 1 zł / darmo”, „płyta za 1 zł”, „500 za 2000”.
Koszyk odniesienia (euro.com.pl / OleOle!, ceny brutto, 25.10.2026): **17 293,99 zł**, kod `RKPROGAGD1026` → **−3 000 zł** = 14 293,99 zł; po cashbackach (Whirlpool 750 + Samsung 400) **13 143,99 zł**.

## Jak czytać kolumnę „pewność”

- **wysoka** — przeczytany regulamin PDF albo strona promocji odczytana dziś.
- **średnia** — mechanika z ≥2 niezależnych agregatorów (Pepper/Picodi/Rabatio/Goodie) + tytuł strony sklepu; regulamin sklepu niedostępny.
- **niepotwierdzone (snippet)** — jeden snippet, brak regulaminu, nie wliczać do budżetu.

Ograniczenia dostępu (nie obchodzone): `euro.com.pl`, `oleole.pl`, `neonet.pl` → **HTTP 403** (Akamai) na wszystkich stronach HTML, także `/cms/`. PDF-y z euro bywają dostępne, ale link do regulaminu „wielosztuk” nie jest publikowany na stronach, do których mam dostęp. Media Expert: strony LP i karty produktów czytają się, ale `curl` na karty dostaje 403 — karty czytałem narzędziem tekstowym, emblematy **potwierdzone na żywo**.

---

## Tabela główna

| Promocja | Sklep | Mechanika | Ważność | Czy pasuje do naszego koszyka | Szacowany rabat na naszym koszyku | Źródło | Pewność |
|---|---|---|---|---|---|---|---|
| **Wielosztuki — „5. produkt za 1 zł”** (kod `WIEL` / `IEL`) | euro.com.pl / OleOle! | Min. **2 różne** produkty z listy. Rabat liczony **na najtańszy produkt zestawu**: 2 produkty → **−30%**, 3 → **−55%**, 4 → **−80%**, 5+ → **najtańszy za 1 zł**. Jedna transakcja = jeden rabat. | **do odwołania**; kod wg Pepper „wygasa za 11 dni” (≈05.11.2026) | **TAK — 9/9 pozycji** (ta sama baza produktowa co promocja progowa) | **−2 656,09 zł** przy podziale **4+3+2** (patrz niżej) → 14 637,90 zł | [euro.com.pl/cms/piaty-za-1-zl.bhtml](https://www.euro.com.pl/cms/piaty-za-1-zl.bhtml) (tytuł: „piąty **najtańszy** produkt za 1 zł”), [Pepper](https://www.pepper.pl/kupony/euro.com.pl) (kod sprawdzony, „zadziałał użytkownikom przy kasie”), [Rabatio](https://rabatio.com/sklepy/rtv-euro-agd), [Goodie](https://goodie.pl/okazje/rtv-euro-agd/do-80-lub-5-produkt-za-1-zl-2026-03-04-wazna-do-odwolania) | **średnia** (strona 403; 4 źródła zgodne co do progów, 1 rozbieżność co do „najtańszy” vs „5. w koszyku”) |
| **Multirabaty** (kod `k-4173`, dla 5+ `k-4173-1ZL`) | Media Expert | Min. **2 różne** produkty **z listy promocyjnej**. Rabat na **najtańszy** Produkt promocyjny w transakcji: 2 → −30%, 3 → −55%, 4 → −80%, **5+ → najtańszy za 1 zł**. Max **1 szt. modelu**; różne kolory = osobna sztuka. Wyłączone: **Outlet** i sprzedawcy inni niż Media Expert. **Nie łączy się z innymi promocjami ani kodami** (§5 ust. 7). | **18.04.2025 – do odwołania** (bez daty końcowej) | **CZĘŚCIOWO — tylko 3 pozycje mają emblemat**: piekarnik WOI7A8HT2SBA ✓, płyta WBS0060NE ✓, zmywarka W7I HT58 T ✓. **Okap Amica OTP6651BG — BRAK emblematu** (sprawdzone dziś), lodówka/pralka/suszarka/łącznik — brak. Dodatkowo ME **nie ma** piekarnika z „F” (WOI7A8FHT2SBA) ani płyty WB S2560 NE 1:1. | **−659,45 zł** (3 produkty: −55% × 1 199 zł płyta) przy cenach ME 4 429,99 + 2 299 + 1 199 | [regulamin.pdf](https://www.mediaexpert.pl/lp/promocje/piaty-produkt-1zl/regulamin.pdf) — **przeczytany w całości**, [LP](https://www.mediaexpert.pl/lp,piaty-produkt-1zl), emblematy na kartach (dziś) | **wysoka** |
| **Multirabaty 36% — „drugi tańszy produkt 36% taniej”** (kod `K-5245`) | Media Expert | Min. **2 różne** produkty z załącznika nr 1; rabat **36% ceny drugiego, tańszego** produktu. Tylko **aplikacja** (w salonie trzeba zeskanować kartę klienta z apki). 1 szt. modelu. Wyłączone: Outlet. **Nie łączy się z innymi promocjami** (§6 ust. 6). | **20.10.2026 12:00 – 25.10.2026 23:59** (**dziś**) | Częściowo — zależy od załącznika; nasze modele Samsung/Whirlpool są w ME tylko jako warianty (WOI7A8HT2SBA, WBS0060NE, W7I, DAH/AEEO) | Para najdroższych: 4 429,99 + 3 299 → **−1 187,64 zł**. Realnie, bez dodatkowych zakupów, poniżej `K-5241` | [LP](https://www.mediaexpert.pl/lp,k-5245-drugi-tanszy-36-proc-taniej) + [regulamin.pdf](https://www.mediaexpert.pl/lp/promocje/k-5245-drugi-tanszy-36-proc-taniej/regulamin.pdf) — **przeczytany** | **wysoka** (mechanika), **średnia** (lista załącznika) |
| **„Drugi produkt Whirlpool −40%”** | euro.com.pl | Koszyk: **2 produkty Whirlpool** z listy → **−40% na drugi, tańszy**. Bez minimum kwotowego. | **wygasa jutro** (26.10.2026); Picodi podaje kod do 27.10.2026 | **TAK** — mamy 4 urządzenia Whirlpool (piekarnik 3499, zmywarka 2299,99, mikrofalówka 1698, płyta 1348) | **−920,00 zł** (para piekarnik + zmywarka: 40% × 2 299,99) | [Pepper](https://www.pepper.pl/kupony/euro.com.pl) (kod sprawdzony przez redakcję 5 dni temu), [Picodi](https://www.picodi.com/pl/rtveuroagd) | **średnia** (brak regulaminu; strona 403) |
| **Whirlpool Days — „płyta −50% przy piekarniku”** | euro.com.pl | Kup **piekarnik Whirlpool** z oferty → **50% zniżki na płytę indukcyjną** z oferty. Kod w koszyku. | **wygasa jutro** (26.10.2026); Picodi: kod do 27.10.2026 | **Prawdopodobnie TAK**: piekarnik 3499 + płyta WB S2560 NE 1348 (przynależność płyty do listy — `niepotwierdzone`) | **−674,00 zł** (50% × 1 348) | [Pepper](https://www.pepper.pl/kupony/euro.com.pl) („Przy zakupie piekarnika Whirlpool objętego promocją otrzymujesz 50% zniżki na płytę indukcyjną”), [Picodi](https://www.picodi.com/pl/rtveuroagd) | **średnia** (mechanika), **niepotwierdzone** (model płyty) |
| **„Pralka −50% przy suszarce”** (Whirlpool Days / `K-5241`) | euro.com.pl, Media Expert | Zestaw **suszarka + pralka** (euro: Whirlpool; ME: Samsung/Bosch/Electrolux/Hisense/Gorenje) → **−50% ceny pralki**. | euro: wygasa 26.10.2026; ME `K-5241`: **do 31.10.2026 23:59** | **TAK w ME** (pralka 2 299,99 → 1 149,99), **NIE w euro** (nasza pralka jest Samsung, promocja euro dotyczy Whirlpoola) | euro: 0 zł; ME: **−1 150,00 zł** — ale wymaga pralki ME (DAH) w cenie 2 299,99 | [Pepper](https://www.pepper.pl/kupony/euro.com.pl), [Picodi ME](https://www.picodi.com/pl/media-expert), raport `mediaexpert.pl.md` (LP `k-5241`) | **średnia** |
| **„Drugi tańszy sprzęt AGD Whirlpool −40%”** | Media Expert | **2 różne produkty Whirlpool** z listy → **−40% na tańszy**. Kategorie: lodówki, pralki, zmywarki, płyty, okapy, kuchenki (**piekarników nie ma na liście**). Kod w koszyku. | **do 26.10.2026** | Częściowo: mamy zmywarkę W7I (2 299) i płytę WBS0060NE (1 199); **piekarnik poza listą** | **−479,60 zł** (40% × 1 199) | [Picodi ME](https://www.picodi.com/pl/media-expert) | **średnia** |
| **ZestawoMania** (plakietka „5 produkt za 1zł!”) | MediaMarkt | **2 → −30% / 3 → −55% / 4 → −80% / 5 → najtańszy za 1 zł**, rabat **na najtańszy produkt zestawu**, jedna transakcja wiązana, lista dużego AGD / AGD do zabudowy / RTV. Nie łączy się z akcją urodzinową. | **19.10.2026 16:00 – 25.10.2026 23:59:59** (**dziś**) | **NIE 1:1** — MM nie ma 8 z 12 naszych kodów; tylko zamienniki (m.in. WOI11P8FHT2SBAF, BRB80F30ADS0EO) | ≈ **−2 534 zł** na koszyku zamienników (wg `mediamarkt.pl.md`) | [mediamarkt.pl/pl/specials/zestawomania](https://mediamarkt.pl/pl/specials/zestawomania) (odczytane dziś), regulamin + aneks (przeczytany w `mediamarkt.pl.md`) | **wysoka** (mechanika), **średnia** (kwota) |
| **Akcja urodzinowa −36% / −28%** („drugi produkt −36%”) | MediaMarkt | Zestaw **2–6 różnych** produktów z załącznika; rabat = **36% ceny produktu drugiego od najwyższej ceny** (w aplikacji; na stronie 28%). **Można łączyć wielokrotnie** — osobne transakcje → koszyk 9 pozycji rozbity na **4 zamówienia**. | **15.10–25.10.2026 23:59:59** (**dziś**) | **NIE 1:1** (tylko zamienniki); lista obejmuje 9/9 pozycji *ich* koszyka | **−3 299,76 zł** — **jedyna mechanika z nominalnym rabatem > 3 000 zł**, ale koszyk MM to 19 911,99 zł → 16 612,23 zł (vs nasze 13 143,99 zł netto) | [regulamin 36%](https://mediamarkt.pl/pl/specials/zestawomania), `mediamarkt.pl.md` (regulaminy przeczytane 25.10) | **wysoka** (mechanika), **średnia** (kwota, dostępność modeli) |
| **„50 zł za każde wydane 500 zł”, max 2 000 zł** | euro.com.pl | Rabat **50 zł / 500 zł** koszyka na wybrane produkty, **limit 2 000 zł**. Kod w koszyku. | do **03–04.11.2026** (Pepper/Rabatio: 03.11; Picodi: 04.11) | Prawdopodobnie TAK (jeśli wszystkie pozycje są „wybrane”) | **−1 700 zł** (34 × 50 zł; limit 2 000 zł nie wiąże) | [Pepper](https://www.pepper.pl/kupony/euro.com.pl), [Rabatio](https://rabatio.com/sklepy/rtv-euro-agd), [Picodi](https://www.picodi.com/pl/rtveuroagd) | **średnia** (wcześniejsza edycja wygasła 12.10 — obecna edycja potwierdzona tylko agregatorami) |
| **„Płyta za 1 zł”** (kod `K-5239` / `1ZL`) | Media Expert, euro.com.pl | Koszyk: **piekarnik Samsung + zmywarka Samsung** z listy → **płyta Samsung za 1 zł**. | **do 31.10.2026 23:59** | **NIE** — nie mamy piekarnika ani zmywarki Samsung | 0 zł (nie da się złożyć warunku bez wymiany 2 pozycji) | raport `promocje.md` (LP `k-5239`), [Picodi](https://www.picodi.com/pl/rtveuroagd) (kod `1ZL`) | **średnia** |
| **„500 za 2000”** (rabat progowy Whirlpool) | sklepy Whirlpool / oficjalny | 500 zł rabatu za każde 2 000 zł koszyka. Na kartach produktów aktywne klastry `500za2000` (płyta WB S2560 NE, zmywarka W7I HT58 T). | **nieznana** — lista `/regulaminy-promocji` kończy się na 2024 | Prawdopodobnie TAK (klastry sprzedażowe na 2 naszych kartach) | hipotetycznie **−2 000 zł** (koszyk Whirlpoola 8 845,99 zł → 4 × 500) | [whirlpool.pl/regulaminy-promocji](https://www.whirlpool.pl/regulaminy-promocji) | **niepotwierdzone (snippet)** — brak regulaminu bieżącej edycji, nie wliczać |
| **Amica „Wielorabaty”** | amica.pl | Min. **2 produkty z różnych kategorii**; rabat na najtańszy: 2 → −30%, 3 → −55%, 4 → −80%, 5 → −99%. Od cen regularnych. | **21.10 – 03.11.2026** | **NIE** — z koszyka tylko okap OTP6651BG (679 zł na amica.pl); brak drugiej kategorii Amica | 0 zł (samo okap nie spełnia minimum 2 kategorii) | raport `ceneo-i-producenci.md` / `promocje.md` (strona amica.pl) | **wysoka** (mechanika), dotyczy tylko amica.pl |
| **Samsung „MULTI” (multirabaty)** | samsung.pl | −30% na 2., −55% na 3., −80% na 4., **5. za 1 zł** (rabat na najtańszy), produkty z **różnych grup**. | „do wypowiedzenia przez Organizatora” | **NIE** — mamy 4 produkty Samsung (lodówka, pralka, suszarka, łącznik), próg to 5 | 0 zł (o 1 produkt za mało) | [samsung.com/pl/offer/promocja-agd](https://www.samsung.com/pl/offer/promocja-agd/) | **średnia** |
| **Neonet „Multirabaty w zestawie” + `SAMSUNG50`/`BOSCH50`** | neonet.pl | Progi/stawki **nieznane**; −50% dotyczy pralki w zestawie z suszarką (Samsung/Bosch). | −50%: do **31.10.2026** (wg `promocje.md`) | **niepotwierdzone** — dzisiaj 403 na wszystkich stronach Neonetu | nieznany | [neonet.pl/promocje](https://www.neonet.pl/promocje) — **403** | **niepotwierdzone (snippet)** |
| **„Drugi produkt AGD do zabudowy −35%” w Neonet** | neonet.pl | 2 produkty z listy → −35% na drugi | **WYGASŁA** — artykuł z 2022 r. („ponad rok temu”, cashback 2022) | nie dotyczy | 0 zł | [agdmaniak.pl/83491](https://www.agdmaniak.pl/83491/drugi-produkt-agd-taniej-neonet/) | **wysoka** (że nieaktualna) |

---

## Ile realnie wychodzi na naszym koszyku

Reguła wspólna dla „5. za 1 zł” w euro i ME/MM: rabat dostaje **jeden** produkt na transakcję — **najtańszy w zestawie**. To odwraca intuicję: im więcej pozycji w jednym zamówieniu, tym *mniejszy* rabat (bo najtańszy jest coraz tańszy). Dlatego 9 pozycji w jednym koszyku daje **−248 zł** (łącznik 249 zł → 1 zł), a nie −1 348 zł.

**Podział na zestawy (dozwolony, każdy zestaw = osobna transakcja, min. 2 różne produkty):**

| Grupowanie | Rabat |
|---|---|
| **4 + 3 + 2** (optymalne) — {piekarnik, lodówka, suszarka, zmywarka} −80% × 2 299,99; {pralka, mikrofalówka, płyta} −55% × 1 348; {okap, łącznik} −30% × 249 | **−2 656,09 zł** → 14 637,90 zł |
| 2+2+2+2+1 — cztery pary −30% (na 3 299 / 2 299,99 / 1 348 / 249) | **−2 373,00 zł** → 14 920,99 zł |
| 5 + 4 — 5 najdroższych (pralka 1 799 za 1 zł) + 4 pozostałe −80% × 249 | **−1 997,20 zł** → 15 296,79 zł |
| 9 w jednej transakcji | **−248,00 zł** → 17 045,99 zł |

**Wniosek liczbowy: maksimum „5. za 1 zł” na naszym koszyku to −2 656,09 zł — o 343,91 zł mniej niż kod `RKPROGAGD1026` (−3 000 zł).** Przewaga kodu progowego jest niewielka, ale nie da się jej odwrócić podziałem na więcej zestawów (9 produktów to za mało na dwa zestawy po 5).

Ryzyko prawne podziału: ME zakazuje „wielokrotnych, pojedynczych zakupów” (§5 ust. 4a) — trzy zamówienia po 4/3/2 produkty to nie „pojedyncze zakupy”, ale przy 3 zamówieniach w jednym dniu sklep może prowadzić postępowanie wyjaśniające. Euro: regulamin niedostępny, zasada „jedna transakcja = jeden rabat” wynika z opisów agregatorów.

---

## Łączenie z kodem 3 000 zł i z cashbackami

| Promocja | Z `RKPROGAGD1026` (3 000 zł) | Z cashbackiem producenta |
|---|---|---|
| euro „Wielosztuki / 5. za 1 zł” | **NIE** — to drugi kod koszykowy. Kod progowy „może łączyć się z innymi kodami, ale nie z drugim kodem koszykowym tej samej transakcji” (Zasady stosowania kodów euro). | TAK — paragon/faktura bez zmian, cashback Samsung/Whirlpool liczony od zakupu modelu |
| ME Multirabaty `k-4173` | **NIE** — §5 ust. 7 regulaminu: „nie łączy się z innymi promocjami… w szczególności z innymi akcjami wymagającymi podania kodu rabatowego” | TAK (karta produktu nie traci kwalifikacji; ale ME nie ma naszych wzorców) |
| ME `K-5245` −36% | **NIE** — §6 ust. 6: „nie łączy się z innymi promocjami równolegle obowiązującymi” | TAK |
| ME `K-5241` −50% pralki | **NIE** (dwa kody) | TAK |
| euro Whirlpool −40% / Whirlpool Days −50% płyta | **NIE** (własny kod) | **TAK i to jest najciekawsze**: rabat nie usuwa piekarnika z koszyka, więc warunek cashbacku Whirlpoola (piekarnik + drugie urządzenie) dalej jest spełniony. [INFERENCE z warunków cashbacku — nie ma kontrwarunku „cena nie może być obniżona”] |
| MM ZestawoMania / urodziny | **NIE** (inny sklep, inny mechanizm) | TAK, o ile model jest na liście cashbacku (MM ma inne warianty: AHEO/AEEO) |
| euro „50 zł / 500 zł” | **NIE** (drugi kod koszykowy) | TAK |

**Cashbacki są jedyną warstwą, która realnie się dokłada** do dowolnego rabatu sklepowego — bo rozlicza je producent, nie sklep. Uwaga: cashback Whirlpoola wymaga piekarnika **i** drugiego urządzenia Whirlpoola z listy (płyta / mikrofalówka do zabudowy / lodówka; **zmywarki nie wchodzą**), a cashback Samsunga — pralki i suszarki z końcówką **EO** (nasze modele: WW90CGC04DAE 200 zł, DV9MDG52A0AEEO 200 zł; lodówka BRB70F30BES0EO **nie jest** na liście).

---

## Werdykt

1. **Żadna promocja koszykowa na NASZYM koszyku nie bije 3 000 zł.** Najmocniejsza alternatywa to euro „5. za 1 zł” z podziałem 4+3+2 → **−2 656,09 zł** (0,88 × kodu progowego). Wszystko inne jest wyraźnie słabsze: −1 700 zł (50/500), −1 187 zł (`K-5245`), −1 150 zł (`K-5241`), −920 zł (Whirlpool −40%), −674 zł (płyta −50%), −659 zł (ME Multirabaty).
2. **Jedyna mechanika z nominalnym rabatem > 3 000 zł to akcja urodzinowa MediaMarktu −36%** (−3 299,76 zł), ale tylko dlatego, że pozwala **wielokrotnie** powtarzać rabat w osobnych transakcjach i tylko na **zamiennikach** (MM nie ma 8 z 12 naszych kodów). Po podliczeniu koszyk MM = 16 612,23 zł, czyli **+3 468 zł drożej** niż nasze 13 143,99 zł netto. Rabat większy, cena końcowa gorsza.
3. **Łączenie: nie istnieje.** Każda z tych promocji wymaga własnego kodu, a regulaminy ME (§5.7, §6.6) i zasady kodów euro wprost wykluczają równoległe akcje kodowe. Wybór jest binarny: **albo 3 000 zł, albo mechanika koszykowa** — nigdy oba.
4. **Cashbacki łączą się ze wszystkim** (1 150 zł: Whirlpool 750 + Samsung 400) i nie zależą od tego, którym kodem zbijesz cenę. To potwierdza, że nie warto wymieniać 3 000 zł na 2 656 zł „dla zasady”.
5. **Największe ryzyko w tym skanie:** brak regulaminu euro „wielosztuk” (403). Tytuł strony mówi „piąty **najtańszy**”, a Pepper opisuje „piąty produkt **w koszyku**” za 1 zł. Gdyby działała wersja Peppera, kolejność pozycji w koszyku mogłaby dać rabat do −3 498 zł (piekarnik jako 5. pozycja) i wtedy **pokonałaby kod progowy**. Tego **nie wolno** planować bez regulaminu — traktuj jako ciekawostkę, nie oszczędność.

## Czego nie udało się potwierdzić

- Regulamin euro „wielosztuki” (`euro.com.pl/cms/piaty-za-1-zl.bhtml` → 403; nie znalazłem linku do PDF). Wszystkie liczby dla euro opierają się na tytule strony + 3 agregatorach.
- Regulaminy promocji Whirlpoola w euro (−40% drugi produkt, Whirlpool Days −50%) — tylko opisy Peppera/Picodi; **data 26 vs 27.10 jest sporna**.
- Czy płyta **WB S2560 NE** jest na liście „wybranych płyt” Whirlpool Days (decyduje o −674 zł).
- „500 za 2000” Whirlpoola — brak jakiegokolwiek regulaminu bieżącej edycji.
- Neonet (403) i lista załącznika `K-5245` — bez dostępu; liczby dla ME policzone na modelach zamiennych.
- Kwoty cashbacku Whirlpoola dla WOI7A8FHT2SBA / WB S2560 NE / W7 MD440 NB (strona LP 403) — w raporcie używam 750 zł z briefu, nie z regulaminu.
