---
url: https://arxiv.org/abs/2512.23236
type: paper
tags: [kernel-optimization, ai-accelerators, mlsys, recommendation-models, meta]
date_saved: 2026-02-14
---
# KernelEvolve: Scaling Agentic Kernel Coding for Heterogeneous AI Accelerators at Meta

## Summary
Presents KernelEvolve, an agentic kernel coding framework for optimizing deep learning recommendation model (DLRM) kernels across heterogeneous hardware (NVIDIA, AMD GPUs, Meta's AI accelerators). Uses graph-based search with retrieval-augmented prompt synthesis, operating at multiple programming abstractions from Triton/CuTe DSL to low-level hardware-agnostic languages.

## Key Points
- Addresses three key challenges: model architecture diversity, kernel primitive diversity, and hardware heterogeneity
- Takes kernel specifications as input and automates kernel generation and optimization
- Uses graph-based search with selection policy, fitness function, and termination rules
- Operates across Triton, CuTe DSL, and low-level hardware-agnostic languages
- Deployed in production at Meta across multiple GPU generations and custom accelerators

## Related
- [[triton-kernels]]
- [[mlsys-optimization]]
- [[recommendation-systems]]
