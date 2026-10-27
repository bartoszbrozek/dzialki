---
type: synthesis
domain: dzialki-siepraw
created: 2026-10-27
updated: 2026-10-27
sources: ["[[dzialki-siepraw]]"]
tags: [weryfikacja, lint]
aliases: ["raport weryfikacji", "weryfikacja 2026-10-27"]
---

# Raport weryfikacji wiki – 27.10.2026

Ta strona opisuje sprawdzenie całej wiki o działkach 2834/8, 2834/9 i 2834/11. Celem było usunąć nieprawdę, niedopowiedzenia i sprzeczności między stronami.

## Cel i metoda

Każdy pakiet stron przeszedł 3 kroki:

1. **Weryfikator** – czytał każde stwierdzenie i porównywał je ze źródłem pierwotnym: tekstem MPZP XIV/110/25, ustawami i rozporządzeniami (ISAP, ELI), opinią geotechniczną, mailem i ofertą Z57, danymi GIS (ULDK, KIUT, NMT), stronami urzędów i TAURON.
2. **Sceptyk** – próbował obalić każde zgłoszenie. Zgłoszenie bez dowodu odrzucał.
3. **Korektor** – wprowadzał tylko potwierdzone poprawki. Na każdej zmienionej stronie dodał tag `zweryfikowane-2026-10-27` i sekcję „Weryfikacja”.

Po 12 pakietach odbyła się runda 2: **audyt spójności** (czy strony mówią to samo) i **audyt kompletności** (czego brakuje kupującym).

Zasada pisania po weryfikacji: fakt ze źródła ma źródło. Wniosek agenta ma oznaczenie „Wniosek:”. Rzecz niepotwierdzona ma oznaczenie „do sprawdzenia”.

## Wyniki w liczbach

| Pakiet | Strony | Sprawdzone stwierdzenia | Zgłoszone | Potwierdzone | Poprawione | Odrzucone |
|---|---|---|---|---|---|---|
| MPZP – ogólne | [[dzs-mpzp-uchwala]], [[dzs-mpzp-definicje]], [[dzs-mpzp-ustalenia-ogolne]] | 172 | 17 | 17 | 17 | 0 |
| MPZP – tereny | [[dzs-mpzp-teren-mn]], [[dzs-mpzp-teren-mn-u]], [[dzs-mpzp-infrastruktura-i-komunikacja]] | 168 | 12 | 12 | 12 | 0 |
| Warunki techniczne | [[dzs-warunki-techniczne-odleglosci]] | 96 | 9 | 9 | 9 | 0 |
| Geotechnika | [[dzs-opinia-geotechniczna]], [[dzs-warunki-gruntowe]] | 132 | 10 | 10 | 10 | 0 |
| Działki | [[dzs-dzialka-2834-8]], [[dzs-dzialka-2834-9]], [[dzs-dzialka-2834-11]] | 186 | 12 | 12 | 12 | 0 |
| GIS i uzbrojenie | [[dzs-dane-gis-i-3d]], [[dzs-uzbrojenie-terenu]] | 152 | 18 | 16 | 16 | 2 |
| Dokumenty i planer | [[dzs-dokumenty-i-linki]], [[dzs-planer-dzialki-dom]] | 115 | 16 | 15 | 15 | 1 |
| Urzędy i dostawcy | [[dzs-urzad-gminy-siepraw]], [[dzs-starostwo-myslenice]], [[dzs-dostawcy-mediow]], [[dzs-z57-real-estate]] | 168 | 16 | 15 | 15 | 1 |
| Formalności | [[dzs-procedura-budowy]], [[dzs-koszty-zakupu-i-podatki]] | 112 | 24 | 23 | 23 | 1 |
| Transakcja | [[dzs-oferta-i-mail-z57]], [[dzs-transakcja]], [[dzs-harmonogram]] | 72 | 11 | 11 | 11 | 0 |
| Hub i FAQ | [[dzialki-siepraw]], [[dzs-szybkie-odpowiedzi]] | 162 | 21 | 18 | 18 | 3 |
| Reszta | [[dzs-checklista-przed-zakupem]], [[dzs-ryzyka]], [[dzs-pomysly]], [[dzs-slownik]], `dzs-mapa-mysli.canvas` | 172 | 30 | 29 | 29 | 1 |
| **Suma 12 pakietów** | 32 pliki | **1707** | **196** | **187** | **187** | **9** |
| Runda 2: spójność i kompletność | cała wiki | – | 60 | 58 | 58 | 2 |
| **Razem** | | **1707** | **256** | **245** | **245** | **11** |

