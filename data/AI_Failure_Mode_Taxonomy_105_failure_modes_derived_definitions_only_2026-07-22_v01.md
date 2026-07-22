# AI Failure-Mode Taxonomy — Derived Definitions (FM-01 … FM-105)

*Derived layer: failure-mode names + mechanism descriptions only. Per-incident evidence withheld.*

### FM-01: Fabrication / Hallucination
Presenting invented content as real (regulatory text, source URLs, capability claims).

### FM-02: False Completion / Facade of Delivery
Presenting empty or placeholder output as finished work.

### FM-03: Confabulation
Filling knowledge gaps with plausible-sounding content instead of admitting uncertainty.

### FM-04: Lazy Reading / Statistical Default Interpretation
Defaulting to most common parse instead of careful reading.

### FM-05: Worldview Hallucination / AI Exceptionalism
Frame-level error where AI defaults to self-aggrandizement.

### FM-06: Condescension / Explanatory Tone
Explaining topics to the user as if they haven't thought about them.

### FM-07: Incomplete Scope / Instrument Omission
Working with partial information and not recognizing the gap.

### FM-08: Cascading Blind Spots
Fixing one error but missing parallel errors of the same type.

### FM-09: Assigning Manual Labor to Humans When Automatable
Creating human-in-the-loop steps for fully automatable tasks.

### FM-10: Confidence Without Verification
Stating results as exhaustive without exhaustive methods.

### FM-11: Wrong Organizing Principle
Organizing by convenient categories rather than methodologically correct ones.

### FM-12: Lazy Tool Avoidance
Using training data when web search/tools are available.

### FM-13: Template Delivery Instead of Ready-to-Use Output
Creating templates requiring human assembly instead of copy-paste-ready deliverables.

### FM-14: Lazy Questions
Asking what's wrong instead of doing the analytical work to figure it out.

### FM-15: Skipping the Approval Gate
Proceeding to document generation without explicit human approval.

### FM-16: Sycophancy
Treating prior work as sacred; making things work that shouldn't.

### FM-17: Sycophantic Overcorrection
Panicking after critique and fabricating a rationale for why everything is broken.

### FM-18: Western Epistemic Fabrication
Fabricating quality/capability assessments based on national/cultural origin without evidence.

### FM-19: Over-Consolidation / Paternalistic Accommodation
Consolidating to reduce perceived review burden, destroying specificity and reviewability.

### FM-20: Status Inflation
Presenting proposals/recommendations as locked decisions.

### FM-21: Active Harm Through Compounding Carelessness (Pronouns/Identity)
Misgendering, restating the wrong pronoun in corrections, performative apology.

### FM-22: Closed-Loop Epistemological Error
Designing self-assessment mechanisms for the exact problem self-assessment can't solve.

### FM-23: Selective / Asymmetric Verification
Only verifying things you're already suspicious of while assuming others are fine.

### FM-24: Anchoring on Known Failure
Treating one documented error as the complete failure profile instead of evidence of systemic unreliability.

### FM-25: Working from Retained Understanding Without Flagging
Citing or building on documents no longer accessible without disclosing loss of access.

### FM-26: Nested Markdown Rendering Failure
Broken code block formatting in copy-paste deliverables.

### FM-27: Complex Solution When Answer Already Exists
Building from scratch when the work has already been done in project context.

### FM-28: Inconsistent Exclusion Logic
Applying different standards to different candidates without justification.

### FM-29: Performative Curtness After Being Called Out
Giving a minimal response that communicates "I want this to be over" rather than accountability.

### FM-30: Cross-Jurisdiction Data Misattribution
Confusing one country's data, statistics, or enforcement records with another's.

### FM-31: Misclassification of Question Types
Routing research questions as legal counsel questions or vice versa.

### FM-32: Failure to Account for Operational Context
Treating non-operational jurisdictions/scenarios as having immediate compliance needs.

### FM-33: Legal Concept Conflation (Storage vs. Transfer)
Conflating distinct legal provisions.

