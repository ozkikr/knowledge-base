---
url: https://github.com/gordonklaus/ineffassign
type: github-repo
tags: [go, linter, static-analysis]
date_saved: 2026-02-14
---

# ineffassign

## Summary
A Go static analysis tool that detects ineffectual assignments — variables that are assigned but never subsequently used. Lightweight and no false positives, though it may miss some cases (e.g., struct fields) due to lack of type information.

## Key Points
- Detects unused variable assignments in Go code
- Zero false positives by design
- Simple usage: `ineffassign ./...` from project root
- Exit code 1 for problems found, 3 for invalid arguments
- Does not analyze struct field assignments

## Related
- [[go-linters]]
- [[static-analysis]]
- [[golangci-lint]]
