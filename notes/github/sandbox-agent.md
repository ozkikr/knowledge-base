---
url: https://github.com/rivet-dev/sandbox-agent
type: github-repo
languages: [Rust, TypeScript, HTML, Dockerfile, JavaScript, Shell]
tags: [sandbox, agent-runtime, api]
date_saved: 2026-02-15
---
# sandbox-agent

## Summary
sandbox-agent runs coding agents inside isolated sandboxes and exposes a unified HTTP/SSE control interface. It normalizes heterogeneous agent APIs and event formats so applications can swap agents without rewriting integration logic. The project targets remote, production-safe agent execution with streaming and replay-friendly telemetry.

## Key Points
- Offers one API for multiple coding agents including Claude Code, Codex, OpenCode, Cursor, Amp, and Pi.
- Can run as an in-sandbox server or be consumed through a TypeScript SDK.
- Streams standardized session events for external persistence and auditing.
- Includes CLI tooling, inspector UI, and OpenAPI documentation for integration workflows.
- Emphasizes sandbox isolation as a requirement for safe autonomous code execution.

## Related
- [[Sandboxing]]
- [[Server-Sent Events]]
- [[Agent APIs]]
