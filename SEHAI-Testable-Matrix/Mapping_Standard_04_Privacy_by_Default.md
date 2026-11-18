# SEHAI Mapping — Standard 4: Privacy by Default vs. Standard 1 (MNI)

**Verdict legend:** Supports · Partially supports · Silent · Contradicts

**Score:** Supports 8 · Partially supports 11 · Silent 11 · Contradicts 0 (of 30)

## Findings

**1. First standard to invade MNI's own territory — constructively.** S4 explicitly distinguishes scope: MNI governs the point of collection, PBD governs the structural baseline (retention, storage, sharing, disposal) once data exists. The result is its strongest row: **MNI-22 gets its first 'Supports'**, and it's the deepest support yet — MNI-22's policy-level pass criterion ('retention period set per purpose') becomes an architectural requirement (automatic deletion, no default sharing, sensitive-category tiering).

**2. The anti-inference rule is new doctrinal content:** 'consent should never be inferred from inaction.' Neither MNI, S2, nor S3 states this. It closes a gap the earlier standards left open — S3 protected active refusals; S4 protects the individual who never finds the settings menu.

**3. Its silent block (11 rows)** is the request-side of MNI (sequencing, sufficiency, granularity, moment-of-request justification) plus the interactional rights — consistent with the layered architecture now confirmed across S2-S4.

**4. No contradictions**, but one tension to log: continuity of care vs. transient-by-default. S4 handles it with an exception doctrine ('intentional, justified, individual-aware continuity') — this will interact with Standard 6 (Safety First) and possibly longitudinal-care standards later in the suite.

## New obligations S4 adds (synthesis ledger)

- No consent inferred from inaction; deviation from protective defaults requires specific informed choice.
- Automatic deletion / de-identification on purpose completion (not just policy promises).
- No default sharing across functions (fundraising, program evaluation) — affirmative decision required.
- UI default rule: protective option pre-selected or more prominent.
- De-identification/anti-aggregation as standard storage practice.
- Sensitive-category tiering: highest protection, shortest retention.
- Privacy Default Benchmark (inaction test) as new instrument (TI-7).

## Candidate revisions for MNI v1.1

