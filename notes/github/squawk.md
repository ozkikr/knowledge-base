---
url: https://github.com/sbdchd/squawk
type: github-repo
languages: [Rust]
tags: [postgres, SQL, linter, migrations, database]
date_saved: 2026-02-14
---
# Squawk

## Summary
Squawk is a linter for PostgreSQL migrations and SQL that prevents unexpected downtime caused by database migrations. It catches issues like using serial instead of identity columns, varchar instead of text, and other patterns that require expensive locks.

## Key Points
- Lints Postgres migrations to prevent downtime from unsafe schema changes
- Catches issues like prefer-bigint-over-int, prefer-identity, prefer-text-field
- Available via npm, pip, Docker, VSCode extension, and WASM playground
- GitHub Action available for CI integration
- Shows helpful suggestions with exact code fixes

## Related
- [[PostgreSQL]]
- [[Database Migrations]]
- [[SQL Linting]]
- [[DevOps]]