Weryfikatorzy oznaczali wagę jako „istotne” albo „drobne”. Żadne zgłoszenie nie dostało wagi „krytyczne”. Niżej są wszystkie potwierdzone poprawki o wadze „istotne” (75).

## Poprawki istotne

### MPZP i warunki techniczne

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-mpzp-uchwala]] | „Data ogłoszenia nieznana” → ogłoszenie Dz. Urz. Woj. Małop. 2025 poz. 4532 z 16.07.2025; plan obowiązuje od 31.07.2025; okres renty planistycznej do ok. 31.07.2030 | Dziennik Urzędowy (edziennik.malopolska.uw.gov.pl/WDU_K/2025/4532), MPZP §58 |
| [[dzs-mpzp-definicje]] | „taras/zielony dach liczy się w 50%” → tylko taras lub stropodach z roślinami, min. 10 m²; taras utwardzony się nie liczy | upzp art. 2 pkt 28 |
| [[dzs-mpzp-ustalenia-ogolne]] | zakaz grodzenia 1,5 m i pas 5 m od cieku bez warunków → 1,5 m tylko przy wodach publicznych; w pasie 5 m wyjątek dla melioracji | MPZP §8 ust. 1 pkt 4–5 |
| [[dzs-mpzp-ustalenia-ogolne]] | pytanie o strefy bez odpowiedzi → wstępny odczyt rysunku: teren 3.22MN, osuwisko SOPO na NW poza działkami, granica aglomeracji przy W granicy 2834/8, gazociąg w.c. na SW | rysunek MPZP, legenda |
| [[dzs-mpzp-teren-mn]], [[dzs-mpzp-teren-mn-u]] | budynek przy granicy „tylko gdy front < 16 m” → także garaż ≤ 6,5 × 3 m (WT §12 ust. 4 pkt 3) i przyleganie do budynku sąsiada (WT §12 ust. 3) | MPZP §23 ust. 1, WT §12 |
| [[dzs-mpzp-teren-mn]], [[dzs-mpzp-teren-mn-u]] | brak zasady pomiaru wysokości → od średniej poziomu terenu przy budynku; na 2834/9 teren opada o ok. 3,3 m | MPZP §3 ust. 1 pkt 22, upzp art. 2 pkt 30 |
| [[dzs-mpzp-infrastruktura-i-komunikacja]] | „sprzedający zobowiązuje się wybudować kanalizację” → to zapowiedź w mailu, nie umowa; obejmuje też wodociąg i prawo do likwidacji szamba | mail Z57 |
| [[dzs-mpzp-infrastruktura-i-komunikacja]] | „odczytaj aglomerację z rysunku” → granica aglomeracji biegnie wzdłuż W granicy 2834/8; działki prawdopodobnie w aglomeracji | rysunek i legenda MPZP |
| [[dzs-warunki-techniczne-odleglosci]] | dom na zgłoszenie = art. 29 ust. 2 i art. 102b → art. 29 ust. 1 pkt 1; stare WT tylko z oświadczeniem (art. 102a ust. 1 pkt 3) | Pb Dz.U. 2026 poz. 524, Dz.U. 2026 poz. 1161 |
| [[dzs-warunki-techniczne-odleglosci]] | zmiana WT w życie 01.04.2024 → 01.08.2024 (termin przesunęło Dz.U. 2024 poz. 474) | Dz.U. 2024 poz. 474 §1 pkt 2 |
| [[dzs-warunki-techniczne-odleglosci]] | brak uwagi o garażu w bryle domu → „droga A” dotyczy tylko garażu wolnostojącego | WT §12 ust. 4 pkt 3 |

