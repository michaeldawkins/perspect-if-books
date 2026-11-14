# Working in perspect-if-books

This repo holds Michael's books. Read `README.md` first, then the interview log of the book you are working on.

## Voice and output
- Michael's voice: warm, heartfelt, fellow traveller, humour underneath. Never guru, never corporate, no AI-speak, no listicles, no claims of absolute truth.
- No em dashes in anything new. Scan and strip before saving.
- Dates DD-MM-YYYY. Sentence-case headers. Lowercase-hyphen filenames.
- Outward-facing text speaks of an organisation, not an organism.
- Never "I'm Michael", always "My name is Michael".

## How we write
- **Interview first.** Michael thinks out loud; Claude catches and structures. One question at a time, Claude's recommendation first, then Michael decides.
- **Push back.** Treat Michael's convictions as strong starting points, not facts. Name where the drafts or the evidence point elsewhere.
- **Maturity on every claim:** draft (Claude or old source), confirmed (Michael said it), settled (Michael locked it). Log every change in the book's `thesis-interview-log.md` or equivalent, with the date.
- **Provenance.** No claim about the world goes into a manuscript without a source. Prefer strong ground (McGilchrist, Kastrup, Maté, Vervaeke) over contested ground (psi, morphic fields) for anything load-bearing.
- **Privacy.** `backstory-brief.md` holds personal history. Nothing from it goes into a manuscript without Michael's explicit yes, chapter by chapter.

## Sources are frozen
Files under any `sources/` folder are snapshots, kept exactly as found. Never edit them. New writing goes in new files. `SOURCES.md` says where each came from and which copy is the live one.

## The rest of the system
- **perspect-if** (GitHub): the hub and vision. The books express Perspect-IF; each book states which version of the Perspect-IF vision it reflects.
- **agentic-os** (GitHub): the operating system and the master narrative. Its nightly build owns `docs/master-narrative-v0.1.md`; the copy here is a snapshot.
- **Claude Vault** (Obsidian, Michael's laptop): the original book folders and his life context (`memory/context/`: age-anchored timeline, seven lives, Interview A, voice profile).
- **Google Drive / Dropbox:** older drafts. Snapshots are in `sources/`.
- **The Field** (NotebookLM) and the **Source Library**: research wells for citations.
