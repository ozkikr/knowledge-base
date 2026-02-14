---
url: https://www.dolthub.com/blog/2025-10-10-how-slow-is-channel-iteration/
type: article
tags: [go, channels, performance, benchmarking, iterators]
date_saved: 2026-02-14
---
# How Slow Is Channel-Based Iteration?

## Summary
DoltHub benchmarks Go channel-based iteration vs Go 1.23 iter package for bridging impedance mismatches in B-tree range scans. Channels introduce goroutine overhead making them significantly slower, while the iter-based solution provides a cleaner and faster alternative for adapting callback-style APIs to pull-based iterators.

## Key Points
- Channels used to bridge callback-style btree iteration to pull-based Next() interface
- Go 1.23 iter package provides a better, faster solution for the same impedance mismatch
- Benchmarks across 10,000-element trees with random range scans
- Channel iterator requires goroutine per scan, adding allocation and scheduling overhead
- Practical guidance: channels are fine when iteration isn't a bottleneck, but iter is preferred

## Related
- [[centrifugo]] - Go real-time infrastructure
- [[go-arch-lint]] - Go tooling
