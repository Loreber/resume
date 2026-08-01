# Currículum de Lorena Bersabé Granado

Dos currículums de una página, escritos en LaTeX y optimizados para lectura humana y sistemas ATS:

- `lorena-bersabe-granado-es.tex`: edición en español de España.
- `lorena-bersabe-granado-en.tex`: edición en inglés estadounidense.

Ambos usan `cv-style.sty`, que reproduce la tipografía del currículum de Juan: Charter a 10 pt, nombre a 25 pt, títulos de sección en negrita y enlaces negros. `main.tex` apunta a la edición española para mantener un punto de entrada cómodo en el editor.

## Compilación

Con `latexmk`:

```sh
latexmk -xelatex lorena-bersabe-granado-es.tex
latexmk -xelatex lorena-bersabe-granado-en.tex
```

O directamente con XeLaTeX (dos pasadas para estabilizar enlaces y metadatos):

```sh
xelatex lorena-bersabe-granado-es.tex
xelatex lorena-bersabe-granado-es.tex
xelatex lorena-bersabe-granado-en.tex
xelatex lorena-bersabe-granado-en.tex
```

Los enlaces del encabezado y de los proyectos son clicables en ambos PDF.
