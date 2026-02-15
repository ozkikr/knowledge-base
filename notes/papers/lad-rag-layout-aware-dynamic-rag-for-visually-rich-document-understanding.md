---
url: https://arxiv.org/abs/2510.07233
type: paper
tags: [rag, document-understanding, layout-aware-retrieval]
date_saved: 2026-02-15
---
# LAD-RAG: Layout-aware Dynamic RAG for Visually-Rich Document Understanding
## Summary
LAD-RAG addresses question answering over visually rich, multi-page documents by combining neural retrieval with a symbolic layout graph. The approach preserves structural and cross-page dependencies during ingestion and performs adaptive evidence retrieval at inference time. Results show higher recall and improved QA quality versus fixed-top-k baselines, with limited latency overhead.

## Key Points
- Targets failures of standard RAG on documents where layout and cross-page links matter.
- Builds a symbolic document graph alongside neural embeddings during indexing.
- Uses an LLM agent to dynamically decide what and how much evidence to retrieve.
- Achieves strong recall on multiple VRD benchmarks without manual top-k tuning.
- Improves end-task QA accuracy while keeping retrieval noise and latency manageable.

## Related
- [[document-ai]]
- [[retrieval-augmented-generation]]
- [[multimodal-reasoning]]
