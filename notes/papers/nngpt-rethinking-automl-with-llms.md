---
url: https://arxiv.org/abs/2511.20333v1
type: paper
tags: [automl, llm, neural-architecture-search, computer-vision, self-improving-ai]
date_saved: 2026-02-14
---
# NNGPT: Rethinking AutoML with Large Language Models

## Summary
NNGPT is an open-source framework that turns an LLM into a self-improving AutoML engine for neural network development, primarily for computer vision. It integrates five LLM-based pipelines: zero-shot architecture synthesis, HPO, accuracy prediction, NN-RAG, and reinforcement learning in a closed-loop system.

## Key Points
- Closed-loop system of generation, assessment, and self-improvement for neural networks
- Five synergistic pipelines: zero-shot synthesis, HPO, code-aware prediction, NN-RAG, and RL
- Built on LEMUR dataset as audited corpus with reproducible metrics
- NN-RAG achieves 73% executability on 1,289 targets
- Framework-agnostic via PyTorch adapter with hash-based deduplication saving hundreds of runs

## Related
- [[automl]]
- [[neural-architecture-search]]
- [[llm-code-generation]]
- [[reinforcement-learning]]
