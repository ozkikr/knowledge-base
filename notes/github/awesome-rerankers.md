---
url: https://github.com/agentset-ai/awesome-rerankers
type: github-repo
languages: [Python]
tags: [reranking, RAG, information-retrieval, cross-encoders, awesome-list]
date_saved: 2026-02-14
---
# Awesome Rerankers

## Summary
A curated awesome-list of reranking models, libraries, and resources for RAG applications. Covers cross-encoder, T5-based, and LLM-based rerankers, plus commercial APIs, framework integrations, benchmarks, and evaluation metrics.

## Key Points
- Rerankers use cross-encoders to jointly encode query-document pairs for higher accuracy than vector search
- Typical pipeline: retrieve 50-100 candidates with vector search, rerank to top 3-5
- Covers models: Cohere Rerank, Voyage Rerank 2.5, Jina Reranker v2, BGE-Reranker
- Includes integrations for LangChain, LlamaIndex, and Haystack
- Three reranking types: pointwise, pairwise, listwise

## Related
- [[RAG]] - retrieval-augmented generation pipelines
- [[vector-search]] - first-stage retrieval
- [[cross-encoders]] - core reranking architecture
