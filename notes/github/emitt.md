---
url: https://github.com/schappim/emitt
type: github-repo
languages: [Go, Shell]
tags: [email-automation, llm-tools, smtp]
date_saved: 2026-02-15
---
# eMitt
## Summary
eMitt is an inbound email processing server that combines SMTP ingestion with LLM-driven automation. It routes messages through configurable mailbox rules and can trigger built-in tools such as HTTP requests, SQL queries, and outbound replies. The project is aimed at building intelligent mailbox workflows similar to inbound processing platforms.

## Key Points
- Includes a built-in SMTP server and YAML-based routing on from/to/subject patterns.
- Supports LLM processors with function-calling and optional MCP server integrations.
- Persists emails, tool calls, and logs in SQLite for traceability and auditing.
- Enables automated support, ticketing, forwarding, and webhook-driven workflows.

## Related
- [[Email automation]]
- [[LLM function calling]]
- [[SMTP servers]]
