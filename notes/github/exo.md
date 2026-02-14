---
url: https://github.com/exo-explore/exo
type: github-repo
languages: [Python]
tags: [distributed-ai, local-inference, llm, thunderbolt, rdma, mlx]
date_saved: 2026-02-14
---
# exo - Run Frontier AI Locally

## Summary
exo connects all your devices into an AI cluster, enabling running models larger than a single device can handle. With day-0 RDMA over Thunderbolt 5 support, it achieves significant speedups through tensor parallelism across multiple devices.

## Key Points
- Automatic device discovery — no manual configuration needed
- RDMA over Thunderbolt 5 for 99% latency reduction between devices
- Topology-aware auto parallelism based on real-time device topology
- Tensor parallelism: up to 1.8x speedup on 2 devices, 3.2x on 4 devices
- Uses MLX as inference backend; includes built-in dashboard for cluster management

## Related
- [[MLX]]
- [[distributed-inference]]
- [[local-llm]]
