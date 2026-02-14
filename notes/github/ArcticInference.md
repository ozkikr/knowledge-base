---
url: https://github.com/snowflakedb/ArcticInference
type: github-repo
languages: [Python]
tags: [llm-inference, vllm, speculative-decoding, embeddings, snowflake]
date_saved: 2026-02-14
---
# ArcticInference — vLLM Plugin for High-Throughput LLM Inference

## Summary
ArcticInference is Snowflake's open-source vLLM plugin that delivers high-throughput, low-latency inference for LLMs and embeddings. It automatically patches vLLM with optimizations like Shift Parallelism, speculative decoding, and SwiftKV.

## Key Points
- Drop-in vLLM plugin: `pip install arctic-inference[vllm]` auto-patches vLLM
- 3.4x faster request completion via Shift Parallelism
- 16x faster embedding inference on short sequences vs plain vLLM
- Includes Arctic Speculator, Suffix Decoding, and SwiftKV optimizations
- Supports sequence parallelism (Ulysses) for long-context inference

## Related
- [[vLLM]]
- [[Speculative Decoding]]
- [[LLM Inference]]
- [[Snowflake]]
