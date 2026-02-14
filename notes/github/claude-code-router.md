---
url: https://github.com/musistudio/claude-code-router
type: github-repo
tags: [claude-code, model-routing, proxy, ai-coding]
date_saved: 2026-02-14
---

# Claude Code Router

## Summary
A tool that routes Claude Code requests to different LLM models and providers, letting you customize which model handles which type of request. Supports dynamic model switching, multi-provider backends, and request/response transformation.

## Key Points
- Route requests to different models based on task type (background, thinking, long context)
- Multi-provider support: OpenRouter, DeepSeek, Ollama, Gemini, Volcengine, SiliconFlow
- Dynamic model switching via `/model` command within Claude Code
- Plugin system for custom request/response transformers
- GitHub Actions integration for CI/CD workflows

## Related
- [[claude-code]] [[model-routing]] [[ai-coding-tools]] [[llm-proxy]]
