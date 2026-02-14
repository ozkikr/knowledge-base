---
url: https://github.com/ergo-services/ergo
type: github-repo
tags: [golang, actor-model, erlang, distributed-systems]
date_saved: 2026-02-14
---
# Ergo Framework

## Summary
Ergo is an actor-based framework for Go inspired by Erlang, providing network transparency for building event-driven architectures. It features zero dependencies, supervision trees, and distributed system primitives like service discovery and pub/sub.

## Key Points
- Actor model with isolated processes, message passing, and four-priority mailboxes
- Network transparency: actors interact the same way locally or remotely
- Supervision trees with multiple strategies (One For One, All For One, etc.)
- Meta processes bridge blocking I/O (TCP, UDP, Web) with the actor model
- Distributed systems support: service discovery, pub/sub, remote spawning

## Related
- [[Erlang]] [[OTP]] [[distributed-systems]] [[message-passing]]
