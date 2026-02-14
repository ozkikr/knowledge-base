---
url: https://github.com/Yinghao-Guan/Veru
type: github-repo
languages: [Python, TypeScript]
tags: [ai-verification, hallucination-detection, citations, academic-research]
date_saved: 2026-02-14
---
# Veru

## Summary
Veru is an AI citation auditor and hallucination detector that verifies ChatGPT/Claude citations against real academic databases. It uses a multi-tier verification pipeline checking OpenAlex, Semantic Scholar, and Google Search Grounding.

## Key Points
- Anti-hallucination extraction using Gemini 2.0 (no autocorrection of user errors)
- Three-tier verification: OpenAlex (250M+ works) → Semantic Scholar → Google Search Grounding
- Content consistency checks comparing claims against actual abstracts
- Local history with no login required
- Next.js frontend + FastAPI backend

## Related
- [[data-agents]] - LLM-powered data workflows
