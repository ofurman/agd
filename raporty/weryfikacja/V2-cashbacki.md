# V2: weryfikacja cashbacków producentów (runda 2)

**Data weryfikacji:** 2026-10-25.
**Metoda:** pobrałem regulaminy PDF przez `curl` i odczytałem je przez `pdftotext`. Numery stron to strony PDF. Raportów rundy 1 nie traktowałem jako źródła.

Pobrane i przeczytane dokumenty:

| Skrót | Dokument | Strony |
|---|---|---|
| **[S]** | Samsung, Regulamin Cashback DA 1.10–30.11.2026 (PDF z 16.09.2026) — [PDF](https://images.samsung.com/is/content/samsung/assets/pl/regulaminy_2026/Regulamin_promocji_Cashback_DA_1.10-30.11.2026_15.09.2026.pdf) | 20 |
| **[W]** | Whirlpool „Spokój zaczyna się od mądrych decyzji” (PDF z 28.08.2026) — [PDF](https://whirlpool-promocja.pl/storage/1/REGULAMIN_WHIRLPOOL_Spok%C3%B3j-zaczyna-si%C4%99-od-m%C4%85drych-decyzji-2.pdf) | 16 |
| **[BS]** | Bosch, suszarki i pralko-suszarki „Jakość LikeABosch” — [PDF](https://media3.bosch-home.com/Documents/29538572_260728_Promocja_suszarek_pralko-suszarek_marki_Bosch_pazdziernik_2026.pdf) | 11 |
| **[BG]** | Bosch, urządzenia do gotowania „Zyskaj do 3000 zł” — [PDF](https://media3.bosch-home.com/Documents/29490128_260825_Regulamin_Promocja_urzadzen_do_gotowania_marki_Bosch_Zyskaj_do_3000zl_zwrotu_na_konto.pdf) | 9 |
| **[H]** | Haier „Otrzymaj zwrot do 5 000 zł” — [PDF](https://www.promocja-haier.pl/docs/2026.08.24_Haier_regulamin_Odbierz_cashback_jesien_zima_2026.pdf) | 17 |
| **[E]** | Electrolux „płaci Twoje rachunki” 1.10–13.12.2026 — [PDF (kopia na Neonet)](https://cdn-prod.neonet.pl/static-pages-assets/232/20260928electrolux_promocja_1102026-13122026_electrolux_rachunki_jesie.pdf) | 12 |

---

## 1. Tabela: model → akcja → kwota → status

Legenda: ✅ model jest w załączniku i kwota jest potwierdzona · ❌ modelu nie ma w akcji · ⚠️ objęty warunkowo (kwota zależy od ceny albo jest ryzyko kodu lub sklepu).

### Samsung, Cashback AGD 1.10–30.11.2026 [S], załącznik nr 1, s. 11–17

| Model | Kwota | Status | Źródło (strona, cytat) |
|---|---|---|---|
| WW90CGC04DAEEO | **200 zł** | ✅ | [S] s. 16: „WW90CGC04DAEEO 200 zł” |
| **WW90CGC04DAHEO** (wariant H, Neonet/ME/MM/Avans) | **200 zł** | ✅ | [S] s. 16: „WW90CGC04DAHEO 200 zł” |
| WW90CGC04DTHEO | 200 zł | ✅ | [S] s. 16 |
| WW90CGC04DABEO | 200 zł | ✅ | [S] s. 15 |
| DV9MDG52A0AEEO | **200 zł** | ✅ | [S] s. 17: „DV9MDG52A0AEEO 200 zł” |
| DV90DG52A0AEEO | **200 zł** | ✅ | [S] s. 17: „DV90DG52A0AEEO 200 zł” |
| **DV90DG52A0TEEO** | **200 zł** | ✅ | [S] s. 17: „DV90DG52A0TEEO 200 zł” |
| **DV90DG52A0AHEO** | **300 zł** (o 100 zł więcej niż AE) | ✅ | [S] s. 16: „DV90DG52A0AHEO 300 zł” |
| DV90DG52A0ABEO | 300 zł | ✅ | [S] s. 16 |
| **BRB70F30BES0EO** (wzorzec) | **0 zł** | ❌ | [S] s. 11–12: brak w załączniku. Tabela lodówek zawiera tylko serię BRB80F… |
| **BRB80F30ADS0EO** | **300 zł** | ✅ | [S] s. 12: „BRB80F30ADS0EO 300 zł” |
| BRB80F30ADF0EO | 300 zł | ✅ | [S] s. 12 |
| BRB80F30BDS0EO (litera **D**, nie E) | 300 zł | ✅ | [S] s. 12: „BRB80F30BDS0EO 300 zł” |
| **BRB80F30BES0EO** | **0 zł** | ❌ | [S] s. 12: brak. Jest tylko BRB80F30**BD**S0EO. |
| BRB80F26ACS0EO / ADS0EO / ACF0EO / ADF0EO / BDF0EO | 300 zł | ✅ | [S] s. 12 |

**Warunki Samsunga (z regulaminu):**

- **Termin zakupu.** Od 1.10.2026 00:01 do 30.11.2026, albo do wyczerpania puli 2 480 000 zł ([S] s. 3–4, s. 6).
- **Rejestracja.** Do **21.12.2026** na cashbackagd.samsung.pl, z kontem Samsung Account ([S] s. 3–4). Wypłata do 8.02.2027 ([S] s. 4, s. 7).
- **Sklepy.** „Punkt Handlowy” to „sklep … prowadzący sprzedaż detaliczną … w tym sklep internetowy” w Polsce, a także samsung.com/pl ([S] s. 2). Nie ma listy zamkniętej ani wykluczeń. Neonet, Media Expert, MediaMarkt, RTV Euro AGD i Avans kwalifikują się (✅).
  - **Allegro** nie jest wymienione ani wykluczone (⚠️). Kwalifikuje się tylko wtedy, gdy sprzedawca wystawi paragon albo fakturę imienną z widocznym NIP sklepu ([S] s. 6). Towar musi być „wprowadzony do obrotu przez Organizatora” w Polsce ([S] s. 2 i s. 5), czyli z polskiej dystrybucji z kodem …EO. Import nie przejdzie.
- **Jeden sprzedawca czy kilku.** Pojedyncze produkty mogą pochodzić z różnych sklepów ([S] s. 5: „Produkty mogą być zakupione w różnych Punktach Handlowych”). Zestaw, czyli 2–6 produktów w jednym zgłoszeniu, musi pochodzić od jednego sprzedawcy, z jednego zakupu ([S] s. 2). Kwota za zestaw to suma kwot z załącznika, bez premii za sam zestaw ([S] s. 2).
- **Limity zgłoszeń.** Najwyżej 4 zgłoszenia i najwyżej 5 produktów w jednym zgłoszeniu ([S] s. 5).
- **Opinia.** Co najmniej 200 znaków, z hasztagami #OpiniaZaCashbackwPromocji i #PromocjaSamsungUrzadzeniaAGDQ42026 ([S] s. 1). Można ją opublikować na samsung.com, na stronie sprzedawcy albo w porównywarce.
- **Wymagane załączniki.** Zdjęcie tabliczki znamionowej i dowód zakupu bez NIP kupującego ([S] s. 6).
- **Odstąpienie od umowy** (zwrot towaru w 14 dni) oznacza utratę prawa do zwrotu ([S] s. 5).
- **Łączenie z kodami sklepowymi.** Regulamin nie zawiera zakazu łączenia (⚠️, brak zapisu wprost). Kwota zależy tylko od modelu, więc kod sklepowy jej nie zmienia.
- **Podatek.** Gross-up 11,11% ([S] s. 7), więc wypłata nie jest pomniejszana.

> **Praktyczne:** sklepy często podają kod bez „EO” (np. „WW90CGC04DAH”, „DV90DG52A0AH”). W regulaminie liczy się pełny kod z tabliczki: **…DAHEO** / **…AHEO**. Przed zakupem warto sprawdzić EAN albo pełny kod na karcie produktu.

### Whirlpool „Spokój zaczyna się od mądrych decyzji” [W], załącznik nr 1, s. 10–15

| Model | Kategoria | Kwota | Status | Źródło (strona, cytat) |
|---|---|---|---|---|
| **WOI7A8FHT2SBA** (wzorzec) | piekarnik | **350 zł** | ✅ | [W] s. 12: „WOI7A8FHT2SBA Piekarniki do zabudowy 350 zł” |
| **WOI7P8FHT1SBA** | piekarnik | **750 zł** | ✅ | [W] s. 12: „WOI7P8FHT1SBA Piekarniki do zabudowy 750 zł” |
| **WOI11P8FHT2SBAF** | piekarnik | **750 zł** | ✅ | [W] s. 12: „WOI11P8FHT2SBAF Piekarniki do zabudowy 750 zł” |
| WOI7A8HT2SBA (bez F) | piekarnik | 350 zł | ✅ | [W] s. 12 |
| **WB S2560 NE** (= WBS2560NE) | płyta | **200 zł** | ✅ | [W] s. 13: „WBS2560NE Płyty indukcyjne 200 zł” |
| WBS2560NEBM | płyta | 200 zł | ✅ | [W] s. 14 |
| **WMD7O4TX** | mikrofalówka | **200 zł** | ✅ | [W] s. 11: „WMD7O4TX Mikrofalówki do zabudowy 200 zł” |
| **WMD44MB** | mikrofalówka | **200 zł** | ✅ | [W] s. 11: „WMD44MB Mikrofalówki do zabudowy 200 zł” |
| **WMD44MX** | mikrofalówka | **200 zł** | ✅ | [W] s. 11: „WMD44MX Mikrofalówki do zabudowy 200 zł” |
| W7 MD440 NB | mikrofalówka | 0 zł | ❌ | [W]: brak w załączniku |
| **W7I HT58 T** | zmywarka | 0 zł | ❌ | [W] s. 1, pkt 1.4: akcja obejmuje tylko „piekarników …, płyt …, mikrofalówek … oraz lodówek” |
| okapy (wszystkie) | okap | 0 zł | ❌ | [W] s. 1, pkt 1.4 (jak wyżej) |

**Warunki Whirlpoola (z regulaminu):**

- **Zestaw.** Trzeba kupić **co najmniej 2 produkty, w tym obowiązkowo piekarnik** ([W] s. 1, pkt 1.5). Zestaw bez piekarnika nie daje zwrotu.
- **Liczba produktów.** W jednym zgłoszeniu płatny jest najwyżej 1 produkt z każdej kategorii (piekarnik, płyta, mikrofalówka, lodówka), czyli najwyżej 4 produkty. Przy dwóch produktach z tej samej kategorii liczy się tańszy cashback (pkt 3.14, s. 6).
- **Limity kwot.** Najwyżej **3000 zł** na zgłoszenie (pkt 4.1, s. 7) i najwyżej 3 zgłoszenia (pkt 3.13). Pula wynosi 1 500 000 zł (pkt 4.3).
- **Terminy.** Zakup od 1.09 do **31.12.2026** (pkt 1.6). Zgłoszenia do **14.01.2027** (pkt 1.8).
  - Piekarnik trzeba zarejestrować **w ciągu 14 dni od daty zakupu** z dowodu zakupu (pkt 1.9).
  - Pozostałe produkty trzeba zarejestrować **w ciągu 3 dni od rejestracji piekarnika** (pkt 3.10). Produkty dokupione po rejestracji piekarnika muszą zdążyć w tym 3-dniowym oknie (pkt 1.6).
  - Produkt kupiony przed 1.09.2026 się nie liczy (s. 5, przykład).
- **Sklepy.** „Wszystkie sklepy stacjonarne i internetowe” w Polsce (pkt 1.10, s. 2). Allegro, Neonet, ME, MM i Euro kwalifikują się. Produkty mogą pochodzić z różnych sklepów i być na różnych dowodach zakupu.
- **Dowód zakupu i opinia.**
  - Dowód zakupu: paragon albo faktura bez NIP kupującego (pkt 3.2.2).
  - Opinia **osobno dla każdego produktu**, z hasztagiem #PromocjaZyskajSpokój (pkt 3.2.3). Publikuje się ją na stronie sklepu, jeśli sklep ma sekcję opinii, albo w dowolnej porównywarce.
- **Łączenie z innymi akcjami.** Dowodu zakupu nie można zgłosić w innych równoległych akcjach Beko/Whirlpool na te same kategorie (pkt 8.6, s. 10). Zakazu łączenia z kodami sklepowymi nie ma, a kwota jest stała, niezależna od ceny.
- **Podatek** (pkt 4.5, s. 7–8). Do nagrody powyżej 2000 zł „przypisana jest dodatkowa nagroda” przeznaczona na 10% podatku. To mechanizm gross-up, więc uczestnik dostaje pełną kwotę.

### Bosch [BS], [BG]

| Model | Akcja | Kwota | Status | Źródło (strona, cytat) |
|---|---|---|---|---|
| **WQG245DEPL** | suszarki [BS] | zależy od ceny: przy 2999–3498,99 zł **500 zł**, przy 2499–2998,99 zł **400 zł** | ✅ na liście / ⚠️ kwota zależy od ceny | [BS] s. 11, poz. „WQG245DEPL”; próg ceny: s. 1, pkt 1.4 |
| **WQG244CSPL** | suszarki [BS] | przy 2999,00 zł (Avans) **500 zł**. Każdy kod obniżający cenę poniżej 2999 zł daje **400 zł** | ✅ / ⚠️ | [BS] s. 11, poz. „WQG244CSPL” |
| **WQG243DKPL** | suszarki [BS] | według tabeli progów (200–1000 zł) | ✅ / ⚠️ | [BS] s. 11, poz. „WQG243DKPL” |
| **WGG244ZEPL** | pralka | 0 zł | ❌ | [BS] pkt 1.4 obejmuje tylko „suszarek i pralko-suszarek”. Na bosch-home.pl/promocje dla pralek jest tylko 10-letnia gwarancja na silnik. |
| **WGG244Z0PL** | pralka | 0 zł | ❌ | jak wyżej |
| (piekarnik, płyta, mikrofalówka, okap Bosch, np. DFS067K51) | gotowanie [BG] | progi od łącznej ceny: 1299–2599,99 zł → 200 zł; 2600–3999,99 zł → 400 zł; 4000–5999,99 zł → 600 zł; dalej do 3000 zł | ✅ kategoria objęta (lista kategorii, bez listy modeli) | [BG] s. 1: kategorie, w tym „okapy”. Zmywarek i pralek tam nie ma. |

**Warunki Boscha:**

- **Suszarki [BS].**
  - Zakup od 01.10 do 31.12.2026 ([BS] pkt 1.5), zgłoszenie do **30.01.2027** (pkt 3.5). Pula wynosi 2,5 mln zł.
  - Premia zależy od „ostatecznej ceny … po uwzględnieniu wszystkich … rabatów” (s. 1). **Kod sklepowy łączy się z akcją, ale obniża próg ceny.**
  - Wykluczone są tylko sklepy prowadzone bezpośrednio przez BSH (pkt 2.5). Inne sklepy w Polsce, w tym Allegro przy paragonie, kwalifikują się.
  - Wymagana opinia z #opiniamotywowanapromocją.
  - ⚠️ Przy zestawie pralka + suszarka próg liczy się od ceny suszarki **widocznej na dowodzie zakupu**. Gdy sklep rozbije cenę zestawu, suszarka może spaść poniżej 2999 zł.
- **Gotowanie [BG].**
  - Zakup od 1.10 do 31.12.2026. „Jeden zakup” to urządzenia kupione w ciągu 30 dni.
  - Zgłoszenie w ciągu 30 dni od ostatniego zakupu, najpóźniej do 30.01.2027 (s. 2, s. 5).
  - Wykluczone są sklepy prowadzone bezpośrednio przez organizatora (s. 4).

### Inne marki (tylko akcje, które istnieją)

| Marka / akcja | Kandydaci z raportów | Kwota | Status | Źródło |
|---|---|---|---|---|
| **Haier** „Otrzymaj zwrot do 5 000 zł” [H], 21.09–31.12.2026 | lodówka EHBQW5519ECM, zmywarka XI 6B0S3FSB, piekarnik H6 ID2P5B5EYTB: **wszystkie trzy są w zał. 1** | od łącznej ceny **min. 2 urządzeń Haier**: 3800–6499,99 zł → 400 zł; 6500–9499,99 zł → 800 zł; … ≥21 000 zł → 5000 zł | ⚠️ | [H] s. 12, 14, 16 (modele). Warunek co najmniej 2 urządzeń: s. 1. Termin: s. 4 („Akcja rozpoczyna się w dniu 21.09.2026”). **Sklepy tylko: Media Expert i RTV Euro AGD**, bez outletów (zał. 2, s. 17). Rejestracja w ciągu 14 dni od zakupu, #PromocjaOpiniaHaier. **Neonet, MediaMarkt i Allegro się nie kwalifikują.** |
| **Electrolux/AEG** „płaci Twoje rachunki” [E], 1.10–13.12.2026 | piekarniki EOD4P57H / EOD6F77WZ, okapy LFP326FB / LFP616X / LFP626AK itd. | od łącznej wartości zakupu (jednorazowo, min. 1500 zł): 1500–1999,99 zł → 200 zł; 2000–2999,99 zł → 300 zł; 3000–3999,99 zł → 400 zł; 4000–5999,99 zł → 500 zł … | ⚠️ | [E] s. 1: kategorie, „wszystkie Produkty z następujących kategorii: płyty, piekarniki…”, w tym okapy. Zgłoszenia do 20.12.2026. **Wypłata jako opłacenie 1–5 rachunków** (prąd, gaz, internet…), nie przelew dowolnej kwoty. **Sklepy tylko z listy** (s. 1–2): Euro/OleOle, Media Expert/Avans/electro.pl, Neonet/neo24, MediaMarkt, Kakto, Elektrohome, electrolux.pl, Sferis, studia kuchenne. **Allegro się nie kwalifikuje.** |
| Gorenje | GV663B65, NRKI519D61WF, BM251M2BG | – | ❌ cashbacku brak | Jest tylko „Satysfakcja gwarantowana” (1.06–31.12.2026). To zwrot pieniędzy po oddaniu produktu, nie cashback. Źródło: [satysfakcjagorenje.pl](https://satysfakcjagorenje.pl/), wynik wyszukiwania, PDF nieczytany. |
| Beko | MEDIN3755A, BM3T49249W, BDIN38542P | – | ❌ (nie znaleziono aktywnej akcji) | Ostatnia polska akcja (SpacePro, lodówki) trwała do 13.09.2026. Teraz są tylko sklepowe kody rabatowe. |
| Amica | OTP6651BG | – | ❌ cashbacku brak | Są tylko rabaty na amica.pl („Amica200”, „Wielorabaty”), bez zwrotu od producenta. |

---

## 2. Sprzeczności w raportach rundy 1 i rozstrzygnięcie

1. **Czy BRB70F30BES0EO jest objęta cashbackiem Samsunga?** **Nie.**
   - [S] zał. 1 (s. 11–12) nie zawiera ani BRB70F30BES0EO, ani żadnego BRB70.
   - Raport allegro.pl.md też podaje „BRB70F30BES0EO nie ma na liście” (wiersz cashbacku oraz pkt 257/276/305). Sugestię, że „jest”, mogła dać tylko ogólna informacja Spider's Web o lodówkach „do 1200 zł”, a ta nie dotyczy tego modelu.
   - **Rozstrzygnięcie: 0 zł.**
2. **BRB80F30BES0EO jako tańsza alternatywa z cashbackiem** (morele/avans: „funkcjonalnie ten sam”).
   - Model BES0EO **nie jest na liście**. Na liście jest **BRB80F30BDS0EO** (300 zł) i **BRB80F30ADS0EO** (300 zł).
   - Uwaga na jedną literę: E i D to różne modele.
3. **Wariant H pralki: WW90CGC04DAH(EO)** (Avans: „niepotwierdzone”, koszyk-4-sklepy: „prawdopodobnie”).
   - **Potwierdzony, 200 zł** ([S] s. 16). Tak samo WW90CGC04DTHEO.
4. **Suszarki DV90DG52A0AH(EO) i DV90DG52A0TEEO.**
   - Obie są na liście. **AHEO daje 300 zł**, czyli więcej niż AEEO i DV9M (po 200 zł). **TEEO daje 200 zł.**
   - Żaden raport rundy 1 nie podał 300 zł dla AHEO.
5. **WOI7P8FHT1SBA i WOI11P8FHT2SBAF** (Avans: „nie występują w widocznej części listy”).
   - **Oba są na liście, po 750 zł** ([W] s. 12).
   - Zamiana wzorca WOI7A8FHT2SBA (350 zł) na jeden z nich daje **+400 zł** cashbacku.
6. **Kwoty Whirlpoola dla WOI7A8FHT2SBA i WB S2560 NE** (allegro: „nie znalazłem”).
   - **Potwierdzone: 350 zł i 200 zł.**
7. **Mikrofalówka.**
   - **WMD7O4TX, WMD44MB i WMD44MX są na liście, po 200 zł.** Raport zakup-optimal (WMD7O4TX 200 zł) jest poprawny.
   - W7 MD440 NB nie ma na liście.
8. **Podatek Whirlpoola** (promocje.md: „3000 zł → 2700 zł na konto”).
   - **Prawdopodobnie błędne.** Pkt 4.5 przypisuje *dodatkową* nagrodę na pokrycie 10% podatku (gross-up), więc nagroda główna nie jest pomniejszana.
   - Dla naszego koszyka (750–1150 zł) to i tak nie ma znaczenia.
9. **Whirlpool „wprost łączy się z kodami sklepowymi”** (koszyk-euro.md).
   - Regulamin **nie ma takiego zdania**. Jest tylko brak zakazu, a pkt 8.6 zakazuje łączenia z innymi akcjami Beko/Whirlpool.
   - Efekt praktyczny jest ten sam: kod sklepowy nie zmienia kwoty.
10. **Samsung: „łączy się ze wszystkimi innymi promocjami”** (ceneo-i-producenci.md, cytat z samsung.com).
    - **Nie potwierdzam.** Strona akcji z 25.10 nie ma tego zdania, a regulamin milczy.
    - Brak zakazu łączenia, ale także brak zgody wprost (⚠️).
11. **Samsung: zestaw u jednego sprzedawcy.** Raporty piszą to ogólnie, ale regulamin rozróżnia dwa przypadki:
    - Produkty zgłaszane pojedynczo mogą pochodzić z **różnych sklepów** ([S] s. 5).
    - Wymóg „jeden sprzedawca, jeden zakup” dotyczy tylko zgłoszenia w formie Zestawu.
    - Kwota jest taka sama (suma kwot modeli), więc pralkę i suszarkę **można kupić w dwóch różnych sklepach**.
12. **Bosch pralki** (WGG244ZEPL / WGG244Z0PL). Raporty zgodnie podają brak cashbacku i to się potwierdza ([BS] pkt 1.4: tylko suszarki i pralko-suszarki).
13. **Bosch WQG244CSPL** (avans: „niepotwierdzone”). **Jest na liście** ([BS] s. 11). Przy cenie 2999 zł daje 500 zł, ale każdy rabat obniża premię do 400 zł.
14. **Haier i Electrolux.**
    - Runda 1 nie sprawdziła listy sklepów. Obie akcje mają **zamkniętą listę sklepów**:
      - Haier: tylko Media Expert i RTV Euro AGD.
      - Electrolux: lista z [E], bez Allegro.
    - Nagroda Electroluxa to opłacenie rachunków, a nie przelew.

---

## 3. Wnioski dla koszyka

**Najtańsza para z cashbackiem: WW90CGC04DAHEO i DV90DG52A0AHEO.**
- Samsung za pralkę i suszarkę daje 400 zł przy wariantach AE/DV9M.
- Przy suszarce **DV90DG52A0AHEO** daje **500 zł**. Ta para ma kody wariantu H, czyli tańsze oferty w Neonet, ME i MM.
- Warunek: zakup do **30.11**, rejestracja do **21.12**.

**Lodówka.**
- Wzorzec BRB70F30BES0EO nie ma cashbacku.
- Zwrot 300 zł dają tylko BRB80F30**ADS0EO**, **ADF0EO**, **BDS0EO** oraz BRB80F26*.

**Whirlpool.**
- **WOI7A8FHT2SBA (350 zł) + WBS2560NE (200 zł) + WMD7O4TX lub WMD44MB/MX (200 zł) = 750 zł.**
- Z WOI7P8FHT1SBA lub WOI11P8FHT2SBAF zamiast WOI7A8FHT2SBA: **1150 zł**.
- Zmywarka i okap nic nie dają.
- **Pilnuj 14 dni od zakupu piekarnika i 3 dni na dorejestrowanie reszty.**

**Bosch WQG244CSPL / WQG245DEPL / WQG243DKPL.**
- Kwota zależy od ceny na paragonie: 400 zł poniżej 2999 zł, 500 zł od 2999 zł.
