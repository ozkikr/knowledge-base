---
url: https://github.com/pardeike/GABP
type: github-repo
tags: [gaming, ai-agents, protocol, game-modding]
date_saved: 2026-02-14
---
# GABP (Game Agent Bridge Protocol)

## Summary
GABP is a communication protocol enabling AI tools to interact with games through a standardized bridge between AI agents and game modifications. It uses JSON-RPC-style messages over stdio, TCP, or pipes with token-based authentication.

## Key Points
- Standard protocol for AI-to-game communication (version 1.0)
- JSON-RPC message format with requests, responses, and events
- Transport via stdio, TCP (local only), and pipes/sockets
- Security model with token authentication and local-only connections
- Capability negotiation via handshake for feature discovery

## Related
- [[MCP]] [[game-modding]] [[AI-agents]] [[JSON-RPC]]
