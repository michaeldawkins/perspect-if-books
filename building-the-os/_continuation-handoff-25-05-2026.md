---
title: "Continuation handoff — Building the OS book"
date: 2026-05-25
type: handoff
status: active
purpose: "Start-here context for a new conversation continuing the agentic-OS book work"
tags: [handoff, os, book, continuation, agents]
---

# Continuation handoff — Building the OS

**Read this first to resume.** This captures the full state of the work as of 25-05-2026 so a new conversation can pick up without re-deriving anything. Companion files (all in `Building the OS Book/` or vault root) are linked at the end.

> **Update 28-05-2026:** Partial answers to Cluster 3, 4, and 6 captured during a Decision Cockpit sweep. See `_cluster-answers-2026-05-28.md` — promotes Q22, Q23, Q31, Q32 to [confirmed][T1]; defers Q15, Q17 explicitly; schedules Cluster 3 for a focused block. The remainder of the interview is unchanged.

---

## 1. What we're doing

Michael is **archiving the old Obsidian vault and building a new agentic-first operating system from the ground up** — understandable, persistent, interchangeable, CebimifAi- and Perspect-if-style. We are writing a book, *Building the Operating System*, that is simultaneously: a **learning journey** (metabolising Michael's insights into clarity), a **clarity artifact** (the single coherent picture), and a **builder's manual** (precise enough to hand to an LLM to build from, and to ask another person the questions to operationalise their own — a Perspect-if/CebimifAi asset).

The book is the primary artifact. It's built with a strict **provenance system** (every claim tagged with where it came from + how much to trust it) and a **knowledge-tier model** (how locked each fact is).

---

## 2. Confirmed decisions (treat as near-Canon — Michael said these directly)

**Purpose (Cluster 1):** An OS for running an agentic-AI-and-people collaborative organisation where people are supported by AI/automation in realising their full potential and flourishing — as individuals and teams — and outputting projects that do the same for people and nature.

**Who it serves, in order:** Michael → therefore Jannie & Ila → CebimifAi → ultimately the Perspect-if vision, one project at a time. CebimifAi is a company doing one part of this.

**The "this is it" morning surface:** overnight decisions made + work shipped by the AI; the decisions Michael must make in yes/no/revise form; new insights to learn **+ a short quiz** to help metabolise them; the **one** high-leverage deep-work thing; all wellbeing/family-aware. **Hard constraint: 4-hour max work day.** The system must *compress* his work, not expand it.

**Never do:** never fail to mirror the truth (no distortion/flattery); never operate without checks and feedback loops; trustworthy in all ways, aligned with people, clients, and nature.

**The human's role — the tower, not the cockpit (v0.3 reframe):** The flight (agentic org) is autonomous. The human's destination role is **mission control / the tower** — directing on vision/purpose, not piloting. Michael = flight director (owns destination, safety envelope, Canon; can ground the plane). Board members = sector controllers directing domains from the tower. **The system's job is to graduate people from cockpit → tower** as trust builds (the autonomy ladder read from the human's side). Principle: **autonomy of execution, never autonomy of intent or values.** This graduation *is* the Perspect-if method.

**Multi-person:** "Me first, then multiply." Person = a row + RLS policy filling a board seat; tenant = a sovereign brain; federation = a scoped MCP grant. A board seat is a portfolio, not a person.

**The knowledge model (two axes):**
- *Provenance* = where from + trust label ([confirmed]/[authoritative]/[inferred]/[proposed]).
- *Tier* = how locked: **T0 Canon** (locked single source of truth) · T1 Confirmed · T2 Working · T3 Evidence · T4 Ephemeral.
- **Canon Amendment Protocol:** propose-don't-edit; two humans to approve, or (solo) a challenge ritual + cooling-off + second confirmation; append-only amendment log. Keeps the source of truth pure.

---

## 3. The architecture in one breath (proposed, from the blueprint)

