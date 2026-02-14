---
url: https://github.com/pgvector/pgvector
type: github-repo
languages: [C]
tags: [postgres, vector-search, embeddings, database-extension]
date_saved: 2026-02-14
---
# pgvector - Vector Similarity Search for Postgres

## Summary
pgvector is an open-source PostgreSQL extension for vector similarity search. It supports exact and approximate nearest neighbor search with multiple vector types and distance metrics, allowing you to store vectors alongside your regular data with full ACID compliance.

## Key Points
- PostgreSQL extension for vector similarity search (Postgres 13+)
- Supports single-precision, half-precision, binary, and sparse vectors
- Distance metrics: L2, inner product, cosine, L1, Hamming, Jaccard
- Exact and approximate nearest neighbor search (IVFFlat, HNSW indexes)
- Works with any language that has a Postgres client

## Related
- [[vector-databases]]
- [[lancedb]]
- [[postgresql]]
- [[embeddings]]
