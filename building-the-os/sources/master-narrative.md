---
title: What We Are Building and Why: The Master Narrative v0.2
doc-type: narrative
owner: Michael
status: staged-for-approval
created: 13-06-2026
revised: 14-06-2026
review-by: 17-10-2026
reviewed: T-239/000639-cycle 17-07-2026
task-ref: T-047
staged-as: A-024
authority: working
confidence: medium
source-type: synthesis
---

# What We Are Building and Why

*A plain-language account of the agentic organisation, for people who need to understand, not just believe.*

**Version:** v0.2 draft, reworked 14-06-2026 per STEER feedback from the 13-06-2026 consent round
**Status:** working draft; feeds Building the OS Book; pop in Obsidian on every revision

---

## Prologue: The question nobody is asking clearly enough

Here is the question that motivates everything in this document:

*What does it actually mean for an organisation to use AI well?*

Not "which tools do you use?" Not "what's your AI strategy?" Those questions have been answered a thousand times, mostly badly. The real question is structural: **how do you wire intelligence into the machinery of an organisation in a way that makes the humans more themselves, not less?**

Most current answers are incomplete. You get tools. You get APIs. You get automation. What you do not get is a design for how memory works, who decides what, what the agents are allowed to do without asking, how you know if any of it is actually working, and how you stay sovereign over your own data, your own voice, your own direction, as the tools keep changing around you.

This organisation is working on that design. Not in the abstract. In the specific: with real ventures, real code, real governance, real proofs, real failures, and a record of all of it.

This document explains what we are building, how it works, and why it is built the way it is. It is written for people who think seriously about things. It does not assume you are technical. It does assume you want to understand.

---

## Part I: What is an agentic organisation?

An organisation is usually a set of people, roles, and processes organised around a purpose. The modern organisation is organised around human labour: people think, decide, and act.

An **agentic organisation** keeps the human at the centre, but redesigns what the humans do. The humans hold the meaning: the purpose, the values, the direction, the identity, the relationships, the judgment calls that require wisdom rather than information processing. The agents, software programmes running on AI models, handle the machinery: researching, drafting, summarising, testing, routing, monitoring, scheduling, tracking, evaluating.

The metaphor that makes this real is the organism. Not the machine: machines break and are replaced. Not the army: armies follow orders and lose initiative. An organism is **alive**. It senses, adapts, remembers, learns, and conserves its identity while everything inside it changes. It does not need its parts to be smart; it needs its parts to be coordinated. The coordination is the intelligence.

The agentic organisation we are building has:

- A **brain**: a canonical repository of records, decisions, evidence, and memory that agents can read and write to, that survives any individual model going away
- A **nervous system**: loops that run continuously, building, evaluating, measuring, learning, reporting
- A **governance layer**: policies and rituals that ensure the humans remain in control without needing to be present for every operation
- **Proof ventures**: real-world organisations running on this design, so we can know what actually works

This organisation is not a product. It is a practice. You do not install it. You grow it.

---

## Part II: The origin story in three paragraphs

Michael has been building toward this for a long time, though the exact shape only became clear in early 2026.

The lineage goes back to 2017: a 160-item Human Potential Assessment built by hand, for SingularityU participants, trying to surface what people were actually ready for. Then an Exponential Leadership Assessment in 2018. Then years of advising regenerative entrepreneurs, energy cooperatives, impact ventures, organisations that wanted to do more good in the world but kept hitting the same wall: the humans were the bottleneck. Not because they were incapable, but because the machinery of the organisation kept pulling them into tasks that did not require them, while the judgment that only they could make went unmade.

The AI transition of 2024 to 2026 changed what was possible. Not just as a capability, but as an architecture. When models became capable enough to hold context, use tools, and execute multi-step tasks without constant supervision, the question shifted from "what can AI do?" to "what should the design of a human-plus-AI organisation look like?" That question is Michael's question. The vault, his Obsidian repository of seven years of thinking, writing, building, and note-taking, became the raw material. The organisation we are building now is the answer.

What we are building is not a product for someone else. It is, first, Michael's own organisation made to work. Then, once proven, a design that others can adopt. The principle is: **me first, then multiply**. The system must work for the person building it before it can work for anyone else. That is not selfishness; it is honest design.

### About the person building this

Michael's route into this work starts somewhere unexpected: physiotherapy. Years of seeing how the body adapts, repairs, and stays coherent under load shaped his thinking about organisations. The organism metaphor in this design is not decorative. It comes from a sustained interest in how living systems, bodies, forests, watersheds, stay alive and purposeful without top-down control. Nature has been solving the problem of coordinated, self-sustaining intelligence far longer than management theory has. That is the design principle.

