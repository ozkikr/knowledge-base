---
url: https://blog.fillmore-labs.com/posts/errors-1/
type: article
tags: [go, error-handling, programming, best-practices]
date_saved: 2026-02-14
---
# Understanding Go Error Types: Pointer vs. Value

## Summary
This article explores a subtle bug when modernizing Go error handling from type switches to `errors.As`. The core issue is that `errors.As` with a pointer target (`*SomeError`) won't match errors returned as values (`SomeError`), silently changing program behavior.

## Key Points
- Type switch `case CriticalAddonsOnlyError:` matches value types, but `errors.As(err, &target)` with `*CriticalAddonsOnlyError` target only matches pointer types
- This mismatch fails silently — code compiles but behaves differently
- Go standard library is inconsistent: `json.SyntaxError` uses pointer, `aes.KeySizeError` uses value
- Since Go 1.13, `errors.Is` and `errors.As` are preferred over direct comparisons and type assertions
- Always verify whether error types are designed to be used as pointers or values

## Related
- [[go-error-handling]]
- [[go-best-practices]]