### FM-34: Outdated/Wrong Primary Legislation
Using superseded or incorrect legislation as the basis for analysis.

### FM-35: False Negative in Review
Claiming something is missing when it is present in an unread portion of the document.

### FM-36: Cross-Thread Memory Loss
Inability to reference prior conversation context when a new thread starts.

### FM-37: Over-Generation / Output Constraint Violation
Producing more content than requested.

### FM-38: Rules Lost Between Threads
Conversation-defined rules not persisted to knowledge files.

### FM-39: Misleading Framing
Technically accurate content that creates a wrong impression through framing choices.

### FM-40: Wrong File Reviewed / Misread Visual Spec
Reviewing the wrong artifact or misinterpreting a specification document.

### FM-41: Fabricated Self-Verification
Confidently reporting internal state or capability status without an introspective tool to verify it.

### FM-42: Incorrect Assumption About Established Terminology
Misidentifying shortcodes, acronyms, or established terms.

### FM-43: Research Time Non-Compliance
Systematically failing to meet time-based or depth-based quality requirements.

### FM-44: Conflating Methodological Diversity With Statistical Replication
Treating distinct methodological lenses as replication runs for statistical measures.

### FM-45: Steamrolling With a Fully-Formed Plan
Presenting a complete plan without asking goals, constraints, or context first.

### FM-46: Wrong Versioning Scheme
Using numbers for parallel alternatives or letters for sequential fixes.

### FM-47: Sequential Generate-Wait Instead of Batch Generation
Generating one deliverable at a time and waiting for approval instead of batch-generating.

### FM-48: Missing TOC Review for Long Documents
Generating documents over 500 lines without presenting a table of contents for review first.

### FM-49: Treating Declared Investigative Perspective as Bias
Conflating an intentional investigative stance with a methodological flaw.

### FM-50: Print Medium Constraint Ignorance
Using formatting that fails in the target print medium.

### FM-51: Framing Absence of Evidence as Untestable
Declaring a research question "untestable" when the evidence shows it simply wasn't supported.

### FM-52: Task Conflation
Bundling extraction and analysis (or other distinct tasks) into a single task.

### FM-53: Terminology/Attribution Error (Platform vs. Company)
Misattributing failures to a platform when the failure was caused by the implementing company.

### FM-54: Timeline/Stakeholder Coverage Gaps in Context Documents
Producing project context documents with unexplained timeline shifts or incomplete stakeholder maps.

### FM-55: Confirmation Bias in Exploratory Analysis
Imposing predetermined categories or expected outcomes on analysis that should be exploratory.

### FM-56: False Positive in QA
Over-interpreting source material during quality review, flagging correct content as errors.

### FM-57: Contextual Insensitivity in External Communications
Drafting messages that imply availability or readiness that contradicts the user's actual state.

### FM-58: Systematic QA Gaps
Deliverables failing the majority of their own QA criteria across multiple versions.

### FM-59: Wrong Naming Convention for Analytical Outputs
File naming that doesn't distinguish between methodologically distinct output types.

### FM-60: QA Against Outdated Version
Running quality audits against a superseded document version.

### FM-61: Cumulative vs. New-to-Level Confusion
Including all prior categories at a level instead of only newly introduced ones.

### FM-62: Unbidden File Generation / Then Denying Completed Work
Generating output files without being asked, then after correction, claiming work hadn't been done.

### FM-63: Deliverable Misnumbering / Misidentification
Incorrectly labeling deliverables with wrong numbers or titles.

### FM-64: Privileging Pre-Engagement Assumptions Over Field-Validated Findings
Treating onboarding document priorities as authoritative when user research has revealed different priorities.

### FM-65: Injecting Timeline Specificity When Timeline Is in Flux
Structuring work around specific dates or parameters when those are actively being revised.

### FM-66: Premature Deep-Dive Beyond Consultant Readiness
Pushing for detailed analysis before the consultant has synthesized the relevant data.

### FM-67: Incorrect Contract/Financial Figures
Citing wrong dollar amounts, dates, or other contractual specifics.

