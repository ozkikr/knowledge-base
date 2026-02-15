---
url: https://github.com/localgpt-app/localgpt
type: github-repo
languages: [Rust]
tags: [local-first, security, autonomous-agent]
date_saved: 2026-02-15
---
# LocalGPT
## Summary
LocalGPT is a Rust-based local-device AI assistant focused on persistent markdown memory, autonomous heartbeat tasks, and multi-interface operation. It aims to be OpenClaw-compatible while remaining lightweight and self-contained. A major emphasis is defense-in-depth security for command execution and policy integrity.

## Key Points
- Ships as a single binary with CLI, daemon, web UI, desktop GUI, and Telegram support.
- Uses markdown workspace files plus SQLite FTS/semantic indexing for memory retrieval.
- Supports multiple providers including Anthropic, OpenAI-compatible endpoints, and local servers.
- Adds layered security: sandboxing, signed policy file verification, injection defenses, and audit chains.
- Designed for local-first operation where user data and memory stay on-device.

## Related
- [[rust-agents]]
- [[local-first-ai]]
- [[agent-security]]
