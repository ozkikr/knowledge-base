---
url: https://openai.com/index/unlocking-the-codex-harness/
type: article
tags: [codex, app-server, json-rpc]
date_saved: 2026-02-15
---
# Unlocking the Codex harness: how we built the App Server
## Summary
This post explains how OpenAI evolved the Codex App Server from internal reuse tooling into a stable integration surface for IDEs, desktop, and web clients. The server exposes Codex core over a bidirectional JSON-RPC protocol so clients can stream events, handle approvals, and persist thread state. The architecture focuses on backward compatibility and reusable conversation primitives that map cleanly to rich UIs.

## Key Points
- The App Server hosts Codex core sessions and translates internal agent events into stable, UI-ready JSON-RPC notifications.
- Core protocol primitives are item, turn, and thread, each with explicit lifecycle events for streaming and persistence.
- The protocol is bidirectional: clients send requests while servers can pause execution to request approvals.
- Multiple client surfaces (VS Code, desktop, web, TUI) share the same harness through transport adapters.
- Versioning and compatibility are treated as first-class requirements for partner integrations.

## Related
- [[agent-loop]]
- [[json-rpc]]
- [[thread-management]]
