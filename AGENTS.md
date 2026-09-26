# Repository agent guide

## Repository workflow and completion

`jrnl/` holds Python code and `tests/` pytest/BDD coverage. Follow `CONTRIBUTING.md`, including its development-branch convention. Python is >=3.10,<3.14; use Poetry/poetry.lock and `poetry install`. `poetry run poe test` runs configured lint and tox tests; inspect definitions for focused checks and retain required ordering.

Use temporary config and synthetic journals for CLI/encryption/import/migration tests. Never target real journal data. Docs checking can delete generated outputs and invoke browser tooling; read it first. Report preservation/round-trip evidence separately from package builds.

Continue the authorized change through relevant validation and repair of failures it causes; preserve unrelated work. Report checks actually run, commands only inspected, and exact missing prerequisites. Ask only when a material decision, missing authorization, or required input blocks progress; continue independent reversible work. Existing mandatory contribution and validation gates still apply.
