# Portfolio and Repository Guide

_Last reviewed: 14 November 2026_

This document explains the public GitHub portfolio, the purpose of each published repository, and the improvements identified during a portfolio review. It is intended for recruiters, collaborators, reviewers, and anyone exploring these projects.

## Portfolio overview

The portfolio contains projects in data analysis, business intelligence, automation, and applied machine learning. The repositories demonstrate several stages of analytical work: defining a business question, exploring data, evaluating approaches, presenting findings, and building practical tools.

Some repositories are published as complete case studies; others are concise demonstrations or dashboards. The notes below describe the current public presentation and the most useful areas for further refinement.

## Public projects

| Repository | Area | What a reader can explore | Recommended documentation improvements |
|---|---|---|---|
| [TED-talks](https://github.com/karinakaisarova-prog/TED-talks) | Data analysis / BI | Analysis notes, business questions, and a linked DataLens dashboard | Make the methodology, dashboard screenshots, and analytical limitations easy to find |
| [HR-analitics](https://github.com/karinakaisarova-prog/HR-analitics) | HR analytics / machine learning | Notebook-based analysis and model metrics | Correct the repository spelling when convenient, cite the dataset source, and document reproducibility |
| [eda-spb-apataments-sales](https://github.com/karinakaisarova-prog/eda-spb-apataments-sales) | Exploratory data analysis | Notebook exploring apartment sales in Saint Petersburg | Correct the repository spelling when convenient, polish the README, and document the dataset source and key conclusions |
| [Business-Metrics-Analysis-Saransk](https://github.com/karinakaisarova-prog/Business-Metrics-Analysis-Saransk) | Business analytics / BI | Dashboard image and business-metrics case study | Add the supporting analytical report, explain metric definitions and methodology, and reconcile figures across materials |
| [used-car-valuation-service](https://github.com/karinakaisarova-prog/used-car-valuation-service) | Applied machine learning | Analytical report and project materials for used-car price prediction | Add the training/evaluation notebook or source code and explain the model-selection trade-off |
| [google-drive-file-renamer](https://github.com/karinakaisarova-prog/google-drive-file-renamer) | Automation | Google Apps Script for renaming files in Google Drive | Document safe preview mode, duplicate-name handling, execution logs, and test scenarios |
| [application-register-automation](https://github.com/karinakaisarova-prog/application-register-automation) | Office automation / VBA | Excel and Word automation modules, documentation, and test materials | Complete and document compilation and target-application testing; keep environment-specific examples generalized |
| [karinakaisarova-prog](https://github.com/karinakaisarova-prog) | Portfolio index | Profile README and links to selected work | Keep the project index current and make the strongest case studies easy to discover |

## How to read the portfolio

For each project, start with its README. A strong project page should answer these questions:

1. What problem or business question does the project address?
2. What data or input materials were used, and where did they come from?
3. What transformations, assumptions, and methods were applied?
4. What are the main findings or results?
5. How can a reviewer reproduce or inspect the work?
6. What are the known limitations?

For analytical projects, the most useful supporting materials are a reproducible notebook or SQL scripts, a clear data dictionary or source reference, metric definitions, and a concise conclusions section. For dashboards, include a working dashboard link, screenshots, and a short explanation of the data model and filters. For automation tools, explain prerequisites, installation, safe execution, expected output, and test coverage.

## Portfolio maintenance principles

- Keep one canonical public repository for each finished project.
- Use clear, consistent repository names and descriptive README files.
- Keep claims, metrics, screenshots, notebooks, and reports aligned.
- Clearly distinguish demonstrated results from planned improvements.
- Provide data provenance and explain any unavailable or excluded data.
- Review links and instructions periodically.
- Keep credentials, personal data, internal infrastructure details, and private project materials out of public documentation.

## Review scope and status

The portfolio review on 14 November 2026 covered 16 repositories: 8 public and 8 private. This public guide describes the published portfolio and general documentation recommendations. Private development repositories and environment-specific findings are intentionally excluded from this public document.

The review was based on repository metadata, README files, directory listings, and selected documentation. It was a documentation and structure review; it did not constitute a full code audit, security assessment, or execution of every notebook, script, and test suite.

Repository contents and recommendations reflect the state observed on the review date. A recommendation indicates a useful improvement, not a claim that the work has already been completed.
