## 📝 Úvod
Tento Power BI projekt vizualizuje týdenní cvičební plán klienta vytvořený na základě požadavků trenéra.
Cílem je přehledně a interaktivně zobrazit:

- plánované cviky v týdnu

- jejich zaměření na různé svalové skupiny

- rozložení času věnovaného jednotlivým cvičením

- nastavené cíle (targety) klienta

## Projekt využívá možnosti Power BI k interaktivní práci s daty a plnění následujících požadavků:

✅ 2-3 stránky
✅ Minimálně 5 různých typů vizuálů
✅ Filtrování pomocí slicerů
✅ Navigace pomocí bookmarks
✅ Propojení více datových zdrojů
✅ Hierarchii dat (Den → Cvičení)
✅ Measure + kalkulovaný sloupec
✅ Grafická úprava a profesionální design

## 🗂️ Struktura reportu
## Stránka 1 — Týdenní přehled cvičení
Card → Zobrazení celkového počtu cvičení v týdnu

Pie Chart → Podíl typů cvičení podle svalových skupin

Line Chart → Vývoj celkového času cvičení v jednotlivých dnech

Clustered Column Chart → Délka cvičení podle svalových skupin

Matrix → Rozpis cvičení podle dne a typu cvičení

Slicer → Filtrování cvičení dle cíle (Target)

Navigační tlačítka → Přepínání mezi stránkami

## Stránka 2 — Targety (Cíle cvičení)
Table/Matrix → Přehled všech cílů a jejich plánované délky v měsících

Clustered Column Chart → Porovnání délky jednotlivých cílů

Slicer → Filtrování vizualizací podle vybraného cíle (Target)

Navigační tlačítka → Návrat na přehledovou stránku

## 📊 Použité techniky a prvky
- Propojení datových zdrojů
Data načtena z Excel souboru → dvě tabulky Cvičení a Targets

- Propojeno pomocí sloupce Target (kalkulovaný sloupec Target Category)

- Hierarchie
Hierarchie Den → Cvičení pro možnost drill-down v Matrix nebo jiných vizuálech

- Measure
Vytvořená míra → Počet cvičení (COUNTROWS)

- Kalkulovaný sloupec
Vytvořen kalkulovaný sloupec Target Category pomocí funkce SWITCH → přiřazuje cvikům cíle podle svalových skupin

- Uživatelské ovládání
Pomocí Slicerů lze filtrovat cvičení podle zvoleného cíle nebo dne v týdnu

- Pomocí Navigačních tlačítek lze snadno přepínat mezi stránkami

## ✔️ Závěr
Projekt splňuje všechny požadavky zadání a přináší profesionálně zpracovaný report, který umožňuje rychlý přehled o rozložení cvičení v týdnu, kontrolu zaměření cvičení podle cíle, vizuální znázornění plánovaných cílů (targetů) klienta a interaktivní práci s daty


## Autor: Adéla Pečená
