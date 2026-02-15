---
url: https://github.com/hirano00o/ollama-openai-proxy
type: github-repo
languages: [Go, Dockerfile]
tags: [ollama, openai, proxy]
date_saved: 2026-02-15
---
# ollama-openai-proxy
## Summary
ollama-openai-proxy emulates the Ollama REST API and forwards compatible requests to OpenAI. It is designed to let tools like JetBrains AI Assistant talk to OpenAI models through an Ollama-shaped interface. This makes local-style integrations work with hosted model backends.

## Key Points
- Implements an Ollama-compatible API layer and proxies calls to OpenAI.
- Uses `go-openai` under the hood for OpenAI connectivity.
- Supports a Docker Compose workflow for quick setup.
- Includes specific setup guidance for JetBrains AI Assistant model configuration.

## Related
- [[Ollama]]
- [[OpenAI API]]
- [[JetBrains AI Assistant]]
