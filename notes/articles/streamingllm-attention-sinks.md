---
url: https://hanlab.mit.edu/blog/streamingllm
type: article
tags: [llm, attention, inference, streaming]
date_saved: 2026-02-14
---
# StreamingLLM: How Attention Sinks Keep Language Models Stable

## Summary
StreamingLLM addresses the problem of LLMs failing catastrophically on long conversations when old tokens are evicted from the KV cache. The researchers discovered that models dump massive attention onto the first few tokens as "attention sinks" because softmax requires weights to sum to 1. By keeping the first 4 tokens permanently while sliding the window for everything else, models can stably process 4M+ tokens.

## Key Points
- Models allocate disproportionate attention to initial tokens as "sinks" for unused attention weight
- Simply keeping the first 4 tokens + a sliding window enables stable infinite-length generation
- Now integrated into HuggingFace, NVIDIA TensorRT-LLM, and OpenAI's GPT-OSS models
- OpenAI added a trainable scalar per attention head inspired by this work
- Research originated during a Meta internship in summer 2023

## Related
- [[attention-mechanisms]]
- [[kv-cache]]
- [[long-context-llm]]
