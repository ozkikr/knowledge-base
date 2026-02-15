---
url: https://motherduck.com/blog/obsidian-rag-duckdb-motherduck/
type: article
tags: [rag, duckdb, obsidian]
date_saved: 2026-02-15
---
# Building an Obsidian RAG with DuckDB and MotherDuck
## Summary
This article details a local-first RAG system built on Obsidian notes, using DuckDB vector search locally and MotherDuck for browser-based sharing. The author combines semantic retrieval with Obsidian backlinks to surface both direct and hidden idea connections. It also covers practical architecture choices, chunking strategy, and deployment trade-offs.

## Key Points
- Implements markdown-aware chunking and embeddings (including BGE-M3) for semantic retrieval over notes.
- Uses Obsidian wikilinks/backlinks as graph signals for multi-hop exploration and "graph-boosted" ranking.
- Stores and queries note metadata, links, chunks, and embeddings in DuckDB.
- Extends local workflows to a web app via MotherDuck + DuckDB WASM in the browser.
- Emphasizes privacy and control through local-first model execution and data ownership.

## Related
- [[Obsidian]]
- [[DuckDB Vector Search]]
- [[Graph-Enhanced RAG]]
