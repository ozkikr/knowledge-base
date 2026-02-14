---
url: https://shopify.engineering/building-production-ready-agentic-systems
type: article
tags: [agentic-systems, shopify, llm-evaluation, production-ai, jit-instructions]
date_saved: 2026-02-14
---
# Building Production-Ready Agentic Systems: Lessons from Shopify Sidekick

## Summary
Shopify shares lessons from building Sidekick, an AI assistant for merchants, presented at ICML 2025. Key innovations include Just-in-Time (JIT) instructions to solve prompt bloat at scale, and rigorous LLM evaluation using Ground Truth Sets instead of "vibe testing."

## Key Points
- Tool scaling problem: 0-20 tools is manageable, 50+ leads to "Death by a Thousand Instructions" in system prompts
- JIT instructions: return relevant guidance alongside tool data exactly when needed, not all upfront — improves cache efficiency and modularity
- Moved from curated "golden" datasets to Ground Truth Sets (GTX) sampled from real production conversations
- Emphasizes principled, statistically rigorous evaluation over vibe-based LLM judges
- Architecture follows Anthropic's "agentic loop" pattern: input → LLM decision → action → feedback → repeat

## Related
- [[llm-agents]]
- [[prompt-engineering]]
- [[llm-evaluation]]
- [[agentic-systems]]
