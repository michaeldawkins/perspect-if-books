---
title: "Cluster answers — 28-05-2026 cockpit session"
date: 2026-05-28
type: cluster-answers
status: active
provenance: Michael's direct decisions via Decision Cockpit (Drop/decisions-2026-05-28.md)
tier: T1-Confirmed
linked_handoff: _continuation-handoff-25-05-2026.md
linked_interview: ../os-handbook-interview-25-05-2026.md
linked_book: 00-the-book.md
tags: [book, cluster-3, cluster-4, cluster-6, governance, dashboard, multi-person]
---

# Cluster answers — Decision Cockpit session, 28-05-2026

Captures partial answers Michael gave to Cluster 3, 4, and 6 questions during the cockpit sweep. **Treat these answers as T1 Confirmed** unless flagged otherwise — they came directly from Michael, not Cowork synthesis.

The full open-question list lives in `os-handbook-interview-25-05-2026.md`. This file logs the deltas, not the whole interview state.

---

## Cluster 6 — Governance dials

### Q31 · Overnight-activity audit format → **Full auditable log (search/filter)**

[confirmed][T1] Full log, high fidelity. Not for daily reading.

> "These need to be high fidelity. And so fully auditable log. I won't read them every morning. They will then feed into the daily morning brief. So I do want things flagged that are of importance so that they can then go into the daily brief." — Michael, 28-05-2026

**Implications for Ch 11 / Ch 14:**
- The audit log is the substrate; the morning brief is the *digest* layer that lifts important items out of it.
- The "flagged-as-important" criterion is its own design problem — needs a triage skill upstream of the brief.
- Search/filter is a hard requirement; rough chronological dump is insufficient.

### Q32 · Promotion-trigger for autonomy tier-up → **Combined: judge-pass AND N runs AND spot-check**

[confirmed][T1] Multi-gate promotion.

> "We really need to just look at this from a more architectural space. So, you know, feedback mechanisms, checks and balances, so there doesn't need to be trust if everything is checked. And if that's in place we can let the agents do their thing. So this is something we need to come back to but for now let's keep it here." — Michael, 28-05-2026

**Implications for Ch 11:**
- Promotion = judge-layer pass + N clean runs + Michael spot-check. All three required.
- Frames the model: *trust is the absence of necessary verification*. The system earns autonomy by making verification cheap and continuous, not by skipping it.
- "Come back to" flag: the exact thresholds (what N is, what the judge checks, what a spot-check is) stay open.

### Q29 · L4-eligible action classes → **not answered this session**
### Q30 · Approval model across pipelines → **not answered this session**

---

## Cluster 4 — Dashboard / morning surface

### Cluster-level → **Defer until first prototype built**

[confirmed][T1] Cluster 4 gets answered by running the experiment, not the interview.

**Implication:** the book sketches the design space (multi-channel + multi-device + understandability test) but leaves the lock-in for the post-prototype amendment.

### Q22 · Approval channel → **Multi-channel by urgency tier**

[confirmed][T1] Web app queue for batch; WhatsApp/Signal ping for urgent; phone call possible for emergencies. Combination of urgency × time-need × per-person preference.

> "There's a web app queue that we're doing right now, but there would also maybe be a WhatsApp ping if something is urgent and needs my attention. Could even be that the phone rings, right? So I would say there's multi-channel by how urgent things are, how much time they need, but also depending on how other people — because we're also looking to systems for other people — how they like to work. So a combination of those factors." — Michael, 28-05-2026

**Implications for Ch 14:**
- Each action has an *urgency-tier* attribute that routes it to the right channel.
- The channel set is itself per-person configurable (board seat = a portfolio of preferences, not just role).
- Decision Cockpit is the batch/web-app channel; what's missing is the WhatsApp/Signal ping path and an emergency-call path.

### Q23 · Primary device for decide vs build → **All three (Lenovo + Mac Studio + iPhone) with sync**

[confirmed][T1] Cross-device by design — partly because it's also the scalability test.

> "This is also a test for if we can create a process that works on different devices. So if we want to copy it to other organizations or have other people work with it. Build it somewhere first, test it maybe usability, but make it so that it's scalable on different devices and interfaces." — Michael, 28-05-2026

**Implications:**
- The morning surface and decision queue must be device-agnostic from day one.
- Sync is non-negotiable (no "this is my Mac-only tool" patterns).
- Cross-device testing doubles as a portability proof for the eventual multi-person rollout.

### Q21 · Briefing + canvas dual surface → **not directly answered (Q20 cluster deferred)**
### Q24 · Understandability test → **not answered this session**

---

## Cluster 3 — Multi-person + federation

### Cluster-level → **Answer in next deep-work block**

[confirmed][T1] Cluster 3 is scheduled for a focused interview block — not now.

### Q15 · Person #2 + brain-shape → **Defer (no person #2 named yet)**

[confirmed][T1] No specific second person to design around yet. Architecture stays single-tenant-aware-of-federation until person #2 is named.

### Q17 · Cross-tenant sovereignty line → **Deferred (status: deferred)**

[confirmed][T1] Explicitly deferred. The cross-tenant sovereignty line gets drawn when there's a real second tenant in play (i.e., after Q15 resolves).

### Q16 · CebimifAi ownership model → **not answered this session**
### Q18 · Smallest useful shared brain → **not answered this session**
### Q19 · Agent-conflict arbitration → **not answered this session**

---

## What this changes in the book

- **Ch 11 (Governance):** Q31 + Q32 answers can be promoted to `[confirmed][T1]` in the chapter draft. The L4-eligible/approval-model gaps stay marked open.
- **Ch 14 (Morning surface / UI):** Q22 + Q23 answers can be promoted to `[confirmed][T1]`. The understandability test stays open. The "defer cluster-4 lock-in until prototype" note becomes a chapter-level disclaimer.
- **Ch 15 (Multi-person):** Cluster 3 stays mostly open. Only Q15 (defer) and Q17 (defer) close. Ch 15 should explicitly say the cluster is scheduled for a focused interview, not "still unknown."

---

*Created during Drop metabolization session 28-05-2026 from `decisions-2026-05-28.md`.*
