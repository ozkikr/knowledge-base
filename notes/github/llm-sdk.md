---
url: https://github.com/hoangvvo/llm-sdk
type: github-repo
languages: [TypeScript, Rust, Go]
tags: [llm, sdk, multi-provider, agent, unified-api]
date_saved: 2026-02-14
---
# llm-sdk - Unified LLM API & Agent Library

## Summary
llm-sdk is an open-source suite providing cross-language clients (JavaScript, Rust, Go) that talk to multiple LLM providers through one unified LanguageModel interface, plus a minimal agent library for orchestrating model generations and tool executions.

## Key Points
- Unified API across JS/TS, Rust, and Go with consistent serialization
- Supports text, image, and audio modalities with streaming
- Multi-modality function calling, citations (RAG), and reasoning support
- Token usage reporting with cost calculation
- Zero-abstraction agent library: thin for-loop, no chains/graphs; OpenTelemetry tracing built-in

## Related
- [[gorag]] - Go RAG library
- [[airweave]] - context retrieval layer
- [[claude-agent-sdk-container]] - Claude-specific agent SDK
