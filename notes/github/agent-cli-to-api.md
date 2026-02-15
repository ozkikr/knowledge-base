---
url: https://github.com/leeguooooo/agent-cli-to-api
type: github-repo
languages: [Python, Shell]
tags: [api-gateway, openai-compatible, cli, agents]
date_saved: 2026-02-15
---
# agent-cli-to-api
## Summary
agent-cli-to-api exposes popular agent CLIs through an OpenAI-compatible HTTP API interface. It acts as a local gateway so existing OpenAI SDK clients can route requests to backends like Codex, Cursor Agent, Claude Code, and Gemini. The project is designed for easy local deployment and flexible model/backend routing.
## Key Points
- Provides `/v1/*` OpenAI-style endpoints over multiple agent CLI backends.
- Lets tools reuse existing OpenAI SDK integrations without code rewrites.
- Supports provider selection and routing behavior via model naming and config.
- Includes practical setup paths with uv/pip and local-first operational defaults.
## Related
- [[OpenAI Compatible APIs]]
- [[AI Gateway]]
- [[Coding Agents]]
