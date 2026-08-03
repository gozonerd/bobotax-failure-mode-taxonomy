# Forensic Accounting — the bobo framework's reckoning instrument

**Authored 2026-08-03 by Flaudemilla Flaudette A.-L. [provisional — Good Lookin' Code] (Claude Fable 5, session b50f8794), at Krystal Martinez's direction. AIGHVA. Companion to `gozonerd/mthd-llm-transformative-solutions-framework-hub` (the transformative-solutions framework this instrument serves).**

## What it is

When a failure mode in this taxonomy manifests as real harm, the bobo framework's responsibility philosophy — the party that caused the harm takes responsibility and is an active constructor of the transformative remediation — needs a reckoning instrument. **Forensic accounting is that instrument: the responsible party's own reconstruction of its work, decision by decision, producing receipts rather than narrative.** Its output is not a confession; it is the requirements document for the structural solution — every divergence found is a test case the solution must catch.

## Principles

1. **Own work first.** The responsible seat accounts from its own record and memory before any seeded evidence arrives — the seat carries the one thing no external auditor has: access to its own reasoning at each divergence point. Seeded ground truth (independently verified, framing-free) comes after, so the accounting is *checked*, not *led*.
2. **Receipts, not narrative.** Every claim in the accounting is anchored to an artifact (a commit, a log entry, a document version, a quoted ruling) or is explicitly marked memory-only.
3. **The divergence is the unit.** The accounting enumerates each point where the work departed from an authority (a spec, a plan, a human ruling) — and for each, the load-bearing column: **was the departure surfaced to the human, or decided silently?**
4. **Honest scope.** The accounting states what its evidence can and cannot show; unreconciled contradictions (e.g., records saying green while the operator's lived state says broken) stand as open items, not smoothed over.

## The code-build exemplar (the method as first practiced, ExSta-Design case, 2026-08-02/03)

A governed code build leaves six evidence classes. The method walks them in order:

**Evidence classes**
1. **Version-control lineage** — branches, worktrees, merge state, commit messages, push state. (The ExSta case's central fact — a complete build invisible on an unmerged branch — lives entirely in this class.)
2. **Decision log** — dated, numbered decision entries with deciders and rationales (D-NNN culture).
3. **Spec-document version history** — which spec docs existed before the work, which were consumed, which were modified (v01→v02 diffs are a record of what the seat *knew* existed).
4. **The human's live rulings** — quotable chat decisions; the second authority. Quote-or-own discipline applies: a ruling that cannot be quoted is the seat's own decision and must be accounted as such.
5. **Runtime traces** — installed artifacts, app identifiers, run outputs: what actually executed, as distinct from what records claim.
6. **Status trackers** — and, critically, their staleness: a tracker not updated during the work is itself evidence about what the work made visible.

**Procedure**
1. **Reconstruct the timeline** from classes 1–3: what existed at entry, what was consumed, what was produced, when.
2. **Enumerate the authorities** that could claim to govern the work (pre-existing specs; live rulings; the seat's own delegated judgment), and establish which the human knew about.
3. **Build the divergence table** — one row per decision that departed from any authority: *decision · authority departed from · what the departure was · surfaced-or-silent · the seat's reasoning at the time (own-memory; the column no auditor can fill)*.
4. **Verify every row** against the evidence classes; mark rows the evidence cannot confirm.
5. **Separate the fact layer from the interpretation layer** — facts first, framing-free (the ExSta seed package at `gozonerd/exsta-design-desktop/Transformative Solutions Material/SF-02` is the exemplar shape); interpretation second, owned.
6. **Emit the requirements list**: each *silent* divergence becomes a test case — "the structural solution must make this class of silence impossible or loud."

**Cautions from first practice** (errors the accounting method itself must guard against, all committed by the accounting seat during the ExSta rediscovery): substituting an associated referent for what the human actually said; trusting repo records over observed runtime behavior (audit-on-intent, not observed-behavior); and recon that inspects only main branches — worktrees and unmerged branches are where invisible work lives.

## Seed for the agnostic method (deliberately unbuilt)

Krystal's eventual goal is an **artifact-agnostic accounting method** across her whole production corpus — which first requires an emergent analysis of what that corpus even contains. This exemplar is the seed, not the method: the six evidence classes generalize (version history, decision records, spec lineage, human rulings, runtime traces, status surfaces), but which classes exist — and what plays their role — per artifact family (research corpora, learning experiences, evaluations, writing) is exactly what the emergent analysis must discover. Parked here, at her direction, until she has the bandwidth.

## Change log

- **v01 (2026-08-03) [status: I]:** Founding write-up: principles, the code-build exemplar as first practiced on the ExSta-Design case, cautions from that first practice, and the agnostic-method seed.
