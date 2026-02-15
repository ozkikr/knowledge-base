---
url: https://agentclientprotocol.com/protocol/terminals
type: article
tags: [acp, protocol, terminals, json-rpc, agent-infrastructure]
date_saved: 2026-02-15
---
# Terminals (Agent Client Protocol)
## Summary
This documentation page specifies the ACP terminal API for running and managing shell commands from an agent through JSON-RPC. It covers terminal lifecycle operations, output retrieval, cancellation, timeouts, and safe capability checks. The page is effectively a protocol guide for integrating command execution into agent workflows.

## Key Points
- Agents must verify terminal capability in `initialize` response before invoking terminal methods.
- Core lifecycle methods are `terminal/create`, `terminal/output`, `terminal/wait_for_exit`, `terminal/kill`, and `terminal/release`.
- `outputByteLimit` supports bounded output storage with truncation behavior defined by the client.
- Terminal streams can be embedded into tool calls for live UX in client interfaces.
- Recommended timeout pattern combines `wait_for_exit`, timer logic, `kill`, output retrieval, and explicit release.

## Related
- [[agent-client-protocol]]
- [[terminal-automation]]
- [[json-rpc]]
