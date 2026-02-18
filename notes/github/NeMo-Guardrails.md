---
url: https://github.com/NVIDIA-NeMo/Guardrails
type: github-repo
tags: [llm-guardrails, safety, nvidia, conversational-ai, python, nemo]
languages: [Python]
date_saved: 2026-02-18
---

# NeMo Guardrails

Open-source toolkit by NVIDIA for adding programmable guardrails to LLM-based conversational systems.

## Summary

NeMo Guardrails enables developers to easily add programmable guardrails between application code and LLMs. Guardrails ("rails") control LLM output — preventing unwanted topics, enforcing dialog paths, ensuring language style, extracting structured data, and more.

## Key Points

- **Programmable guardrails** using Colang scripting language (event-driven architecture)
- Supports Python 3.10-3.13
- Uses [[annoy]] (Spotify) for vector similarity
- Key benefits: trustworthy/safe LLM apps, secure service connections, controllable dialog
- Latest version: 0.20.0 (beta)
- Apache 2.0 license
- Official docs at docs.nvidia.com/nemo/guardrails
- Academic paper: [arXiv:2310.10501](https://arxiv.org/abs/2310.10501)
- Can triple latency/costs if not properly tuned (per independent evaluations)
- Steep learning curve but highly customizable

## Related

- [[Guardrails-AI]] — alternative lightweight guardrails framework
- [[LlamaGuard]] — Meta's safety classifier
- [[deepeval]] — evaluation framework that can test guardrail effectiveness
