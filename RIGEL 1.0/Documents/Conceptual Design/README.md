# RIGEL 1.0 – Conceptual Design Report

- `main.tex` – entry point; `preamble.tex` – packages and settings.
- `chapters/` – one file per chapter; each section lead edits only their own chapters (owner is in the first comment of each file).
- `figures/` – images (PDF/PNG/SVG exported); reference them by file name only.
- Open points: use `\todo{...}`.
- Build: `latexmk -pdf main.tex`
- Work on your own branch, then open a pull request.
