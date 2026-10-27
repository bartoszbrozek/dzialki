---
type: raw-manifest
created: 2026-10-27
domain: dzialki-siepraw
---

# Manifest danych GIS i 3D — działki 2834/8, 2834/9, 2834/11 (Siepraw), pobrane 2026-10-27

Dane pobrał agent skryptami `gis.py` i `kiut.py` (python3 + GDAL 3.13). Pliki leżą w `raw/dzialki-siepraw/gis/` z prefiksem `dzs-`. Skryptów nie zarchiwizowano; parametry z tabeli wystarczą do ponownego pobrania. Strefę MPZP ustalono z georeferowanego rysunku planu z BIP (`https://bip.malopolska.pl/api/files/3859132`, EPSG:2178).

| Dane | Usługa / źródło | Parametry | Plik |
|---|---|---|---|
| Geometria działek | ULDK GUGiK `https://uldk.gugik.gov.pl/` `GetParcelByIdOrNr` | id `Siepraw 2834/x`, srid 2180; TERYT `120906_2.0003.2834/x` | `dzs-dzialki-epsg2180.geojson`, `dzs-dzialki-wgs84.geojson` |
| NMT 1 m | WCS `https://mapy.geoportal.gov.pl/wss/service/PZGIK/NMT/GRID1/WCS/DigitalTerrainModelFormatTIFF` | coverage `DTM_PL-KRON86-NH_TIFF`, bbox EPSG:2180 = obwiednia działek + 40 m | `dzs-nmt-1m-epsg2180.tif`, `dzs-nmt-1m-xyz-epsg2180.csv` |
| Poziomice 0,5 m | `gdal_contour` z NMT | | `dzs-poziomice-0.5m-epsg2180.geojson` |
| Ortofotomapa | WMS `https://mapy.geoportal.gov.pl/wss/service/PZGIK/ORTO/WMS/HighResolution`, warstwa `Raster` | 4 px/m | `dzs-mapa-ortofoto.png` |
| Ewidencja gruntów | WMS `https://integracja.gugik.gov.pl/cgi-bin/KrajowaIntegracjaEwidencjiGruntow`, warstwy `dzialki,numery_dzialek,budynki` | 4 px/m | `dzs-mapa-ewidencja.png` |
| Uzbrojenie terenu | WMS `https://integracja.gugik.gov.pl/cgi-bin/KrajowaIntegracjaUzbrojeniaTerenu` (KIUT), warstwy `gesut,kgesut,kgesut_dane,przewod_*` | 4 px/m; analiza per warstwa | `dzs-mapa-uzbrojenie.png`, `dzs-kiut-przeciecia.json` |
| Pochodne | numpy/matplotlib z NMT | spadki, ekspozycja, profile wzdłuż/w poprzek, widok 3D | `dzs-mapa-rzezba-poziomice.png`, `dzs-mapa-spadki.png`, `dzs-profile-terenu.png`, `dzs-widok-3d-teren.png`, `dzs-summary.json` |

## Ograniczenia

- Wysokości są w układzie **PL-KRON86-NH**. Projekty budowlane używają obecnie **PL-EVRF2007-NH**. Różnicę między układami uwzględnia projektant lub geodeta (mapa do celów projektowych).
- NMPT (pokrycie terenu: drzewa, budynki) nie jest dostępny jako wysokości przez WCS GUGiK (usługa zwraca tylko obraz RGB). Pokrycie widać na ortofotomapie.
- `kiut-przeciecia.json`: `inside_m` to przybliżona długość narysowanej linii wewnątrz działki (piksele / 4), a nie długość z bazy GESUT. Dokładny przebieg pokaże mapa do celów projektowych.
- Granice działek z ULDK to dane ewidencyjne (EGiB), a nie wznowienie granic przez geodetę.
