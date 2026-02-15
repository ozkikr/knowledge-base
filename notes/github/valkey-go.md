---
url: https://github.com/valkey-io/valkey-go
type: github-repo
languages: [Go, C, Shell]
tags: [valkey, go-client, caching]
date_saved: 2026-02-15
---
# valkey-go
## Summary
valkey-go is a high-performance Go client for Valkey focused on throughput and latency improvements through automatic pipelining. It includes first-class support for server-assisted client-side caching and cluster-oriented deployments. The library also ships integrations for observability, compatibility adapters, and helper modules for common patterns.

## Key Points
- Auto-pipelines concurrent non-blocking commands to reduce round trips and system calls.
- Implements client-side cache primitives with invalidation support and cache-hit introspection.
- Provides additional packages for cache-aside, distributed locking, hooks, and OpenTelemetry.
- Supports cluster/sentinel deployments and Redis ecosystem modules through a typed builder API.

## Related
- [[Valkey]]
- [[Redis clients]]
- [[Client-side caching]]
