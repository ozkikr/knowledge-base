---
url: https://github.com/riyaz-ali/sqlite
type: github-repo
languages: [Go, C]
tags: [sqlite, extensions, golang, cgo]
date_saved: 2026-02-14
---
# riyaz-ali/sqlite

## Summary
A Go library for building SQLite extensions that can be loaded dynamically at runtime or linked statically at build-time. It provides a low-level cgo interface for creating custom functions, virtual tables, collations, and hooks.

## Key Points
- Build SQLite extensions in Go using `-buildmode=c-shared` to produce .so/.dll files
- Supports scalar, aggregate, and window functions
- Custom virtual tables, collation sequences, and commit/rollback hooks
- Requires a working C compiler (cgo)
- MIT licensed; available at `go.riyazali.net/sqlite`

## Related
- [[sqlite]]
- [[golang]]
- [[sqlite-extensions]]
