---
url: https://github.com/memvid/memvid
type: github-repo
languages: [Rust, Python]
tags: [ai-memory, rag, vector-search, agents, retrieval]
date_saved: 2026-02-14
---
# Memvid

## Summary
Memvid is a single-file memory layer for AI agents that replaces complex RAG pipelines with serverless, portable memory. It packages data, embeddings, search structure, and metadata into one file, achieving +35% SOTA on LoCoMo benchmarks with ultra-low latency.

## Key Points
- Single-file memory system: no databases, fully portable and versioned
- +35% SOTA on LoCoMo benchmark for long-horizon conversational recall
- +76% multi-hop and +56% temporal reasoning vs industry average
- Ultra-low latency: 0.025ms P50, 1,372× higher throughput than standard approaches
- Model-agnostic with Rust core (memvid-core crate) and Python bindings

## Related
- [[rag]]
- [[ml-clara]]
- [[ai-agent-memory]]
- [[vector-databases]]
