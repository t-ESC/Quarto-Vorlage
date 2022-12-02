# Quarto
Quarto® is an open-source scientific and technical publishing system built on Pandoc

-   Create dynamic content with Python, R, Julia, and Observable.
-   Author documents as plain text markdown or Jupyter notebooks.
-   Publish high-quality articles, reports, presentations, websites, blogs, and books in HTML, PDF, MS Word, ePub, and more.
-   Author with scientific markdown, including equations, citations, crossrefs, figure panels, callouts, advanced layout, and more.

# Usage of Template

-   Definition of Parameters in template.qmd
-   Content is written in ./content/_content.qmd
-   Bibtex can be used in ./ads/quellen.bibtex

# Devcontainer

-   There is one!

# Building PDF files
-   might be nessesary to run `package.install("rmarkdown")` in R
-   run `quarto install tinytex` to build .pdf files
-   build the `template.qmd` file
