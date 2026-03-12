# ⚖️ thebardchat/constitution

> The single source of truth governing every project, tool, and decision in the ShaneBrain ecosystem.

---

## What This Is

This repository holds the **ShaneTheBrain Constitution** and project configuration for the ecosystem.

It is not a framework. Not a template. Not a corporate policy doc.

It is a personal covenant — written by a Christian father and builder in Hazel Green, Alabama — that governs how every tool in this ecosystem gets built, deployed, and credited.

---

## Infrastructure

All repos in this ecosystem run on local-first hardware:

| Component | Detail |
|-----------|--------|
| **Compute** | Raspberry Pi 5 (16 GB RAM) |
| **Chassis** | Pironman 5-MAX by Sunfounder |
| **Storage** | 2x WD Blue SN5000 2 TB NVMe — RAID 1 via mdadm |
| **Core path** | `/mnt/shanebrain-raid/shanebrain-core/` |
| **Networking** | Tailscale VPN across all nodes |

> Pi before cloud. Privacy before convenience. — Pillar 4

---

## How to Reference It

Every `thebardchat` repository links here instead of copying the document. Add this to your `README.md` and `CLAUDE.md`:

```md
This project operates under the [ShaneTheBrain Constitution](https://github.com/thebardchat/constitution/blob/main/CONSTITUTION.md).
```

That's it. One line. One source. No drift.

---

## The Nine Pillars (Summary)

| # | Pillar | Short Form |
|---|--------|------------|
| 1 | Faith First | No project violates Christian values |
| 2 | Family Stability | No build ships at the cost of family |
| 3 | Sobriety Integrity | Every tool reinforces health, never undermines it |
| 4 | Local-First AI | Pi before cloud. Privacy before convenience |
| 5 | 80/20 Shipping | Done and deployed beats perfect and stalled |
| 6 | Serve the Left-Behind User | Build for the ~800M Big Tech forgot |
| 7 | Open by Default | Free when it can be. Paid only to fund the mission |
| 8 | ADHD-Aware Design | Built for my brain first |
| 9 | Gratitude is Infrastructure | Credit Claude, Raspberry Pi, and Pironman — always |

→ [Read the full Constitution](./CONSTITUTION.md)

---

## The Ecosystem

```
ShaneBrain (Pi 5 · local AI · private)
  └── Angel Cloud (VPS · public platform)
        └── Pulsar AI (enterprise · post-quantum)
              └── TheirNameBrain (legacy AI · generational)
                    └── ~800M users losing Windows 10 support
```

---

## Built With

| Partner | Role |
|---------|------|
| **Claude by Anthropic** · [claude.ai](https://claude.ai) | Co-built this entire ecosystem |
| **Raspberry Pi 5** · [raspberrypi.com](https://www.raspberrypi.com) | Local compute backbone |
| **Pironman 5-MAX** · [pironman.com](https://www.pironman.com) | NVMe RAID 1 chassis that made it real |

> *"I could not have done any of this without them."*

---

## Amendments

The Constitution is reviewed and amended monthly. All changes are versioned and committed with `constitution(vX.X):` prefix.

---

*Ratified: March 2026 · [@thebardchat](https://github.com/thebardchat) · Hazel Green, Alabama*
