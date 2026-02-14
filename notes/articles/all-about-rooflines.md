---
url: https://jax-ml.github.io/scaling-book/roofline/
type: article
tags: [performance, ml-systems, hardware, roofline-model]
date_saved: 2026-02-14
---
# All About Rooflines

## Summary
A chapter from JAX-ML's "How To Scale Your Model" book explaining roofline analysis for ML workloads. Covers how to reason about where time goes in deep learning — computation, memory bandwidth, and network communication — with practical formulas and hardware specs for H100 and TPU v6e.

## Key Points
- Time is split between math (FLOPs), HBM bandwidth, and inter-chip communication
- T_math = Computation FLOPs / Accelerator FLOPs/s; T_comms = Communication Bytes / Bandwidth
- H100: ~9.89e14 bf16 FLOPs/s, 3.35TB/s HBM bandwidth; TPU v6e: ~9.1e14 FLOPs/s, 1.6TB/s
- H100s achieve ~80-85% peak FLOPs; TPUs get closer to 95%
- Covers matrix multiplication rooflines and network communication rooflines

## Related
- [[ml-performance]]
- [[gpu-optimization]]
- [[distributed-training]]
