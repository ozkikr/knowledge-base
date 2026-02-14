---
url: https://github.com/sparfenyuk/mcp-proxy
type: github-repo
tags: [mcp, proxy, sse, stdio, transport]
date_saved: 2026-02-14
---
# mcp-proxy

## Summary
A bridge tool that converts between MCP transport protocols — stdio to SSE/Streamable HTTP and vice versa. Enables clients like Claude Desktop to communicate with remote MCP servers over SSE even when not natively supported, and allows SSE-only clients to work with stdio servers.

## Key Points
- Two modes: stdio→SSE/StreamableHTTP and SSE→stdio
- Enables Claude Desktop to connect to remote MCP servers over SSE
- Supports named servers, OAuth2 authentication, and custom headers
- Available via PyPI, GitHub, or container image with Docker Compose support
- Configurable via CLI arguments or config file

## Related
- [[mcp]]
- [[server-sent-events]]
- [[claude-desktop]]
