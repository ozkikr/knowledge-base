---
url: https://cookbook.openai.com/examples/agents_sdk/context_personalization
type: article
tags: [openai, agents-sdk, context-engineering, memory, personalization]
date_saved: 2026-02-15
---
# Context Engineering for Personalization - State Management with Long-Term Memory Notes using OpenAI Agents SDK
## Summary
This guide explains a state-based memory architecture for personalized AI agents using the OpenAI Agents SDK. It shows how to maintain structured profile fields plus unstructured memory notes, then inject the right context at run start. The example focuses on a travel concierge agent with memory capture, consolidation, and conflict-resolution rules.
## Key Points
- Uses `RunContextWrapper` to persist structured state across agent runs.
- Separates global (durable) memory from session (short-lived) memory.
- Introduces memory lifecycle: capture during run, consolidate post-run, reinject later.
- Recommends precedence order for conflicts: latest user input → session overrides → global defaults.
- Emphasizes use-case-driven memory schemas and token-efficient context injection.
## Related
- [[context-engineering]]
- [[agent-memory]]
- [[openai-agents-sdk]]
