---
url: https://docs.getbifrost.ai/quickstart/go-sdk/tool-calling
type: article
tags: [bifrost, go, tool-calling, mcp, function-calling]
date_saved: 2026-02-15
---
# Tool Calling
## Summary
This quickstart explains tool calling in Bifrost’s Go SDK via both custom function schemas and MCP server integrations. It demonstrates how models invoke tools, how to inspect calls, and how to control tool-choice behavior. The guide includes practical examples like calculator, weather, database, and filesystem tools.
## Key Points
- Defines custom function tools with JSON-schema style parameters.
- Shows MCP client configuration for auto-exposing external tool servers.
- Demonstrates parsing tool calls and arguments from model responses.
- Supports multiple tools per request with configurable tool-choice modes.
- Provides end-to-end Go examples for common production patterns.
## Related
- [[tool-calling]]
- [[go-sdk]]
- [[mcp]]
