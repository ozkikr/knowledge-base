---
url: https://github.com/michaelfeil/infinity
type: github-repo
languages: [Python]
tags: [embeddings, reranking, inference-server, clip, colpali]
date_saved: 2026-02-14
---
# Infinity

## Summary
A high-throughput, low-latency REST API for serving text-embeddings, reranking models, CLIP, CLAP, and ColPali. Built on PyTorch, Optimum, and CTranslate2 with FlashAttention support, it serves any HuggingFace model with dynamic batching.

## Key Points
- Supports embedding, reranking, CLIP, CLAP, and ColPali models
- Multiple inference backends: PyTorch, ONNX, TensorRT, CTranslate2
- Hardware support: NVIDIA CUDA, AMD ROCm, CPU, AWS INF2, Apple MPS
- OpenAI-compatible API (FastAPI-based)
- Multi-model orchestration with dynamic batching

## Related
- [[Text Embeddings]]
- [[Vector Search]]
- [[HuggingFace]]
