---
url: https://nsrip.com/posts/goroutineleak.html
type: article
tags: [go, concurrency, goroutines, memory-leaks, patterns]
date_saved: 2026-02-14
---
# Two Concurrency Patterns Which Avoid Goroutine Leaks

## Summary
Explores two patterns from the Go standard library and toolchain that prevent goroutine leaks by design. The first replaces a ticker-in-a-loop with `time.AfterFunc` for periodic flushing, and the second uses a lazily-created worker pool with bounded parallelism via a channel-based queue.

## Key Points
- "Never start a goroutine without knowing how it will stop" (Dave Cheney)
- `time.AfterFunc` pattern: schedule a single flush on write instead of running a persistent ticker goroutine — eliminates leak if stop is forgotten
- Go's `net/http/httputil` reverse proxy was refactored from ticker-loop to AfterFunc pattern (CL 137335)
- Lazily-created worker pool (`par.Queue`): uses a buffered channel as mutex, starts workers on demand, workers exit when backlog empties
- Both patterns avoid leaks structurally rather than relying on callers to clean up

## Related
- [[Go Concurrency]]
- [[Memory Leaks]]
- [[Worker Pools]]
