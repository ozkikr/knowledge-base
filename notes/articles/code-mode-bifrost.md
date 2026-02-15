---
url: https://docs.getbifrost.ai/features/mcp/code-mode
type: article
tags: [bifrost, mcp, code-mode, orchestration, token-efficiency]
date_saved: 2026-02-15
---
# Code Mode
## Summary
This article introduces Bifrost Code Mode, a pattern for scaling MCP usage by replacing large direct tool catalogs with a compact meta-tool interface. The model writes sandboxed Python orchestration code to call underlying tools on demand. The approach aims to reduce context overhead, costs, and round trips in multi-server setups.
## Key Points
- Replaces many direct tool definitions with four meta-tools.
- Uses sandbox execution to handle intermediate orchestration outside the model context.
- Targets large MCP deployments where tool-definition tokens dominate costs.
- Reports practical gains in token usage and end-to-end execution speed.
- Documents enablement paths via UI, API, config files, and Go SDK.
## Related
- [[mcp]]
- [[tool-orchestration]]
- [[token-optimization]]
