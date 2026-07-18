# Printables Index

An index of my **printable reference posters** — print-ready wall posters
built entirely from HTML/CSS (no design tools) and rendered to PDF with
[Vivliostyle CLI](https://vivliostyle.org/) (CSS Paged Media).

Each repo ships the same set of deliverables:

- **Digital PDFs** — RGB, embedded fonts, 5 mm bleed and crop marks
- **Press-ready PDFs** — PDF/X-1a, CMYK, fonts outlined; hand these to a print shop
- **PNG exports** — trim-only rasters for screens or casual printing

All posters come in three landscape sizes: **120 × 80 cm** (primary),
**A1** (84.1 × 59.4 cm), and **A2** (59.4 × 42 cm).

## Index

### Incoterms® 2020 Wall Poster
[![View Repo](https://img.shields.io/badge/View%20Repo-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Incoterms_Poster)

The 11 Incoterms® 2020 rules organized into three responsibility groups
(buyer bears most, shared, seller bears most), with a journey diagram showing
where risk passes from seller to buyer.

[![Incoterms poster preview](https://raw.githubusercontent.com/danielrosehill/Incoterms_Poster/main/posters/preview/incoterms-poster-120x80.png)](https://github.com/danielrosehill/Incoterms_Poster)

---

### The Eurobox System — Wall Poster
[![View Repo](https://img.shields.io/badge/View%20Repo-blue?style=flat-square&logo=github)](https://github.com/danielrosehill/Eurobox_Poster)

The Eurobox / Euro-container system: the 600 × 400 mm module and its
subdivided footprints, the ladder of standard heights with gross volumes, and
how the boxes roll up into Euro pallet loads and 20-ft container (TEU) loads.
Companion piece to the Incoterms poster — same sizes, same stack, same design
language.

[![Eurobox poster preview](https://raw.githubusercontent.com/danielrosehill/Eurobox_Poster/master/posters/preview/eurobox-poster-120x80.png)](https://github.com/danielrosehill/Eurobox_Poster)

---

## Printing guidance

Send the **press-ready PDF/X-1a** file for your size to the print shop and
tell them the trim size — bleed, crop marks, CMYK, and outlined fonts are
already baked in. Print at 100 % (no "fit to page") and cut at the marks.
150–200 gsm matte poster paper works well. Fuller guidance lives in each
poster repo's README.

## Stack

All posters share the same pipeline: a single HTML/CSS master template per
poster rendered to PDF at each size with Vivliostyle CLI driving a local
Chrome/Chromium; Ghostscript produces the press-ready variants and Poppler
(`pdftoppm`) rasterizes the PNGs. Typeface is IBM Plex Sans (+ Condensed),
vendored under the SIL OFL 1.1. Designed with
[Claude Code](https://claude.com/claude-code).

## Adding a new printable

1. Create a separate public repo for the poster (one repo per poster).
2. Add an entry above: name, View Repo badge, 1–2 sentence description, and
   the 120 × 80 preview image hotlinked from the repo's
   `posters/preview/` directory.
