---
url: https://github.com/LeanerCloud/testvet
type: github-repo
languages: [Go]
tags: [static-analysis, testing, code-coverage, go-tools, linter]
date_saved: 2026-02-14
---
# testvet - Go Static Analysis for Missing Test Coverage

## Summary
testvet is a Go static analysis tool that identifies functions missing test coverage and misplaced test functions. It uses AST-based call analysis (not naming conventions) combined with `go test -cover` data to find untested code and tests in wrong files.

## Key Points
- Finds functions/methods not called from any test function via AST analysis
- Detects low coverage functions below a configurable threshold using go test -cover
- Identifies misplaced tests that primarily call functions from a different source file
- Handles methods with receivers including generics
- Option to exclude private/unexported functions from analysis

## Related
- [[go-testing]]
- [[static-analysis]]
- [[code-coverage]]
- [[linter]]
