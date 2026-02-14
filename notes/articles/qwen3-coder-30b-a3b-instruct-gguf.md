---
url: https://huggingface.co/unsloth/Qwen3-Coder-30B-A3B-Instruct-GGUF
type: article
tags: [llm, qwen, coding-model, gguf, mixture-of-experts]
date_saved: 2026-02-14
---

# Qwen3-Coder-30B-A3B-Instruct-GGUF (Unsloth)

## Summary
GGUF quantizations of Qwen3-Coder-30B-A3B-Instruct by Unsloth. A Mixture-of-Experts coding model with 30.5B total params but only 3.3B activated, supporting 256K native context (extendable to 1M). Excels at agentic coding and browser-use tasks.

## Key Points
- 30.5B total / 3.3B activated params (128 experts, 8 active)
- 256K native context, extendable to 1M with YARN
- Non-thinking mode only (no `<think>` blocks)
- Strong at agentic coding: works with Qwen Code, CLINE, etc.
- Supported by Ollama, LMStudio, MLX-LM, llama.cpp, KTransformers

## Related
- [[mixture-of-experts]]
- [[gguf-quantization]]
- [[agentic-coding]]
- [[qwen]]
