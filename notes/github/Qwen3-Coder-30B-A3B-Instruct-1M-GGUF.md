---
url: https://huggingface.co/unsloth/Qwen3-Coder-30B-A3B-Instruct-1M-GGUF
type: article
tags: [llm, gguf, qwen, coding-model, unsloth]
date_saved: 2026-02-14
---
# Qwen3-Coder-30B-A3B-Instruct-1M-GGUF (Unsloth)

## Summary
GGUF quantized version of Qwen3-Coder-30B-A3B by Unsloth, extending context length from 256K to 1M tokens. A Mixture-of-Experts model with 30.5B total params but only 3.3B activated, optimized for agentic coding tasks.

## Key Points
- 128 experts, 48 layers, 32 attention heads (Q) / 4 (KV) with GQA
- Native 256K context, extendable to 1M via YaRN
- Strong performance on agentic coding, browser-use, and foundational coding benchmarks
- Supports platforms like Qwen Code, CLINE with dedicated function call format
- Unsloth provides free Colab notebooks for fine-tuning with 70% less memory

## Related
- [[instructor]]
- [[deepagents]]
- [[claude-context]]
