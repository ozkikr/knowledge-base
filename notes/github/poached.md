---
url: https://github.com/sidequery/poached
type: github-repo
languages: [C++, C, CMake]
tags: [duckdb, sql-parsing, developer-tools]
date_saved: 2026-02-15
---
# poached
## Summary
poached is a DuckDB extension that exposes SQL parsing capabilities for IDEs, editors, analyzers, and other developer tools. It offers both detailed table-function outputs and simpler names-only scalar helpers for common integration patterns. The extension is geared toward syntax intelligence, query introspection, and SQL tooling features.

## Key Points
- Provides parsing APIs for tokens, statements, tables, functions, columns, and WHERE-clause extraction.
- Distinguishes detailed `parse_*` table outputs from lightweight `parse_*_names` scalar outputs.
- Includes validation helpers (`is_valid_sql`, parse error extraction, statement counting).
- Installs via DuckDB community extension workflow (`INSTALL ...; LOAD ...;`).
- Maintains deprecated aliases for backward compatibility while promoting new function names.

## Related
- [[duckdb-extensions]]
- [[sql-analysis]]
- [[developer-tooling]]
