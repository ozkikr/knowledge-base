---
url: https://github.com/karpathy/hn-time-capsule
type: github-repo
languages: [Python]
tags: [hacker-news, llm-analysis, hindsight, data-pipeline, evaluation]
date_saved: 2026-02-15
---
# hn-time-capsule
## Summary
hn-time-capsule is a Python pipeline that revisits Hacker News front pages from 10 years ago and uses an LLM to evaluate discussions with hindsight. It fetches article/comment data, runs analysis prompts, parses grades, and renders summary reports.
## Key Points
- Automates data collection from historical HN front pages.
- Uses staged processing: fetch, prompt, analyze, parse, render.
- Produces per-thread and aggregate grading artifacts for commenters.
- Demonstrates a practical LLM-assisted historical analysis workflow.
## Related
- [[LLM Evaluation]]
- [[Data Pipelines]]
- [[Hacker News]]
