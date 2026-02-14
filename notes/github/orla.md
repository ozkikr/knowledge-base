---
url: https://github.com/dorcha-inc/orla
type: github-repo
languages: [Go]
tags: [agents, llm, cli, unix, serving]
date_saved: 2026-02-14
---
# Orla

## Summary
Orla is a Unix tool for running lightweight open-source local agents. It also serves as an agentic serving stack sitting above LLM backends like SGLang, Ollama, and vLLM, providing agent-granularity control over model selection, inference coordination, and KV cache management.

## Key Points
- Three modes: `orla agent` (interactive), `orla daemon` (serving layer), `orla serve` (MCP server)
- Works with Ollama, SGLang, and vLLM backends
- Optimizes for end-to-end agent completion time and cost
- Supports multi-agent workflows and model cascades
- Installable via Homebrew or shell script

## Related
- [[ollama]] - Local LLM serving
- [[agents]] - AI agent frameworks
- [[youtu-agent]] - Another agent framework
