---
url: https://github.com/sqliteai/sqlite-vector
type: github-repo
languages: [C]
tags: [sqlite, vector-search, embeddings, edge-ai, extension]
date_saved: 2026-02-14
---
# SQLite Vector

## Summary
SQLite Vector is a cross-platform SQLite extension that adds vector search capabilities to embedded databases. It stores vectors as BLOBs in ordinary tables with no virtual tables or preindexing required, using only 30MB of memory by default.

## Key Points
- Supports Float32, Float16, BFloat16, Int8, UInt8, and 1Bit vector types with SIMD acceleration
- No virtual tables, no preindexing, no external server required
- Works on iOS, Android, Windows, Linux, macOS, and WASM
- Drop-in for existing SQLite workflows — just `load_extension('./vector')`
- Ideal for on-device, privacy-preserving, offline AI workloads

## Related
- [[sqlite]]
- [[vector-search]]
- [[edge-ai]]