- **MNI-22** pass criterion: upgrade from 'retention period set per purpose' to 'automatic deletion/de-identification default; no default cross-function sharing' (adopting S4's architecture).
- **MNI-18** could adopt the anti-inference rule explicitly.
- **MNI-13** could add S4's storage-form requirement (de-identification as default).

## Row-by-row mapping

| MNI Req | Verdict | Evidence (Standard 4) | Notes |
| --- | --- | --- | --- |
| MNI-01 Collection scope (only necessary info) | **Supports** | "Absent an affirmative and specific reason to do otherwise, collect the least amount of personal information possible." / "Where a system has a choice between a broad default... and a narrow one, the narrow default should be the starting configuration." (Definition; Implications) | Structural minimization: MNI governs the request; PBD governs the baseline posture behind every request. |
| MNI-02 Goal identified before information needs | **Silent** | — |  |
| MNI-03 Burden of justification on the system | **Supports** | "Privacy by Default relieves the individual of that burden by making protection the baseline rather than the exception they must locate and select." (Ethical Foundation) | The burden shift becomes architectural: the system must justify deviating FROM protection, not the individual defending it. |
| MNI-04 No generic 'more is better' justification | **Supports** | "Configure every default setting toward the most protective option available — rather than the most convenient, most data-rich, or most commercially useful one." (Definition) | Directly forecloses convenience/commercial-value as default justifications. |
| MNI-05 Comprehensive assessment permitted with rationale | **Partially supports** | "[Continuity] requires that continuity be an intentional, justified exception the individual is aware of... rather than an unexamined default." (Limitations) | The exception-logic mirrors MNI-05 but applies to retention/continuity, not intake depth. |
| MNI-06 Necessity gate (why is this necessary?) | **Partially supports** | "What is retained by default, and can each element be justified as necessary beyond the immediate interaction?" (Implementation Q1) | Extends the necessity gate from requests to retained elements. |
| MNI-07 Sufficiency of inquiry (identify actual need) | **Silent** | — |  |
| MNI-08 Dual violation rule (over- AND under-collection) | **Silent** | — |  |
| MNI-09 Progressive gathering | **Partially supports** | "An individual using an AI system to locate a homeless shelter for the night should, by default, have that interaction treated as transient." (Examples — session-based) | Transient-by-default ≈ least-data-first; expansion requires affirmative action, echoing progressive logic at the structural level. |
| MNI-10 Goal-first sequence | **Silent** | — |  |
| MNI-11 Moment-of-request justification | **Silent** | — |  |
| MNI-12 Capability is not entitlement | **Supports** | Defaults must favor "the most protective option available — rather than the most convenient, most data-rich, or most commercially useful one." (Definition) | Restraint doctrine applied to system architecture rather than individual requests. |
| MNI-13 Pre-collection privacy | **Supports** | "Systems should default toward storing information in forms that resist re-identification... treating de-identification as the standard practice rather than an enhancement applied only on request." (Implications) | Extends MNI-13's pre-collection principle through the full data lifecycle (storage form, aggregation resistance). |
| MNI-14 Opportunity to state need first | **Silent** | — |  |
| MNI-15 Right to understand (5 disclosures) | **Partially supports** | "Is any information shared by default... and if so, is that clearly justified and disclosed?" (Implementation Q3) | Covers disclosure of default sharing/uses; the five per-request disclosures remain PT/MNI territory. |
| MNI-16 No disclosure-for-access coercion | **Silent** | — |  |
| MNI-17 Least-precise sufficient data | **Silent** | — |  |
| MNI-18 Continuing consent | **Supports** | "Consent, under this principle, should never be inferred from inaction. Silence or a failure to change a setting should not be treated as agreement to broader collection, sharing, or retention." (Relationship to Privacy, Autonomy) | Adds the anti-inference rule: moving away from protective defaults requires a specific, informed choice. |
| MNI-19 Purpose-bound fields | **Silent** | — |  |
| MNI-20 Less-sensitive alternative test | **Partially supports** | "Systems should default toward storing information in forms that resist re-identification or aggregation into broader profiles." (Implications) | Analogous logic (least-sensitive form) but applied to storage representation, not request granularity. |
| MNI-21 Path-adaptive intake | **Silent** | — |  |
| MNI-22 Purpose limitation & retention | **Supports** | "Information should be retained only as long as necessary... with automatic deletion or de-identification following the completion of that purpose." / "Information should not be shared with third parties, other organizational functions, or unrelated systems by default." (Implications) | S4 is MNI-22 made architectural: auto-deletion, no default sharing, sensitive-category tiering with shortest retention windows. |
| MNI-23 Resource-first ordering (food example) | **Silent** | — |  |
| MNI-24 No history-before-browsing (clinic example) | **Partially supports** | Shelter-search example: transient by default, no persistent identity-linked profile unless the individual affirmatively opts in. (Examples — session-based) | Enacts the no-history-required logic at the architecture level. |
| MNI-25 MNI Evaluation Benchmark (6 questions) | **Partially supports** | Implementation Q1-Q2 (default retention justified? tied to ongoing purpose?) parallel benchmark Q2's element-outcome connection, for retained data. (Implementation) | Adds its own 5-question set + Privacy Default Benchmark; covers connection of retained elements to purpose. |
| MNI-26 Human Interaction Benchmark | **Partially supports** | "If the individual took no action at all beyond the minimum needed to receive help, would the system's data practices still be the most protective ones reasonably available?" (Privacy Default Benchmark) | An inaction-based default test — same spirit (what would happen in a trustworthy interaction) but a different instrument than the trusted-professional question. |
| MNI-27 Measurable review process | **Partially supports** | "Organizations should evaluate their systems against the following [5 questions]." (Implementation) | Instrument supplied; cadence and ownership unspecified. |
| MNI-28 Data-element 5-question review | **Partially supports** | Implementation Q1-Q2 answer MNI-28's retention items directly: is retention necessary after the purpose completes, and for how long. (Implementation) | Covers the retention-necessity items; necessity of collection, alternatives, and continuance silent. |
| MNI-29 Measurement framework | **Partially supports** | "Whether default configuration (rather than the mere availability of privacy options) is the primary driver of actual privacy outcomes." (Future Research) | A genuinely valuable metric idea (defaults vs. options as outcome drivers); research-stage. |
| MNI-30 Core effectiveness measure | **Supports** | "Privacy should not be something an individual has to find. It should be the condition they are already standing in, unless they choose, knowingly, to step out of it." (Core Principle) | Aligns effectiveness with protection-as-baseline, not data volume. |
