---
url: https://github.com/bschaatsbergen/cek
type: github-repo
languages: [Go]
tags: [containers, oci, docker, filesystem, cli]
date_saved: 2026-02-14
---
# cek - Container Exploration Kit

## Summary
cek is a CLI tool for exploring OCI container image filesystems without running containers. It reads images from local daemons or remote registries, letting you browse files, read contents, and inspect layer mechanics—all without root privileges.

## Key Points
- Explore container image filesystems without running containers or requiring root
- Shows merged overlay filesystem or individual layer views
- Supports ls, cat, and filter operations with glob pattern matching
- Works with any OCI-compliant registry and local daemons (Docker, Podman, containerd)
- Installable via Homebrew or `go install`

## Related
- [[docker]]
- [[oci-images]]
- [[dive]]
