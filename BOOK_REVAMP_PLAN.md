# R Book Revamp Plan

## Goal

Turn the inherited bookdown demo and accumulated R coursework into a clean,
dependable R study book without losing useful source material.

## Phase 1 — Safe foundation

- [x] Audit the Git repository, remote, working tree, source layout, and live
  GitHub Pages site.
- [x] Identify local RStudio state, generated output, duplicate datasets, and
  coursework that should not be published automatically.
- [x] Define project-specific AI and content rules.
- [x] Replace recursive chapter discovery with an explicit canonical list.
- [x] Simplify the standard build to HTML.
- [x] Remove obsolete tracked state and generated artifacts.
- [x] Render and verify the cleaned book.
- [x] Rename the local folder to `002_r_book`.

## Phase 2 — Editorial review

- Standardize chapter hierarchy, terminology, prose, and code style.
- Split large foundation chapters into focused lessons.
- Test examples without globally permitting errors.
- Add concise chapters on functions, iteration, debugging, data manipulation,
  visualization, reproducibility, and modeling workflow.
- Add exercises and solutions only after the explanatory chapters are stable.

## Phase 3 — Coursework curation

- [x] Inventory coursework by topic, uniqueness, portability, attribution, and
  data dependency.
- [x] Integrate useful, generalizable material into canonical chapters.
- [x] Avoid retaining supplied datasets when no canonical example requires
  them.
- [x] Delete confirmed duplicate, obsolete, generated, or unsuitable local
  archive material after the expanded book passes validation.

## Audit notes

- The public book is linked from the personal website and currently reachable.
- The repository began from a bookdown demo and has only one historical commit.
- The pre-cleanup working tree mixed meaningful source reorganization with
  RStudio state, generated output, and relocated course datasets.
- Two directories contained identical copies of 332 air-pollution CSV files.
- The former `rmd_subdir: yes` setting unintentionally treated coursework and
  notebook-style files as public book chapters.
- Archived coursework was reviewed locally under the Git-ignored
  `__REPO/archive/` directory. Its final disposition is recorded in
  `ARCHIVE_INVENTORY.md`.
