---
url: https://github.com/KellerJordan/modded-nanogpt
type: github-repo
languages: [Python, CUDA]
tags: [llm-training, gpt, optimization, speedrun, muon-optimizer]
date_saved: 2026-02-14
---
# Modded-NanoGPT

## Summary
A collaborative/competitive speedrun to train a GPT-2 (124M) model as fast as possible on 8x H100 GPUs. Descended from Karpathy's NanoGPT/llm.c, it achieves the target 3.28 val loss in under 100 seconds (vs original 45 minutes) using under 500M tokens (vs 10B).

## Key Points
- Trains GPT-2 124M to 3.28 val loss in <100 seconds on 8xH100
- Uses Muon optimizer, rotary embeddings, QK-Norm, ReLU²
- FP8 matmul, Flash Attention 3 with sliding window
- Zero-init projections, skip connections from embedding to every block
- Community-driven speedrun with many contributors

## Related
- [[muon-optimizer]]
- [[nanogpt]]
- [[llm-training-efficiency]]
- [[flash-attention]]
