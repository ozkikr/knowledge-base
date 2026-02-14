---
url: https://blog.abdellatif.io/production-rag-processing-5m-documents
type: article
tags: [rag, production, document-processing, vector-search]
date_saved: 2026-02-14
---
# Production RAG: What I Learned from Processing 5M+ Documents

## Summary
Practical lessons from 8 months building production RAG systems for Usul AI (9M pages) and an enterprise legal AI (4M pages). Started with LangChain/LlamaIndex prototypes that looked great on 100 docs but fell apart at scale, then systematically rewrote components ranked by ROI.

## Key Points
- Query generation (LLM reviews thread, generates multiple semantic + keyword queries in parallel) was high-impact
- Reranking is the highest-value 5 lines of code: 50 chunks in → 15 out
- Chunking strategy requires the most effort; ensure chunks are logical units
- Injecting metadata (title, author) alongside chunk text significantly improves answers
- Query routing detects non-RAG questions and handles them differently
- Stack: Turbopuffer, custom extraction, text-embedding-3-large, Zerank reranker, GPT 4.1

## Related
- [[agentset]]
- [[rag-architecture]]
- [[vector-databases]]