### Grunt

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-opinia-geotechniczna]] | „Zakaz” oczyszczalni i studni chłonnych → zalecenie geologa; MPZP je dopuszcza poza osuwiskami | opinia s. 9 wn. 14, MPZP §53 ust. 3 pkt 4 i 8 |
| [[dzs-warunki-gruntowe]] | „opinia zakazuje” (3 miejsca) → „opinia odradza; decyduje projektant” | jw. |
| [[dzs-warunki-gruntowe]] | „przy II kategorii zwykle projekt geotechniczny” → zawsze dokumentacja badań i projekt geotechniczny; dom 1–2-kondygnacyjny może być I kategorią | Dz.U. 2012 poz. 463 §4, §7 |

### Działki, GIS i uzbrojenie

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-dzialka-2834-9]] | 725/41 „pas drogowy” → wąska działka prywatna, prawdopodobnie droga; w MPZP teren MN; użytek w EGiB nieustalony | rysunek MPZP, KIEG |
| [[dzs-dzialka-2834-8]], [[dzs-dzialka-2834-9]] | gaz „ok. 47 m na SW” → KIUT ok. 47 m, rysunek MPZP gazociąg w.c. ok. 17–19 m; sieć przesyłowa, nie do przyłącza | KIUT, rysunek MPZP |
| [[dzs-dzialka-2834-9]] | cytat o szambie bez końca zdania → pełny cytat „prawo do jego likwidacji po określonej dacie”; nie wiadomo, kto likwiduje | mail Z57 |
| [[dzs-uzbrojenie-terenu]] | brak opisu gazociągu z MPZP → gazociąg w.c. ze strefą kontrolowaną (element informacyjny) | MPZP §4 ust. 3 pkt 5, §53 ust. 4 |
| [[dzs-uzbrojenie-terenu]] | „Gaz: brak sieci w pobliżu” → brak na działkach i do 3 m; najbliższy ok. 47 m | KIUT |
| [[dzs-uzbrojenie-terenu]] | nowa sieć „w pasie drogi na wschodzie” → mail nie podaje trasy | mail Z57 |
| [[dzs-uzbrojenie-terenu]] | brak zapisów MPZP o ściekach → szambo i POŚ dopuszczone; na osuwiskach zakaz rozsączania | MPZP §53 ust. 3 pkt 4, 6; §12 |
| [[dzs-uzbrojenie-terenu]] | służebność przesyłu „często za wynagrodzeniem” → zawsze za wynagrodzeniem; żądać może przedsiębiorca albo właściciel | KC art. 305² |
| [[dzs-dokumenty-i-linki]] | osuwiska „ok. 60–100 m” → ok. 25–30 m na NW od 2834/8 | rysunek MPZP (pomiar z rastra) |
| [[dzs-dokumenty-i-linki]] | „brak linii rozgraniczającej przy działkach” → W granica 2834/8 pokrywa się z linią 3.22MN / 86RN | rysunek MPZP, §3 ust. 1 pkt 9 |
| [[dzs-dokumenty-i-linki]] | las 58L „ok. 150 m” → tereny L ok. 35–40 m na W/NW i 50–55 m na N; 58L ok. 85–90 m | rysunek MPZP, §23 ust. 2 |
| [[dzs-planer-dzialki-dom]] | wskaźniki tylko dla 1868 m² → dla samej 2834/9: zabudowa ok. 30%, intensywność ok. 0,30 | raport planera, MPZP §3 |

