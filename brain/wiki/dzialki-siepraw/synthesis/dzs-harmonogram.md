---
type: synthesis
domain: dzialki-siepraw
created: 2026-10-27
updated: 2026-10-27
sources: ["[[dzs-oferta-i-mail-z57]]", "[[dzs-transakcja]]", "[[dzs-procedura-budowy]]", "[[dzs-warunki-techniczne-odleglosci]]", "[[dzs-dostawcy-mediow]]", "[[dzs-urzad-gminy-siepraw]]", "[[dzs-starostwo-myslenice]]"]
tags: [harmonogram, terminy, os-czasu, budowa, zweryfikowane-2026-10-27]
aliases: ["harmonogram", "oś czasu", "terminy"]
---

# Harmonogram – od dziś do zamieszkania

Oś czasu od 27.10.2026 do budowy domu. Strona pokazuje twarde terminy, terminy z przepisów i zależności między krokami. Daty bez źródła to nasz plan roboczy.

## Twarde terminy

| Data | Zdarzenie | Źródło |
|---|---|---|
| 27.10.2026 | Dziś – start due diligence | – |
| koniec XI 2026 | Akt notarialny, płatność 401 072 zł | [[dzs-oferta-i-mail-z57]], warunek 3 (nasza numeracja) |
| akt + 14 dni | IN-1 albo IR-1 (zależnie od użytku w EGiB) do UG Siepraw | [[dzs-urzad-gminy-siepraw]] |
| po 1.09.2027 (najwcześniej) | Dopłata 30 627 zł po wykreśleniu hipoteki eFaktor | mail ([[dzs-oferta-i-mail-z57]]), [[dzs-transakcja]] |
| do ok. 20.03.2028 | Ostatni dzień na wniosek/zgłoszenie wg starych WT (z oświadczeniem inwestora) | Pb art. 102a ([[dzs-warunki-techniczne-odleglosci]]) |
| 31.07.2027 | Koniec obecnej taryfy wod-kan gminy | [[dzs-dostawcy-mediow]] |
| ok. 31.07.2030 (5 lat od wejścia planu w życie 31.07.2025; Dz. Urz. Woj. Małop. 2025 poz. 4532 z 16.07.2025 + 14 dni, [[dzs-mpzp-uchwala]] §58) | Koniec okresu opłaty planistycznej 20%. Płaci zbywający; może dotyczyć nas tylko przy odsprzedaży przed tą datą | upzp art. 36 ust. 4, art. 37 ust. 3; stawka [[dzs-mpzp-uchwala]] §56, wejście w życie §58 |
| ? | Termin budowy sieci i likwidacji szamba – **do ustalenia w akcie** | [[dzs-transakcja]] |

## Oś czasu

```mermaid
gantt
    title Działki Siepraw – plan roboczy
    dateFormat YYYY-MM-DD
    axisFormat %m.%Y
    section Zakup
    Due diligence, wypis/wyrys, KW      :a1, 2026-10-27, 2026-11-20
    Projekt aktu i negocjacje           :a2, 2026-11-10, 2026-11-25
    Akt notarialny                      :milestone, m1, 2026-11-27, 0d
    IN-1 lub IR-1 (14 dni)              :a3, 2026-11-27, 14d
    Dopłata 30 627 zł (najwcześniej)    :milestone, m2, 2027-09-02, 0d
    section Sieci i media
    Budowa sieci (zobowiązany i termin wg aktu) :s1, 2027-01-01, 2027-08-31
    Likwidacja szamba (data z aktu)     :s2, 2027-06-01, 2027-09-30
    Warunki przyłączenia prądu (21 dni) :s3, 2026-12-01, 21d
    Ewentualne przełożenie linii nN (czas do ustalenia z TAURON) :s4, 2027-02-01, 365d
    section Projekt
    Wznowienie granic, mapa do celów projektowych :p1, 2026-12-01, 2027-02-15
    Projekt domu                        :p2, 2027-02-01, 2027-08-31
    Zgłoszenie z projektem (bufor do 20.03.2028) :p3, 2027-09-01, 2027-10-15
    Termin WT                           :milestone, m3, 2028-03-20, 0d
    section Budowa
    Roboty ziemne (pora sucha)          :b1, 2028-04-01, 2028-06-30
    Stan surowy i wykończenie           :b2, 2028-06-01, 2029-06-30
    Zawiadomienie PINB (14 dni)         :b3, 2029-07-01, 14d
```

Daty w sekcjach „Sieci”, „Projekt” i „Budowa” to plan roboczy. Czasy urzędowe: [[dzs-procedura-budowy]].

