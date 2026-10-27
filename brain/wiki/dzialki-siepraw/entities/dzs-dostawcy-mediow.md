---
type: entity
domain: dzialki-siepraw
created: 2026-10-27
updated: 2026-10-27
sources: ["[[dzs-mpzp-uchwala]]", "[[dzs-oferta-i-mail-z57]]", "[[dzs-dane-gis-i-3d]]"]
tags: [media, wodociag, kanalizacja, energia, tauron, gaz, psg, telekom, przylacza, zweryfikowane-2026-10-27]
aliases: [Dostawcy mediów Siepraw, Przyłącza Siepraw, Media]
---

# Dostawcy mediów (woda, kanalizacja, prąd, gaz, telekom)

Ta strona mówi, kto dostarcza każde medium do działek w Sieprawiu i jak zamówić warunki przyłączenia. Pokazuje też, co już leży w działkach wg mapy uzbrojenia.

## Podsumowanie

| Medium | Operator | Co jest przy działkach (KIUT, 2026-10-27) | Pierwszy krok |
|---|---|---|---|
| Woda | Gmina Siepraw (Urząd Gminy) | wodociąg przechodzi przez 2834/8, ok. 20,5 m w działce | wniosek o warunki przyłączenia w UG |
| Kanalizacja sanitarna | Gmina Siepraw | przewód kanalizacyjny w 2834/9, ok. 19,8 m, do małego obiektu przy E granicy (szambo?) | wniosek o warunki w UG; ustalić status sieci obiecanej przez Z57 |
| Prąd | TAURON Dystrybucja S.A. | linia elektroenergetyczna: 65,5 m w 2834/8, 41,0 m w 2834/9, do 3 m od 2834/11 | wniosek o warunki przyłączenia; uzgodnienie kolizji |
| Gaz | Polska Spółka Gazownictwa (PSG), Oddział Zakład Gazowniczy w Krakowie | KIUT: najbliższy gazociąg ok. 47 m na SW od narożnika SW 2834/8 (odczyt z dzs-mapa-uzbrojenie.png); na działkach i do 3 m od nich brak przewodu gazowego; rysunek MPZP: gazociąg wysokiego ciśnienia ok. 17–18 m od 2834/8 (pomiar z rastra) | sprawdzić dostępność w PSG |
| Telekom | do ustalenia | brak przewodów telekom. w okolicy wg KIUT | zapytać operatorów |

Dane KIUT: `dzs-kiut-przeciecia.json`, `dzs-mapa-uzbrojenie.png`. „inside_m” to przybliżona długość z obrazu mapy, nie z bazy GESUT. Dokładny przebieg pokaże mapa do celów projektowych ([[dzs-uzbrojenie-terenu]]).

![[dzs-mapa-uzbrojenie.png]]

## Woda i kanalizacja – Gmina Siepraw

Fakty z https://samorzad.gov.pl/web/gmina-siepraw/wodociagi-i-kanalizacja2:

