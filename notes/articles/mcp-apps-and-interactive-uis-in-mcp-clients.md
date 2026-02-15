---
url: https://den.dev/blog/mcp-apps/
type: article
tags: [mcp, agent-interfaces, protocol-design]
date_saved: 2026-02-15
---
# MCP Apps And Interactive UIs In MCP Clients
## Summary
This post announces MCP Apps, a new extension that brings interactive UI support to Model Context Protocol clients. Instead of only passing text over JSON-RPC, developers can now ship HTML-based app surfaces that run in sandboxed iframes and talk bidirectionally with MCP tools. The author highlights early support in Claude and VS Code Insiders, plus active community contribution paths.

## Key Points
- MCP Apps is presented as the first official extension to core MCP, building on earlier MCP-UI and OpenAI app work.
- The extension enables interactive interfaces instead of only text responses and links.
- Apps run in host-controlled sandboxed iframes for stronger isolation and safer embedding.
- The architecture keeps protocol changes relatively small for client/server implementers.
- Developers can already start using docs, quickstarts, samples, and GitHub issue/discussion channels.

## Related
- [[Model Context Protocol]]
- [[Agent Tooling]]
- [[Sandboxed UI]]
