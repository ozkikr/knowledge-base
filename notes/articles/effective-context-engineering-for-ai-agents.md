---
url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
type: article
tags: [context-engineering, ai-agents, prompt-engineering, anthropic]
date_saved: 2026-02-14
---
# Effective Context Engineering for AI Agents

## Summary
Anthropic's guide on context engineering as the evolution of prompt engineering. It focuses on optimizing the full set of tokens available to an LLM during inference—not just prompts, but tools, MCP, external data, and conversation history—to consistently achieve desired agent behavior.

## Key Points
- Context engineering = curating and maintaining optimal tokens during LLM inference
- Goes beyond prompt engineering to manage entire context state (system instructions, tools, MCP, data, messages)
- Think in context: consider the holistic state available to the LLM at any given time
- Natural progression as agents operate over multiple turns and longer time horizons
- Includes strategies for managing Model Context Protocol (MCP) and external data

## Related
- [[how-to-turn-claude-code-into-a-domain-specific-coding-agent]] - Practical context engineering with Claude Code
- [[agenta]] - LLMOps for prompt management
