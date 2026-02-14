---
url: https://arxiv.org/abs/2511.20227v1
type: paper
tags: [rag, document-understanding, visual-qa, multimodal, information-retrieval]
date_saved: 2026-02-14
---
# HKRAG: Holistic Knowledge Retrieval-Augmented Generation Over Visually-Rich Documents

## Summary
HKRAG is a RAG framework for visually-rich documents that captures both salient knowledge (prominent text/visuals) and fine-print knowledge (small text, contextual details). It uses hybrid masking-based retrieval and an uncertainty-guided agentic generator for optimal response generation.

## Key Points
- Addresses bias in existing multimodal RAG toward salient knowledge while neglecting fine-print details
- Hybrid Masking-based Holistic Retriever separately models salient and fine-print knowledge
- Uncertainty-guided Agentic Generator dynamically assesses and integrates two knowledge streams
- Outperforms existing methods in both zero-shot and supervised settings on visual QA benchmarks
- Demonstrates importance of holistic knowledge retrieval for visually-rich document understanding

## Related
- [[rag]]
- [[multimodal-ai]]
- [[document-understanding]]
- [[visual-question-answering]]
