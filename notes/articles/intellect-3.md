---
url: https://www.primeintellect.ai/blog/intellect-3
type: article
tags: [llm, reinforcement-learning, moe, open-source, training]
date_saved: 2026-02-14
---
# INTELLECT-3: A 100B+ MoE Trained with Large-Scale RL

## Summary
Prime Intellect releases INTELLECT-3, a 106B parameter Mixture-of-Experts model trained with SFT and RL on top of GLM 4.5 Air base model. It achieves SOTA performance for its size across math, code, science, and reasoning benchmarks, outperforming many larger frontier models. The complete recipe is open-sourced.

## Key Points
- 106B parameter MoE model trained on 512 NVIDIA H200 GPUs across 64 nodes
- Built with PRIME-RL, a custom async-only RL framework (always off-policy)
- Uses verifiers library and Environments Hub for RL training environments
- Async training is key to scaling RL to long-horizon agentic rollouts
- Full open-source release: weights, frameworks, datasets, RL environments, evaluations

## Related
- [[Reinforcement Learning]]
- [[Mixture of Experts]]
- [[Open Source LLMs]]
- [[GRPO]]
