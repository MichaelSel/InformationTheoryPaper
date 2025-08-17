arXiv Two-Column LaTeX Template
===============================

Contents
--------
- main.tex                : Two-column template wired for figures, tables, equations
- refs.bib                : BibTeX database (natbib)
- figures/*.pdf           : Placeholder figures (single, subfigs, and full-width)
- tables/results.tex      : Table split out into its own file

How to Compile (TeXworks; LuaLaTeX + BibTeX)
--------------------------------------------
1) Open `main.tex` and select the engine: LuaLaTeX.
2) Compile once (LuaLaTeX).
3) Switch to `BibTeX` in the drop-down and compile once (to build the bibliography).
4) Switch back to LuaLaTeX and compile twice more (to resolve references).

Notes
-----
- Replace PDFs under ./figures with your actual plots/figures.
- Edit or add tables in ./tables and `\input{}` them in `main.tex`.
- If you prefer pdfLaTeX/XeLaTeX, the template will still compile.
