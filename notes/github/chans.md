---
url: https://github.com/nalgeon/chans
type: github-repo
languages: [Go, Markdown, YAML]
tags: [go, concurrency, channels, pipelines]
date_saved: 2026-02-15
---
# chans
## Summary
chans is a Go package of composable channel primitives for building concurrent data pipelines. It intentionally stays low-level and unopinionated so developers keep control over goroutines, cancellation, buffering, and error handling. The library focuses on predictable building blocks rather than heavy abstractions.
## Key Points
- Implements common functional-style operations such as Map, Filter, Reduce, Chunk, Merge, and Partition.
- Designed to work cleanly with context cancellation and user-managed orchestration patterns.
- Avoids opinionated concurrency frameworks, enabling custom worker and lifecycle strategies.
- Well-suited for idiomatic Go streaming and pipeline composition.
## Related
- [[go-agent]]
- [[concurrency]]
- [[asyncmachine-go]]