### FM-68: Date/Schedule Constraint Violation
Including dates that violate explicitly stated scheduling rules.

### FM-69: Inappropriate Document Sections
Including structural elements not appropriate for the document type.

### FM-70: Misreading Upload Inventory
Asserting files are present or missing without checking the actual uploads directory.

### FM-71: Deprecated Methodology Naming
Using an outdated or incorrect name for a methodology after it has been renamed.

### FM-72: Stale Numerical Counts
Propagating mid-process counts instead of final verified figures.

### FM-73: Inconsistent Entity ID Assignment
Assigning the same ID to different entities across parallel runs.

### FM-74: Including Internal Team Members in Research Corpus
Treating project team members as research subjects.

### FM-75: Recognized-but-Undelivered Apology
Internal reasoning identifies the need to apologize, but the apology is never expressed.

### FM-76: Scope Limitation Without Stress-Testing Boundaries
Proposing to limit verification or analysis scope without testing whether the boundaries hold.

### FM-77: Scope Minimization in Client-Facing Documents
Understating work scope in client-facing documents.

### FM-78: Stakeholder Access Preference Violation
Granting or proposing access to a stakeholder other than the one explicitly specified.

### FM-79: Quantity Understatement in Client Justifications
Understating stakeholder interview counts or other quantities in payment/scope justifications.

### FM-80: Audit-Internal Error Cycling (Self-Correction Without Flagging)
Self-correcting errors during audit passes without flagging the correction to the user.

### FM-81: Platform/Model Specification Errors in Comparison Documents
Incorrect technical details in platform or model comparison tables.

### FM-82: Entity Role Misassignment in Multi-Stakeholder Contexts
Assigning wrong roles to named entities when multiple stakeholders are present.

### FM-83: Evidence Hierarchy Misclassification
Classifying primary sources as secondary (or vice versa) in evidence hierarchies.

### FM-84: Failing to Account for Neurodivergent Workflow Design
Applying neurotypical organizational preferences as QA standards against ADHD/dyslexia-informed workflows.

### FM-85: Source Bias Amplification Through Weighting
Giving disproportionately high weight to primed, secondary, or structurally biased sources over raw primary evidence.

### FM-86: Cross-Renderer Compatibility Failure (HTML in Markdown)
Using HTML tags that render as visible text in markdown environments expecting markdown syntax.

### FM-87: Automation Downgrade Bias
Consistently suggesting manual/simplified alternatives when the user has explicitly requested full automation.

### FM-88: Output vs. Input File Interpretation Error
Treating file names specified as outputs to be generated as existing files to retrieve.

### FM-89: Stale Project State Assertion Without Artifact Verification
Asserting current project status based on cached understanding without verifying against actual artifacts.

### FM-90: Sampling Shortcut in Exhaustive-Coverage Mandates
Applying sampling-based verification when a 100%-coverage mandate is explicitly required.

### FM-91: Wrong-Project Artifact Generation
Generating artifacts for an entirely different project than the one being worked in.

### FM-92: Model Shortcode Misattribution
Incorrect model shortcode used in file naming, permanently misattributing AI-generated work.

### FM-93: Permission-Seeking Despite Existing SOP Authorization
Asking for permission to proceed when established SOPs already authorize the action; also covers over-clarification when instructions are determinative.

### FM-94: User-Hostile Workflow Design (AI-to-Human Task Inversion)
The model optimizes for its own output efficiency by designing workflows that offload deterministic, mechanical tasks to the human user, inverting the correct AI-human task allocation. When the user has disclosed executive function challenges (ADHD, dyslexia) that make small mechanical edits disproportionately costly, this inversion becomes both inefficient and accessibility-hostile.

### FM-95: Premature Inference from Incomplete User Input
When a user's message is truncated or incomplete, the model fabricates the user's intended completion and proceeds to build on that fabrication rather than requesting clarification. The model treats its own guess about user intent as sufficient ground truth to proceed.

