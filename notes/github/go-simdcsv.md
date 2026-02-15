---
url: https://github.com/nnnkkk7/go-simdcsv
type: github-repo
languages: [Go]
tags: [go, csv, simd]
date_saved: 2026-02-15
---
# go-simdcsv
## Summary
go-simdcsv is a SIMD-accelerated CSV parser for modern Go runtimes. It aims to be a drop-in replacement for encoding/csv while improving throughput on supported hardware.

## Key Points
- Maintains API compatibility with Go's standard encoding/csv patterns.
- Uses SIMD acceleration for higher performance parsing.
- Includes fallback behavior for environments without required CPU support.
- Best suited for high-volume CSV ingestion pipelines.

## Related
- [[Go Performance]]
- [[SIMD]]
- [[CSV Processing]]