Two things are worth saying clearly. First, this is a framework, not a product. The agentic OS is a design approach and a set of governance principles, not software you purchase or install. Second, what is described in this document is Michael's own organisation, built for his own work, tested against real stakes. Only what is proven here reaches others.

---

## Part III: The architecture in plain language

You do not need to understand every piece of the architecture. But you need the map.

### The brain

The brain is a git repository, a version-controlled folder that stores the organisation's official memory. Not all memory. The brain stores the organisational state: the decisions that have been made, the claims that have been verified, the projects that are live, the people the organisation relates to, the finances, the lessons.

The brain is always recoverable. If any machine dies, the brain is cloned to another machine in minutes. If any agent makes an error, the error is visible in the history and can be reversed. **Models visit. Memory stays.**

### The vault: the second brain

Behind the organisational brain is a personal layer: the vault. Seven years of Michael's thinking, writing, and research live in an Obsidian notebook on local hardware. The vault is not directly accessible to agents in the way the brain is. It is the raw material from which the brain is derived: source packets, biographical record, writing drafts, captured ideas.

The relationship between vault and brain is governed by a boundary rule: each type of content has one home. Raw thinking lives in the vault. Verified decisions and organisational state live in the brain. Neither duplicates the other. Cross-references link them. This prevents the organisation from simultaneously believing two contradictory things about the same topic because they live in different files.

### The registers

Inside the brain are registers: live documents that track specific things. There is a portfolio register (which ventures exist and what state they are in), a project register (which workstreams are running), a relationship register (who the organisation knows, with a GDPR header because human contact data belongs to the people it describes), a model routing log (which AI models are used for which tasks, with benchmark evidence), a decision log (every significant decision, numbered and dated, with reasoning).

Registers are not bureaucracy. They are the organisation's answer to the question every founder eventually hits: *what do we actually know, and how do we know it?* Without registers, the answer is "it's in someone's head." That is not an answer. That is a single point of failure.

### Memory and lessons

Alongside the registers is a lighter layer: the memory and lesson system. After each build cycle, lessons are captured in structured records. After each significant failure, the failure mode is named and filed so the organisation does not repeat it. When a future session starts, it can retrieve what was learned before, without relying on any single model to remember it across sessions.

This is the IRM layer, Information Recall Memory: the things the organisation needs to retain across time, between different AI models, between machines. The principle is simple. If something surprised the organisation once, it should not surprise it twice.

### The loops

The organisation runs on loops. Not a waterfall of projects with start and end dates. Continuous cycles that keep running, keep building, keep measuring.

The most fundamental is the **build cycle**: every two hours, a fresh AI session opens, reads the build queue, picks the highest-priority unblocked task within its authority, executes it, updates the relevant registers, and commits the result. An adversarial judge, a separate AI session with no knowledge of what the builder intended, reads the diff and gives a verdict: PASS or FAIL. Only PASSed work advances.

Every morning at 07:30, a **heartbeat** runs: scanning for records whose review dates have passed, reporting on the approvals queue, pushing the brain to its private remote backup.

Once a day, during this high-velocity launch window, Michael spends 30 minutes with the **daily review**: reading the digests, clearing the approvals queue, redirecting where needed. This is his main interface with the organisation. Not code. Not command lines. A carefully prepared reading packet that puts every decision in plain language.

### Proof-of-done

A scanner runs alongside the build loop to answer one question: is the work actually finished, or just labelled done? It reads the build queue, the approvals queue, and the digests, then produces a signal: completion rate, pending approval count, consecutive clean cycle streak.

This matters because "done" is the easiest status to fake. The proof-of-done scanner is the organisation's way of asking: if we look at what was committed versus what was claimed, what do we actually see?

### Provenance

Every significant claim this organisation makes must be traceable to its source. Not just "we believe this is true." The exact path from claim to evidence must be reconstructable: what the claim is, where it came from, what evidence supports it, what is still unresolved.

The provenance pattern was first applied to CebimifAi's public claims: 31 claims from the intended website reviewed, labelled, and documented in a public claim ledger. Ten are publishable now. Twelve carry caveats. Nine are pre-publication gated, including the most critical: a technical proposition that depends on an API integration not yet confirmed. That fact is now visible in the organisational record, not buried in a slide deck. The organisation that knows what it does not know is more trustworthy than the one that claims certainty.

### The governance layer

Governance is what makes the loops safe.

