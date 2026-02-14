---
url: https://github.com/katanemo/archgw
type: github-repo
tags: [ai-gateway, agentic-infrastructure, llm-proxy, envoy]
date_saved: 2026-02-14
---

# Arch Gateway (now Plano)

## Summary
Plano (formerly Arch Gateway) is an AI-native proxy and data plane for agentic applications, built on Envoy by its core contributors. It centralizes agent routing/orchestration, guardrails, observability, and LLM routing so developers can focus on core agent logic using any language or framework.

## Key Points
- Declarative YAML config for multi-agent orchestration with a built-in 4B-parameter routing model
- Model agility: route by name, alias, or automatic preferences across providers (OpenAI, Anthropic, etc.)
- Zero-code OpenTelemetry tracing and "Agentic Signals" capture across all agents
- Filter Chains for moderation, jailbreak protection, and memory hooks
- Agents are just HTTP servers implementing OpenAI-compatible chat completions — framework agnostic

## Related
- [[context-engineering-for-agents]] — context management for agents
- [[openmemory]] — memory layer that could plug into filter chains
