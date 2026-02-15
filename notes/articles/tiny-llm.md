---
url: https://geddydukes.com/blog/tiny-llm
type: article
tags: [tiny-llm, local-training, command-generation]
date_saved: 2026-02-15
---
# Tiny LLM on Consumer Hardware for CLI Command Generation
## Summary
This write-up documents training a 66.73M-parameter transformer on an M4 Mac Mini and reaching 93.94% exact-match accuracy for CLI command generation. The author details architecture choices, streaming data pipeline design, strict evaluation, and failure analysis rather than benchmark hype. A key takeaway is that narrow, exact tasks can be solved effectively with small models when data and evaluation are carefully engineered.

## Key Points
- End-to-end training used Apple Silicon MPS, 204.8M tokens, and about 13 hours of pretraining.
- Architecture used modern but conservative components (RoPE, RMSNorm, SwiGLU, weight tying).
- Exact-match evaluation exposed real failure modes, especially early termination on symbol-dense commands.
- Continual-learning gates accepted updates only when they improved new performance without harming baseline behavior.
- The author argues data targeting and instrumentation matter more than adding raw model scale.

## Related
- [[Small Language Models]]
- [[Instruction Tuning]]
- [[Exact-Match Evaluation]]