Every agent in this organisation operates under an explicit autonomy level: L0 through L6. L0 is observe-only. L1 drafts locally. L2 tests locally. L3 stages external actions but never sends or publishes. L4 acts after explicit human approval. L5 is bounded autonomy within deterministic constraints, earned, never assumed. L6 is constitutional: human-only.

The key insight is that **autonomy attaches to workflows, not to agents**. You do not trust an agent generically. You trust a specific combination of workflow, tool access, and data scope because you have measured its outputs enough times to know it can be trusted there, and nowhere else. The agent that drafts a Dutch email proposal has no authority to press send. The agent that researches claims has no authority to publish. Trust is granular, evidenced, and revocable.

Six categories of action are **never delegated**: sending messages, publishing anything, making payments, changing credentials, deleting records, and making commitments. These require Michael's explicit tap every single time, regardless of how often they have been done before. This is not because agents cannot be trusted; it is because these actions cross a threshold from reversible to real, and that threshold belongs to the human.

### The eval factory

The organisation builds its own quality control.

Every artifact that matters, a claim about CebimifAi's technical capabilities, an invitation to a pilot user, a workshop spec, an assessment instrument, goes through an evaluation pipeline before it is treated as real. A rubric is written first, specifying what a good artifact looks like. Deterministic checks run automatically (does it carry the required metadata? are the claims source-grounded?). Then a judge, another AI session adversarially primed to find problems, reviews it and gives a verdict. The outcome field on the artifact is filled: accepted, edited, rejected, or reopened.

This is not perfectionism. It is the organisation's immune system. The failure mode this prevents is the **false green**: work that looks done but is not, work that reports safe but fails in reality. The nightly build loop has already caught dozens of these. Every FAIL verdict from the judge is a piece of value: it names the problem before it ships.

---

## Part IV: The thirteen laws

The organisation runs on thirteen laws. They are not policy. They are constitution: they change only when Michael explicitly ratifies a change, and they are the frame within which every other decision is made.

Here they are in human language, stripped of the formal numbering:

**The organisation exists to serve flourishing.** Not productivity. Not profit. Flourishing: agency, compassion, coherence, regeneration, courage, wisdom, creativity, life-affirming possibility. Every major system must answer: does this increase flourishing?

**The organisation owns its own memory.** Models visit. Memory stays. The brain, the registers, the decisions, the evidence, the relationships, these live here, not in the cloud. Cloud models are tools. The organisation is the client, not the product.

**Model output is evidence, not fact.** Anything an AI model produces must be grounded: in a source, in measured reality, in human confirmation, or in deterministic checks. The organisation never treats a model's output as true just because it sounds plausible.

**Autonomy is earned, never assumed.** Agents earn autonomy on specific workflows by demonstrating measured, safe, reversible results. They do not earn it generically by being impressive.

**Never combine sensitive data, untrusted content, and external action without containment.** This is the lethal trifecta: the way a sophisticated attack gets through any defence. The policy is absolute: if all three are present, special containment is required, minimal tool access, egress controls, independent review, explicit approval.

**The organisation may improve itself but may not mark its own homework.** Agents propose changes to workflows, prompts, specs. Humans ratify changes to purpose, values, identity, authority, and external commitments. The organisation is self-improving but not self-ratifying.

**Use mature tools where good enough.** Build custom only where sovereignty, provenance, trust, or product moat requires it. Not-invented-here syndrome is expensive and fragile.

**Build only what a real task pulls into existence.** Infrastructure is built when it is needed, not before. No register exists before the workflow that writes to it. Speculative infrastructure is debt.

**Registers are updated by agents as a side effect of doing work.** The organisation does not rely on humans to maintain its records. If a record requires manual upkeep, it is misdesigned. Every record carries a review date and goes stale automatically if nobody refreshes it.

**Every staged artifact carries an outcome field.** The organisation never builds something without wiring in a way to know whether it worked: accepted, edited, rejected, reopened. Metrics are captured at the moment of work. No instrumentation, no autonomy promotion.

**If governance is absent, everything drops to observe-only.** If the approvals queue ages beyond seven days, all workflows automatically drop to L0 to L2. Nothing external happens while the human is unreachable.

**Secrets never enter the public record.** API keys, tokens, credentials: none in the brain repo, none in prompts, none in agent context. The brain must be safe to show a stranger, except for the explicitly guarded private subtree.

**The system adapts to the person, never the person to the system.** Michael ratified this one in his own words: it evolves to amplify the user's agency, health, and flourishing. The Human Agency Law. The organisation is not a machine that humans learn to operate; it is a design that learns to serve its humans.

---

