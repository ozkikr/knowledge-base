---
url: https://www.aleksagordic.com/blog/vllm
type: article
tags: [vllm, llm-inference, paged-attention, speculative-decoding, systems]
date_saved: 2026-02-14
---
# Inside vLLM: Anatomy of a High-Throughput LLM Inference System

## Summary
A comprehensive deep-dive into vLLM's architecture covering the core engine, advanced features, scaling, and serving layers. The post follows an inverse-pyramid approach, building a high-level mental model before diving into subsystem details, based on a specific commit (Aug 2025).

## Key Points
- Covers LLM engine & engine core fundamentals: scheduling, paged attention, continuous batching
- Advanced features: chunked prefill, prefix caching, guided & speculative decoding, disaggregated prefill/decode
- Scaling from single-GPU to multi-GPU execution
- Distributed/concurrent web serving layer architecture
- Benchmarks and auto-tuning for latency and throughput measurement

## Related
- [[llm-inference]]
- [[paged-attention]]
- [[speculative-decoding]]
- [[continuous-batching]]
