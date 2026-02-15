---
url: https://github.com/Siddhant-K-code/distill
type: github-repo
languages: [Go, Dockerfile]
tags: [rag, deduplication, context-engineering]
date_saved: 2026-02-15
---
# Siddhant-K-code/distill
## Summary
Distill is a reliability layer for LLM/RAG context that focuses on deterministic deduplication and compression before prompts are sent to a model. It aims to reduce redundancy, improve consistency, and lower token costs by applying clustering and re-ranking rather than relying on additional LLM calls. The project offers CLI, API, MCP integration, and vector database interoperability.

## Key Points
- Targets common RAG failure modes caused by semantically redundant context.
- Uses deterministic clustering, representative selection, and MMR re-ranking.
- Supports standalone dedupe API and vector-database-backed retrieval flows.
- Provides MCP mode for assistant integration and self-hosting deployment options.
- Includes observability hooks (Prometheus metrics, Grafana dashboard artifacts).

## Related
- [[RAG Pipeline]]
- [[Context Compression]]
- [[Deterministic Retrieval]]
