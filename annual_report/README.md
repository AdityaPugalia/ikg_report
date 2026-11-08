# Annual progress report (LaTeX)

Import this folder into Overleaf as a project, or zip it and upload. The main file is `main.tex`.

- Compiler: pdfLaTeX (Overleaf default). Bibliography: BibTeX via `natbib` (`references.bib`).
- Packages used: geometry, amsmath, booktabs, enumitem, caption, tikz (positioning, arrows.meta, shapes.geometric, fit, calc, backgrounds), pgfplots (compat 1.18), natbib, hyperref. All are in a standard TeX Live distribution.
- Every diagram is drawn in TikZ/pgfplots inside `figures/`, so there are no image files to upload.
- Sections live in `sections/`; edit them independently.

Local build (if a TeX distribution is installed):

    latexmk -pdf main.tex

The numbers in the report are taken from the project log (`CLAUDE.md`) and the run reports under `runs/` as of 8 November 2026.
