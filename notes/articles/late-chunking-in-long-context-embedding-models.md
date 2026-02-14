---
url: https://jina.ai/news/late-chunking-in-long-context-embedding-models/
type: article
tags: [embeddings, rag, chunking, nlp, jina-ai]
date_saved: 2026-02-14
---
# Late Chunking in Long-Context Embedding Models

## Summary
This Jina AI article introduces "Late Chunking," a technique that addresses the lost context problem in RAG pipelines. Instead of chunking text before embedding (losing cross-chunk references like pronouns), late chunking first encodes the full document through the long-context embedding model, then chunks the resulting token representations — preserving contextual information across chunk boundaries.

## Key Points
- Traditional chunking-then-embedding destroys long-distance contextual dependencies (e.g., "its" referencing "Berlin" in an earlier chunk)
- Late chunking runs the full document through the embedding model first, then splits the contextualized token representations
- Leverages long-context embedding models (8K+ tokens) that would otherwise seem unnecessary for chunk-level retrieval
- Avoids heuristic workarounds like sliding windows or multi-pass scans
- Produces higher-quality chunk embeddings that retain document-level context

## Related
- [[WeKnora]] - RAG framework
- [[mnemo]] - Context caching approach (alternative to chunking)
- [[avocadodb]] - Deterministic context database
