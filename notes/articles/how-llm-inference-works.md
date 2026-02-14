---
url: https://arpitbhayani.me/blogs/how-llm-inference-works
type: article
tags: [llm, inference, transformers, tokenization, embeddings]
date_saved: 2026-02-14
---
# How LLM Inference Works

## Summary
A walkthrough of the full LLM inference pipeline: from text input through tokenization (BPE), token embeddings, positional encodings, transformer layers (self-attention + FFN), to autoregressive token generation. Covers decoder-only architectures like GPT-4, Claude, and Llama.

## Key Points
- LLMs are decoder-only transformers that generate one token at a time autoregressively
- Tokenization via BPE converts text to integer IDs; common words become single tokens, rare words split into subwords
- Embedding layer maps token IDs to high-dimensional vectors; positional encodings (e.g., RoPE) add sequence order information
- Each transformer layer has self-attention (relating tokens to each other) and feed-forward networks
- Model size = number of parameters (weight matrices storing learned knowledge across all layers)

## Related
- [[the-q-k-v-matrices]]
- [[transformer-architecture]]
- [[byte-pair-encoding]]
