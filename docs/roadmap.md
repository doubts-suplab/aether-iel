# Aether IEL — Roadmap

> Aether IEL is a **methodology framework** (no runtime code): the 12-phase Intelligence Engineering
> Lifecycle, the Intelligence Maturity Model, standards, and templates. This roadmap tracks how to turn
> the methodology from an excellent on-paper framework into **living, enforceable practice**.
>
> Part of the [Æ Aether ecosystem improvement backlog](https://github.com/doubts-suplab/aether/blob/main/docs/roadmaps/ecosystem-improvements.md).
> License unchanged (AGPL-3.0).

---

## Ecosystem review — future backlog

> Planned, not started. Feasibility: **S** small · **M** moderate · **L** large.

| Item | Feasibility | Notes |
|---|---|---|
| More complete phase guides + examples mapped to the **actual** runtime repos (Core, Grid, Memory, Vault, Flow) | **M** | Make each of the 12 phases concrete against a real Aether component, not just abstract prose. |
| Runnable checklists / tooling that can be executed **against a codebase** | **M–L** | Turn phase-gate standards into something CI or a CLI can evaluate. |
| Automated maturity scoring (run the IMM against a repo) | **M–L** | The methodology's highest-leverage "living practice" step; ties into the ecosystem's methodology-enforcement theme. |
| Case studies of applying AIEL to Core / Grid / etc. | **S–M** | Demonstrate the lifecycle end-to-end on components that already exist. |
| Broader adoption beyond the Aether team | **S** | Positioning + examples so external teams can apply AIEL to their own intelligence systems. |

---

## How this connects to the ecosystem

AIEL is the methodological backbone; the ecosystem review calls for **methodology enforcement &
tooling** (theme 5): ADR-generation hooks, phase-gate checks in CI, and a tight artifact↔phase mapping
so that Core/Grid/Memory/Vault/Flow artifacts trace cleanly to IEL phases and templates. Those
cross-cutting items live in the [ecosystem improvement backlog](https://github.com/doubts-suplab/aether/blob/main/docs/roadmaps/ecosystem-improvements.md);
the repo-specific methodology work is tracked above.

> Nothing here is claimed as delivered. Items graduate to a progress log as they ship.
