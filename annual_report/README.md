# Annual progress report (LaTeX)

Import this folder into Overleaf as a project, or zip it and upload. The main file is `main.tex`.

- Compiler: pdfLaTeX (Overleaf default). Bibliography: BibTeX via `natbib` (`references.bib`).
- Packages used: geometry, amsmath, booktabs, enumitem, caption, tikz (positioning, arrows.meta, shapes.geometric, fit, calc, backgrounds), pgfplots (compat 1.18), natbib, hyperref. All are in a standard TeX Live distribution.
- Every diagram is drawn in TikZ inside `figures/` (the CAPM graph, the three knowledge bases, the question-answering loop), so there are no image files to upload.
- Sections live in `sections/`: `01_problem` (the task and the three measured failures), `02_method` (what makes the system), `03_novelty` (against existing work), `04_results`, `05_limitations_next`. No table of contents, no appendix; the target length is under 10 pages at 10pt.

Local build (if a TeX distribution is installed):

    latexmk -pdf main.tex

or, with tectonic:

    tectonic main.tex

The numbers in the report are taken from the project log (`CLAUDE.md`) and the run reports under `runs/` as of 9 November 2026.
