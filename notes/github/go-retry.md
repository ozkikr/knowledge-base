---
url: https://github.com/sethvargo/go-retry
type: github-repo
languages: [Go]
tags: [retry, backoff, resilience, error-handling]
date_saved: 2026-02-14
---
# go-retry - Retry with Configurable Backoffs

## Summary
A Go library for facilitating retry logic and backoff. Highly extensible with full control over how and when retries occur, with no external dependencies. Supports constant, exponential, and Fibonacci backoff strategies.

## Key Points
- Built-in backoff algorithms: constant, exponential, Fibonacci
- Extensible via middleware pattern (inspired by Go's HTTP package)
- Context-aware with native Go context support for cancellation
- Concurrent-safe by default
- Zero external dependencies

## Related
- [[go-libraries]]
- [[go-limiter]]
- [[resilience-patterns]]
