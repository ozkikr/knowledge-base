---
url: https://github.com/lusingander/gotip
type: github-repo
tags: [go, testing, tui, developer-tools]
date_saved: 2026-02-14
---

# gotip - Go Test Interactive Picker

## Summary
A TUI application for interactively selecting and running Go tests. Supports fuzzy filtering, table-driven subtest detection, test history, and re-running previous tests.

## Key Points
- Fuzzy filtering of test cases in a terminal UI
- Detects subtest names from table-driven tests (partial support)
- Run individual subtests or parent test groups
- Test execution history with re-run capability (`gotip --rerun`)
- Pass additional flags to `go test` via `--` separator

## Related
- [[go-testing]] - Go's testing ecosystem
- [[television]] - fuzzy finder TUI
- [[bubbletea]] - Go TUI framework
