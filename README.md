# Final State Exam

Study material for MUNI BCS state exam - law and security studies

Study material for MUNI BCS state exam - IT

## Struktura

- `main.tex` pouze skládá dokument a obsahuje společnou preamble.
- `technologie/` obsahuje otázky z okruhu **Technologie**.
- `bezpecnost/` obsahuje otázky z okruhu **Bezpečnost**.
- `pravo-a-politika/` obsahuje otázky z okruhu **Právo a politika pro kyberbezpečnost**.
- `uvod-IT.tex`, `uvod-BSS.tex`, `stavova-tabulka.tex` a `zaverecne-poznamky.tex` obsahují původní úvodní a závěrečné části.
- `assets/` obsahuje obrázky použité v otázkách.
- `mindmap/` obsahuje samostatné TikZ šablony pro mind mapy a jeden vyplněný příklad. Návod je v `mindmap/README.md`.

Názvy souborů jsou kvůli spolehlivosti LaTeXu bez diakritiky a bez mezer. Přesné názvy otázek jsou v tabulkách níže a v nadpisech uvnitř souborů.

Číslování v nadpisech uvnitř souborů odpovídá oficiálnímu pořadí v rámci každé kategorie. Kategorie jsou v PDF oddělené samostatnými part stránkami.

## Kontrola podle oficiálního seznamu

Zdroj: oficiální seznam **Otázky B-CS Kyberbezpečnost – jednooborový studijní plán** (FI MU).

### Technologie

| # | Otázka | Soubor | Stav |
|---:|---|---|---|
| 1 | Výpočetní systémy | `technologie/vypocetni-systemy.tex` | hotovo |
| 2 | Operační systémy | `technologie/operacni-systemy.tex` | hotovo |
| 3 | Souborové systémy | `technologie/souborove-systemy.tex` | hotovo |
| 4 | Sítě a síťové aplikace | `technologie/site-a-sitove-aplikace.tex` | hotovo, sloučené původní otázky 4 a 5 |
| 5 | Principy programování | `technologie/principy-programovani.tex` | hotovo |
| 6 | Databáze | `technologie/databaze.tex` | hotovo |
| 7 | Softwarové a informační systémy | `technologie/softwarove-a-informacni-systemy.tex` | hotovo |

### Bezpečnost

| # | Otázka | Soubor | Stav |
|---:|---|---|---|
| 1 | Základní bezpečnostní funkce a jejich zajištění | `bezpecnost/zakladni-bezpecnostni-funkce-a-jejich-zajisteni.tex` | hotovo |
| 2 | Metody autentizace a řízení přístupu | `bezpecnost/metody-autentizace-a-rizeni-pristupu.tex` | hotovo |
| 3 | Analýza a řízení rizik | `bezpecnost/analyza-a-rizeni-rizik.tex` | hotovo |
| 4 | Bezpečnostní architektura | `bezpecnost/bezpecnostni-architektura.tex` | hotovo |
| 5 | Služby kyberbezpečnostního týmu organizace | — | **CHYBÍ** (PV210, PB177) |
| 6 | Kyberútoky | — | **CHYBÍ** (PB177) |

### Právo a politika pro kyberbezpečnost

| # | Otázka | Soubor | Stav |
|---:|---|---|---|
| 1 | Vymezení bezpečnostních studií | `pravo-a-politika/vymezeni-bezpecnostnich-studii.tex` | hotovo |
| 2 | Bezpečnostní strategie | `pravo-a-politika/bezpecnostni-strategie.tex` | hotovo |
| 3 | Ochrana kritické infrastruktury | `pravo-a-politika/ochrana-kriticke-infrastruktury.tex` | hotovo |
| 4 | Právní úprava kyberbezpečnosti v ČR a EU | `pravo-a-politika/pravni-uprava-kyberbezpecnosti-v-cr-a-eu.tex` | hotovo |
| 5 | Kyberkriminalita | `pravo-a-politika/kyberkriminalita.tex` | hotovo |
| 6 | Elektronické důkazy a jejich zajišťování | `pravo-a-politika/elektronicke-dukazy-a-jejich-zajistovani.tex` | hotovo |
| 7 | Ochrana osobních údajů | `pravo-a-politika/ochrana-osobnich-udaju.tex` | hotovo |
| 8 | Elektronický podpis a elektronická pečeť | `pravo-a-politika/elektronicky-podpis-a-elektronicka-pecet.tex` | hotovo |
| 9 | Formální prameny práva v ČR | — | **CHYBÍ** (BVV14K) |
| 10 | Subjektivní a objektivní odpovědnost | — | **CHYBÍ** (BVV14K) |
| 11 | Ochrana spotřebitele online | — | **CHYBÍ** (BI201K) |
| 12 | Odpovědnost ISP | — | **CHYBÍ** (BI201K) |

## Doplňkové téma mimo aktuální oficiální seznam

- `pravo-a-politika/kybervalka.tex` – Kyberválka. V původních materiálech je zpracovaná, ale v aktuálním oficiálním seznamu pro B-CS Kyberbezpečnost už není. Proto je zařazená na konec dokumentu jako doplňkové téma.

## Co chybí

Pro úplnost oficiálního seznamu chybí šest otázek:

- Bezpečnost 5: Služby kyberbezpečnostního týmu organizace (PV210, PB177)
- Bezpečnost 6: Kyberútoky (PB177)
- Právo 9: Formální prameny práva v ČR (BVV14K)
- Právo 10: Subjektivní a objektivní odpovědnost (BVV14K)
- Právo 11: Ochrana spotřebitele online (BI201K)
- Právo 12: Odpovědnost ISP (BI201K)

Otázky 5–6 v okruhu Bezpečnost a otázky 9–12 v okruhu Právo jsou podmíněné absolvovanými předměty. Základní seznam bez nich obsahuje 7 + 4 + 8 = 19 otázek a všechny ty jsou v repozitáři zpracované.
