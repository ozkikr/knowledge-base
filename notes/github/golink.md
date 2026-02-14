---
url: https://github.com/tailscale/golink
type: github-repo
languages: [Go]
tags: [tailscale, shortlinks, internal-tools, networking]
date_saved: 2026-02-14
---
# golink

## Summary
golink is a private shortlink service for Tailscale tailnets. It lets you create short, memorable links (like `go/docs`) for websites your team uses most, accessible only within your private network.

## Key Points
- Creates private short links accessible only within a Tailscale tailnet
- Uses SQLite for link storage
- Can run via Go binary or Docker container
- Supports dev mode for local testing without joining a tailnet
- Integrates with Tailscale auth keys and ACL tags for access control

## Related
- [[tailscale]]
- [[internal-tools]]
