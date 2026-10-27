---
type: synthesis
domain: dzialki-siepraw
created: 2026-10-27
updated: 2026-10-27
sources: ["[[dzs-dzialka-2834-8]]", "[[dzs-dzialka-2834-9]]", "[[dzs-dzialka-2834-11]]", "[[dzs-uzbrojenie-terenu]]"]
tags: [gis, 3d, nmt, wspolrzedne, mapy, siepraw, zweryfikowane-2026-10-27]
aliases: ["dane GIS", "dane 3D", "współrzędne działek", "NMT"]
---

# Dane GIS i 3D — działki 2834/8, 2834/9, 2834/11

Wszystkie dane przestrzenne o trzech działkach w jednym miejscu: pliki, współrzędne narożników, linki do map, statystyki terenu i mapy. Dane pobrano 2026-10-27 z usług GUGiK (ULDK, NMT, KIEG, KIUT). Opis źródeł: `2026-10-27-dzs-gis-manifest.md`.

## Szybki przegląd

| Działka | Pow. oferta | Pow. geometria | Wymiary (ok.) | H min–max (PL-KRON86-NH) | Δh | Spadek śr. | Ekspozycja |
|---|---|---|---|---|---|---|---|
| [[dzs-dzialka-2834-8]] | 833 m² | 832,4 m² | 36,5 × 22,7 m | 310,58–316,18 m | 5,60 m | 16,0% (9,1°) | SW (212°) |
| [[dzs-dzialka-2834-9]] | 777 m² | 775,8 m² | 34,2 × 22,7 m | 313,71–317,02 m | 3,31 m | 12,9% (7,3°) | S (194°) |
| [[dzs-dzialka-2834-11]] | 249 m² | 248,6 m² | 46,7 × ok. 5,0 m (bok wschodni 9,21 m z „hakiem”) | 311,91–314,58 m | 2,67 m | 14,1% (8,0°) | S (199°) |
| **Razem** | **1859 m²** | **1856,8 m²** | ok. 73 m (W–E); głębokość N–S ok. 23 m przy W i ok. 30 m przy E (obwiednia 73,2 × 35,9 m) | 310,58–317,02 m | 6,44 m | — | S–SW |

Źródło: `dzs-summary.json`, oferta: [[dzs-oferta-i-mail-z57]].

Najważniejsze wnioski:
- Cały teren opada na **południe i południowy zachód**. Najwyżej jest NE narożnik 2834/9, najniżej SW narożnik 2834/8.
- 2834/9 jest najbardziej płaska (12,9%). Kierunek wschód–zachód jest tam prawie poziomy (rozstęp wysokości 0,58 m na 37 m).
- Wysokości w NMT są w układzie **PL-KRON86-NH**. Projekt budowlany używa **PL-EVRF2007-NH**. Różnicę uwzględnia geodeta lub projektant.

## Pliki

Pliki źródłowe leżą w `raw/dzialki-siepraw/gis/`. Plik KML jest w `assets/`.

