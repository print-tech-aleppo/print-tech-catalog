# Print Tech Catalog — Gemini version (self-contained)

The product catalog for Print Tech (RTL Arabic, mobile-first, silver +
kiwi + white, 57 products, search, filters, favorites, lightbox, deep
links). This is the MAIN customer-facing site:
https://print-tech-aleppo.github.io/print-tech-catalog/

Fully self-contained since 2026-11-18: the page reads its data from the
local `catalog.json` and `images/` in this repo — it no longer fetches
anything from the 1tarekdesign-web account. Future catalog edits must be
synced here (copy the rebuilt `catalog.json` + any new images from
`site/` and push to this repo).

Small fixes applied after Gemini's build (see `gemini-version/` for the
original file): lightbox "Next" button bug, sticky filter bar alignment,
footer logo in color, multi-image thumbnails in the lightbox, keyboard
arrows, branches + Instagram moved to the bottom.
