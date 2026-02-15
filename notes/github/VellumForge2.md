---
url: https://github.com/lemon07r/VellumForge2
type: github-repo
languages: [Go, Shell, Python]
tags: [dataset-generation, dpo, synthetic-data, llm-training]
date_saved: 2026-02-15
---
# VellumForge2
## Summary
VellumForge2 is a high-performance CLI for generating synthetic LLM training datasets. It supports formats such as SFT, DPO, KTO, and MO-DPO with hierarchical prompt pipelines and optional LLM-as-judge scoring. The tool is provider-agnostic and can push generated datasets directly to Hugging Face.
## Key Points
- Generates multiple preference-training dataset formats from configurable pipelines.
- Supports concurrent workers, checkpoint/resume, and rate-limited provider execution.
- Works with OpenAI-compatible APIs across many local and hosted model providers.
- Includes one-command Hugging Face upload workflows for publication.
## Related
- [[Synthetic Data]]
- [[Preference Optimization]]
- [[LLM Fine-Tuning]]