- Wnioski o przyłączenie do sieci wodociągowo-kanalizacyjnej przyjmuje Urząd Gminy Siepraw (https://samorzad.gov.pl/web/gmina-siepraw/wodociagi-i-kanalizacja2). Wniosek: strona gminy nie wskazuje osobnej spółki wodociągowej.
- Gmina kupuje wodę od 4 dostawców: MZWiK Myślenice, MPWiK Kraków, UMiG Świątniki Górne, UMiG Dobczyce. Sieć ma ok. 109 km.
- Ścieki płyną do gminnej oczyszczalni w Sieprawiu albo do oczyszczalni w Dobczycach.
- Ok. 60% mieszkańców gminy ma kanalizację. Reszta ma szamba albo przydomowe oczyszczalnie (POŚ).
- Taryfa: decyzja Wód Polskich z 12.07.2024, ważna od 1.08.2024 do 31.07.2027.
- Od 1.03.2026 gmina nie rejestruje nowych POŚ ze szczelnym zbiornikiem odcieku. Ich zbiorniki trzeba opróżniać co najmniej co 2 miesiące.

Uzasadnienie planu ogólnego (29.04.2026) podaje inne liczby: zwodociągowanie ok. 83%, kanalizacja obejmuje 32% mieszkańców miejscowości Siepraw (`dzs-plan-ogolny-uzasadnienie-2026-04-29.pdf`, rozdz. o infrastrukturze technicznej).

> [!warning] Sprzeczność
> Strona gminy podaje ok. 90% zwodociągowania i ok. 60% skanalizowania gminy. Uzasadnienie planu ogólnego podaje ok. 83% zwodociągowania gminy (s. 49) i kanalizację dla 32% mieszkańców miejscowości Siepraw (s. 50). Liczby dotyczą różnych obszarów i dat. Dla Was ważny jest stan sieci przy samych działkach.

### Procedura przyłączenia wody i kanalizacji

1. Złóż w UG „Wniosek o wydanie warunków przyłączenia do sieci wodociągowej i/lub kanalizacyjnej” (formularz na stronie gminy).
2. Podaj cel poboru wody, zapotrzebowanie (m³/d) oraz ilość i rodzaj ścieków.
3. Odbierz warunki przyłączenia.
4. Zleć projekt przyłączy (zwykle razem z projektem domu).
5. Złóż w UG „Zgłoszenie zamiaru wykonania przyłącza”.
6. Wykonaj przyłącze i zgłoś odbiór w UG.

Wydanie warunków jest zwykle bezpłatne, a budowę przyłącza opłaca właściciel. To ogólna zasada, nie z dokumentu gminy (https://muratordom.pl/instalacje/instalacja-wodna/wniosek-o-wydanie-warunkow-technicznych-przylaczenia-do-sieci-wodociagowej-i-kanalizacyjnej-jak-wypelnic-i-zlozyc-aa-6rKY-RjAD-8GFz.html).

### MPZP o wodzie i ściekach

- Dopuszcza indywidualne studnie ([[dzs-mpzp-uchwala]] § 53 ust. 2 pkt 3).
- Obowiązuje kanalizacja rozdzielcza ([[dzs-mpzp-uchwala]] § 53 ust. 3 pkt 3).
- Dopuszcza szczelne szamba i POŚ ([[dzs-mpzp-uchwala]] § 53 ust. 3 pkt 4).
- Wody opadowe trzeba zagospodarować na działce albo odprowadzić do kanalizacji, cieku lub rowu ([[dzs-mpzp-uchwala]] § 53 ust. 3 pkt 8).
- Na obszarach osuwisk obowiązuje zakaz rozsączania ścieków i wód opadowych w gruncie ([[dzs-mpzp-uchwala]] § 12 ust. 2 pkt 2; § 53 ust. 3 pkt 6).

Więcej: [[dzs-mpzp-infrastruktura-i-komunikacja]].

### Sieć obiecana przez sprzedającego

Z57 obiecuje w umowie „konkretne zobowiązania dotyczące terminowej budowy sieci kanalizacyjnej i wodociągowej” oraz likwidację istniejącego szamba ([[dzs-oferta-i-mail-z57]]).

> [!warning] Nie wiadomo, kto zbuduje sieć
> Strona „Inwestycje” gminy zawiera tylko spis kategorii finansowania, bez listy zadań (https://samorzad.gov.pl/web/gmina-siepraw/inwestycje). Wniosek: nie wiadomo, kto zbuduje sieć przy działkach 2834/x (gmina, Z57 czy inny inwestor). Zapytaj Z57 i Urząd Gminy.

Zapytaj przed aktem:

- Kto będzie właścicielem sieci po budowie? Czy gmina ją przejmie i od kiedy?
- Czy są już warunki przyłączenia i projekt sieci? Jaki jest termin budowy?
- Co się stanie, jeśli Z57 nie zbuduje sieci w terminie (kara umowna, zatrzymanie części ceny)?
- Czy przewód kanalizacyjny w 2834/9 (KIUT) to sieć gminna, czy prywatny przewód do szamba?

## Prąd – TAURON Dystrybucja

- Wniosek o warunki przyłączenia online: https://www.tauron-dystrybucja.pl/przylaczenie-do-sieci/wniosek-online (portal: https://portal.tauron-dystrybucja.pl/).
- Do wniosku: dane, opis obiektu (dom jednorodzinny), moc przyłączeniowa (kW), tytuł prawny do działki (nie jest konieczny, zob. niżej), plan zabudowy lub szkic (https://www.tauron-dystrybucja.pl/-/media/offer-documents/dystrybucja/przylaczenie/materialy-informacyjne/td-obsluga-wniosku-wp.ashx).
- Termin wydania warunków wraz z projektem umowy dla grupy V (dom, do 1 kV): do 21 dni (źródło: https://www.tauron-dystrybucja.pl/-/media/offer-documents/dystrybucja/przylaczenie/materialy-informacyjne/td-obsluga-wniosku-wp.ashx).
- Opłata przyłączeniowa: ok. 73,63 zł netto za 1 kW dla przyłącza kablowego (źródło wtórne, artykuł z 29.09.2026: https://muratordom.pl/instalacje/przylacza/przylacza-do-dzialki-ile-kosztuja-prad-woda-kanalizacja-i-gaz-oraz-jak-dlugo-sie-czeka-aa-TrFg-VVus-bRUL.html). Sprawdź stawkę w taryfie TAURON Dystrybucja.

> [!question] Do sprawdzenia
> Aktualna stawka opłaty przyłączeniowej w taryfie TAURON Dystrybucja na 2026 r.

> [!tip] Wniosek przed aktem
> Wniosek o warunki przyłączenia może złożyć też osoba bez tytułu prawnego do działki. We wniosku zaznacz pole „nie posiadam tytułu prawnego do korzystania z Obiektu”. Wtedy o możliwości przyłączenia decyduje TAURON. Możecie więc złożyć wniosek przed aktem (źródło: td-obsluga-wniosku-wp.ashx, slajd „Brak tytułu prawnego”).

### Linia przez 2834/8 i 2834/9 – kolizja

Mapa KIUT pokazuje linię elektroenergetyczną wzdłuż N granicy 2834/8 i 2834/9 ([[dzs-uzbrojenie-terenu]]).

- MPZP dopuszcza przebudowę i skablowanie linii (zmianę przebiegu) ([[dzs-mpzp-uchwala]] § 53 ust. 6 pkt 1). Przy kolizji z nowym obiektem dopuszcza przebudowę sieci ([[dzs-mpzp-uchwala]] § 53 ust. 1 pkt 6).
- Procedura TAURON: (1) wniosek o **uzgodnienie branżowe**, (2) wniosek o **warunki usunięcia kolizji**, (3) **umowa** o sposobie wykonania i finansowania przebudowy. Za wniosek pobierana jest opłata wg cennika usług pozataryfowych (https://www.tauron-dystrybucja.pl/uslugi-dystrybucyjne/uzgodnienia-branzowe).
- Jeśli to przyłącze (a nie linia sieci): przebudowę może zrobić wykonawca wybrany przez Was, na podstawie warunków usunięcia kolizji i umowy, albo TAURON (co najmniej 12 miesięcy od umowy, opłata wg rzeczywistych nakładów) (https://www.tauron-dystrybucja.pl/przylaczenie-do-sieci/przebudowa-przylacza). Dla linii sieci sposób wykonania i finansowania ustala porozumienie po warunkach usunięcia kolizji (https://www.tauron-dystrybucja.pl/uslugi-dystrybucyjne/uzgodnienia-branzowe).

> [!question] Do sprawdzenia
> Kto płaci za przebudowę linii? Zwykle płaci ten, kto wnioskuje o usunięcie kolizji, ale strona TAURON tego wprost nie mówi. Zapytaj Z57, czy przebudowa linii wchodzi w jego zobowiązania. Zapytaj też, czy linia ma służebność przesyłu wpisaną w KW.

> [!question] Do sprawdzenia
> Minimalna odległość domu od linii nN i SN. Nie znalazłem wiarygodnego źródła z liczbą. Projektant musi uzgodnić lokalizację domu z TAURON. Najpierw ustal napięcie linii (nN 0,4 kV czy SN 15 kV) na mapie do celów projektowych.

## Gaz – PSG

- Operator dystrybucyjny w Małopolsce: Polska Spółka Gazownictwa, Oddział Zakład Gazowniczy w Krakowie.
- KIUT: najbliższy gazociąg ok. 47 m na SW od narożnika SW 2834/8 (odczyt z `dzs-mapa-uzbrojenie.png`). Na działkach i do 3 m od nich nie ma przewodu gazowego (`dzs-kiut-przeciecia.json`). Flaga `przewod_gazowy._any_in_bbox = true` oznacza tylko, że przewód jest w obszarze analizy (obwiednia działek + 40 m), a nie odległość 40 m.
- Rysunek MPZP pokazuje gazociąg wysokiego ciśnienia ok. 17–18 m od 2834/8 (pomiar z rastra).
- MPZP utrzymuje sieć gazową i wymaga stref kontrolowanych wzdłuż gazociągów ([[dzs-mpzp-uchwala]] § 53 ust. 4).

> [!question] Do sprawdzenia
> Czy gazociąg obok działek to sieć niskiego ciśnienia, do której można się przyłączyć. Sprawdź w PSG (wniosek o warunki przyłączenia, strona www.psgaz.pl). W 2022 r. gminy Metropolii Krakowskiej zgłaszały brak budżetu PSG na przyłącza (https://globenergia.pl/gminy-metropolii-krakowskiej-bez-przylaczy-gazowych-wymiana-palenisk-nie-przyspieszy/). Aktualnej sytuacji nie sprawdziłem.

## Telekomunikacja

- KIUT nie pokazuje przewodów telekomunikacyjnych w okolicy działek (`dzs-kiut-przeciecia.json`).
- MPZP w terenach MN dopuszcza tylko infrastrukturę telekom. o nieznacznym oddziaływaniu ([[dzs-mpzp-uchwala]] § 53 ust. 7 pkt 3).

> [!question] Do sprawdzenia
> Dostępność światłowodu i internetu radiowego/5G pod adresem. Zapytaj operatorów po nadaniu numeru porządkowego.

## Weryfikacja

- 2026-10-27: sprawdzono ze źródłami pierwotnymi; poprawiono 8 miejsc (zob. [[dzs-raport-weryfikacji-2026-10-27]]).
- 2026-10-27 (runda 2, spójność i kompletność): sprawdzono ze źródłami pierwotnymi; poprawiono 2 miejsca (zob. [[dzs-raport-weryfikacji-2026-10-27]]).

## Powiązane

- [[dzialki-siepraw]]
- [[dzs-uzbrojenie-terenu]] · [[dzs-dane-gis-i-3d]]
- [[dzs-mpzp-infrastruktura-i-komunikacja]] · [[dzs-mpzp-uchwala]]
- [[dzs-urzad-gminy-siepraw]] · [[dzs-z57-real-estate]] · [[dzs-transakcja]]
- [[dzs-procedura-budowy]] · [[dzs-ryzyka]]
- [[dzs-harmonogram]] · [[dzs-pomysly]] · [[dzs-transakcja]]
