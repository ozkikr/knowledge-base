---
url: https://github.com/kelindar/timeline
type: github-repo
languages: [Go]
tags: [scheduler, real-time, task-scheduling, concurrency, performance]
date_saved: 2026-02-14
---
# Timeline

## Summary
A high-performance, in-memory task scheduler for Go with 10ms resolution. Uses a bucketing system for scalable scheduling, designed for real-time and concurrent applications like game loops and real-time updates.

## Key Points
- 10ms scheduling precision with bucketing design
- Thread-safe for concurrent multi-threaded use
- Predictable linear memory consumption
- Best for frequent short-lived tasks, not long-term scheduling
- Dependency-free, in-process scheduler

## Related
- [[roaring]] - Go data structures
- [[arc]] - time-series data
