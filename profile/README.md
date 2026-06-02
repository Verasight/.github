# Verasight

Verasight provides survey data from verified respondents.

This GitHub organization is for public methodology notes, data-release materials, and research tooling for Verasight survey work.

## Research Approach

Verasight's public site says it verifies respondents before their first answer and describes its recruitment approach as blending probability and non-probability methods. Public methodology materials should document:

- sample source and fielding dates
- respondent verification practices
- weighting approach and benchmark sources, where applicable
- quality-control procedures, where applicable
- questionnaire wording, toplines, and any release-specific caveats

Each public data release keeps findings, questionnaire text, and methodology notes together so readers can evaluate the survey in context.

## Verasight Links

- Website: <https://www.verasight.io/>
- Data Library: <https://data.verasight.io/>
- Reports: <https://www.verasight.io/reports>

## How These Resources Fit Together

- Verasight's website is the main home for company, product, and contact information.
- The Data Library presents key findings from Verasight survey research.
- Report pages provide report-specific instruments, methodology, and source materials.
- GitHub repositories provide structured data-release materials and research tooling when a public file format is useful.

## Public Repositories

Verasight repositories may include:

| Repository | Purpose |
|---|---|
| [`verasight-methodology`](https://github.com/Verasight/verasight-methodology) | Shared public documentation for panel construction, weighting, quality checks, and reporting conventions. |
| [`verasight-data-releases`](https://github.com/Verasight/verasight-data-releases) | Index of public Verasight data releases and report-level metadata. |
| [`verasight-report-variety10126`](https://github.com/Verasight/verasight-report-variety10126) | Report-specific materials for report `variety10126`. |

## How To Use This Org

- Start with [`verasight-data-releases`](https://github.com/Verasight/verasight-data-releases) to find a report and its current publication status.
- Use `verasight-report-*` repositories for report-specific methodology, questionnaire text, toplines, codebooks, citation metadata, and reuse terms.
- Use [`verasight-methodology`](https://github.com/Verasight/verasight-methodology) for shared background on Verasight survey practices.
- Use [data.verasight.io](https://data.verasight.io/) for curated topic pages and readable Data Library summaries.
- Use [reports.verasight.io](https://reports.verasight.io/) as the official source-report destination.

## Data-Release Standard

A public report repository should include:

- `README.md` with study summary, report link, and file inventory
- `docs/methodology.md` with fielding, sample, weighting, and QA notes
- `docs/questionnaire.md` with final question wording and response options
- `data/toplines.csv` with one row per reported response option
- `data/codebook.csv` explaining the data schema
- citation metadata
- license or reuse terms
