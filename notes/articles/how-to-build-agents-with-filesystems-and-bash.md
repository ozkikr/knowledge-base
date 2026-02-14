---
url: https://vercel.com/blog/how-to-build-agents-with-filesystems-and-bash
type: article
tags: [ai-agents, filesystems, bash, context-management, vercel]
date_saved: 2026-02-14
---
# How to Build Agents with Filesystems and Bash

## Summary
Vercel found that replacing custom agent tooling with filesystem and bash tools dramatically reduced costs (from ~$1.00 to ~$0.25 per call) while improving output quality. The key insight is that LLMs already understand filesystem navigation from training on code, so structuring any data as files lets agents leverage those skills for non-code tasks.

## Key Points
- LLMs excel at filesystem operations because they've been trained on massive amounts of code navigation
- Replacing custom tooling with filesystem + bash reduced costs by 75% and improved quality
- Structure any domain data (support tickets, sales calls, CRM) as files and let agents use Unix commands
- Agents run in sandboxed environments, isolating tool execution from reasoning
- Filesystems offer better tradeoffs than prompt stuffing or vector search for structured data retrieval

## Related
- [[agents-and-tool-use]]
- [[context-management]]
- [[unix-philosophy]]
