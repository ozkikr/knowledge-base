---
url: https://huggingface.co/blog/hf-skills-training
type: article
tags: [huggingface, training, coding-agents, claude, fine-tuning]
date_saved: 2026-02-15
---
# We Got Claude to Fine-Tune an Open Source LLM
## Summary
Hugging Face introduces “Skills” that let coding agents (Claude Code, Codex, Gemini CLI) run real fine-tuning workflows end-to-end: dataset checks, hardware selection, job submission, monitoring, and model publishing.

## Key Points
- The `hf-llm-trainer` skill enables SFT, DPO, and GRPO training flows via Hugging Face Jobs.
- Workflow includes authentication, config review, cost/time estimates, and asynchronous progress tracking.
- Supports practical model sizes and deployment workflows (including GGUF conversion).
- Emphasizes production-friendly steps: validation, monitoring, and iterative debugging.

## Related
- https://huggingface.co/blog/hf-skills-training
- https://github.com/huggingface/skills
- https://huggingface.co/mcp?bouquet=skills