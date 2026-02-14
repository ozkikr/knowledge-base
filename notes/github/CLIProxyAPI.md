---
url: https://github.com/router-for-me/CLIProxyAPI
type: github-repo
languages: [Go]
tags: [proxy, api, openai-compatible, gemini, claude-code, codex]
date_saved: 2026-02-14
---
# CLIProxyAPI

## Summary
A proxy server that wraps CLI tools (Gemini CLI, Claude Code, ChatGPT Codex, Qwen Code, etc.) as OpenAI/Gemini/Claude compatible API endpoints. Enables using free CLI model access through standard API interfaces with multi-account round-robin load balancing.

## Key Points
- OpenAI/Gemini/Claude compatible API endpoints for CLI models
- Supports Codex, Claude Code, Qwen Code, iFlow via OAuth login
- Multi-account round-robin load balancing with failover
- Streaming and non-streaming responses with function calling support
- Reusable Go SDK for embedding the proxy

## Related
- [[vibeproxy]]
- [[API-proxy]]
- [[LLM-tooling]]
