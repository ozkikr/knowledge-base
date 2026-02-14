---
url: https://www.anthropic.com/engineering/contextual-retrieval
type: article
tags: [RAG, contextual-retrieval, embeddings, BM25, reranking, Anthropic]
date_saved: 2026-02-14
---
# Contextual Retrieval in AI Systems

## Summary
Anthropic's engineering post on Contextual Retrieval, a method that dramatically improves RAG retrieval by adding context to chunks before embedding. Using Contextual Embeddings and Contextual BM25, it reduces failed retrievals by 49%, and by 67% when combined with reranking.

## Key Points
- Traditional RAG loses context when chunking documents, leading to retrieval failures
- Contextual Retrieval adds document-level context to each chunk before embedding
- Combines Contextual Embeddings + Contextual BM25 for hybrid retrieval
- 49% reduction in failed retrievals; 67% with reranking added
- For small knowledge bases (<200K tokens), just include everything in the prompt with caching
- BM25 catches exact matches (error codes, IDs) that semantic embeddings miss

## Related
- [[RAG]]
- [[BM25]]
- [[Embeddings]]
- [[Advanced RAG Techniques]]
