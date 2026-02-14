---
url: https://github.com/Shaivpidadi/refrag
type: github-repo
languages: [Python]
tags: [rag, retrieval, llm, micro-chunking, compression]
date_saved: 2026-02-14
---
# REFRAG: Representation-Focused Retrieval Augmented Generation

## Summary
REFRAG improves RAG systems by using micro-chunking (16-32 tokens) instead of large chunks (512-1024), with query-time compression that dynamically decides whether to send raw or compressed chunks to the LLM. Based on arXiv:2509.01092.

## Key Points
- Micro-chunking at 16-32 tokens for fine-grained retrieval
- No LLM calls during indexing (direct encoding) — blazing fast
- Query-time compression: high-priority chunks get full detail, others compressed to keywords
- Mixed context strategy reduces token usage while maintaining quality
- Based on REFRAG research paper (arXiv:2509.01092)

## Related
- [[rag]]
- [[context-compression]]
- [[vector-search]]
- [[chunking-strategies]]
