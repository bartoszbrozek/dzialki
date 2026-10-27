---
type: source
domain: dzialki-siepraw
created: 2026-10-27
updated: 2026-10-27
sources: ["[[dzs-z57-real-estate]]"]
tags: [zrodlo, oferta, mail, cena, z57, transakcja, zweryfikowane-2026-10-27]
aliases: ["oferta Z57", "mail od sprzedającego", "warunki sprzedaży", "oferta xlsx"]
---

# Oferta xlsx i mail z warunkami sprzedaży (Z57)

Dwa dokumenty od sprzedającego: tabela cenowa (xlsx) i mail z warunkami sprzedaży 3 działek. Strona podaje je wiernie i tłumaczy każdy warunek prostym językiem. Analizę i ryzyka opisuje [[dzs-transakcja]].

Pliki raw: `raw/dzialki-siepraw/documents/dzs-oferta-2834-8-9-11.xlsx` (oferta), `raw/dzialki-siepraw/notes/2026-10-27-mail-warunki-sprzedazy-z57.md` (mail). Sprzedający: [[dzs-z57-real-estate]].

## Oferta – tabela xlsx

| Działka | Pow. | Księga wieczysta | Cena netto za m² | Cena netto | Cena brutto (VAT 23%) |
|---|---|---|---|---|---|
| [[dzs-dzialka-2834-8]] | 833 m² | KR1Y/00091772/7 | 175 zł | 145 775,00 zł | 179 303,25 zł |
| [[dzs-dzialka-2834-9]] | 777 m² | KR1Y/00091772/7 | 200 zł | 155 400,00 zł | 191 142,00 zł |
| [[dzs-dzialka-2834-11]] | 249 m² | KR1Y/00059868/1 | 200 zł | 49 800,00 zł | 61 254,00 zł |
| **Suma** | **1859 m²** | 2 księgi | – | **350 975,00 zł** | **431 699,25 zł** |

Źródło: `dzs-oferta-2834-8-9-11.xlsx`, arkusz 1, wiersze 2-5. Formuły w arkuszu: cena netto = pow. × cena za m²; brutto = netto × 1,23.

Arkusz sumuje tylko ceny (E5, F5). Suma powierzchni 1859 m² pochodzi z maila i zgadza się z 833 + 777 + 249. »2 księgi« policzyliśmy z kolumny KW.

Wartości obliczone (nie ma ich w arkuszu):

| Wielkość | Wartość | Jak policzono |
|---|---|---|
| VAT razem | 80 724,25 zł | 431 699,25 − 350 975,00 |
| Cena brutto za m² – 2834/8 | 215,25 zł | 175 × 1,23 |
| Cena brutto za m² – 2834/9 i 2834/11 | 246,00 zł | 200 × 1,23 |
| Średnia cena brutto za m² | 232,22 zł | 431 699,25 / 1859 |
| 50% ceny 2834/11 | 30 627,00 zł | 61 254 / 2 |

## Mail – warunki punkt po punkcie

Mail napisał prezes zarządu Z57 do pośrednika. Treść oryginalna jest w pliku raw (patrz wyżej).

Numery 1–8 nadaliśmy sami. Mail nie ma numerowanych punktów.

