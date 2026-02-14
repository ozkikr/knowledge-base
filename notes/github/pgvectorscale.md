---
url: https://github.com/timescale/pgvectorscale
type: github-repo
languages: [Rust]
tags: [postgres, vector-search, diskann, embeddings, ai, pgvector]
date_saved: 2026-02-14
---
# pgvectorscale

## Summary
A Postgres extension that complements pgvector with higher performance vector search using StreamingDiskANN index and Statistical Binary Quantization. Achieves 28x lower p95 latency and 16x higher throughput compared to Pinecone at 75% less cost.

## Key Points
- StreamingDiskANN index inspired by Microsoft's DiskANN algorithm
- Statistical Binary Quantization improves on standard Binary Quantization
- Label-based filtered vector search (Filtered DiskANN)
- 28x lower p95 latency vs Pinecone s1 at 99% recall on 50M embeddings
- Written in Rust using PGRX framework, Postgres OSS licensed

## Related
- [[electric]] - Postgres sync engine
- [[roaring]] - bitmap indexing data structures
- [[garage]] - distributed storage
