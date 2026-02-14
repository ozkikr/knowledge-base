---
url: https://go.dev/blog/deadcode
type: article
tags: [go, static-analysis, dead-code, tooling]
date_saved: 2026-02-14
---

# Finding Unreachable Functions with deadcode

## Summary
Official Go blog post introducing the `deadcode` tool, which identifies unreachable functions in Go programs. Uses a whole-program analysis algorithm that works forwards from main to determine which functions can actually be called at runtime.

## Key Points
- `deadcode` finds functions that are part of source code but can never be reached in any execution
- Uses whole-program analysis starting from main, tracking concrete types through interfaces
- More precise than simple reference checking — understands which interface implementations are actually reachable
- Install via `go install golang.org/x/tools/cmd/deadcode@latest`
- Motivated by gopls refactoring work where unreachable callers wasted effort

## Related
- [[golang]]
- [[static-analysis]]
- [[go-critic]]
- [[dead-code-elimination]]
