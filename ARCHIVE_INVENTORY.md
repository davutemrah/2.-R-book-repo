# Archived Coursework Inventory

## Purpose

This inventory records how the local, Git-ignored archive was curated. Useful
ideas were rewritten in original language as small, tested book examples. Raw
course instructions, answer keys, copied exercise prose, supplied datasets,
and generated files were not added to the public repository.

## Decisions

| Archived material | Main topic | Final disposition |
| --- | --- | --- |
| `legacy_notes/00_01_intro_legacy.Rmd` | R objects, files, vectors | General concepts integrated into R Foundations; raw file removed. |
| `legacy_notes/00_02_data_legacy.Rmd` | Vectors, matrices, data frames, factors | General concepts integrated into Vectors and Data Structures; raw file removed. |
| `Assignment2/` | Closures, caching, and `<<-` | Closure and state concepts integrated into Control Flow and Functions; course instructions and answer removed. |
| `Sample_for_loop.Rmd`, `week3-assignment_example.Rmd`, `zombie_attack.R` | `for` and `while` loops | Loop patterns integrated with safer indexing and preallocation; redundant exercises removed. |
| `loop/week3_looping.Rmd`, `loop/looping-swirl.Rmd` | Apply family, splitting, grouped operations | General patterns integrated into Iteration and Grouped Operations; copied course dialogue and dependencies removed. |
| `loop/week3-debugging.Rmd` | Warnings, errors, traceback, and debugging | Rewritten into Debugging and Testing; intentionally failing and interactive examples removed. |
| `week4-simulation/week4.Rmd`, `swirl-application.Rmd` | Random generation, sampling, simulation, profiling | Reproducible concepts integrated into Simulation and Reproducibility; copied exercise narration removed. |
| `functions/`, `data/specdata/` | Air-pollution assignment functions and 332 CSV files | Removed as course-answer material with a large supplied-data dependency; no canonical chapter requires it. |
| `assignment3/` | Hospital-ranking assignment, answers, and supplied data | Removed as course-specific answer material unsuitable for the public study book. |
| `notes.R` | Unfinished external-data plotting exercise | Removed because it depends on unavailable data and does not add unique material. |
| `summation_example.R`, empty `testdir/` files | Small practice snippets | Removed after confirming the canonical chapters cover the concepts. |
| `.Rproj`, `.Rhistory`, `.DS_Store`, notebook HTML, and generated PDFs | Editor or generated state | Removed as non-source clutter. |

## Result

The useful archive topics now appear in six new canonical chapters:

1. Control Flow and Functions
2. Iteration and Grouped Operations
3. Data Manipulation
4. Missing and Non-finite Values
5. Simulation and Reproducibility
6. Debugging and Testing

The raw local archive was removed only after the expanded book rendered and its
examples passed validation. Earlier tracked material remains recoverable from
Git history where applicable.
