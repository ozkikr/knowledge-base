---
url: https://cookbook.openai.com/examples/agents_sdk/session_memory
type: article
tags: [openai, agents-sdk, context-management, session-memory, trimming]
date_saved: 2026-02-15
---
# Context Engineering - Short-Term Memory Management with Sessions from OpenAI Agents SDK
## Summary
This cookbook covers short-term memory control for long-running agent conversations using the Agents SDK Session object. It compares two practical strategies: trimming to recent turns versus summarizing older context. The article frames these choices around latency, cost, recall quality, and operational reliability.
## Key Points
- Explains why unmanaged context causes higher cost, lower accuracy, and drift.
- Details trimming (last-N turns) as deterministic and low-latency but forgetful.
- Details summarization as better for long-range continuity with added risk of distortion.
- Provides practical guidance for choosing methods by workload type.
- Includes implementation patterns for custom session memory behavior.
## Related
- [[session-memory]]
- [[context-window-management]]
- [[openai-agents-sdk]]
