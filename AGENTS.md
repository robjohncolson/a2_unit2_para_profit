# Repository Guidelines

## Project Structure & Materials

This repository contains Algebra 2 PBL resources organized by phase:
- `00_TEACHER_PLANNING_AND_RESOURCES`: calendars, project planners, and reference rubrics.
- `01_PROJECT_LAUNCH_AND_SETUP`: entry events, contracts, hook materials, and menu JSON/TXT files (for example, `01_PROJECT_LAUNCH_AND_SETUP/goldenmonkey_menu.json`).
- `02_MATH_LESSONS_AND_MODULES`: lesson packs and math modules.
- `03_DATA_AND_SURVEY_MATERIALS`: CSV/XLSX datasets and survey templates (for example, `03_DATA_AND_SURVEY_MATERIALS/DATA_Synthetic_Datasets/DATA_GoldenMonkey_BubbleTea.csv`).
- `04_FINAL_PRODUCT_FILES_AND_REPORTS`: report and presentation templates.
- `05_ASSESSMENT_AND_RUBRICS`: assessment rubrics.
- `ZZ_STUDENT_EXEMPLARS` and `backup/`: exemplars and historical copies; edit only when curating, not for day-to-day work.

## Build, Test, and Development Workflow

There is no code build system for this repository. Edit `.docx` files in Word/Google Docs and `.csv`/`.xlsx` files in a spreadsheet tool. When adding data files, open them once to confirm formatting, delimiters, and headers match existing examples.

## File Naming & Content Conventions

Follow existing prefixes:
- Planning: `PLAN_...`, reference: `REF_...`, templates: `TPL_...`, worksheets: `WKS_...`, data: `DATA_...`, rubrics: `RUBRIC_...`, exemplars: `EX_...`, modules/lessons: `MOD_...`, `LESSON_...`, games: `GAME_...`.
- Use descriptive names after the prefix (for example, `MOD_M3_Vertex_by_Hand_Audit.docx`).
- Avoid spaces where possible; prefer `_` or short separators like `M3`.

## Data & Quality Checks

- Keep CSV headers consistent across related datasets.
- Verify numeric fields (prices, quantities, totals) for obvious errors before sharing with students.
- If you generate new datasets, include a short description in the file or a nearby `.txt` note.

## Versioning, Commits & Pull Requests

- Group related changes by phase (for example, “Update launch materials for 2025 unit”).
- Use clear, imperative commit messages such as “Add profit zone module worksheet”.
- Pull requests should summarize instructional changes, list major files touched, and note any breaking changes for existing lesson plans.

## Agent-Specific Instructions

- Respect the directory purposes and naming patterns above.
- Do not delete or rewrite student exemplar work; add new exemplars instead.
- Prefer adding new versions over overwriting original source files when making substantial revisions.

