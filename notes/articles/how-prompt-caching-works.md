---
url: https://sankalp.bearblog.dev/how-prompt-caching-works/
type: article
tags: [prompt-caching, paged-attention, vLLM, KV-cache, LLM-inference]
date_saved: 2026-02-14
---
# How Prompt Caching Works

## Summary
A deep dive into prompt caching mechanics, covering Paged Attention (vLLM's OS-inspired memory management for KV caches) and Automatic Prefix Caching. Includes practical tips for maximizing cache hits across conversations and users.

## Key Points
- System prompts can be cached across different users sharing the same API key/org
- Paged Attention solves KV cache memory fragmentation using block tables (like OS virtual memory)
- Prefix caching uses block hashing to find longest matching cached prefix
- Key mistake: putting user-specific data at end of system prompt breaks cross-user cache sharing
- Covers LLM inference basics: prefill, decode, and KV caching fundamentals

## Related
- [[vLLM]] - inference engine implementing paged attention
- [[KV-cache]] - key-value caching in transformers
- [[LLM-inference-optimization]] - broader optimization techniques
