# VRP Demo — Behavioral Event Stream Preview

This repository is a **public demonstration layer** for VRP behavior.
It focuses on **observable routing dynamics** (conceptual), using a mock event stream designed for visualization.

This is not a production routing engine.
This repo exists to make VRP behavior easy to review.

---

## What’s Inside

- `docs/` — demo overview and notes  
- `src/mock/` — mock VRP sessions and movement flows (JSONL event stream)  
- `src/ui/` — minimal UI for visualizing routing behavior *(planned)*  
- `src/websocket/` — event stream listener *(planned)*  

---

## Demo Entry Point

Start here:

- `docs/demo-overview.md` — what the demo shows / does not show  
- `src/mock/sample_events.jsonl` — the demo event timeline (JSONL)

Each JSON line represents a deterministic signal, decision, or state transition.

---

## Event Types (Preview)

Typical events in the stream include:

- `SESSION_CREATED`
- `CANDIDATES_DISCOVERED`
- `PATH_SELECTED`
- `VOLATILITY_SIGNAL`
- `STATE_CHANGE`
- `MUTATION_TICK`
- `RECOVERY_SIGNAL`
- `AUDIT_EVENT`

No real routing, no real cryptography, and no performance claims are made in this repository.

---

## Status

Source code is released in stages.
Current status:

- Mock event stream: available
- UI visualization layer: planned
- WebSocket event stream listener: planned

---

## Contact

For technical discussions:

📩 riabovasvitalijus@gmail.com

---

## Related Repositories

- Jumping VPN (architectural preview):  
  https://github.com/Endless33/jumping-vpn-preview

- VRP SDK (integration layer preview):  
  https://github.com/Endless33/vrp-sdk
```0