## Zależności

```mermaid
flowchart TD
    DD[Due diligence<br/>KW, wypis/wyrys, granice] --> AKT[Akt koniec XI 2026]
    AKT --> IN1[IN-1 lub IR-1 w 14 dni]
    AKT --> TYT[Tytuł prawny do działki]
    DD --> WP[Wnioski o warunki przyłączy<br/>TAURON – możliwy już przed aktem, gmina]
    TYT -.-> WP
    TYT --> MAPA[Mapa do celów projektowych]
    WP --> KOL{Kolizja z linią nN?}
    KOL -- tak --> PRZ[Przełożenie linii<br/>czas do ustalenia]
    KOL -- nie --> PROJ
    MAPA --> PROJ[Projekt domu]
    PRZ --> PROJ
    AKT --> SIEC["Z57 (?) buduje sieci<br/>zobowiązany i termin wg aktu"]
    SIEC --> SZ[Likwidacja szamba]
    SIEC --> SCIEKI[Ścieki do kanalizacji]
    SZ --> PROJ
    PROJ --> ZGL[Zgłoszenie z projektem<br/>przed ok. 20.03.2028]
    ZGL --> BUD[Budowa<br/>21 dni bez sprzeciwu]
    SCIEKI --> ODB[Zawiadomienie PINB<br/>14 dni]
    BUD --> ODB
    AKT --> HIP{Hipoteka eFaktor<br/>wykreślona?}
    HIP -- tak, po 1.09.2027 --> DOP[Dopłata 30 627 zł]
```

## Co blokuje co

| Krok | Zależy od | Dlaczego |
|---|---|---|
| Wnioski o warunki przyłączy | nie wymaga aktu (TAURON) | Wniosek o warunki przyłączenia do TAURON można złożyć także bez tytułu prawnego. Zaznacz wtedy pole „nie posiadam tytułu prawnego do korzystania z Obiektu”. O możliwości przyłączenia decyduje wtedy TAURON (td-obsluga-wniosku-wp.ashx, slajd „Brak tytułu prawnego”, [[dzs-dostawcy-mediow]]). |
| Projekt domu | mapa do celów projektowych, warunki przyłączy, likwidacja szamba, decyzja o linii nN | położenie domu, garażu i podjazdu ([[dzs-uzbrojenie-terenu]]) |
| Zgłoszenie budowy | projekt; termin WT ok. 20.03.2028 | po tej dacie nieznane nowe przepisy ([[dzs-warunki-techniczne-odleglosci]]) |
| Zamieszkanie | kanalizacja (albo szczelne szambo), woda, prąd | oczyszczalnia odradzana w opinii geotechnicznej (s. 9, pkt 14) ([[dzs-opinia-geotechniczna]]) |
| Scalenie 3 działek | wykreślenie hipoteki eFaktor | 2834/11 ma osobną KW; hipoteka eFaktor najpewniej na niej (do sprawdzenia w EKW) |
| Dopłata 30 627 zł | wykreślenie hipoteki i data po 1.09.2027 | warunek z maila ([[dzs-oferta-i-mail-z57]]) |

> [!warning] Najdłuższa ścieżka
> Przełożenie linii nN (czas do ustalenia z TAURON; dla porównania przebudowa przyłącza przez TAURON trwa min. 12 mies. od umowy) i budowa sieci (zobowiązany wg aktu) mogą opóźnić projekt. Wniosek do TAURON można złożyć już przed aktem. Zgłoszenie z projektem warto złożyć do końca 2027 r., z zapasem przed 20.03.2028.

## Weryfikacja

- 2026-10-27: sprawdzono ze źródłami pierwotnymi; poprawiono 10 miejsc (zob. [[dzs-raport-weryfikacji-2026-10-27]]).
- 2026-10-27 (runda 2, spójność i kompletność): sprawdzono ze źródłami pierwotnymi; poprawiono 4 miejsca (zob. [[dzs-raport-weryfikacji-2026-10-27]]).

## Powiązane

- [[dzialki-siepraw]] · [[dzs-mapa-mysli.canvas]]
- [[dzs-procedura-budowy]] · [[dzs-transakcja]] · [[dzs-checklista-przed-zakupem]]
- [[dzs-urzad-gminy-siepraw]] · [[dzs-starostwo-myslenice]] · [[dzs-dostawcy-mediow]]
- [[dzs-warunki-techniczne-odleglosci]] · [[dzs-ryzyka]] · [[dzs-pomysly]]
