---
url: https://github.com/sanonone/kektordb
type: github-repo
languages: [Go]
tags: [vector-database, graph-database, rag, hnsw, embedded-database]
date_saved: 2026-02-14
---
# KektorDB

## Summary
An embeddable, in-memory vector + graph database written in pure Go. It fuses HNSW with a lightweight semantic graph, combining vector similarity with explicit relationships without the complexity of a full graph database. Follows the SQLite philosophy: serverless, zero dependencies.

## Key Points
- HNSW engine with hybrid search (BM25 + vector) and metadata filtering
- Lightweight graph layer for N-Hop traversal and context retrieval
- Embeddable (like SQLite) or runs as lightweight microservice
- Persistent storage via AOF + Snapshot
- Built-in RAG pipeline with GraphRAG context

## Related
- [[vector-databases]] [[graph-databases]] [[rag]] [[go]] [[hnsw]] [[embedded-database]]
