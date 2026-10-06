# Economics research project template

Use this repository as a starting point for an individual or team economics project. When creating a project repository from this template, choose **Private** during setup unless the authors and Society have explicitly approved a public workspace. Keep the Society-supported project under the organization so the team can hand it over when members graduate.

## Start a project

1. Create a repository from this template and choose a clear, stable project name.
2. Fill in `metadata.yml` and `docs/PROJECT_PLAN.md` before substantial analysis begins.
3. Identify sources and terms for every dataset. The Society’s [shared data repository](https://github.com/Pondi-Uni-Economics-Society/Database-) includes a [DuckDB guide](https://github.com/Pondi-Uni-Economics-Society/Database-/tree/main/datasets/macroeconomic-indicators/duckdb).
4. Put reproducible analysis code under `analysis/` and document the exact steps in `docs/REPRODUCIBILITY.md`.
5. Keep drafts and review history in `manuscript/`. Agree with co-authors how feedback and authorship will be handled.
6. Before public release, confirm permissions, any ethics or department approvals, author consent, and the publication destination.

## Suggested folders

- `docs/`: project plan, methods, and reproducibility notes
- `data/`: documentation and references to data sources
- `analysis/`: scripts and notebooks
- `manuscript/`: working-paper drafts and final text
- `tests/`: checks for the data preparation or analysis workflow

Never commit credentials, participant identifiers, confidential or restricted research data, or files that consent or licensing does not allow you to share. A private GitHub repository is not secure storage for restricted data. Use University-approved storage and seek required review before collecting or using sensitive research data.
