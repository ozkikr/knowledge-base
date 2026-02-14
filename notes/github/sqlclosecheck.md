---
url: https://github.com/ryanrolds/sqlclosecheck
type: github-repo
languages: [Go]
tags: [linter, sql, go, static-analysis, database]
date_saved: 2026-02-14
---
# sqlclosecheck

## Summary
A Go linter that checks whether SQL rows and statements are properly closed. Helps prevent resource leaks in Go database code by statically analyzing that `sql.Rows` and `sql.Stmt` objects have their `Close()` methods called.

## Key Points
- Detects unclosed `sql.Rows` and `sql.Stmt` objects
- Static analysis tool (Go vet compatible)
- Prevents database connection/resource leaks
- Integrates with golangci-lint

## Related
- [[10x-commandments-of-highly-effective-go]] - Go best practices
- [[bleve]] - Go library
