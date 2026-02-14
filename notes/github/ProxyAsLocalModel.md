---
url: https://github.com/Stream29/ProxyAsLocalModel
type: github-repo
languages: [Kotlin]
tags: [llm-proxy, ollama, lm-studio, jetbrains, api-proxy]
date_saved: 2026-02-14
---
# ProxyAsLocalModel

## Summary
ProxyAsLocalModel proxies remote LLM APIs (OpenAI, Claude, Gemini, Deepseek, Mistral, etc.) as local model endpoints compatible with Ollama and LM Studio. This enables using custom LLM providers in JetBrains AI Assistant and other tools that only support local models.

## Key Points
- Proxies from OpenAI, Claude, DashScope (Qwen), Gemini, Deepseek, Mistral, SiliconFlow, xAI
- Exposes as Ollama or LM Studio compatible endpoints
- Built with Ktor and kotlinx.serialization for GraalVM native image compatibility
- Distributed as fat JAR and GraalVM native image for cross-platform fast startup
- Streaming chat completion API support

## Related
- [[ollama]]
- [[lm-studio]]
- [[jetbrains]]
- [[enchanted]]