| Plik | Co zawiera | Układ | Do czego | Jak otworzyć |
|---|---|---|---|---|
| `dzs-dzialki-wgs84.geojson` | granice 3 działek (poligony) | WGS84 (EPSG:4326) | podgląd na mapie świata, nawigacja | https://geojson.io (przeciągnij plik), QGIS |
| `dzs-dzialki-epsg2180.geojson` | granice 3 działek | PL-1992 (EPSG:2180) | pomiary, nakładanie na mapy GUGiK | QGIS (Warstwa → Dodaj warstwę wektorową) |
| `dzs-dzialki-wgs84.kml` | granice 3 działek (konwersja z dzs-dzialki-wgs84.geojson) | WGS84 | Google Earth (widok 3D z budynkami) | Google Earth Pro: Plik → Otwórz; Google Earth Web: Projekty → Importuj plik KML |
| `dzs-nmt-1m-epsg2180.tif` | numeryczny model terenu, siatka 1 m, obszar działek + 40 m | EPSG:2180, H w PL-KRON86-NH | modelowanie terenu, przekroje, objętości ziemi | QGIS (Warstwa rastrowa), wtyczka Profile Tool, Qgis2threejs (3D) |
| `dzs-nmt-1m-xyz-epsg2180.csv` | ten sam NMT jako punkty x, y, h | EPSG:2180, PL-KRON86-NH | import do CAD, Excel, SketchUp | Excel / Numbers, QGIS (Dodaj warstwę tekstową), CAD |
| `dzs-poziomice-0.5m-epsg2180.geojson` | poziomice co 0,5 m (z NMT) | EPSG:2180, PL-KRON86-NH | szkice zagospodarowania, podkład dla architekta | QGIS, CAD (po eksporcie do DXF) |
| `dzs-summary.json` | pola, obwody, boki, centroidy, statystyki terenu, profile | EPSG:2180 + WGS84 | szybkie liczby | dowolny edytor tekstu |
| `dzs-kiut-przeciecia.json` | które sieci przecinają działki (długości przybliżone) | — | analiza uzbrojenia | edytor tekstu |
| `dzs-mapa-ewidencja.png` | mapa ewidencyjna (KIEG) | EPSG:2180 | numery działek, sąsiedzi | Obsidian, przeglądarka obrazów |
| `dzs-mapa-ortofoto.png` | ortofotomapa (pusta, patrz ograniczenia) | EPSG:2180 | — | — |
| `dzs-mapa-uzbrojenie.png` | sieci uzbrojenia (KIUT) | EPSG:2180 | przebieg sieci | Obsidian |
| `dzs-mapa-rzezba-poziomice.png` | cieniowanie + poziomice 0,5 m | EPSG:2180 | rzeźba terenu | Obsidian |
| `dzs-mapa-spadki.png` | mapa spadków [%] | EPSG:2180 | strome miejsca | Obsidian |
| `dzs-profile-terenu.png` | 6 profili (2 na działkę) | — | przekroje terenu | Obsidian |
| `dzs-widok-3d-teren.png` | model 3D terenu (przewyższenie ×3) | — | ogląd całości | Obsidian |

> [!question] Do sprawdzenia
> GeoTIFF i GeoJSON w EPSG:2180 otwieraj w QGIS z ustawionym układem projektu EPSG:2180. Zrzuty PNG nie mają georeferencji, służą tylko do oglądania.

## Współrzędne narożników

Układ PL-1992 (EPSG:2180) i WGS84. Kolumna „E (x GIS)” to współrzędna wschodnia, a „N (y GIS)” to północna.

