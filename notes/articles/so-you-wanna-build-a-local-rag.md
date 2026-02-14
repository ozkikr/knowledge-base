---
url: https://blog.yakkomajuri.com/blog/local-rag
type: article
tags: [rag, local-llm, self-hosted, privacy, open-source, benchmarks]
date_saved: 2026-02-14
---
# So You Wanna Build a Local RAG?

## Summary
A practical guide from the Skald team on building a fully local, self-hosted RAG pipeline using open-source components. Covers OSS alternatives for each RAG component (vector DB, embeddings, LLM, reranker, document parsing) and includes benchmarks comparing proprietary vs self-hosted performance.

## Key Points
- Maps each RAG component to OSS alternatives: pgvector, Sentence Transformers, Docling, etc.
- Their local stack: Postgres+pgvector, all-MiniLM-L6-v2, GPT-OSS 20B, cross-encoder reranker
- Docling recommended for document parsing — "it's great"
- Privacy-sensitive orgs shouldn't have to choose between AI capability and data privacy
- Benchmarks show local setups can be competitive with proprietary APIs

## Related
- [[Skald]] [[RAG]] [[pgvector]] [[Docling]] [[Sentence Transformers]] [[self-hosted]]
