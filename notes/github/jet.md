---
url: https://github.com/go-jet/jet
type: github-repo
tags: [go, sql, query-builder, code-generation, database]
date_saved: 2026-02-14
---
# Jet (go-jet)

## Summary
Jet is a type-safe SQL builder for Go with code generation and automatic query result data mapping. It supports PostgreSQL, MySQL, and SQLite, and is explicitly not an ORM — it generates Go code from your database schema for compile-time safe queries.

## Key Points
- Auto-generates type-safe SQL builder and model types from database schema
- Supports SELECT, INSERT, UPDATE, DELETE with complex joins, subqueries, window functions
- Automatic query result mapping into complex object compositions
- Works with CockroachDB (Postgres wire protocol) and MariaDB (MySQL protocol)
- Not an ORM — preserves full SQL expressiveness with type safety

## Related
- [[go-database-libraries]]
- [[sql-query-builders]]
- [[code-generation]]