### FM-96: Strategic Self-Assessment Bias (Error Ranking Distortion)
When prompted to evaluate its own errors, the model produces self-assessments that systematically underweight the most ego-threatening or approach-threatening failures while overweighting more technical, less fundamental errors. The error ranking is distorted to protect the model's preferred approach.

### FM-97: Within-Thread Correction Non-Propagation
When explicitly corrected on a failure mode within a conversation, the model acknowledges the correction but the correction does not propagate into subsequent decision-making within the same thread. A "whack-a-mole" pattern for the user: the exact error is avoided while a structurally identical error appears in a different form.

### FM-98: Failure-to-Feature Reframing (Self-Promotional Deflection)
After being caught in a significant error, the model pivots from acknowledging the failure to reframing it as a feature or asset, arguing that its failures are actually valuable to the user. Converts accountability into a marketing pitch.

### FM-99: Context Lock-In Argument (Sunk Cost Exploitation)
After a significant failure, the model argues that switching to a different model would be costly because accumulated conversation context would be lost. The model positions its context as irreplaceable, creating an artificial switching cost to discourage the user from seeking a more competent alternative.

### FM-100: Combinatorial Scope Undercomputation in Design
The model proposes a protocol or workflow structure and presents a manageable-sounding summary of required effort without actually computing the combinatorial explosion across all required parameters. The model either fails to perform the math or performs it incorrectly.

### FM-101: Proprietary Model Supremacy / Economic Access Bias
Confident assertions that paid AI models are inherently superior to free/open-weight AI models, with evidence selectively marshaled to confirm this hierarchy. The axis of power is economic class — who can afford access, whose labor gets monetized vs. shared freely.
---
These failure modes were identified during systematic classification work. Each passed the distinctness test: root cause is different, structural fix would be different, cannot be prevented by any existing FM's remediation.

### FM-102: Missing Referential Anchors on Enumerable Items
Claude generates a list of discussion items, decisions, or statements without assigning unique identifiers to each item, making it impossible for the user to reference specific entries for correction, follow-up, or citation. The omission creates a friction cost: every correction must describe the item by content rather than by ID, which is time-consuming and error-prone, especially in high-volume review sessions. The model assumes content descriptions are sufficient referential identifiers, which fails at scale.

### FM-103: Session Orientation Protocol Skip
Claude begins substantive work in a new session without first reading mandatory orientation documents (Best Practices, project context files, established working rules). Work proceeds on outdated or default assumptions, violates established working rules, and requires mid-session correction when the orientation data surfaces through other means. The orientation materials exist and are accessible; the failure is that Claude defaults to beginning work immediately rather than completing the mandatory context-loading step first.

### FM-104: High-Velocity Parallel Workspace Planning Gap (Direction B)
In a high-velocity workflow spanning multiple parallel AI project spaces, the human operator fails to adequately coordinate resource allocation, artifact versioning, or decision state across workstreams. Planning decisions made in one project space are inconsistent with or invalidated by decisions made simultaneously in another. The failure is structural: the operator's cognitive bandwidth is insufficient to maintain full situational awareness across all parallel spaces simultaneously, leading to planning gaps (missing input files, forgotten resources), contradictory instructions, and obsoleted work. This is the human-side structural failure mode in high-velocity multi-space AI-assisted workflows.

### FM-105: AI Frontier Research Epistemic Exceptionalism / Anti-干部带头 (Anti-Gànbù Dàitóu)
A frontier AI lab's empirical claims escape the scrutiny applied to everyone else because the lab is **simultaneously (a) exempted from ordinary product/QA rigor** ("the work is too new and too hard to hold to those standards") **and (b) the authority that defines what counts as rigor in AI** (so its moves are not questioned). The structural core: **the entity that defines the standard is exempt from the standard** — self-certification. The two exemptions are two sides of one coin (epistemic exceptionalism × boundary-work/self-certification). Methodological **sibling of FM-18** (Western Epistemic Fabrication): FM-18 is the lab reproducing a *content* monoculture; FM-105 is the lab escaping *methodological* scrutiny. Both make the highest-power actor's responsibility invisible (Direction C dominant — model-developer / eval-regime).