### Urzędy, formalności i koszty

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-starostwo-myslenice]] | „czekaj 21 dni” dla każdego zgłoszenia → dom do 70 m²: budowa zaraz po doręczeniu | Pb art. 30 ust. 5j–5k |
| [[dzs-dostawcy-mediow]] | wniosek do TAURON „tylko z tytułem prawnym, po akcie” → można przed aktem, bez tytułu | TAURON td-obsluga-wniosku-wp |
| [[dzs-starostwo-myslenice]] | „zmian nie sprawdziłem” → art. 102a: stare WT z oświadczeniem do ok. 20.03.2028; poz. 1347 od 1.12.2026 | Dz.U. 2026 poz. 1161, ELI |
| [[dzs-dostawcy-mediow]] | sieć „najpewniej prywatna, budowana przez sprzedającego” → nie wiadomo, kto zbuduje sieć | strona gminy, mail Z57 |
| [[dzs-z57-real-estate]] | „hipoteka eFaktor na 2834/11” → KW nieznana; sprawdź dział IV obu KW | mail Z57 |
| [[dzs-koszty-zakupu-i-podatki]] | wypisy aktu 6 zł/str. → od 5.11.2026: 12 / 10 / 8 zł/str. | Dz.U. 2026 poz. 1370 |
| [[dzs-koszty-zakupu-i-podatki]] | koszt wniosków KW „do sprawdzenia” → maks. 300 zł netto za wniosek (§15c) | Dz.U. 2026 poz. 1370 |
| [[dzs-koszty-zakupu-i-podatki]] | termin 5 lat z art. 36 ust. 4 → art. 37 ust. 3–4 upzp | upzp |
| [[dzs-koszty-zakupu-i-podatki]] | podatek „grunty pozostałe” bez warunku → przy użytku rolnym podatek rolny i IR-1 | ustawa o podatkach lokalnych art. 2 ust. 2 |
| [[dzs-koszty-zakupu-i-podatki]] | stawki „do sprawdzenia” → 0,41 zł/m² grunt, 0,90 zł/m² budynek mieszkalny | uchwała VIII/54/24 |
| [[dzs-koszty-zakupu-i-podatki]] | dopłata „po 1.09.2027” → po wykreśleniu hipoteki eFaktor, ale nie wcześniej niż po 1.09.2027 | mail Z57 |
| [[dzs-procedura-budowy]] | „zmian nie sprawdziłem” → zmiany 605, 646, 1161; nowe WT od 20.09.2026; okres przejściowy 18 mies. | Dz.U. 2026 poz. 1161 |
| [[dzs-procedura-budowy]] | przebudowa linii „min. 12 mies.” → 12 mies. dotyczy przyłącza; termin dla linii do sprawdzenia | TAURON przebudowa-przylacza |
| [[dzs-procedura-budowy]] | tryb do 70 m² bez warunków → oświadczenie pod rygorem karnym; inwestor odpowiada za kierowanie budową | Pb art. 30 ust. 2a |

