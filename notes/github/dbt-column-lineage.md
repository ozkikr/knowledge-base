---
url: https://github.com/Fszta/dbt-column-lineage
type: github-repo
languages: [Python]
tags: [dbt, data-lineage, impact-analysis, sqlglot, data-engineering]
date_saved: 2026-02-14
---
# dbt-column-lineage - Column-Level Lineage & Impact Analysis for dbt

## Summary
dbt-column-lineage provides open-source column-level lineage and impact analysis for dbt projects. It uses SQLGlot to parse SQL and helps answer "what happens if I change this column?" with an interactive web explorer for visualizing dependencies and transformations.

## Key Points
- Column-level impact analysis showing affected models, transformations, and exposures
- Interactive web explorer UI for visual lineage exploration
- Powered by SQLGlot for SQL parsing across dialects
- Distinguishes pass-through columns from transformed ones
- Install via pip (`dbt-col-lineage`); works with dbt compile + docs generate output

## Related
- [[dbt]]
- [[data-lineage]]
- [[sqlglot]]
- [[data-engineering]]
