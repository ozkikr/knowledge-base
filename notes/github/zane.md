---
url: https://github.com/z-siddiqi/zane
type: github-repo
languages: [TypeScript, Svelte]
tags: [codex, remote-control, cloudflare]
date_saved: 2026-02-15
---
# zane
## Summary
Zane is a remote control layer for local Codex CLI sessions, designed for phone, tablet, and browser access. It combines a local daemon (“Anchor”) with a Cloudflare-hosted control plane (“Orbit”) to relay JSON-RPC events and approvals. The project targets practical mobile oversight of long-running coding agent sessions without exposing local ports.

## Key Points
- Supports remote task start, live event streaming, diff review, and approval workflows.
- Uses passkey-based authentication and push notifications for secure mobile interaction.
- Architecture bridges browser clients to local Codex app-server via WebSockets and JSON-RPC.
- Includes both managed mode and optional full self-host deployment on Cloudflare.
- Provides a CLI for setup, diagnostics, updates, and uninstall flows.

## Related
- [[codex-cli]]
- [[json-rpc]]
- [[passkey-authentication]]
