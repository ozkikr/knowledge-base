---
url: https://github.com/tj-actions/coverage-badge-go
type: github-repo
tags: [go, github-actions, testing, coverage, ci-cd]
date_saved: 2026-02-14
---

# coverage-badge-go

## Summary
A GitHub Action that generates coverage badges for Go modules without uploading results to third-party services. Reads go test coverage output and updates README badges automatically.

## Key Points
- Generates coverage badges locally without third-party services
- Works with standard `go test -coverprofile` output
- Auto-commits badge updates to README.md
- Simple integration into existing CI/CD workflows
- Pairs well with tj-actions/verify-changed-files for conditional commits

## Related
- [[github-actions]] - CI/CD platform
- [[go-testing]] - Go's testing ecosystem
- [[codecov]] - third-party alternative for coverage tracking
