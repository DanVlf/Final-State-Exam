# Mind map šablony

Složka obsahuje samostatné šablony pro rychlé kreslení mind map k jednotlivým otázkám.

## Soubory

| Soubor | Co obsahuje |
|---|---|
| `01-radialni-mindmap.tex` | Radiální mind mapu s centrální elipsou a barevnými větvemi. Hodí se pro rychlý přehled pojmů. |
| `02-boxes-mindmap.tex` | Centrální elipsu, hlavní větve jako zaoblené boxy a detaily jako menší boxy. Hodí se pro strukturovanější odpověď. |
| `03-priklad-vypocetni-systemy.tex` | Vyplněný příklad pro otázku **Výpočetní systémy**. Ukazuje, jak šablonu naplnit skutečným obsahem. |

Všechny soubory jsou samostatné dokumenty. Lze je přeložit přímo:

```bash
pdflatex mindmap/01-radialni-mindmap.tex
pdflatex mindmap/02-boxes-mindmap.tex
pdflatex mindmap/03-priklad-vypocetni-systemy.tex
```

## Jak šablonu použít v otázce

1. Otevři šablonu a zkopíruj blok od `\begin{tikzpicture}` do `\end{tikzpicture}`.
2. Vlož ho do souboru s odpovědí na otázku, ideálně na začátek nebo na konec oddílu.
3. Přepiš `TÉMA`, `ČÁST 1`, `detail A` apod. vlastními pojmy.
4. Pokud chceš mapu zmenšit, obal ji například:

```tex
\begin{center}
\resizebox{\linewidth}{!}{%
\begin{tikzpicture}
  ...
\end{tikzpicture}%
}
\end{center}
```

`main.tex` už načítá TikZ a potřebné knihovny, takže vložený blok funguje i v hlavním dokumentu.

## Úpravy vzhledu

- **Barvy:** měň `blue!60!black`, `blue!35` a `blue!12`. Pro jinou kategorii můžeš použít například `green!50!black`, `orange!60!black` nebo `red!50!black`.
- **Velikost centra:** uprav `minimum width` a `minimum height` u stylu `center` nebo `root`.
- **Vzdálenosti větví:** u radiální mapy uprav `level distance` a `sibling angle`.
- **Počet větví:** přidej nebo uber `child { ... }` bloky. U radiální mapy pak uprav `sibling angle` tak, aby součet úhlů seděl (např. 6 větví = 60, 5 větví = 72).
- **Boxy:** šablona s boxy nepoužívá pevné souřadnice `at (x,y)`. Větve jsou umístěné relativně přes `above left=of c` apod. Vzdálenosti měníš jedním parametrem `node distance=3.0cm and 4.5cm`; detaily se posouvají podle svých větví.

## Poznámka

Šablony jsou záměrně bez konkrétního obsahu, aby se daly použít pro jakoukoli otázku. Vyplněný příklad slouží jen jako vzor hustoty a členění.
