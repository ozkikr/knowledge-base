---
url: https://github.com/Tencent/WeKnora
type: github-repo
languages: [Python]
tags: [rag, document-understanding, knowledge-base, tencent, llm]
date_saved: 2026-02-14
---
# WeKnora - LLM-Powered Document Understanding & Retrieval Framework

## Summary
WeKnora is Tencent's open-source LLM-powered framework for deep document understanding and semantic retrieval. It follows the RAG paradigm with a modular architecture combining multimodal preprocessing, semantic vector indexing, intelligent retrieval, and LLM inference to provide context-aware answers from complex, heterogeneous documents.

## Key Points
- Modular RAG architecture: multimodal preprocessing → vector indexing → retrieval → LLM inference
- Shared spaces with member invitations and tenant-isolated retrieval
- Agent skills system with sandboxed execution for security
- Built-in Data Analyst agent for CSV/Excel analysis
- Supports multiple search providers (Bing, Google, DuckDuckGo)
- Helm chart for Kubernetes deployment

## Related
- [[late-chunking]] - Improved chunking for embeddings
- [[mnemo]] - Context caching alternative to RAG
- [[avocadodb]] - Deterministic context database