### Transakcja, hub, FAQ i reszta

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-oferta-i-mail-z57]], [[dzs-transakcja]], [[dzs-harmonogram]] | „sprzedający buduje sieci” → mail nie mówi, kto buduje; „Z57 (?)” | mail Z57 |
| [[dzs-oferta-i-mail-z57]] | służebności „przez 725/41 i 726/1” → mail obiecuje „do wszystkich głównych dróg dojazdowych”, bez numerów | mail Z57 |
| [[dzs-transakcja]] | „hipoteka ciąży na KR1Y/00059868/1” → wniosek; sprawdź obie KW | mail Z57 |
| [[dzs-harmonogram]] | koniec renty „31.07.2030, §56” → podstawa upzp art. 36–37; data potem potwierdzona (zob. runda 2) | upzp, Dz. Urz. 2025 poz. 4532 |
| [[dzs-transakcja]] | „opinia zakazuje oczyszczalni” → opinia odradza | opinia wn. 14 |
| [[dzs-szybkie-odpowiedzi]] | bliźniak „Nie” → plan wyklucza tylko zabudowę szeregową i grupową | MPZP §26 ust. 2 |
| [[dzs-szybkie-odpowiedzi]] | „taras i zielony dach 50%” → tylko z roślinami, min. 10 m² | upzp art. 2 pkt 28 |
| [[dzs-szybkie-odpowiedzi]] | wskaźniki 12,3% / 0,12 → to 3 działki razem; dla 2834/9 ok. 29,7% / 0,30 | raport planera |
| [[dzialki-siepraw]] | pasy 725/41 i 726/1 „są prywatne” → prawdopodobnie niegminne; właściciela sprawdź w KW | KIEG (grupa 15) |
| `dzs-mapa-mysli.canvas` | „bez bliźniaka” → bez zabudowy szeregowej i grupowej | MPZP §26 ust. 2 |
| [[dzs-pomysly]], [[dzs-ryzyka]], [[dzs-slownik]], `dzs-mapa-mysli.canvas` | „POŚ zakazana” → MPZP dopuszcza, opinia odradza | MPZP §53 ust. 3 pkt 4, opinia wn. 14 |
| [[dzs-pomysly]] | „piwnica odradzana przez opinię” → opinia dotyczy domu bez piwnicy; piwnica wymaga nowej oceny | opinia, Wstęp |
| [[dzs-pomysly]] | budynek na 2834/11 „3/4 m od granic” → front < 16 m: 1,5 m albo w granicy | MPZP §23 ust. 1, WT §12 ust. 4 |
| [[dzs-pomysly]] | garaż w granicy bez skutków → ściana bez otworów; obszar oddziaływania obejmie sąsiada | WT §12 ust. 4 pkt 3, ust. 5 |
| [[dzs-ryzyka]] | klasa gruntu: prawdop. „N” → „Ś”; obok kontury PsIII | rysunek MPZP |
| `dzs-mapa-mysli.canvas` | „operator: Gmina Siepraw” → do ustalenia | mail Z57 |
| [[dzs-slownik]] | PBC: tarasy i dachy 50% bez warunków → z roślinami, min. 10 m² | upzp art. 2 pkt 28 |

### Runda 2 – spójność i kompletność

| Strona | Było → jest | Źródło |
|---|---|---|
| [[dzs-szybkie-odpowiedzi]] | las „ok. 150 m, pewne” → lasy L 35–40 m i 50–55 m, 58L 85–90 m; „do sprawdzenia (Ls w EGiB)” | rysunek MPZP, WT §271 ust. 8 |
| [[dzs-szybkie-odpowiedzi]] | osuwiska „60–100 m” → ok. 25–35 m na NW | rysunek MPZP |
| [[dzs-harmonogram]] | TAURON „tylko z tytułem” → wniosek możliwy bez tytułu; zmieniono diagram | TAURON |
| [[dzs-dostawcy-mediow]] | gazociąg „w promieniu 40 m” → 40 m to bufor analizy, nie pomiar; KIUT ok. 47 m | manifest GIS, KIUT |
| [[dzs-oferta-i-mail-z57]] | szambo sąsiada „możemy je usunąć” → wniosek z KIUT; mail nie mówi, czyje prawo | mail Z57 |
| [[dzs-szybkie-odpowiedzi]] | „Gmina, bez spółki; sieci buduje sprzedający, pewne” → do sprawdzenia | mail Z57, strona gminy |
| [[dzialki-siepraw]] | hipoteka „wg maila na 2834/11” → wniosek; sprawdź obie KW | mail Z57 |
| [[dzs-szybkie-odpowiedzi]] | garaż w granicy „pewne” → dotyczy garażu osobnego; dobudowany = część domu | WT §12 |
| [[dzs-szybkie-odpowiedzi]] | dach i wysokość garażu „pewne” → pewne tylko dla garażu wolnostojącego | MPZP §26 ust. 6 pkt 2–3 |
| [[dzs-szybkie-odpowiedzi]] | brak ochrony sąsiadów przy deszczówce → nie kierować wody na 2834/12 i 2834/13 | MPZP §53 ust. 3 pkt 9, WT §29 |
| [[dzs-szybkie-odpowiedzi]] | II kategoria bez skutku → potrzebna dokumentacja badań i projekt geotechniczny | Dz.U. 2012 poz. 463 §7 ust. 2 |
| [[dzs-szybkie-odpowiedzi]] | brak zaleceń budowlanych → nowy wiersz „Na co uważać przy budowie?” | opinia wn. 6–17, s. 8 |
| [[dzs-szybkie-odpowiedzi]] | brak warunku dla WT → callout: stare WT tylko z oświadczeniem do ok. 20.03.2028 | Pb art. 102a |
| [[dzs-ryzyka]] | brak ryzyka garażu → nowe ryzyko #22 „Garaż dobudowany do domu” | MPZP §26, WT §12 |