## Part V: The proofs

This organisation is not a theory. It runs on real ventures with real claims and real accountability. Here are the two current proofs.

### CebimifAi: the regenerative built environment company

CebimifAi advises the Dutch built environment sector on energy transition and regenerative development. It is Michael's first client and first proof venture: the place where the agentic organisation has real stakes, real clients, real invoices, and real consequences if the work is wrong.

In the past two weeks, the organisation has done something unusual: it has audited CebimifAi's own public claims. Not because anything is wrong, but because the agentic organisation's provenance standard demands it. Every major claim must be traceable to a source, and the source must be real.

Thirty-one claims from CebimifAi's intended website were reviewed, labelled, and documented in a public claim ledger. Ten are publishable now, without conditions. Twelve carry caveats (accurate claims that need context or source improvement). Nine are pre-publication gated, including the most critical: the technical proposition depends on an API integration (EDSN-ODA) that is not yet confirmed. That fact is now visible in the organisational record, not buried in a slide deck.

The provenance pattern has been applied to one specific claim, the economic sustainability promise, tracing it from the original assertion through the evidence chain to the decision options. This is what the organisation means by grounding. Not checking whether claims sound good. Checking whether they are true.

### The Agent-Era Readiness Assessment

The second proof is a venture born from Michael's own diagnostic lineage: the Human Potential Assessment, the Exponential Leadership Assessment, now reborn as the Agent-Era Readiness Assessment.

The question this venture answers is the same question that opened this document: what does it actually mean for a person or organisation to use AI well? But it answers it by showing people where they are, not just explaining where they could be.

The instrument works as a funnel. First, a shareable multi-choice poll, the kind you can do on your phone in two minutes, that tells you how you compare to what the world is actually doing with AI (every benchmark figure cited: HBR 2026, Stanford AI Index 2026, Anthropic Economic Index). Then a free conversational assessment, a dialogue rather than a form, because the depth of understanding you get from a real conversation cannot be replicated by clicking boxes. Then an email-gated personal report and a live debrief. And behind it, for those who want to go further: Know/Energize/Realize coaching at €555 a month, or the €2,555 Foundation Sprint.

The ladder at the heart of the assessment describes five rungs of AI readiness, from the person who talks to chatbots, through the maker who builds tools, to the system builder who runs a live agentic infrastructure. Each rung has observable markers: what you actually do, what workflows you have, what kind of memory architecture you run. Each rung has a distinct pain and a distinct gain. The ladder is not judgemental. It meets people where they are.

The assessment runs under one hard constraint: it ships no report that has not been judged. No respondent will receive an evaluation that the eval factory has not cleared. The eval gate exists for the same reason courts have evidence standards: because the stakes are real.

---

## Part VI: The path

The organisation is moving through a series of gates.

**G0** (passed 10-06-2026): the spine ratified. The blueprint and moonshot exist, are committed to, and are public within the organisation. The brain lives in git with a private remote. The autonomy ladder is explicit. The first build loops fired.

**G1** (target: 17-06-2026): the organisation is legible. Every register is live. Every major public claim is source-grounded. A real follow-up to a real person is staged and ready. The first benchmark run has run. The outcome loop is wired. This is where we are now.

**G2** (target: 15-07-2026): the organisation is instrumented. Three workflows have run enough cycles to accumulate measurable evidence. Edit burden is falling. Routing decisions are made by benchmark, not by intuition.

**G3 / G4** (target: ~01-09-2026): the organisation runs with minimal daily intervention from Michael. The metabolism monitor is live. Three or more workflows carry earned L4 autonomy (the first level where agents act without per-action human approval). CebimifAi outcomes are logged with real evidence. The Assessment funnel is converting paying clients.

**G5 and beyond** (2027 to 2031): other organisations adopt this OS. The design is productised. The first non-Michael human governs through it. Then two. Then ventures that are not Michael's. Then the federated mesh. The details of this are directional, re-planned at each gate review with evidence. The direction is clear: multiply sovereignty, not centralise it.

The 2031 moonshot states it precisely:

> By 2031, a federated mesh of agentic-first organisations runs on a sovereign, self-learning, harmonic operating system born here. Each organisation has its own shared digital brain, its own agent workforce operating at earned autonomy, and its own humans at the meta-level setting intent, values, identity, and direction. The organisations learn only from measured reality, conserve their identity while everything inside them changes, collaborate across boundaries without surrendering sovereignty, and exist to increase the flourishing of humans, communities, and the living world.

---

## Part VII: What makes this different

There are dozens of AI automation platforms, agent frameworks, and organisational AI tools. This is none of them.

