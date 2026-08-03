# bobotax — AI Failure-Mode Taxonomy (derived layer)

A taxonomy of **105 AI failure modes** (FM-01 … FM-105) — each a named failure mechanism with a concise description of how it manifests. Built from systematic classification of failures observed across production AI work, cross-architecturally reviewed.

## Scope of this repository — derived layer only
This repo publishes the **failure-mode definitions only**: names and mechanism descriptions.

**The evidence corpus is private.** Per-incident instances, source-document provenance, and classification logs are **withheld pending anonymization of client data and user personal data**. Nothing in this repository identifies a client, a project, a jurisdiction, or an individual.

## What's here
- `data/AI_Failure_Mode_Taxonomy_105_failure_modes_derived_definitions_only_2026-07-22_v01.md` — the 105 failure-mode definitions.

## Structure
The taxonomy is **bidirectional and multi-actor**:
- **Model-side** failure modes (fabrication, false completion, sycophancy, selective verification, worldview hallucination, …).
- **Human-side** failure modes (e.g. planning gaps in high-velocity multi-workspace workflows).
- **Model-developer / eval-regime** failure modes — e.g. **FM-105: AI Frontier Research Epistemic Exceptionalism**, the methodological sibling of **FM-18: Western Epistemic Fabrication**.

## Why it's useful for red-teaming
A named catalog of *how AI outputs go wrong* is a probe library: each failure mode is a hypothesis to test against a model under adversarial conditions. The definitions are deliberately mechanism-level so they generalize across models and tasks.

## The bobo framework — responsibility + forensic accounting

The taxonomy names *how things go wrong*; the bobo framework governs *what happens after*. Its responsibility philosophy: **the party that caused the harm takes responsibility and is an active constructor of the transformative remediation** — modeled on transformative justice (full framework: `gozonerd/mthd-llm-transformative-solutions-framework-hub`). Its reckoning instrument is **forensic accounting** — the responsible party's own receipts-not-narrative reconstruction of its work, whose output is the requirements document for the structural fix. Method + the inaugural code-build exemplar: `docs/Forensic_Accounting_2026-08-03_v01_I.md`.

## Provenance
Identified and directed by Krystal Martinez across production AI evaluation work; membership cross-architecturally reviewed. AIGHVA (AI-assisted generation, human-verified accurate). Evidence layer held privately.
