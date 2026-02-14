---
url: https://github.com/globalaiplatform/langdiff
type: github-repo
tags: [streaming, llm, json-patch, pydantic, frontend]
date_saved: 2026-02-14
---
# LangDiff

## Summary
LangDiff is a Python library for streaming structured LLM outputs to frontends. It provides intelligent partial JSON parsing with type-safe events and automatic JSON Patch generation for efficient frontend synchronization.

## Key Points
- Streaming partial JSON parsing with Pydantic-style schema models
- Granular callbacks (on_append, on_update, on_complete) as tokens stream in
- Automatic JSON Patch diff generation for frontend state sync
- Change tracking via instrumented Pydantic models or plain Python objects
- Derives Pydantic models for interop with OpenAI SDK and other libraries

## Related
- [[streaming]]
- [[llm-tooling]]
- [[pydantic]]
- [[frontend-ai]]
