# VRP Demo — Event Stream Preview

This repository is a demonstration layer for VRP (Veil Routing Protocol) behavior.

It does not implement a real routing engine or real cryptography.
It demonstrates **behavioral intent** through an event stream that can be visualized.

---

## What this demo shows

- A session-centric view of routing behavior
- Mutation cycles (“route drift” over time)
- Candidate path competition and selection
- Explicit reason-coded decisions (no magic behavior)
- An observable timeline suitable for UI / dashboards

---

## What this demo does NOT show (by design)

- No real packet forwarding
- No real anonymity claims
- No production-grade threat resistance
- No full VRP internals
- No performance claims

---

## How to read the demo

The demo is represented as a JSONL event stream:

- Each line = one event
- Events form a timeline
- The timeline describes how VRP would adapt under volatility

See:

- `src/mock/sample_events.jsonl`

---

## Related repositories

- Jumping VPN architectural preview:
  https://github.com/Endless33/jumping-vpn-preview

- VRP SDK (integration layer preview):
  https://github.com/Endless33/vrp-sdk