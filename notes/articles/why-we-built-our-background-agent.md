---
url: https://builders.ramp.com/post/why-we-built-our-background-agent
type: article
tags: [coding-agents, developer-tools, devex, background-agents, ramp]
date_saved: 2026-02-14
---
# Why We Built Our Background Agent (Inspect)

## Summary
Ramp built Inspect, a background coding agent that runs in sandboxed VMs on Modal. It writes code, verifies its own work via tests/telemetry/visual checks, and supports multiplayer sessions across Slack, Chrome extension, web UI, and PR discussions. ~30% of Ramp's merged PRs are now written by Inspect.

## Key Points
- Each session runs in a sandboxed Modal VM with full dev environment (Vite, Postgres, Temporal) plus integrations (Sentry, Datadog, GitHub, Slack, etc.)
- Images are pre-built every 30 minutes with repo snapshots; sessions restore from snapshots for near-instant startup
- Built on OpenCode as the underlying coding agent, chosen for its server-first architecture and typed SDK
- Multiplayer: sessions are shareable, accessible from Slack, Chrome extension, web UI, mobile, and PR comments
- Unlimited concurrent sessions with no local machine involvement — ideas can be captured instantly

## Related
- [[Coding Agents]]
- [[Modal]]
- [[OpenCode]]
- [[Developer Productivity]]
