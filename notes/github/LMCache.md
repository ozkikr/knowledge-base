---
url: https://github.com/LMCache/LMCache
type: github-repo
languages: [Python, C++, CUDA]
tags: [LLM-serving, KV-cache, inference, vLLM, performance]
date_saved: 2026-02-14
---
# LMCache: Supercharge Your LLM with the Fastest KV Cache Layer

## Summary
LMCache is an LLM serving engine extension that reduces time-to-first-token (TTFT) and increases throughput by storing and reusing KV caches across GPU, CPU, disk, and S3. Combined with vLLM, it achieves 3-10x delay savings in multi-round QA and RAG scenarios.

## Key Points
- KV cache storage across GPU, CPU, disk, and S3 with zero-copy, NIXL, GDS acceleration
- 3-10x latency reduction when combined with vLLM
- Supports disaggregated prefill and P2P KV cache sharing
- Integration with both vLLM v1 and SGLang
- Reuses KV caches for any reused text, not just prefix matches

## Related
- [[vLLM]]
- [[LLM-inference]]
- [[KV-cache]]
