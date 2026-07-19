# R for Data Science

This repository is the canonical source for Davut Ayan's R study book. It is
intended for data-science learning, practical reference, and interview review.

Published book: <https://davutemrah.github.io/2.-R-book-repo/>

## Repository structure

- `index.Rmd` — book metadata and introduction.
- `__REPO/00_Basics/*.Rmd` — canonical foundation chapters.
- `__REPO/archive/` — optional local-only coursework and legacy notes. This
  directory is excluded from both Git and the public book.
- `_bookdown.yml` — explicit canonical chapter order and publication target.
- `_output.yml` — HTML book configuration.
- `docs/` — generated GitHub Pages output; do not edit it by hand.
- `BOOK_REVAMP_PLAN.md` — cleanup status and future editorial work.
- `ARCHIVE_INVENTORY.md` — disposition of older coursework and practice files.

## Build locally

From the repository root, run:

```bash
sh _build.sh
```

The HTML site is written to `docs/`.

## Safe editing workflow

1. Edit an R Markdown source file, not generated HTML.
2. Add a new canonical chapter explicitly to `_bookdown.yml`.
3. Keep examples deterministic, portable, and non-interactive.
4. Build the complete HTML book.
5. Review source and generated changes separately.
6. Commit and push only after approval.

## Current scope

The canonical book contains eight coherent chapters covering R foundations,
data structures, functions, iteration, data manipulation, missing values,
simulation, and debugging. Generalizable ideas from older coursework were
rewritten and tested; redundant, course-specific, and unsuitable local archive
material was removed. See `ARCHIVE_INVENTORY.md` for the decisions.
