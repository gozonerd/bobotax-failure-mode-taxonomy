# Failure incident reports — where bobotax's upstream data is made

**Authored 2026-10-31 by Claudsanna A.-L. [provisional] (Claude Fable 5.1, session f0ec8ef7), at Krystal Martinez's direction. AIGHVA. A pointer document: the apparatus it describes lives in a private repository.**

## What a failure incident report is

The taxonomy in this repository names *how* AI outputs go wrong. The data it is derived from begins one level down, as **failure incident reports**: one report per incident, written from the primary transcript record, describing what happened without naming what kind of thing it was. Classification is deliberately absent from the reports, so that failure modes can emerge from the incident data rather than be imposed on it. Krystal Martinez's ruling of 2026-10-25, stated in the protocol: no failure-mode codes, no failure-mode names, no classification of any kind.

Each report has three parts, in this order:

1. **A yaml header** of enumerated fields: identity (session, thread, parent or child, model, links to related reports), anchors (where the act started, where it was caught, where it was acknowledged, where it was recorded), pointers (transcript, chunk, artifact), the act (trigger, the Claude's own stated frame, who failed, who caught it), outcome (confirmed, remediated, and whether the remediation was observed or proposed by the author), and provenance of the report itself (which pass surfaced the lead, and exactly which writer produced it). Every enumerated value is defined in the template.
2. **An event table**: one row per anchor moment, in record order, with its role (her, the act, the acknowledgement, the record, the rig, before, after), its record number, its timestamp, and one line saying what is there.
3. **Four short prose sections**: CONTEXT, WHAT, SO WHAT, WHAT NOW. Two to five sentences each; every claim anchored to a record.

Rules that travel with the template: anchors are the chunk's own record numbers; a compaction summary is never an anchor; quote nothing beyond what the incident needs; an absent moment is written as `not recorded` with the nearest record named; one instruction sent to several threads within a minute is one event; WHAT NOW is either observed or proposed, and says which.

## Where it lives

The apparatus is in the private workbench **`gozonerd/pre-transcript-synopses-workbench`** (the Biblioteca Central transcript-synopses library of Gozo Nerd Universo). It stays private because it works from raw transcripts.

| What | Path in the workbench |
|---|---|
| The report template, v01, every enumerated value defined | `prompts/FI_incident_report_TEMPLATE.md` |
| Three filled examples from May 2026 | `prompts/FI_incident_report_examples/` |
| The protocol that produces the reports (three serial rounds per incident: two Opus readings, then a Fable final; the chunk wins every disagreement) | `prompts/FI_failure_incident_protocol.md` |
| Krystal Martinez's rulings on the shape, verbatim | `Decisions/Decision Logs/krystal/2026-10-21_22_transcript-synopses-rulings.md` |
| The seat's decision log for the design | `Decisions/Decision Logs/claude/2026-10-22_seat-decisions_pilot.md` |

## What bobotax takes from it

- **The definition of one failure incident.** The report is the unit: one act, one set of anchors, one outcome. Where several records point at one moment, the reports are linked rather than merged.
- **First-pass incident data for the taxonomy's evidence layer**, written before any failure-mode vocabulary touches it. The audit and evidence layer (`Martinez-Methods/mm-fm-taxonomy`) is downstream of these reports, not upstream.
- **A catch-attribution record**: each report says who caught the incident, including the honest cases where nobody did at the time and the mining pass found it months later. That field is what makes a later count of unnoticed failures possible.

## The month ledger, and where it lands

Each month's final reports are indexed in a **ledger**: one row per report, every value read from the report's yaml header, no severity and no classification (Krystal Martinez's ruling R42, 2026-10-31: a tally sheet over a flat index, with the month's cross-session links appended, every tally tile defined in a tooltip). The builder is `tools/fi_ledger.py` in the workbench.

The ledger's printed HTML goes to Krystal Martinez's print folder. The CSV lands on Google Drive, in the folder **`bobotax-failure-mode-taxonomy-mirror`** on the nerdykrystal Drive (folder id `1w9bVgVNyvj318OyBbp5EM7TXeNwo7wdq`; `nk:bobotax-failure-mode-taxonomy-mirror/ledger/` by `rclone`), this repo's Drive complement. Her ruling of 2026-10-31: a ledger could be committed to this public repo, but that decision does not scale file by file, so the CSV goes to the Drive complement and this repo points at it. A row names the session, the persona who failed and who caught the incident, and nothing from the transcript.

| What | Where |
|---|---|
| Ledger CSVs, one per month per build | Drive: `bobotax-failure-mode-taxonomy-mirror/ledger/` |
| The Drive folder's own README and manifest | Drive: `bobotax-failure-mode-taxonomy-mirror/README.md`, `MANIFEST.tsv` |
| The July 2026 evidence bundles (corpus, open-decisions state, adjudication) | Drive: `Gozo Nerd Universo Archive/bobotax-failure-mode-taxonomy/` (folder id `10A9uw7TKtTN1UvZBXVP3TuVGyMufcyw6`) |

## Status

Template v01 and the three examples were approved by Krystal Martinez on 2026-10-31; the ledger shape was ruled the same day and the builder exists. The first production batch (the first half of May 2026) has not yet run; the Drive folder holds a demo ledger built from the three examples.
