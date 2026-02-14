---
url: https://github.com/MacroPower/kat
type: github-repo
tags: [kubernetes, tui, helm, kustomize, go]
date_saved: 2026-02-14
---

# kat - Kubernetes Manifest TUI

## Summary
A TUI and rule-based rendering engine for Kubernetes manifests. Automatically invokes manifest generators (Helm, Kustomize, etc.) and provides a persistent, navigable view of rendered resources with live reloading and validation.

## Key Points
- Auto-renders Helm charts, Kustomize overlays, and other generators
- Live reload with file watching and diff visualization between renders
- Integrated validation with tools like kubeconform and kyverno
- CEL-based project detection for automatic profile selection
- Plugin system for custom keybind-triggered commands

## Related
- [[helm]] - Kubernetes package manager
- [[kustomize]] - Kubernetes configuration management
- [[kubeconform]] - Kubernetes manifest validator
