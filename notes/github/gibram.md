---
url: https://github.com/gibram-io/gibram
type: github-repo
languages: [Go, Python, Shell]
tags: [GraphRAG, Knowledge-Graphs, Retrieval-Augmented-Generation]
date_saved: 2026-02-15
---
# GibRAM
## Summary
GibRAM is an in-memory knowledge graph server for GraphRAG-style retrieval workflows. It combines entity/relationship graph structures with vector search to improve context retrieval beyond plain semantic similarity. The project provides server binaries, Docker options, and a Python SDK for indexing and querying.

## Key Points
- Keeps graph and embedding data together in RAM for low-latency retrieval.
- Supports relationship traversal plus vector similarity for richer context assembly.
- Designed for ephemeral sessions with configurable time-to-live behavior.
- Includes Python SDK components for chunking, extraction, embedding, and querying.
- Distributed via install script and containerized deployment options.

## Related
- [[GraphRAG]]
- [[Knowledge-Graphs]]
- [[Retrieval-Augmented-Generation]]
