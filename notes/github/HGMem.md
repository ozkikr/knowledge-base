---
url: https://github.com/Encyclomen/HGMem
type: github-repo
languages: [Python]
tags: [RAG, hypergraph, memory, LLM, multi-step-reasoning]
date_saved: 2026-02-14
---
# HGMem: Hypergraph-based Memory for Multi-step RAG

## Summary
HGMem is a working memory framework for LLMs that uses hypergraph-based memory structures to model high-order correlations between concepts. It improves multi-step RAG for sense-making questions where answers cannot be found directly in documents, dynamically constructing task-specific memory structures.

## Key Points
- Uses hypergraph structures to capture complex relational patterns beyond simple pairwise connections
- Dynamically constructs working memory tailored to specific questions
- Significantly outperforms existing RAG methods on sense-making tasks
- Adapts to different question types and domains
- Based on paper: "Improving Multi-step RAG with Hypergraph-based Memory for Long-Context Complex Relational Modeling"

## Related
- [[LightRAG]]
- [[RAG-Anything]]
- [[knowledge-graphs]]
