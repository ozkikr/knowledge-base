---
url: https://huggingface.co/openai/gpt-oss-120b
type: github-repo
tags: [openai, open-weights, llm, reasoning, moe]
date_saved: 2026-02-14
---
# GPT-OSS-120B

## Summary
GPT-OSS-120B is OpenAI's open-weight model (Apache 2.0) designed for reasoning, agentic tasks, and general developer use cases. It's a 117B parameter MoE model with 5.1B active parameters, fitting on a single 80GB GPU via MXFP4 quantization.

## Key Points
- Apache 2.0 license, fully fine-tunable
- MoE architecture: 117B total params, 5.1B active — runs on single H100/MI300X
- Configurable reasoning effort (low/medium/high) with full chain-of-thought
- Native agentic capabilities: function calling, web browsing, code execution, structured outputs
- Smaller sibling: gpt-oss-20b (21B params, 3.6B active, fits in 16GB)
- Uses harmony response format

## Related
- [[open-weight-models]]
- [[mixture-of-experts]]
- [[gpt-oss-20b]]