## Zgłoszenia odrzucone przez sceptyka

| Zgłoszenie | Strona | Dlaczego odrzucone |
|---|---|---|
| gis-09 | [[dzs-uzbrojenie-terenu]] | Wg ULDK pas na E od 2834/9 i 2834/11 to ta sama działka 725/41. Strona była dobra. |
| gis-13 | [[dzs-dane-gis-i-3d]] | Zgłaszający użył komórki NMT spoza działki. Wynik strony (ok. 1,1 m, ok. 3%) jest dobry. |
| dokumenty-11 | [[dzs-dokumenty-i-linki]] | Serwis e-mpzp ma przełącznik „Plan miejscowy 2004 r.”. Opis strony odpowiada przełącznikowi. |
| urzedy-03 | [[dzs-dostawcy-mediow]] | TAURON mówi, kto płaci tylko za przyłącze, nie za linię sieci. Zdanie strony jest prawdziwe. |
| formalnosci-09 | [[dzs-koszty-zakupu-i-podatki]] | Strona gminy podaje tel. 12 37 21 823 dla pokoju 29. |
| hub-faq-06 | [[dzs-szybkie-odpowiedzi]] | §6 pkt 17 rozporządzenia o taksie daje połowę stawki przy sprzedaży działki budowlanej. 1 248,40 zł netto jest dobre. |
| hub-faq-15 | [[dzs-szybkie-odpowiedzi]] | Strona gminy podaje pokój 15 dla wypisu i wyrysu. |
| hub-faq-21 | [[dzs-szybkie-odpowiedzi]] | Numer poz. 4532 jest w uzasadnieniu planu ogólnego. Datę 16.07.2025 potwierdził potem Dziennik Urzędowy. |
| reszta-15 | [[dzs-pomysly]] | 317,2 m to wysokość przy narożniku NE (317,17 m), a nie maksimum w działce (317,02 m). |
| completeness-12 | [[dzs-warunki-techniczne-odleglosci]] | Wymagania energetyczne są poza tematem strony o odległościach. To nie jest błąd. |
| completeness-18 | [[dzs-warunki-techniczne-odleglosci]] | Strona podaje datę z ISAP poprawnie i ze źródłem. Niespójność była w FAQ i tam ją poprawiono. |

## Poprawki po workflow (orkiestrator, 2026-10-27)

Korektorzy pracowali tylko na stronach z przydzielonej listy. 7 niespójności spoza tych list poprawił orkiestrator po sprawdzeniu w źródłach pierwotnych:

| Strona | Było | Jest | Źródło |
|---|---|---|---|
| [[dzs-slownik]] | koniec okna WT „do ok. 19.03.2028” | „do ok. 20.03.2028” | Dz.U. 2026 poz. 1161, art. 102a ust. 1: „W okresie 18 miesięcy od dnia 20 września 2026 r.” (`raw/dzialki-siepraw/assets/dzs-ustawa-dz-u-2026-1161.pdf`) |
| [[dzs-mpzp-teren-mn]] | „grupa 3.1–24MN / 3.1–26MN” bez przypisania | każdy wskaźnik z właściwą grupą i przepisem; dodano front min. 16,0 m | [[dzs-mpzp-uchwala]] §26 ust. 4 pkt 1 lit. b, pkt 3 lit. a, pkt 4 lit. a; §24 ust. 5 pkt 1 lit. a–b |
| [[dzs-dokumenty-i-linki]], [[dzs-mpzp-infrastruktura-i-komunikacja]] | różne listy działek z gazociągiem w.c. | jedna wersja: przy SW narożniku 2834/10, przez 2835/1, 2835/3, 2836/2 (odczyt z rastra, ± kilka m) | rysunek planu z BIP (`dzs-mpzp-rysunek-okolica.png`) |
| [[dzs-harmonogram]], [[dzs-checklista-przed-zakupem]], [[dzs-slownik]], [[dzs-procedura-budowy]], [[dzs-urzad-gminy-siepraw]], mapa myśli | tylko IN-1 | IN-1 albo IR-1, zależnie od użytku w EGiB | ustawa o podatkach i opłatach lokalnych (IN-1) i ustawa o podatku rolnym (IR-1) |
| [[dzs-warunki-gruntowe]] | „sprzedający ma zbudować kanalizację” | mail zapowiada zobowiązania w umowie, ale nie mówi, kto buduje i do kiedy | `raw/dzialki-siepraw/notes/2026-10-27-mail-warunki-sprzedazy-z57.md` |
| [[dzs-pomysly]] | „opinia: zakaz rozsączania” | opinia (wnioski 12 i 14) zaleca nie rozsączać; to zalecenie geologa, nie zakaz prawny (zakaz prawny jest tylko na obszarach osuwisk, §12 ust. 2 pkt 2) | [[dzs-opinia-geotechniczna]]; [[dzs-mpzp-uchwala]] §12 ust. 2, §53 ust. 3 pkt 4 |
| mapa myśli | „30 zł + 20 zł/A4” | wypis 30 zł (do 5 str.) / 50 zł; wyrys 20 zł za A4, maks. 200 zł | [[dzs-urzad-gminy-siepraw]] |

Orkiestrator sprawdził też w źródłach pierwotnych wybrane poprawki agentów: zmianę WT w życie 01.08.2024 (Dz.U. 2024 poz. 474), art. 102a–102c Pb (Dz.U. 2026 poz. 1161), dopuszczenie szamb i oczyszczalni (§53 ust. 3 pkt 4), bliźniak (§26 ust. 2), 600 m² (§24 ust. 5), wskaźniki planera dla samej 2834/9 (230,6 m² / 777 m² ≈ 30%).

## Czego nie dało się zweryfikować

> [!question] Otwarte po weryfikacji
> - **Użytek i klasa gruntu** działek w EGiB. Obok są kontury PsIII. Od tego zależy podatek (IN-1 / IR-1) i możliwa opłata za wyłączenie z produkcji rolnej.
> - **Dział III i IV ksiąg wieczystych** KR1Y/00091772/7 i KR1Y/00059868/1. Nie wiemy, którą KW obciąża hipoteka eFaktor ani jakie są służebności przejazdu na 2834/11.
> - **Właściciel i użytek działek 725/41 i 726/1**. KIEG podaje grupę rejestrową 15 (spółki prawa handlowego), ale bez użytku i właściciela.
> - **Kto zbuduje sieć kanalizacyjną i wodociągową**, gdzie i do kiedy. Kto ją przejmie (gmina?).
> - **Szambo na 2834/9**: czyje jest i kto je zlikwiduje. Położenie i właściciela wnioskujemy z mapy KIUT.
> - **Odległości z rastra MPZP** (osuwiska, lasy, gazociąg w.c.) mają dokładność ± kilka metrów. Wycinek nie ma georeferencji.
> - **Gazociąg**: dwa źródła, dwie odległości (MPZP ok. 17 m, KIUT ok. 47 m). To mogą być różne linie. KIUT nie podaje ciśnienia ani średnicy.
> - **Czy działki leżą w aglomeracji** Siepraw. Granica biegnie wzdłuż W granicy 2834/8. Z wycinka nie widać, po której stronie jest wnętrze.
> - **Nowe warunki techniczne** po 20.09.2026 nie zostały ogłoszone (źródło branżowe, stan 27.10.2026).
> - **Garaż dobudowany do domu**: czy urząd uzna go za „garaż” (MPZP §26 ust. 6 pkt 3 lit. b) czy za część domu (lit. a).
> - **Wzrost wartości działek przez plan z 2025 r.** Od tego zależy, czy w ogóle powstanie opłata planistyczna.

