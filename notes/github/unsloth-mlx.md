---
url: https://github.com/ARahim3/unsloth-mlx
type: github-repo
languages: [Python, Jupyter Notebook]
tags: [llm-finetuning, mlx, apple-silicon, lora, unsloth]
date_saved: 2026-02-15
---
# unsloth-mlx
## Summary
unsloth-mlx brings an Unsloth-like fine-tuning experience to Apple Silicon by wrapping MLX with a familiar API. It is designed for local prototyping on Mac, then moving the same training workflow to CUDA/Unsloth in the cloud. The repo covers SFT and multiple preference-optimization trainers, plus export options.

## Key Points
- Targets Apple Silicon with MLX while preserving Unsloth-style developer ergonomics.
- Supports SFT, DPO, ORPO, GRPO, KTO, and SimPO training flows.
- Emphasizes code portability between local Mac experiments and cloud GPU production.
- Includes model saving/export paths (HF/GGUF) with documented limitations and workarounds.

## Related
- [[MLX]]
- [[Fine-Tuning]]
- [[LoRA]]
- [[Unsloth]]
