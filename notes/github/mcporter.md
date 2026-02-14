---
url: https://github.com/steipete/mcporter
type: github-repo
languages: [TypeScript]
tags: [mcp, cli, code-generation, typescript, tooling]
date_saved: 2026-02-14
---
# MCPorter - Call MCPs from TypeScript or as CLI

## Summary
MCPorter is a TypeScript runtime, CLI, and code-generation toolkit for the Model Context Protocol. It discovers MCP servers on your system, calls them directly, composes automations in TypeScript, and generates single-purpose CLIs—all with zero-config discovery and typed tool clients.

## Key Points
- Zero-config discovery: merges configs from Cursor, Claude, Codex, Windsurf, VS Code
- One-command CLI generation from any MCP server definition
- Typed TypeScript clients via `emit-ts` for strong typing without hand-written plumbing
- Ergonomic `createServerProxy()` with camelCase methods and JSON-schema validation
- Built-in OAuth caching, log tailing, and ad-hoc connections

## Related
- [[mcp]]
- [[desktop]]
- [[ai-agents]]
