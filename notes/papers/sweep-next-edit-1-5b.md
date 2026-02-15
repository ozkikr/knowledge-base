---
url: https://huggingface.co/sweepai/sweep-next-edit-1.5B
type: paper
tags: [code-models, autocomplete, gguf]
date_saved: 2026-02-15
---
# sweep-next-edit-1.5B
## Summary
Sweep Next-Edit 1.5B is a compact code-edit prediction model distributed in Q8_0 GGUF format for local inference. It is designed for next-edit autocomplete workflows with low latency and references benchmarks comparing favorably against larger models. The model card describes usage, prompt format expectations, and links to implementation details.

## Key Points
- 1.5B-parameter model optimized for next-edit code completion tasks.
- Quantized GGUF distribution (Q8_0) for efficient local deployment.
- Built on Qwen2.5-Coder with an 8192-token context window.
- Includes practical run instructions using `llama-cpp-python` and `huggingface_hub`.
- Links to a technical blog post and editor ecosystem integrations.

## Related
- [[code-completion-models]]
- [[local-llm-inference]]
- [[quantization]]
