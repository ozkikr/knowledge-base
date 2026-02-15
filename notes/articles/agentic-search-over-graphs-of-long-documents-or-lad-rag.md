---
url: https://pierce-lamb.medium.com/agentic-search-over-graphs-of-long-documents-or-lad-rag-1264030158e8
type: article
tags: [lad-rag, agentic-search, long-documents]
date_saved: 2026-02-15
---
# Agentic Search over Graphs of Long Documents (or LAD-RAG++)
## Summary
This long-form post documents practical implementation lessons from applying LAD-RAG ideas to dense, long-form compliance/legal documents. It argues that layout-aware document graphs plus agentic retrieval can outperform naïve chunk-based RAG on multi-hop and precision-heavy queries. The author also discusses production constraints, especially request economics and GPU orchestration, and proposes a hardened “LAD-RAG++” direction.

## Key Points
- Highlights failure modes of vanilla chunked RAG on long, structured documents.
- Uses layout-aware nodes and cross-page graph edges to preserve author-intended structure.
- Shifts retrieval to an agent/tool loop that explores graph evidence rather than static top-k fetch.
- Discusses implementation trade-offs for large-scale processing on cloud GPUs.
- Connects LAD-RAG to broader trends in agentic search over raw document systems.

## Related
- [[LAD-RAG]]
- [[Agentic Retrieval]]
- [[Document Intelligence]]
