---
url: https://docs.ag-ui.com/concepts/messages
type: article
tags: [ag-ui, protocol, messages, streaming, tool-calling]
date_saved: 2026-02-15
---
# Messages
## Summary
This concept page defines the AG-UI message model used for communication between users, assistants, tools, and system components. It specifies message roles, schemas, synchronization modes, and streaming event lifecycles. The design emphasizes vendor-neutral interoperability and privacy-preserving state continuity.
## Key Points
- Defines typed roles including user, assistant, tool, system, activity, developer, and reasoning.
- Supports encrypted fields for privacy-aware continuity and ZDR-style workflows.
- Describes snapshot-based and streaming-based synchronization patterns.
- Details tool-call and tool-result message structures with ID linkage.
- Provides mapping concepts for translating AG-UI messages to provider-native formats.
## Related
- [[ag-ui]]
- [[agent-protocols]]
- [[tool-calling]]
