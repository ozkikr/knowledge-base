---
url: https://github.com/mostlygeek/llama-swap
type: github-repo
languages: [Go]
tags: [llm, model-serving, hot-swap, openai-api, local-llm]
date_saved: 2026-02-14
---
# llama-swap

## Summary
A Go tool for running multiple LLM models locally and hot-swapping between them on demand. Works with any OpenAI/Anthropic API-compatible server (llama.cpp, vLLM, etc.) — one binary, one config file, zero dependencies.

## Key Points
- On-demand model switching without restarting applications
- Supports OpenAI and Anthropic API endpoints (chat, completions, embeddings, audio, images)
- Works with llama.cpp, vLLM, tabbyAPI, stable-diffusion.cpp, etc.
- Single binary, single config file, no external dependencies
- Includes web UI and upstream proxy access

## Related
- [[local-llm]] [[model-serving]] [[llama-cpp]] [[openai-api]]
