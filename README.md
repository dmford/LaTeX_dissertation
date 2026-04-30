# LaTeX_dissertation

This repository contains the LaTeX source files used to compile my dissertation:

**"Causal Evidence on Traffic Stop Policing Bias, Prison Phone Rate Reforms, and Heterogeneous Gas Price Elasticity"**

## Purpose
This repository serves as the central manuscript and document-production repository for the dissertation.

## Structure
- `dissertation_main.tex` : Main dissertation file
- `abstract.tex` : Dissertation abstract
- `chapter1.tex` : Prison phone reform chapter
- `chapter2.tex` : Traffic stop bias chapter
- `chapter3.tex` : Gas tax heterogeneity chapter
- `appendix.tex` : Appendices
- `bibfile.bib` : Bibliography
- `ucr.cls` : UCR dissertation formatting class

## Compilation
Compile `dissertation_main.tex` using:
1. pdflatex
2. bibtex
3. pdflatex
4. pdflatex

## Related Repositories
Each dissertation chapter also has a separate empirical replication repository:
- 01_PRISON_PHONE_paper
- 02_TRAFFIC_BIAS_paper
- 03_GAS_TAX_HETEROGENEITY_paper

## Notes
Large generated files (aux/log/pdf outputs) may be excluded via `.gitignore`.