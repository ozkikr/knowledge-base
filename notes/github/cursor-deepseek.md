---
url: https://github.com/danilofalcao/cursor-deepseek
type: github-repo
languages: [Go, Dockerfile]
tags: [proxy, cursor, deepseek, openrouter]
date_saved: 2026-02-15
---

# cursor-deepseek
## Summary
cursor-deepseek is a high-performance proxy that translates OpenAI-compatible requests for use with DeepSeek, OpenRouter, and Ollama models. It is built to let Cursor Composer and similar tools operate against non-OpenAI backends with minimal client changes. The project supports streaming, function/tool calls, and deployment via Docker.
## Key Points
- Bridges /v1 chat-completions style clients to DeepSeek/OpenRouter/Ollama APIs.
- Includes HTTP/2, compression, CORS, and model mapping features.
- Documents local and containerized deployment options with environment-based config.
- Useful for reusing OpenAI-client tooling against alternative LLM providers.
## Related
- [[Cursor IDE]]
- [[LLM Proxy]]
- [[OpenAI-Compatible APIs]]
