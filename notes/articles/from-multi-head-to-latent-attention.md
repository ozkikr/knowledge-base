---
url: https://vinithavn.medium.com/from-multi-head-to-latent-attention-the-evolution-of-attention-mechanisms-64e3c0505f24
type: article
tags: [attention-mechanisms, transformers, multi-head-attention, deepseek, kv-cache]
date_saved: 2026-02-14
---
# From Multi-Head to Latent Attention: The Evolution of Attention Mechanisms

## Summary
A walkthrough of attention mechanism evolution from Multi-Head Attention (MHA) introduced in "Attention Is All You Need" to Multi-Latent Head Attention (MHLA) used in models like DeepSeek. Covers the fundamentals of queries, keys, values, attention scores, and KV caching.

## Key Points
- Attention allows models to selectively focus on relevant context tokens when generating output
- Core components: Query (current token), Key (context comparison), Value (actual information), and Attention Scores
- KV caching stores precomputed keys/values from previous tokens for faster autoregressive decoding
- Innovations focus on computational speed, memory reduction, and scalability for longer sequences
- Traces evolution from MHA through newer variants like MHLA (used in DeepSeek)

## Related
- [[transformers]]
- [[deepseek]]
- [[kv-cache]]
- [[attention-mechanisms]]
