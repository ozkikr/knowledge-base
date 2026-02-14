---
url: https://blog.fillmore-labs.com/posts/errors-2
type: article
tags: [go, error-handling, linting]
date_saved: 2026-02-14
---
# The Day the Linter Broke My Code

## Summary
An article about Go error design pitfalls when linters like err113 (via golangci-lint) conflict with correct custom error implementations. Demonstrates how implementing `Is()` and `Unwrap()` methods on custom errors can be broken by linter suggestions to avoid direct error comparisons.

## Key Points
- Shows how to implement custom Go errors with `Is()` and `Unwrap()` methods
- The err113 linter discourages direct `err ==` comparisons, suggesting `errors.Is()` instead
- This can break correct `Is()` implementations that intentionally use direct comparison
- Demonstrates the tension between linter rules and language semantics
- Includes Go Playground examples for hands-on testing

## Related
- [[go-error-handling]] - Go error patterns
- [[golangci-lint]] - Go linting tools
