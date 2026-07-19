# R Book Agent Guide

These instructions apply to the `002_r_book` repository and supplement the
workspace-level `AGENTS.md` and `GIT_PROCESS.md`.

## Purpose

Maintain a practical, methodologically sound R study book for data-science
learning, reference, and interview preparation. Keep the public book focused;
coursework and raw practice material are not automatically book chapters.

## Working rules

1. Read `README.md`, `BOOK_REVAMP_PLAN.md`, `_bookdown.yml`, and `_output.yml`
   before changing the book.
2. Edit source under `__REPO/`; never hand-edit generated HTML in `docs/`.
3. Keep the canonical chapter list explicit in `_bookdown.yml`.
4. Do not enable `rmd_subdir: yes`; it can publish archived coursework by
   accident.
5. Build HTML with `sh _build.sh` after source or navigation changes.
6. Treat `docs/` as generated GitHub Pages output and review it separately.
7. Treat `__REPO/archive/` as local-only and Git-ignored. Do not publish its
   assignments, answer keys, private paths, or copied course material without
   reviewing educational value, attribution, and rights.
8. Prefer portable examples that do not change the working directory, install
   packages, require interaction, or leave files behind.
9. Do not mask failing examples with a global `error = TRUE` setting.
10. Keep changes small and do not migrate publishing frameworks without a
    demonstrated need.

## Content standards

- Explain why a method works, when to use it, and important failure modes.
- Prefer base R or widely used tidyverse tools; name the approach being taught.
- Use deterministic seeds for random examples.
- Use `TRUE` and `FALSE` in teaching code rather than abbreviated `T` and `F`.
- Avoid absolute local paths and generated session output.
- Verify examples during the complete build.
- Explain concerns honestly when a requested change would reduce correctness,
  clarity, or maintainability.

## Git and publishing

- Work on `master` unless Davut requests another strategy.
- Never commit, push, or change GitHub Pages settings without explicit approval.
- Before publishing, review source changes, generated changes, navigation,
  internal links, and at least the homepage plus one affected chapter.
