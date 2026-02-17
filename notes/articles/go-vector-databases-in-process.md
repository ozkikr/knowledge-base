---
title: "In-Process Vector Databases for Go"
type: research
tags: [go, vector-database, embeddings, similarity-search, hnsw, ann]
languages: [go, c, cpp]
date_saved: 2026-02-17
---

# In-Process Vector Databases for Go

Research into embedded/in-process vector DB options for Go applications, particularly at scale (millions of vectors).

## Summary

The Go ecosystem for in-process vector search is thin compared to Python (ChromaDB, LanceDB) and Rust (Qdrant). Pure Go options only work at small scale; for millions of vectors, CGo bindings to C/C++ libraries are the practical path.

## Options

### Pure Go

#### kelindar/search
- **URL:** https://github.com/kelindar/search
- **Approach:** Brute-force with SIMD + GPU (Vulkan) acceleration
- **Scale:** <100k vectors
- **Features:**
  - Fully in-process, no external deps
  - Loads GGUF BERT models for embeddings via llama.cpp
  - Cosine/Euclidean similarity
  - Save/load indexes to disk
- **Limitation:** Brute-force only, no ANN indexing — won't scale beyond 100k

#### coder/hnsw
- **URL:** https://github.com/coder/hnsw
- **Approach:** Pure Go HNSW implementation
- **Notes:** Reference/experimental — rolling your own is feasible since HNSW isn't that complex, but you'd be reimplementing what battle-tested C libs already do

### CGo Bindings (Recommended for Scale)

#### usearch (by Unum) ⭐ Recommended
- **URL:** https://github.com/unum-cloud/usearch
- **Approach:** Single-header C core, official Go bindings
- **Scale:** Billions of vectors
- **Features:**
  - HNSW under the hood
  - Single-file index on disk
  - Lightweight C core, minimal CGo overhead
  - Multiple distance metrics
- **Best for:** Production use at 1M-10M+ vectors

#### hnswlib
- **URL:** https://github.com/nmslib/hnswlib
- **Approach:** C++ HNSW implementation, community Go bindings
- **Scale:** Millions of vectors
- **Features:**
  - Battle-tested, been around longer than usearch
  - Well-documented algorithm
- **Caveat:** Go bindings are community-maintained, not official

#### Faiss (by Meta)
- **URL:** https://github.com/facebookresearch/faiss
- **Approach:** C++ library, CGo wrappers exist
- **Scale:** Billions
- **Features:**
  - Multiple index types (IVF, HNSW, PQ, etc.)
  - GPU support
- **Caveat:** Heavier dependency, CGo wrappers are third-party

### Sidecar / Near-In-Process

#### SQLite + vector extension
- **Options:** sqlite-vec or sqlite-vss
- **Approach:** Single-file DB with vector search capability
- **Go driver:** `modernc.org/sqlite` (pure Go, no CGo) — unclear if vector extensions work with it; `mattn/go-sqlite3` (CGo) should work
- **Best for:** When you also need relational queries alongside vectors

#### pgvector
- **URL:** https://github.com/pgvector/pgvector
- **Approach:** PostgreSQL extension
- **Scale:** <50M vectors comfortably
- **Caveat:** Requires a Postgres instance — not truly in-process

## Recommendations by Scale

| Scale | Recommendation |
|-------|---------------|
| <100k | kelindar/search (pure Go, simple) |
| 100k–1M | usearch or hnswlib via CGo |
| 1M–10M | **usearch** (official Go bindings, proven at scale) |
| 10M+ | usearch or Faiss |

## Key Points

- Pure Go ecosystem is immature for vector search at scale
- CGo is unavoidable for millions of vectors with good performance
- usearch is the sweet spot: official Go bindings, lightweight C core, scales to billions
- HNSW is the dominant algorithm across all serious implementations
- At 10M vectors with typical dimensions (384-1536), expect 5-10GB RAM for the index

## Related

- [[go]] [[embeddings]] [[similarity-search]]
