# Currículum de Lorena Bersabé Granado

Currículum de una página, escrito en LaTeX y optimizado para lectura humana y sistemas ATS.

## Compilación

Con `latexmk`:

```sh
latexmk -pdf main.tex
```

O directamente con pdfLaTeX (dos pasadas para estabilizar enlaces y metadatos):

```sh
pdflatex main.tex
pdflatex main.tex
```

El archivo principal es `main.tex`. Los enlaces del encabezado y de los proyectos son clicables en el PDF.
