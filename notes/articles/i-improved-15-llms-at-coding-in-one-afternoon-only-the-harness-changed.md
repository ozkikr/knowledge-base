---
url: https://blog.can.ac/2026/02/12/the-harness-problem/
type: article
tags: [coding-agents, benchmarking, developer-tools]
date_saved: 2026-02-15
---
# I Improved 15 LLMs at Coding in One Afternoon. Only the Harness Changed.
## Summary
This article argues that coding-agent performance is heavily constrained by edit-tool design, not just model quality. The author benchmarks multiple edit formats and shows large gains by switching to hash-anchored line references rather than fragile patch or exact-replace workflows. It highlights harness engineering as a high-leverage area for improving practical agent reliability.

## Key Points
- Compares patch, string-replace, and hashline editing approaches across multiple models.
- Reports substantial benchmark gains from harness changes alone, especially on weaker models.
- Frames many “model failures” as tool-interface failures at the edit boundary.
- Introduces hash-based line anchors for safer, verifiable edits under file drift.
- Calls for open, shared harness innovation rather than model-vendor lock-in.

## Related
- [[Agent Harness]]
- [[Code Editing Interfaces]]
- [[LLM Benchmarks]]