> [!warning] Oznaczenia X / Y u geodety
> W polskiej geodezji „X” oznacza współrzędną **północną**, a „Y” **wschodnią**. W plikach GIS jest odwrotnie (x = wschód). Nie podawaj geodecie liczb bez nazwy osi. Źródło: ULDK GUGiK (https://uldk.gugik.gov.pl/), `dzs-summary.json`, `dzs-dzialki-wgs84.geojson`.

Punkty P1… mają tę samą numerację co tabele boków na stronach działek. Wspólne punkty: P1 2834/8 = P3 2834/9 = P1 2834/11; P2 2834/8 = P2 2834/9; P7 2834/8 = P2 2834/11; P4 2834/9 = P8 2834/11; P5 2834/9 = P7 2834/11.

> [!question] Do sprawdzenia
> To dane ewidencyjne (EGiB), a nie wznowienie granic. Przed budową zamów u geodety wznowienie znaków granicznych lub ustalenie granic. Dokładność punktów EGiB w tym obrębie nie jest znana.

### 2834/8

| Punkt | E (x GIS) [m] | N (y GIS) [m] | Szer. φ (WGS84) | Dł. λ (WGS84) |
|---|---|---|---|---|
| P1 | 569558.28 | 227933.78 | 49.9146671 | 19.9691601 |
| P2 | 569561.08 | 227956.35 | 49.9148698 | 19.9692031 |
| P3 | 569545.80 | 227957.70 | 49.9148838 | 19.9689904 |
| P4 | 569524.68 | 227959.57 | 49.9149031 | 19.9686966 |
| P5 | 569523.10 | 227948.10 | 49.9148000 | 19.9686725 |
| P6 | 569521.89 | 227937.00 | 49.9147003 | 19.9686536 |
| P7 | 569543.82 | 227935.05 | 49.9146803 | 19.9689588 |

### 2834/9

| Punkt | E (x GIS) [m] | N (y GIS) [m] | Szer. φ (WGS84) | Dł. λ (WGS84) |
|---|---|---|---|---|
| P1 | 569570.75 | 227955.50 | 49.9148610 | 19.9693376 |
| P2 | 569561.08 | 227956.35 | 49.9148698 | 19.9692031 |
| P3 | 569558.28 | 227933.78 | 49.9146671 | 19.9691601 |
| P4 | 569590.33 | 227930.95 | 49.9146379 | 19.9696060 |
| P5 | 569592.69 | 227932.86 | 49.9146548 | 19.9696392 |
| P6 | 569593.60 | 227940.58 | 49.9147242 | 19.9696533 |
| P7 | 569595.12 | 227953.34 | 49.9148388 | 19.9696768 |

### 2834/11

| Punkt | E (x GIS) [m] | N (y GIS) [m] | Szer. φ (WGS84) | Dł. λ (WGS84) |
|---|---|---|---|---|
| P1 | 569558.28 | 227933.78 | 49.9146671 | 19.9691601 |
| P2 | 569543.82 | 227935.05 | 49.9146803 | 19.9689588 |
| P3 | 569543.30 | 227930.08 | 49.9146356 | 19.9689506 |
| P4 | 569568.44 | 227927.85 | 49.9146126 | 19.9693005 |
| P5 | 569589.75 | 227925.97 | 49.9145932 | 19.9695971 |
| P6 | 569591.59 | 227923.71 | 49.9145727 | 19.9696223 |
| P7 | 569592.69 | 227932.86 | 49.9146548 | 19.9696392 |
| P8 | 569590.33 | 227930.95 | 49.9146379 | 19.9696060 |

## Centroidy i linki do map

| Działka | Centroid EPSG:2180 (E, N) | Centroid WGS84 (φ, λ) | Google Maps | Geoportal |
|---|---|---|---|---|
| 2834/8 | 569539,81; 227946,79 | 49.914786, 19.968905 | https://www.google.com/maps?q=49.914786,19.968905 | https://mapy.geoportal.gov.pl/imapnext/imap/?identifyParcel=120906_2.0003.2834/8 |
| 2834/9 | 569580,26; 227943,34 | 49.914751, 19.969468 | https://www.google.com/maps?q=49.914751,19.969468 | https://mapy.geoportal.gov.pl/imapnext/imap/?identifyParcel=120906_2.0003.2834/9 |
| 2834/11 | 569572,28; 227930,03 | 49.914632, 19.969354 | https://www.google.com/maps?q=49.914632,19.969354 | https://mapy.geoportal.gov.pl/imapnext/imap/?identifyParcel=120906_2.0003.2834/11 |

Źródło: `dzs-summary.json`.

> [!question] Do sprawdzenia
> Parametr `identifyParcel` w linkach Geoportalu nie był testowany w przeglądarce. Format linku według GUGiK: https://www.geoportal.gov.pl/aktualnosci/znane-funkcjonalnosci-dostepne-w-nowej-wersji-modulow-geoportalu/. Jeśli link nie zaznaczy działki, wpisz w wyszukiwarkę Geoportalu identyfikator `120906_2.0003.2834/9`.

Inne przydatne serwisy:
- Portal MPZP gminy: https://siepraw.e-mpzp.pl/ (patrz [[dzs-dokumenty-i-linki]]).
- Geoportal Krajowy (mapa, ortofoto, NMT, uzbrojenie): https://mapy.geoportal.gov.pl/
- Usługa lokalizacji działek ULDK: https://uldk.gugik.gov.pl/

## Statystyki terenu (NMT 1 m, PL-KRON86-NH)

| Parametr | 2834/8 | 2834/9 | 2834/11 |
|---|---|---|---|
| Liczba komórek NMT (1 m²) | 832 | 777 | 249 |
| H min [m] | 310,58 | 313,71 | 311,91 |
| H max [m] | 316,18 | 317,02 | 314,58 |
| H średnia [m] | 313,65 | 315,47 | 313,45 |
| Δh [m] | 5,60 | 3,31 | 2,67 |
| Spadek średni | 16,0% (9,1°) | 12,9% (7,3°) | 14,1% (8,0°) |
| Spadek p90 | 20,6% | 16,5% | 17,5% |
| Spadek max | 30,4% | 25,1% | 24,5% |
| Ekspozycja (azymut) | SW (212°) | S (194°) | S (199°) |
| Najwyższy punkt (E, N) | 569560,5; 227955,5 (NE) | 569591,5; 227953,5 (NE) | 569592,5; 227932,5 (E) |
| Najniższy punkt (E, N) | 569522,5; 227937,5 (SW) | 569558,5; 227934,5 (SW) | 569543,5; 227930,5 (W) |

Źródło: `dzs-summary.json`.

### Profile terenu (poprawione kierunki)

| Działka | Profil | Długość | Kierunek (poprawiony) | H start → H koniec (PL-KRON86-NH) | Δh na profilu (dh_m z dzs-summary.json; prawdopodobnie max–min) |
|---|---|---|---|---|---|
| 2834/8 | wzdłuż | 37,9 m | E → W | 315,04 → 312,23 m | 2,81 m |
| 2834/8 | w poprzek | 23,6 m | N → S | 315,15 → 312,03 m | 3,12 m |
| 2834/9 | wzdłuż | 37,3 m | nieustalony (patrz niżej) | 315,57 → 315,41 m | 0,58 m |
| 2834/9 | w poprzek | 30,0 m | N → S | 317,09 → 313,68 m | 3,41 m |
| 2834/11 | wzdłuż | 48,9 m | W → E | 312,20 → 313,89 m | 1,80 m |
| 2834/11 | w poprzek | 9,2 m | N → S | 314,31 → 313,27 m | 1,04 m |

Dla 2834/9 wzdłuż i 2834/11 wzdłuż Δh jest większe niż różnica H start − H koniec (0,16 m i 1,69 m), bo teren na profilu się waha.

> [!warning] Sprzeczność
> Pole `from_dir` w `dzs-summary.json` i strzałki w tytułach `dzs-profile-terenu.png` mają odwrócony kierunek. Dowód: wysokości narożników z `dzs-nmt-1m-xyz-epsg2180.csv`. Na 2834/9 narożniki północne mają 316,4–317,2 m, a południowe 313,7–314,6 m. Profil „S→N” zaczyna się na 317,09 m, czyli na północy. Tabela powyżej podaje poprawione kierunki. Wartości wysokości i Δh są poprawne.

Kontrola dla 2834/9 wzdłuż osi E–W: w wierszu NMT N = 227943,5 teren rośnie z ok. 314,8 m (W) do ok. 315,9 m (E), czyli ok. 1,1 m na 34 m (ok. 3%). Profil z `dzs-summary.json` przebiega inną linią. Oba wyniki mówią to samo: kierunek E–W jest prawie płaski.

Wysokości narożników z NMT (PL-KRON86-NH, komórka 1 m):

| Działka | P1 | P2 | P3 | P4 | P5 | P6 | P7 | P8 |
|---|---|---|---|---|---|---|---|---|
| 2834/8 | 313,66 | 316,37 | 315,28 | 314,18 | 312,59 | 310,29 | 312,45 | — |
| 2834/9 | 316,70 | 316,37 | 313,66 | 314,18 | 314,58 | 315,75 | 317,17 | — |
| 2834/11 | 313,66 | 312,45 | 311,91 | 313,44 | 313,42 | 313,15 | 314,58 | 314,18 |

Źródło: `dzs-nmt-1m-xyz-epsg2180.csv` (najbliższa komórka siatki).

## Mapy i widok 3D

### Ewidencja gruntów (KIEG)

![[dzs-mapa-ewidencja.png]]

### Ortofotomapa

![[dzs-mapa-ortofoto.png]]

> [!warning] Ortofotomapa jest pusta
> Plik `dzs-mapa-ortofoto.png` pokazuje tylko granice na białym tle. Usługa WMS odpowiedziała, ale zwróciła pusty (biały) obraz. Oglądaj zdjęcie lotnicze na https://mapy.geoportal.gov.pl/ albo w Google Maps (linki wyżej).

### Uzbrojenie terenu (KIUT)

![[dzs-mapa-uzbrojenie.png]]

Opis sieci: [[dzs-uzbrojenie-terenu]].

### Rzeźba terenu i poziomice co 0,5 m

![[dzs-mapa-rzezba-poziomice.png]]

### Spadki terenu

![[dzs-mapa-spadki.png]]

Kolor zielony to spadek do ok. 10%, żółty ok. 20%, czerwony powyżej 30%. Ostre czerwone pasy na wschodzie i zachodzie to skarpy przy drogach i miedzach poza działkami.

### Profile terenu

![[dzs-profile-terenu.png]]

### Model 3D terenu (przewyższenie ×3)

![[dzs-widok-3d-teren.png]]

Przewyższenie ×3 oznacza, że góry na obrazku są trzy razy wyższe niż w rzeczywistości.

## Ograniczenia danych

- **Układ wysokości:** NMT jest w PL-KRON86-NH. Projekt wymaga PL-EVRF2007-NH. Nie przeliczaj sam, zrób to u geodety (`2026-10-27-dzs-gis-manifest.md`).
- **Dokładność NMT:** siatka 1 m z lotniczego skanowania. Nie pokazuje drzew i budynków ani zmian terenu po dacie nalotu.
- **Brak NMPT:** usługa GUGiK nie udostępnia wysokości pokrycia (drzewa, budynki) przez WCS (`dzs-summary.json`, `dsm_ok: false`).
- **Granice:** dane EGiB z ULDK, nie wznowienie granic.
- **Pole powierzchni:** pola urzędowego (EGiB) nie pobrano. Pola obliczone z geometrii ULDK różnią się od oferty o 0,4–1,2 m². Pole urzędowe podaje wypis z rejestru gruntów.
- **Uzbrojenie:** zrzut WMS 4 px/m, długości przybliżone (`inside_m`). Usługa KIUT nie zwraca danych opisowych sieci (średnica, właściciel, głębokość). Rodzaj sieci wynika tylko z warstwy KIUT. Etykiety na mapie (np. „wo63”, „eN”) mogą zawierać średnicę lub napięcie, ale nie są potwierdzone. Pełne dane pokaże mapa do celów projektowych.
- **Ortofotomapa:** pusta (patrz wyżej).

> [!question] Do sprawdzenia
> Zamów mapę do celów projektowych u geodety uprawnionego. Bez niej projektant nie zacznie projektu. Patrz [[dzs-procedura-budowy]].

## Weryfikacja

- 2026-10-27: sprawdzono ze źródłami pierwotnymi; poprawiono 7 miejsc (zob. [[dzs-raport-weryfikacji-2026-10-27]]).
- 2026-10-27 (runda 2, spójność i kompletność): sprawdzono ze źródłami pierwotnymi; poprawiono 1 miejsce (zob. [[dzs-raport-weryfikacji-2026-10-27]]).

## Powiązane

- [[dzialki-siepraw]] · [[dzs-mapa-mysli.canvas]]
- [[dzs-dzialka-2834-8]] · [[dzs-dzialka-2834-9]] · [[dzs-dzialka-2834-11]]
- [[dzs-uzbrojenie-terenu]] · [[dzs-warunki-gruntowe]] · [[dzs-opinia-geotechniczna]]
- [[dzs-dokumenty-i-linki]] · [[dzs-procedura-budowy]] · [[dzs-szybkie-odpowiedzi]]
- [[dzs-pomysly]] · [[dzs-slownik]]
