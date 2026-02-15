---
url: https://github.com/davegoldblatt/total-recall
type: github-repo
languages: [Shell]
tags: [agent-memory, claude-code, knowledge-management]
date_saved: 2026-02-15
---
# total-recall
## Summary
Total Recall is a persistent-memory plugin for Claude Code that keeps durable notes across sessions while filtering out short-lived noise. It uses a tiered memory model (daily log, registers, working memory, archive) and a write gate so only durable, behavior-changing facts become long-term memory. The project emphasizes human control, correction propagation, and local-file transparency.
## Key Points
- Implements explicit write-gate criteria before promoting memory to durable registers.
- Uses `/recall-*` commands for writing, searching, promotion, maintenance, and forgetting.
- Stores memory as local markdown files with daily-first logging and later curation.
- Propagates corrections across daily logs, registers, and working memory to reduce repeated mistakes.
## Related
- [[Agent Memory]]
- [[Claude Code]]
- [[Persistent Context]]