| Nr | Warunek z maila (skrót) | Co to znaczy dla nas |
|---|---|---|
| 1 | Sprzedaż 2834/8, 2834/9, 2834/11, łącznie 1859 m² | Kupujemy wszystkie 3 działki razem. 2834/8 nie ma własnego dojazdu, więc nie kupujemy jej osobno ([[dzs-dzialka-2834-8]]). |
| 2 | Cena 431 699 zł brutto (w tym VAT 23%), wyliczenie w xlsx | Płacimy cenę z VAT. Nie płacimy PCC 2% ([[dzs-koszty-zakupu-i-podatki]]). Mail zaokrągla cenę: xlsx podaje 431 699,25 zł. |
| 3 | Umowa sprzedaży w ostatnich dniach listopada 2026, bez umowy przedwstępnej | Do aktu nic nie wiąże stron. Sprzedający może zmienić warunki albo sprzedać komuś innemu. Patrz [[dzs-ryzyka]]. |
| 4 | 50% ceny 2834/11 (30 627 zł) odroczone do wykreślenia hipoteki eFaktor, ale nie mniej niż 9 miesięcy (wg maila: najwcześniej po 1.09.2027). Przy umowie płacimy 401 072 zł (kwota z maila). | Przy akcie płacimy 401 072 zł. Resztę (30 627 zł) płacimy, gdy z KW 2834/11 zniknie hipoteka, ale najwcześniej po 1.09.2027. To nasze zabezpieczenie. |
| 5 | Zobowiązanie kupujących: sprzedaż za 1 zł małego trójkąta w SE narożniku 2834/11 albo służebność dla właściciela działki „poniżej”; powód wg maila: »musimy wyrównać granicę po likwidacji drogi« | Sprzedajemy za 1 zł albo dajemy służebność do małego trójkąta w SE narożniku 2834/11 dla właściciela działki „poniżej”. Wg naszej interpretacji geometrii ULDK to ok. 2,2 m² przy 2834/13 (nie ma tego w mailu, [[dzs-dzialka-2834-11]]). Wniosek: wariant ze służebnością jest dla nas prostszy (bez podziału geodezyjnego i bez podatku od sprzedaży). Sprzedający nazywa 2834/11 drogą do likwidacji – sprawdź dział III KW KR1Y/00059868/1 (służebności przejazdu dla innych działek). |
| 6 | Przy akcie służebności do wszystkich głównych dróg dojazdowych | Mail obiecuje służebności do „wszystkich głównych dróg dojazdowych”, bez numerów działek. Wniosek: chodzi najpewniej o pasy 725/41 i 726/1. Według EGiB (grupa 15) nie są one gminne. Wymagaj w akcie numerów wszystkich działek obciążonych służebnością, aż do drogi publicznej. Bez dostępu do drogi publicznej nie dostaniesz pozwolenia na budowę ([[dzs-transakcja]]). |
| 7 | W umowie konkretne zobowiązania: terminowa budowa sieci kanalizacyjnej i wodociągowej | Mail nie mówi wprost, kto buduje sieci. Wniosek: najpewniej sprzedający, bo to on proponuje zapis. Zażądaj w akcie: kto jest zobowiązany, data oddania sieci, kary umowne, prawo wykonania zastępczego. |
| 8 | Likwidacja istniejącego szamba; obecnie brak służebności; prawo likwidacji po określonej dacie | Na 2834/9 jest prawdopodobnie szambo. Według mapy KIUT prowadzi do niego przewód od strony 2834/6 (wniosek, [[dzs-uzbrojenie-terenu]]). Szambo nie ma służebności. Mail zapowiada „prawo do jego likwidacji po określonej dacie”, ale nie mówi, czyje to prawo, kto likwiduje i kto płaci. Ustal to w akcie. |

> [!warning] Mail to nie umowa
> Warunki z maila wiążą dopiero po wpisaniu do aktu notarialnego. Przed aktem poproś o projekt aktu i porównaj go z tą tabelą ([[dzs-checklista-przed-zakupem]]).

> [!question] Do sprawdzenia
> - Mail nie podaje terminu budowy sieci ani daty likwidacji szamba.
> - Mail nie mówi, co się stanie, gdy hipoteka eFaktor nie zostanie wykreślona.
> - Mail nie podaje pola ani numeru działki-odbiorcy trójkąta.
> - Mail nie wskazuje, które drogi są „główne” i gdzie łączą się z drogą publiczną.

## Weryfikacja

- 2026-10-27: sprawdzono ze źródłami pierwotnymi; poprawiono 7 miejsc (zob. [[dzs-raport-weryfikacji-2026-10-27]]).
- 2026-10-27 (runda 2, spójność i kompletność): sprawdzono ze źródłami pierwotnymi; poprawiono 2 miejsca (zob. [[dzs-raport-weryfikacji-2026-10-27]]).

## Powiązane

- [[dzialki-siepraw]] · [[dzs-mapa-mysli.canvas]]
- [[dzs-transakcja]] · [[dzs-z57-real-estate]] · [[dzs-koszty-zakupu-i-podatki]]
- [[dzs-dzialka-2834-8]] · [[dzs-dzialka-2834-9]] · [[dzs-dzialka-2834-11]]
- [[dzs-checklista-przed-zakupem]] · [[dzs-ryzyka]] · [[dzs-harmonogram]] · [[dzs-szybkie-odpowiedzi]]
