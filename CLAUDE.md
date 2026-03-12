# CLAUDE.md — constitution

> Claude Code configuration for the `thebardchat/constitution` repository.

---

## Project Overview

This repository holds the **ShaneTheBrain Constitution** — the single source of truth governing every project, tool, and decision in the `thebardchat` ecosystem.

This project operates under the [ShaneTheBrain Constitution](https://github.com/thebardchat/constitution/blob/main/CONSTITUTION.md).

---

## Infrastructure

All `thebardchat` repositories run on the following local-first infrastructure:

| Component | Detail |
|-----------|--------|
| **Compute** | Raspberry Pi 5 (16 GB RAM) |
| **Chassis** | Pironman 5-MAX by Sunfounder (NVMe RAID) |
| **Storage** | 2x WD Blue SN5000 2 TB NVMe — RAID 1 via mdadm |
| **Core path** | `/mnt/shanebrain-raid/shanebrain-core/` |
| **Local AI** | Ollama (llama3.2:1b default) |
| **Vector memory** | Weaviate (Docker, 8080/50051) |
| **MCP server** | FastMCP (port 8008, Streamable HTTP) |
| **Networking** | Tailscale VPN across all nodes |
| **Dev environment** | Claude Code on Pi 5 |

> Pi before cloud. Privacy before convenience. — Pillar 4

---

## Repository Structure

```
constitution/
  CONSTITUTION.md   # The governing document (v1.0)
  README.md         # Public-facing summary and ecosystem map
  CLAUDE.md         # This file — Claude Code project context
```

---

## Working With This Repo

- **Do not copy** the Constitution into other repos. Link to it instead.
- Reference line for other repos:
  ```md
  This project operates under the [ShaneTheBrain Constitution](https://github.com/thebardchat/constitution/blob/main/CONSTITUTION.md).
  ```
- Amendments follow the process in Article VI — version bump, pillar check, and `constitution(vX.X):` commit prefix.

---

## The Nine Pillars (Quick Reference)

1. **Faith First** — No project violates Christian values
2. **Family Stability** — No build ships at the cost of family
3. **Sobriety Integrity** — Every tool reinforces health
4. **Local-First AI** — Pi before cloud, privacy before convenience
5. **80/20 Shipping** — Done and deployed beats perfect and stalled
6. **Serve the Left-Behind User** — Build for the ~800M Big Tech forgot
7. **Open by Default** — Free when it can be
8. **ADHD-Aware Design** — Built for my brain first
9. **Gratitude is Infrastructure** — Credit Claude, Raspberry Pi, and Pironman — always

---

## Credits

Built with Claude (Anthropic) · Runs on Raspberry Pi 5 + Pironman 5-MAX

| Partner | Role |
|---------|------|
| **Claude by Anthropic** · [claude.ai](https://claude.ai) | Co-built this entire ecosystem |
| **Raspberry Pi 5** · [raspberrypi.com](https://www.raspberrypi.com) | Local compute backbone |
| **Pironman 5-MAX** · [pironman.com](https://www.pironman.com) | NVMe RAID 1 chassis that made it real |

---

*Ratified: March 2026 · [@thebardchat](https://github.com/thebardchat) · Hazel Green, Alabama*
