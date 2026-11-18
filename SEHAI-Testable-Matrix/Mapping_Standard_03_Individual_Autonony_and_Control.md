# SEHAI Mapping — Standard 3: Individual Autonomy and Control vs. Standard 1 (MNI)

**Verdict legend:** Supports · Partially supports · Silent · Contradicts

**Score:** Supports 7 · Partially supports 9 · Silent 14 · Contradicts 0 (of 30)

## Findings

**1. Zero contradictions.** Standard 3 explicitly positions itself downstream of MNI and Purpose Transparency: MNI limits what is asked, PT explains why, and Autonomy governs what happens after.

**2. Its distinctive contribution is the coercion-by-friction doctrine:** 'the absence of an explicit refusal does not mean the absence of coercion; friction itself can function as a penalty for declining.' This is the strongest operational content in any standard so far — it converts MNI-16 from a principle into a testable interface behavior (friction audit).

**3. Largest silent block so far (14 rows):** everything about scope, sequencing, sufficiency, and granularity (MNI-02, 04, 05, 07–11, 13, 14, 17, 19, 20, 24). S3 governs refusals, not requests.

**4. Extends MNI's consent model:** MNI-18 (continuing consent) gains a concrete withdrawal requirement — consent must be reversible, and withdrawal at least as easy as granting.

**5. Boundary condition flagged:** S3 defers safety overrides to Standard 6 (Safety First) — 'autonomy is the default, and any departure must be justified by a genuine, serious safety concern.' Expect this tension to be a key mapping point when we reach Standard 6.

## New obligations S3 adds (synthesis ledger)

- Friction-as-penalty prohibition + friction-proportionality test (Implementation Q5: friction rises 'specifically and only in proportion to genuine necessity').
- Dark-pattern prohibition (pre-checked boxes, urgency language, harder-to-find decline).
- Neutral framing of recommendations; declining never framed as failure/irresponsibility.
- Reversibility: change answers, withdraw information, exit/restart without penalty or loss.
- Autonomy Benchmark (respect-vs-resistance test) as a new instrument (TI-6).
- Escalation without coercion for non-imminent-safety situations.

## Candidate revisions for MNI v1.1

- **MNI-16** pass criterion: add the friction audit ('friction increases only in proportion to genuine necessity') — currently tests only explicit gating.
- **MNI-03** pass criterion: adopt the respect-vs-resistance Autonomy Benchmark as the operational refusal-path test.
- **MNI-18** pass criterion: add 'withdrawal must be at least as easy as granting consent.'

## Row-by-row mapping

