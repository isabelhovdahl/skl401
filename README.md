# SKL401 — Introduction to Python

Source repository for the [SKL401 course website](https://isabelhovdahl.github.io/skl401/), a digital seminar on Python programming for the Master in Economics and Business Administration (MØA) at NHH.

This repo contains the source files used to build the site. Students taking the course should use the [published website](https://isabelhovdahl.github.io/skl401/) rather than this repo directly.

## Structure

- `01-...` – `05-...` — course chapters, one folder per part, containing the `.qmd` source files for each lesson
- `data/` — datasets used in the lessons and exercises throughout the course
- `index.qmd` — the site's welcome/landing page
- `_quarto.yml` — Quarto book configuration (chapter order, site settings)
- `docs/` — rendered site output, published via GitHub Pages

## Building locally

The site is built with [Quarto](https://quarto.org/). To render it locally:

```
quarto render
```

or, to preview with live reload:

```
quarto preview
```

Rendered output is written to `docs/`, which is what GitHub Pages serves.

## Found a mistake?

If you spot an error in the course material, please open an issue or reach out at [isabel.hovdahl@nhh.no](mailto:isabel.hovdahl@nhh.no).
