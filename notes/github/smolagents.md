---
url: https://github.com/huggingface/smolagents
type: github-repo
tags: [agents, huggingface, code-agents, python, mcp]
date_saved: 2026-02-14
---
# smolagents

## Summary
smolagents is a minimal Hugging Face library for building agents that think in code. The core agent logic fits in ~1,000 lines, with first-class support for CodeAgents that write actions as executable code in sandboxed environments.

## Key Points
- Minimal abstraction: core logic in ~1,000 lines of code
- CodeAgent writes actions as code, executed in sandboxed environments (E2B, Modal, Docker, Pyodide)
- Model-agnostic: supports local models, HF Hub providers, OpenAI, Anthropic via LiteLLM
- Modality-agnostic: text, vision, video, audio inputs
- Tool-agnostic: integrates MCP servers, LangChain tools, and HF Hub shared tools

## Related
- [[ai-agents]]
- [[code-execution]]
- [[huggingface]]
- [[model-context-protocol]]
