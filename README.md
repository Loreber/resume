# Lorena Bersabé Granado — Resume / Currículum

One-page, ATS-friendly resumes for junior web developer Lorena Bersabé Granado, available in American English and Castilian Spanish.

Currículums de una página optimizados para sistemas ATS, disponibles en inglés estadounidense y español de España.

## Download / Descargar

- [American English — PDF](https://github.com/Loreber/resume/raw/refs/heads/main/output/pdf/lorena-bersabe-granado-en.pdf)
- [Español de España — PDF](https://github.com/Loreber/resume/raw/refs/heads/main/output/pdf/lorena-bersabe-granado-es.pdf)

Portfolio: [loreber.vercel.app](https://loreber.vercel.app)

## Source / Código fuente

- `lorena-bersabe-granado-en.tex`: American English edition.
- `lorena-bersabe-granado-es.tex`: edición en español de España.
- `cv-style.sty`: shared Charter typography and page layout.
- `main.tex`: default editor entry point for the Spanish edition.

## Build / Compilación

The documents use XeLaTeX and the Charter typeface included with macOS.

Los documentos utilizan XeLaTeX y la familia tipográfica Charter incluida en macOS.

```sh
latexmk -xelatex lorena-bersabe-granado-es.tex
latexmk -xelatex lorena-bersabe-granado-en.tex
```

Without `latexmk`, run XeLaTeX twice for each edition:

```sh
xelatex lorena-bersabe-granado-es.tex
xelatex lorena-bersabe-granado-es.tex
xelatex lorena-bersabe-granado-en.tex
xelatex lorena-bersabe-granado-en.tex
```
