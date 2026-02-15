---
url: https://github.com/vstorm-co/memv
type: github-repo
languages: [Python, HTML, Makefile]
tags: [agent-memory, predict-calibrate, temporal-retrieval]
date_saved: 2026-02-15
---
# memv
## Summary
memv is a structured memory system for agents centered on temporal validity and selective extraction. Inspired by Nemori and related work, it extracts prediction gaps rather than indiscriminately storing all observations. It combines bi-temporal fact tracking with hybrid retrieval (vector + BM25 + fusion).
## Key Points
- Implements predict-calibrate extraction to reduce memory noise.
- Tracks event time and transaction time for point-in-time recall.
- Supports contradiction handling via invalidation instead of destructive overwrite.
- Uses SQLite defaults with vector/text indexes for practical local deployment.
## Related
- [[Agent Memory]]
- [[Temporal Knowledge]]
- [[Retrieval Augmented Generation]]
