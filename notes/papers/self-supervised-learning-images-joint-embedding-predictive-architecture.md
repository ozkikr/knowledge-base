---
url: https://arxiv.org/abs/2301.08243
type: paper
tags: [self-supervised-learning, computer-vision, I-JEPA, vision-transformers]
date_saved: 2026-02-14
---
# Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture (I-JEPA)

## Summary
Introduces I-JEPA, a non-generative self-supervised learning method for images that learns semantic representations without hand-crafted data augmentations. From a single context block, it predicts representations of target blocks in the same image, guided by a masking strategy emphasizing large-scale semantic targets.

## Key Points
- Predicts representations (not pixels) of masked target blocks from context blocks
- Masking strategy is key: large-scale targets + spatially distributed context
- Highly scalable with Vision Transformers (ViT-Huge/14 on ImageNet in <72h on 16 A100s)
- Strong downstream performance on linear classification, object counting, depth prediction
- Published at ICCV 2023; authored by Mahmoud Assran, Yann LeCun et al.

## Related
- [[yann-lecun-ai-model-i-jepa]] - Meta blog post about I-JEPA
- [[vision-transformers]] - backbone architecture used
- [[self-supervised-learning]] - broader field
