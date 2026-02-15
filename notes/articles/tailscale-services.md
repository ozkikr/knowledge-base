---
url: https://tailscale.com/kb/1552/tailscale-services
type: article
tags: [networking, tailscale, platform-engineering]
date_saved: 2026-02-15
---
# Tailscale Services
## Summary
Tailscale Services provide stable, named service endpoints inside a tailnet so clients connect to services instead of specific hosts. This decouples service identity from infrastructure placement and simplifies migrations, scaling, and failover. The documentation covers setup, host approval, routing behavior, and operational lifecycle tasks such as draining and reconfiguration.

## Key Points
- Services expose internal resources with stable MagicDNS names and TailVIPs.
- Hosts can be added, removed, or moved without changing client-facing service addresses.
- Access control and approval workflows are integrated with tailnet policy and identity.
- Setup typically uses `tailscale serve --service ...` to configure and advertise endpoints.
- Operational controls include draining hosts, clearing mappings, and updating service configs safely.

## Related
- [[service-discovery]]
- [[zero-trust-networking]]
- [[high-availability]]