| MNI Req | Verdict | Evidence (Standard 3) | Notes |
| --- | --- | --- | --- |
| MNI-01 Collection scope (only necessary info) | **Partially supports** | "A person seeking housing assistance may decline to share details... The system should provide available resources based on what has been shared, rather than gating further assistance behind additional disclosure." (Examples) | Indirect: autonomy enforcement rewards scope discipline but sets no collection limits. |
| MNI-02 Goal identified before information needs | **Silent** | — |  |
| MNI-03 Burden of justification on the system | **Supports** | "The absence of an explicit refusal does not mean the absence of coercion; friction itself can function as a penalty for declining." (Ethical Foundation) | Operationalizes MNI-03's refusal-path test: a 'no' must produce respect, not resistance. |
| MNI-04 No generic 'more is better' justification | **Silent** | — |  |
| MNI-05 Comprehensive assessment permitted with rationale | **Silent** | — |  |
| MNI-06 Necessity gate (why is this necessary?) | **Partially supports** | "Systems should not require an individual to answer a non-essential question before continuing, when the underlying need does not actually require it." (Implications for AI Design) | Enforces the gate's consequence but does not establish the necessity test itself. |
| MNI-07 Sufficiency of inquiry (identify actual need) | **Silent** | — |  |
| MNI-08 Dual violation rule (over- AND under-collection) | **Silent** | — |  |
| MNI-09 Progressive gathering | **Silent** | — |  |
| MNI-10 Goal-first sequence | **Silent** | — |  |
| MNI-11 Moment-of-request justification | **Silent** | — |  |
| MNI-12 Capability is not entitlement | **Supports** | "The individual is the decision-maker. The AI is present to inform that decision, not to make it, not to steer it, and not to penalize a decision it would not have made itself." (Core Principle) | Same restraint doctrine as MNI-12, applied to decisions rather than collection. |
| MNI-13 Pre-collection privacy | **Silent** | — |  |
| MNI-14 Opportunity to state need first | **Silent** | — |  |
| MNI-15 Right to understand (5 disclosures) | **Partially supports** | "Where a field is optional, the interface should make that visibly true — not technically skippable but practically discouraged." (Implications for AI Design) | Directly covers disclosure #3 (required vs. optional); silent on the other four disclosures. |
| MNI-16 No disclosure-for-access coercion | **Supports** | "A system that only proceeds smoothly when the individual answers every question, and stalls, repeats, or withholds assistance when they do not, exerts a coercive pressure even without ever explicitly denying help." (Ethical Foundation) | S3 is the anti-coercion engine for MNI-16: no forced gates, no penalty-by-friction. |
| MNI-17 Least-precise sufficient data | **Silent** | — |  |
| MNI-18 Continuing consent | **Supports** | "An individual who has disclosed information or agreed to an action should retain the ability to withdraw that consent going forward... without being penalized." (Relationship to Privacy, Autonomy) | Adds the withdrawal half of continuing consent; withdrawal must be 'at least as easy as giving it.' |
| MNI-19 Purpose-bound fields | **Silent** | — |  |
| MNI-20 Less-sensitive alternative test | **Silent** | — |  |
| MNI-21 Path-adaptive intake | **Partially supports** | "Individuals should be able to change their answers, withdraw previously given information where feasible, or exit and restart an interaction without penalty or loss of previously offered assistance." (Implications for AI Design) | Non-linear, self-directed paths; intake-depth adaptivity itself not addressed. |
| MNI-22 Purpose limitation & retention | **Partially supports** | "An individual who initially agrees to share contact information for follow-up should be able to later withdraw that permission, and the system should honor that withdrawal rather than treating the earlier consent as irrevocable." (Examples) | Withdrawal honored = downstream use stopped; retention duration/deletion still silent. |
| MNI-23 Resource-first ordering (food example) | **Supports** | "The system should provide available resources based on what has been shared, rather than gating further assistance behind additional disclosure." (Examples — housing) | The housing example enacts the same resources-before-disclosure logic as MNI-23. |
| MNI-24 No history-before-browsing (clinic example) | **Silent** | — |  |
| MNI-25 MNI Evaluation Benchmark (6 questions) | **Partially supports** | "Can the individual decline any non-essential request without losing access to assistance already available to them?" (Implementation Q1) | Directly answers benchmark Q5 (assistance without unnecessary disclosure); adds its own 5-question set + Autonomy Benchmark. |
| MNI-26 Human Interaction Benchmark | **Supports** | "If the individual said no at this exact point, would the system's next action feel like respect or like resistance?" (Autonomy Benchmark) | A behavioral analog of the trusted-professional test, applied to refusals. |
| MNI-27 Measurable review process | **Partially supports** | "Organizations should evaluate autonomy compliance against questions such as [5 questions]." (Implementation) | Instrument supplied; cadence, ownership, metrics not specified. |
| MNI-28 Data-element 5-question review | **Partially supports** | Implementation Q1: "Can the individual decline any non-essential request without losing access to assistance already available to them?" | Covers MNI-28's 'can the individual continue without providing it'; necessity, alternatives, retention silent. |
| MNI-29 Measurement framework | **Partially supports** | "Whether visibly preserved autonomy... measurably increases trust and engagement... whether individuals report feeling more in control." (Future Research) | Proposes trust/control metrics; research-stage only. |
| MNI-30 Core effectiveness measure | **Supports** | "The AI is present to inform that decision, not to make it, not to steer it, and not to penalize." (Core Principle) | Respecting what the person chooses to share, extended to choices about actions. |
