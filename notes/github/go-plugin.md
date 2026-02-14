---
url: https://github.com/hashicorp/go-plugin
type: github-repo
tags: [golang, plugin-system, rpc, grpc, hashicorp]
date_saved: 2026-02-14
---
# hashicorp/go-plugin

## Summary
A Go plugin system over RPC used by HashiCorp tools (Terraform, Vault, Nomad, Packer, Boundary, Waypoint) for over 4 years. Plugins are Go interface implementations communicated over local RPC (net/rpc or gRPC), with cross-language support via gRPC.

## Key Points
- Plugins feel natural: authors implement Go interfaces, consumers call them as if in-process — RPC is abstracted away
- Cross-language via gRPC: plugins can be written/consumed in any major language
- Supports complex args (interfaces, io.Reader/Writer), bidirectional communication, and host upgrade while plugin runs
- Built-in logging, stdout/stderr syncing, TTY preservation, protocol versioning, and cryptographic verification
- Battle-tested on millions of machines; designed for local networks only (not real network plugins)

## Related
- [[golang]]
- [[grpc]]
- [[terraform]]
- [[plugin-architecture]]
