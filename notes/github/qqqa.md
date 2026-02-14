---
url: https://github.com/iagooar/qqqa
type: github-repo
languages: [Go]
tags: [cli, llm, shell, assistant]
date_saved: 2026-02-14
---
# qqqa

## Summary
A fast, stateless LLM-powered CLI tool with two binaries: `qq` for quick questions and `qa` for a single-step agent that can read/write files and execute commands. Deliberately stateless by design, following Unix philosophy.

## Key Points
- `qq` = quick question (read-only), `qa` = quick agent (with tools)
- Supports OpenRouter, OpenAI, Groq, Ollama, Codex CLI, Claude Code CLI
- Stateless by design — every run is independent and reproducible
- Shell-friendly: compose with pipes and files
- `qa` requires confirmation before running tools (safe by default)

## Related
- [[cli-tools]] [[llm]] [[shell-productivity]] [[unix-philosophy]]
