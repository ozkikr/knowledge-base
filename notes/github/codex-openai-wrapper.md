---
url: https://github.com/GewoonJaap/codex-openai-wrapper
type: github-repo
tags: [openai-codex, api-wrapper, cloudflare-workers]
date_saved: 2026-02-14
---
# Codex OpenAI Wrapper

## Summary
A Cloudflare Workers project that wraps OpenAI's Codex models into OpenAI-compatible API endpoints. Uses OAuth2 authentication from the Codex CLI to provide drop-in replacement endpoints compatible with OpenAI SDKs, Open WebUI, Cline, and other tools.

## Key Points
- Exposes Codex models via standard OpenAI-compatible API endpoints
- Deploys on Cloudflare Workers for global edge deployment
- Supports streaming, function calling, and Ollama compatibility
- Uses OAuth2 credentials from the official OpenAI Codex CLI
- Also available as Docker self-hosted option

## Related
- [[gemini-cli-openai]]
- [[openai-api]]
- [[cloudflare-workers]]
