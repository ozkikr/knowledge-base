---
url: https://github.com/psviderski/uncloud
type: github-repo
languages: [Go]
tags: [container-orchestration, docker, wireguard, self-hosted, devops]
date_saved: 2026-02-14
---
# Uncloud

## Summary
Uncloud is a lightweight clustering and container orchestration tool for deploying and managing containerized apps across cloud VMs and bare metal. It creates a secure WireGuard mesh network between Docker hosts, providing automatic service discovery, load balancing, HTTPS ingress, and simple CLI management without the overhead of Kubernetes or Swarm.

## Key Points
- Fully decentralized design with no central control plane — each machine maintains a synchronized copy of cluster state via peer-to-peer communication
- Uses Docker Compose format for defining services, no new DSL to learn
- Zero-config WireGuard mesh network with automatic peer discovery and NAT traversal
- Supports zero-downtime rolling deployments with automatic rollback coming soon
- Integrates with Unregistry for building and pushing Docker images directly to machines without an external registry

## Related
- [[coolify]]
- [[docker]]
- [[kubernetes]]
- [[wireguard]]
