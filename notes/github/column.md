---
url: https://github.com/kelindar/column
type: github-repo
tags: [go, columnar-store, bitmap-indexing, in-memory, database]
date_saved: 2026-02-14
---
# column

## Summary
A high-performance, columnar, in-memory storage engine in Go with bitmap indexing. It supports fast querying, updates, and iteration with zero heap allocations, SIMD-enabled aggregates, and transaction isolation.

## Key Points
- Cache-friendly columnar (SoA) data layout minimizing cache misses
- Zero heap allocation during queries; batch updates ~12ns per operation
- SIMD-enabled aggregates (sum, avg, min, max) and filtering via bitmap indexes
- Transaction isolation with commit/rollback, concurrent updates via sharded latches
- Supports TTL expiration, primary keys, change data streams, and snapshotting

## Related
- [[columnar-databases]]
- [[bitmap-indexing]]
- [[go-libraries]]
- [[in-memory-stores]]