## Co kupujący muszą potwierdzić sami

| Dokument lub urząd | Co sprawdzić |
|---|---|
| **Wypis i wyrys z MPZP** (UG Siepraw, ul. Kawęciny 30, pok. 15) | teren 3.22MN dla całych działek; osuwiska, aglomeracja, strefa gazociągu, linia MN/RN przy 2834/8 |
| **Wypis z rejestru gruntów (EGiB)** (Starostwo, PODGiK) | użytek i klasa gruntu 2834/8, /9, /11; użytek i właściciel 725/41 i 726/1; pole urzędowe |
| **Odpisy KW** (EKW) KR1Y/00091772/7 i KR1Y/00059868/1 | dział III (służebności, w tym przejazd przez 2834/11), dział IV (hipoteka eFaktor) |
| **Urząd Gminy Siepraw** | czy działki są w aglomeracji; kto przejmie nową sieć; stawki podatku na 2027; uchwała krajobrazowa |
| **Projekt aktu notarialnego** | kto buduje sieci i do kiedy, kary umowne, wykonanie zastępcze; kto likwiduje szambo; numery działek ze służebnością do drogi publicznej; wariant trójkąta (1 zł albo służebność); kwota przy akcie (401 072,00 czy 401 072,25 zł) |
| **TAURON / PSG** | kolizja z linią nN wzdłuż N granicy; szerokość strefy gazociągu w.c.; możliwość przyłącza gazu |
| **Projektant** | kategoria geotechniczna i czy opinia z 2022 r. wystarczy; garaż jako część domu czy osobny budynek; które WT stosuje i czy złożyć oświadczenie (do ok. 20.03.2028); czy dom i taras mieszczą się na 2834/9 |

## Powiązane

- [[dzialki-siepraw]] – strona główna domeny
- [[dzs-szybkie-odpowiedzi]] – FAQ po poprawkach
- MPZP: [[dzs-mpzp-uchwala]], [[dzs-mpzp-definicje]], [[dzs-mpzp-ustalenia-ogolne]], [[dzs-mpzp-teren-mn]], [[dzs-mpzp-teren-mn-u]], [[dzs-mpzp-infrastruktura-i-komunikacja]]
- Przepisy i grunt: [[dzs-warunki-techniczne-odleglosci]], [[dzs-opinia-geotechniczna]], [[dzs-warunki-gruntowe]]
- Działki i dane: [[dzs-dzialka-2834-8]], [[dzs-dzialka-2834-9]], [[dzs-dzialka-2834-11]], [[dzs-dane-gis-i-3d]], [[dzs-uzbrojenie-terenu]], [[dzs-dokumenty-i-linki]], [[dzs-planer-dzialki-dom]]
- Urzędy i strony umowy: [[dzs-urzad-gminy-siepraw]], [[dzs-starostwo-myslenice]], [[dzs-dostawcy-mediow]], [[dzs-z57-real-estate]]
- Formalności i transakcja: [[dzs-procedura-budowy]], [[dzs-koszty-zakupu-i-podatki]], [[dzs-oferta-i-mail-z57]], [[dzs-transakcja]], [[dzs-harmonogram]]
- Synteza: [[dzs-checklista-przed-zakupem]], [[dzs-ryzyka]], [[dzs-pomysly]], [[dzs-slownik]], `dzs-mapa-mysli.canvas`
