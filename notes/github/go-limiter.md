---
url: https://github.com/sethvargo/go-limiter
type: github-repo
languages: [Go]
tags: [rate-limiting, middleware, http, distributed-systems]
date_saved: 2026-02-14
---
# go-limiter - Rate Limiting Package for Go

## Summary
A supersonic rate limiting package for Go with HTTP middleware. Designed for configurability and flexibility without compromising throughput, suitable for HTTP servers and distributed workloads.

## Key Points
- Token bucket rate limiter with configurable tokens and intervals
- Built-in HTTP middleware via httplimit package with RFC-compliant headers
- In-memory store included; extensible store interface
- Sets X-RateLimit-Limit, X-RateLimit-Remaining, X-RateLimit-Reset, Retry-After headers
- Simple Take() API returning tokens, remaining, reset, and ok status

## Related
- [[go-libraries]]
- [[go-retry]]
- [[http-middleware]]
