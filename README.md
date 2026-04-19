# Parsed Page eXplorer (PPX) - Undergraduate Thesis

📄 **[Read the Web Version & Download PDF](https://dbresearch-ontariotech.github.io/ppx-paper/)**
💻 **[View the PPX Source Code](https://github.com/dbresearch-ontariotech/ppx-dev/tree/main)**

This repository contains the manuscript, LaTeX source code, and website files for the undergraduate thesis: **"Parsed Page eXplorer (PPX): A Tool Towards Agentic Human Knowledge Distillation"** by Levi Willms (Ontario Tech University, 2026).

## Repository Structure

- `index.md`: The GitHub Pages landing page.
- `assets/`: Contains the compiled `Parsed-Page-eXplorer.pdf`.
- `src/`: Contains all raw LaTeX source files (`main.tex`, `references.bib`, and figures) for reproducible building.

## Building the PDF Locally

If you wish to compile the LaTeX document yourself, navigate to the `src` directory and use your preferred LaTeX compiler (e.g., `pdflatex` or `latexmk`).

For example:

```bash
cd src
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