Eight layers: L0 Substrate · L1 Memory (the 5 tiers, with forgetting) · L2 Context assembly · L3 Skills · L4 Agents (thin) · L5 Runtime · L6 Orchestration/loops · L7 Governance · L8 Interface (the tower's instruments). Spine = one queryable store (Postgres+pgvector, OB1-style) + Bridge-as-MCP-server + the **MCP/A2A/AG-UI** protocol triad. Build discipline: plumbing before features, sequential before swarm, instrument on consumption not production. Model-router = interchangeability (route by task tier; swap by config). HERMES build loop = how each skill is made (Hunt→Engineer one job→Run at 80%→Multiply/relay→Expand→Systemise).

**Eleven domains** (each a board seat → roles → skills): Direction & Governance · Finance · Sales · MarCom · Product · Delivery & Client Success · People & Culture (human + agent HR) · Legal/Risk · Operations & Systems · Knowledge & Learning · Administration.

---

## 4. Provenance of the ideas (the sources)

- **‹MJD›** Michael — purpose, values, constraints (Cluster 1, the tower reframe, knowledge model).
- **‹VAULT›** his existing vault — crystals, operating-model vision, Mission Control, the Bridge spec (the governance spine), the memory index (the diagnosis).
- **‹NBJ›** Nate B. Jones — the 12 agentic-harness primitives, OB1/Open Brain, the MCP/A2A/AG-UI triad, "produce at 100x, review at 3x."
- **‹AK›** Andrej Karpathy — Software 3.0, LLM-as-OS, vibe-coding vs agentic-engineering.
- **‹SS›** Simon Scrapes — the 5 workflow patterns; "start sequential, earn the swarm."
- **‹JG›** Julian Goldie — the Mission Stack (Intelligence/Execution/Research/Self + Studio), the HERMES build loop, the model-router. *(Most product specifics unverified.)*
- **‹JR›** Jack Roberts — the unified-OS bridge (shared memory across agents).
- **‹CCL›** Claude Code source leak — origin of the 12 primitives, "80% plumbing."
- **‹CW›** Cowork — the synthesis (8-layer model, migration, the org map) — all [proposed] until confirmed.

> Caveat: 2026 tooling (Hermes, OpenClaw, Grok, Antigravity, specific models) is past Cowork's reliable knowledge — treated as [authoritative — unverified]; patterns kept, product specifics treated as perishable.

---

## 5. Open threads / next actions

> **Update 26-05-2026:** Cluster 2 (the stack) is **answered and confirmed**, and **Part IV (Ch 6–11) is written** from it (book now v0.4). Confirmed: build-your-own-harness on the primitives; stable/dev two-system split; sovereignty as a design pillar with the privacy membrane; Postgres + pgvector (OB1, Nate Jones as guide) with documents-rendered-on-the-fly; models-as-instruments / model-router; day-one connectors (Gmail, Calendar, Drive, Plaud, NotebookLM, Canva, Gamma); Folk + Timely **retired**; the myelination rule for the N8N workflow layer. The architecture blueprint stays **set aside** until the book is complete, then read back for gaps. **Next unlock: Cluster 6 (governance) to close Ch 11's autonomy/approval dials; also Clusters 3–8 and Ch 8's primitive enumeration to reconcile.**

1. ~~**Cluster 2 (the stack) is the unlock**~~ — DONE (see update above).
2. **React to the eleven domains** (Ch 5) — right ones? missing? different board seats?
3. **Clusters 3–8 still pending** (multi-person, dynamic UI, production studio, governance, migration, success/constraints) — each unlocks its scaffolded chapter.
4. **NotebookLM offer open** — build a scoped research corpus (the ~30–40 architecture-relevant CCW videos only, not all 244) as a queryable reading tool *for the book*, then archive. Michael has the `notebooklm-field` plugin + Chrome bridge.
5. **Skool note:** payment fixed; gated modules are Skool *levels* (earned via engagement / DM Julian), not bypassable. The ungated Drive files are the real route — Multi-Model Playbook + Hermes Agent OS already pulled.
6. **Interview answers** captured in `os-handbook-interview-25-05-2026.md` (Cluster 1 done; 2–8 open).

---

## 6. Artifacts (all live in the vault)

- **The book:** `Building the OS Book/00-the-book.md` (v0.3) — front matter (purpose, provenance, knowledge model) + Parts I–III written; IV–VII scaffolded.
- **The architecture blueprint:** `forward-os-architecture-blueprint-25-05-2026.md` — the 8 layers, OB1×Bridge spine, 12-primitive scorecard, HERMES loop (§9.7), model-router (§9.8).
- **The founding interview:** `os-handbook-interview-25-05-2026.md` — 40 questions, Cluster 1 answered.
- **The two-vault audit (superseded but useful):** `two-systems-deep-dive-22-05-2026.md`.
- **Key research note:** `Reference/Research/2026-05-20-six-agent-protocols-three-foundational-nate-jones.md` (MCP/A2A/AG-UI).

---

## 7. How to resume in the new conversation

Open with: *"Continue the agentic-OS book. Read `Building the OS Book/_continuation-handoff-25-05-2026.md` and `Building the OS Book/00-the-book.md`, then let's do Cluster 2."* — or whichever thread is alive. Maintain the provenance discipline (tag every claim) and the operator stance (ruthless but constructive, validation-first, mirror the truth).

---

*Handoff written 25-05-2026 by Cowork; updated 26-05-2026. State: book v0.4, Clusters 1–2 confirmed, Part IV (Ch 6–11) written. Next: Cluster 6 (governance dials) to close Ch 11; Clusters 3–8 still open; Ch 8 primitive enumeration to reconcile against the set-aside blueprint.*
