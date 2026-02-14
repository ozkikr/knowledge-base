---
url: https://github.com/sidequery/yardstick
type: github-repo
languages: [C++, SQL]
tags: [duckdb, sql, measures, analytics, extension]
date_saved: 2026-02-14
---
# Yardstick — Measures in SQL for DuckDB

## Summary
Yardstick is a DuckDB extension implementing Julian Hyde's "Measures in SQL" paper. It adds measure-aware SQL to DuckDB, enabling aggregations that automatically re-aggregate when query context changes — percent-of-total, year-over-year comparisons, and drill-down analytics without CTEs or window functions.

## Key Points
- Implements the AGGREGATE() function with AT modifiers for context-aware aggregation
- Enables percent-of-total calculations without CTEs or window functions
- Adds SEMANTIC SELECT syntax for measure-aware queries
- Based on the academic paper arXiv:2406.00251 by Julian Hyde
- Installable from DuckDB community extensions

## Related
- [[duckdb]] [[sql-analytics]] [[measures-in-sql]] [[olap]]