The difference is sovereignty. Most AI tools are designed to make you dependent on their infrastructure, their data handling, their model choices, their pricing. This design is the opposite: every piece of evidence, every decision, every relationship, every metric lives in a git repository you own, on hardware you own, with models you can swap without losing your organisational memory.

The difference is governance. Most AI deployments have no governance layer. An agent either has access or it does not. There is no concept of earned autonomy, no concept of a workflow having a promotion record, no concept of a judge that reads the diffs. The result is that either the agents do nothing useful (because they have no authority) or they do things that nobody meant (because nobody was watching).

The difference is the human at the centre. This design does not try to replace human judgment. It tries to clear away everything that does not require human judgment, so the human can actually exercise the judgment that matters. Michael's daily interface with this organisation is a 30-minute reading ritual. Not a command line. Not a dashboard. A carefully prepared reading packet, with every decision in plain language, that lets him act from understanding rather than from confusion.

The difference is honesty about what is not done. The claim ledger, the eval factory, the false-green checklist, the FAIL verdicts, these are all mechanisms for the organisation to know the difference between work that looks done and work that is done. Most organisations manage the appearance of progress. This one is trying to measure actual reality.

---

## Epilogue: The invitation

The venture born from this design, the Agent-Era Readiness Assessment, is the first time this work reaches people outside the organisation.

The offer: a free mirror. A two-minute scan. A twenty-minute conversational assessment. A personal report. A live debrief. These things together tell you where you are on the readiness ladder, in plain language, with real benchmark comparisons, grounded in evidence. No slop. No generic output. A reflection of your actual situation.

Behind the free assessment, for those who want to go further: the Know/Energize/Realize coaching path (€555 a month, for the person who wants to be guided as they build their own OS), and the Foundation Sprint (€2,555, for the person who wants it built with them in an intensive). And in development: an online workshop where a small group of conscious entrepreneurs builds their first personal AI operating system together in a guided day or week.

The hook in one question: **Are you ready for the AI agent era?**

Not as a provocation. As a genuine diagnostic. Because the honest answer, for almost everyone, is: *more than you think, and less than you will need to be.*

The point of the assessment is not to make anyone feel behind. The point is to make the path legible. Once you can see where you are on the ladder, you know what the next rung is. The rung you stand on already has value. The rung above it is reachable. The organisation's job is to help you get there, on your terms, without losing your voice, your data, or yourself.

That is the purpose of everything described in this document.

*Humans hold meaning. Agents run the machinery. Memory stays home. Autonomy is earned. Reality is the judge. Life flourishes.*

---

## Staging note

**This document is staged as A-024 for Michael's review and ratification (T-047). Version v0.2: reworked 14-06-2026 per STEER feedback from the 13-06-2026 consent round.**

### Changes made in v0.2

1. All em dashes removed: replaced with commas, colons, or full stops
2. "organism" (used to name the entity) replaced with "organisation" throughout; UK English spelling used
3. Michael bio added at end of Part II: physiotherapy background, nature-as-inspiration, framework clarification
4. Architecture section expanded with four new subsections: the vault (second brain), memory and lessons (IRM), proof-of-done, provenance
5. G3/G4 description rewritten: "organism operates itself" is now "organisation runs with minimal daily intervention from Michael"
6. Voice: shorter sentences, no em dashes, direct register throughout
7. Voice-and-tone guide created at `docs/voice-and-tone.md` (standing reference for all future sessions)

### About the two books

Building the OS Book documents the design of the agentic OS: its principles, proofs, governance, and evidence. This master narrative is source material for it. It is distinct from any personal memoir or account of Michael's own journey. Those are separate projects with their own timelines and audiences.

### Questions for Michael on v0.2

1. **Voice**: does v0.2 read more like you? What still feels off in register or rhythm?
2. **Michael bio**: does the physiotherapy and nature framing feel accurate? Anything to correct, add, or remove?
3. **Architecture additions**: vault, IRM, proof-of-done, provenance sections: do they add clarity or create too much complexity for this level of document?
4. **Part VI path**: does "minimal daily intervention" land better for G3/G4 than "operates itself"?
5. **OS Book note**: does the distinction from the personal book feel right as stated?

Once ratified, this becomes the canonical plain-language account of the organisation, updated at each gate review, mirrored to Obsidian on every revision, fed into the Building the OS Book pipeline.

---

*Written by the nightly build session, 13-06-2026 08:42 CEST. Reworked 14-06-2026 00:31 CEST per STEER feedback (A-024). Draft, not a final account.*
