---
url: https://sakana.ai/ab-mcts/
type: paper
tags: [inference-scaling, mcts, multi-model, collective-intelligence, arc-agi]
date_saved: 2026-02-14
---

# AB-MCTS: Inference-Time Scaling and Collective Intelligence for Frontier AI

## Summary
Sakana AI introduces AB-MCTS (Adaptive Branching Monte Carlo Tree Search), an inference-time scaling algorithm that enables multiple frontier AI models to cooperate. Building on their evolutionary model merging work, this approach combines models like o4-mini, Gemini-2.5-Pro, and DeepSeek-R1-0528 to outperform any individual model on ARC-AGI-2.

## Key Points
- AB-MCTS enables effective trial-and-error across multiple frontier models during inference
- Multi-LLM combination (o4-mini + Gemini-2.5-Pro + R1-0528) outperforms each individual model by large margin on ARC-AGI-2
- Extends 2024 evolutionary model merging research from "mixing to create" to "mixing to use"
- Paper: arxiv.org/abs/2503.04412
- Open implementations: treequest (algorithm) and ab-mcts-arc2 (experiments)

## Related
- [[claude-gemini-bridge]] - practical multi-model delegation
- [[autogen]] - multi-agent framework
