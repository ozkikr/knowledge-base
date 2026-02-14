---
url: https://github.com/apple/ml-clara
type: github-repo
languages: [Python]
tags: [rag, retrieval-augmented-generation, compression, apple, machine-learning]
date_saved: 2026-02-14
---
# CLaRa - Continuous Latent Reasoning for RAG

## Summary
CLaRa is Apple's state-of-the-art end-to-end Retrieval-Augmented Generation model that bridges retrieval and generation with continuous latent reasoning. It achieves 32x-64x document compression while preserving essential information through a three-stage training approach.

## Key Points
- Three-stage training: compression pretraining → compression instruction tuning → end-to-end fine-tuning
- Achieves 32x-64x compression rates while preserving semantic information
- Unifies retrieval and generation to avoid redundant encoding
- Models available on HuggingFace (Base, Instruct, E2E variants)
- Addresses limitations of reconstruction-based objectives in soft compression

## Related
- [[rag]]
- [[memvid]]
- [[document-compression]]
- [[retrieval-augmented-generation]]
