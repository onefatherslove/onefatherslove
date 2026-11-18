# SEHAI Mapping — Standard 5: Contextual Relevance and Location Responsibility vs. Standard 1 (MNI)

**Verdict legend:** Supports · Partially supports · Silent · Contradicts

**Score:** Supports 15 · Partially supports 13 · Silent 2 · Contradicts 0 (of 30)

## Findings

**1. Highest support density of the suite so far (15 Supports, only 2 Silences).** This is not a parallel layer like S2-S4 — it is a *domain-specific operationalization* of MNI. The textual lineage is provable: S5's Core Principle repeats MNI's Examples section near-verbatim ("Location should enable access, not become a requirement for trust"), and MNI-17's ZIP-code example becomes this standard's entire design section. Where S2-S4 each owned one slice, S5 re-derives MNI's full logic for one data type.

**2. The two silences are exactly the two opening-phase requirements** (MNI-02 goal-identification, MNI-14 opportunity to state need first) — consistent with every later standard: the *start* of the interaction belongs to MNI alone.

**3. New doctrinal content — the anti-inference rule for location:** "Systems should avoid drawing or acting on inferences about an individual's health status, living situation, or vulnerability based solely on location, without the individual having disclosed the underlying circumstance." This is the suite's first explicit restriction on what the system may *conclude* from data, not merely what it may collect or retain. Highest-value addition to the synthesis ledger.

**4. Second sensitivity tier introduced:** location history > single location point. This gives the suite a working precedent for data-category tiering that S4's sensitive-category handling began.

**5. No contradictions.** Legal/emergency precision exceptions are deferred to Standard 6 — the second forward reference to Std 6, reinforcing it as the suite's exception-hub.

## New obligations S5 adds (synthesis ledger)

- No inference beyond disclosure (location-based inference prohibition).
- Location history = higher sensitivity tier than single points; no default cross-session location history.
- Purpose-specific precision mapping (browsing vs. transport vs. home visit).
- Domestic-safety heightened caution category.
- Location Responsibility Benchmark (destination-only test) as new instrument (TI-8).

## Candidate revisions for MNI v1.1

- **MNI-17** could absorb S5's purpose-specific precision mapping (its current test is location-only; S5 generalizes the logic).
- **MNI-20** could adopt the no-inference rule as a general pass criterion (currently alternatives-only).
- New candidate: an explicit anti-inference requirement for ALL high-inference data types, not just location.

## Row-by-row mapping

| MNI Req | Verdict | Evidence (Standard 5) | Notes |
| --- | --- | --- | --- |
| MNI-01 Collection scope (only necessary info) | **Supports** | "Use geographic and situational context only to the extent necessary to provide accurate, relevant assistance." (Definition) | Location-specific minimization rule. |
| MNI-02 Goal identified before information needs | **Silent** | — |  |
| MNI-03 Burden of justification on the system | **Supports** | "The system bears the burden of justifying the more precise request rather than defaulting to it because it is easier to implement or marginally improves results." (Relationship to Privacy, Autonomy) | Burden doctrine applied to precision levels. |
| MNI-04 No generic 'more is better' justification | **Supports** | "The fact that location is often necessary does not mean any given level of precision, retention, or use of that location is automatically justified." (Ethical Foundation) | Convenience and marginal accuracy gains explicitly rejected as justifications. |
| MNI-05 Comprehensive assessment permitted with rationale | **Partially supports** | "An example of precision being justified by the specific action requested, not assumed as a general default." (Examples — transportation) | Exception logic (specific action justifies precision) mirrors MNI-05's rationale requirement. |
| MNI-06 Necessity gate (why is this necessary?) | **Supports** | "Does the system actually want more precision than the stated purpose requires?" (Location Responsibility Benchmark) | The gate, specialized to precision. |
| MNI-07 Sufficiency of inquiry (identify actual need) | **Partially supports** | "The same duality identified for questioning generally under Minimum Necessary Information's Sufficiency of Inquiry provision, but specific here to a single, high-inference data type." (Ethical Foundation) | Explicitly cites MNI-07's duality; applies it to data handling rather than questioning. |
| MNI-08 Dual violation rule (over- AND under-collection) | **Partially supports** | "A category where under-protection and over-reliance are both realistic failure modes." (Ethical Foundation) | The dual-failure doctrine imported for location; under-inquiry as such not addressed. |
| MNI-09 Progressive gathering | **Supports** | "The system should adjust its request accordingly rather than collecting maximum precision upfront for anticipated future use." (Implications — purpose-specific precision) | Progressive precision: coarse default, expansion only when the chosen action requires it. |
| MNI-10 Goal-first sequence | **Supports** | "The level of precision requested should map to the specific action being taken." (Implications) | Precision follows the action, not vice versa. |
| MNI-11 Moment-of-request justification | **Supports** | "Has the individual been told, specifically, why this level of precision is being requested?" (Implementation Q5) | Per-request, per-precision-level justification. |
| MNI-12 Capability is not entitlement | **Supports** | "SEHAI rejects that exemption." — necessity of location does not exempt it from scrutiny. (Ethical Foundation) | Rejects the 'required for the system to work' exemption argument. |
| MNI-13 Pre-collection privacy | **Supports** | "Request the least precise form of location that accomplishes the task — city or ZIP code rather than a full address, a general area rather than continuous device-level location tracking." (Implications) | Minimization at the collection point for a high-inference data type. |
| MNI-14 Opportunity to state need first | **Silent** | — |  |
| MNI-15 Right to understand (5 disclosures) | **Partially supports** | "Individuals be told, specifically, why location is being requested and at what level of precision." (Relationship to Privacy, Autonomy) | Covers why + precision-level disclosure; other three disclosures not addressed. |
| MNI-16 No disclosure-for-access coercion | **Partially supports** | "[Individuals] retain the ability to choose a less precise alternative where one is sufficient, consistent with Individual Autonomy and Control." (Relationship to Privacy, Autonomy) | Coarse-location alternative must remain functionally available. |
| MNI-17 Least-precise sufficient data | **Supports** | "Request the least precise form of location that accomplishes the task." / Core principle repeats MNI's own wording: "Location should enable access, not become a requirement for trust." | S5 IS MNI-17's example (ZIP vs. street address) expanded into a full standard — the strongest single-row support so far. |
| MNI-18 Continuing consent | **Partially supports** | "Where continuity of location is useful to the individual... this should be an intentional exception, not an automatic behavior." (Implications) | Continuity of location requires opt-in awareness; withdrawal mechanics not detailed. |
| MNI-19 Purpose-bound fields | **Partially supports** | "The level of precision requested should map to the specific action being taken." (Implications) | Precision levels become purpose-bound fields; general field-purpose register not addressed. |
| MNI-20 Less-sensitive alternative test | **Supports** | "Request the least precise form of location... unless a more precise input is demonstrably necessary." (Implications) | The less-sensitive-alternative test made concrete and mandatory for location. |
| MNI-21 Path-adaptive intake | **Supports** | "Browsing nearby resources requires far less precision than scheduling a home visit or arranging transport." (Implications) | Precision adapts to the path — browsing vs. transport vs. home visit. |
| MNI-22 Purpose limitation & retention | **Supports** | "Systems should not retain a history of locations across sessions by default." / "Location history [carries] re-identification and inference risk that a single location data point does not... treat retained location history as a higher sensitivity category." (Implications; Relationship) | Deepens MNI-22 with a location-history tier: higher sensitivity than single points. |
| MNI-23 Resource-first ordering (food example) | **Partially supports** | "An individual searching for a free clinic needs only a city or ZIP code to receive a relevant list of options." (Examples — clinic) | Options-before-precision ordering for location-dependent services. |
| MNI-24 No history-before-browsing (clinic example) | **Supports** | "A full street address is not necessary at this stage, even though it might marginally refine the results." (Examples — clinic) | Directly enacts MNI-24 for the clinic flow. |
| MNI-25 MNI Evaluation Benchmark (6 questions) | **Partially supports** | Implementation Q1-Q2 (least precise form? justified by current action?) parallel benchmark Q2 for location data. (Implementation) | Adds its own 5-question set + Location Responsibility Benchmark. |
| MNI-26 Human Interaction Benchmark | **Partially supports** | "Would this request still make sense if the destination were the individual's only concern?" (Location Responsibility Benchmark) | A necessity-scoped analog of the trusted-professional test. |
| MNI-27 Measurable review process | **Partially supports** | "Organizations should evaluate location handling against the following [5 questions]." (Implementation) | Instrument supplied; cadence/ownership unspecified. |
| MNI-28 Data-element 5-question review | **Partially supports** | Q1 (least precise form?) covers alternatives; Q3 (history retained by default?) covers retention items. (Implementation) | Location-specific answers for the alternative and retention review items. |
| MNI-29 Measurement framework | **Partially supports** | "Whether reduced location precision measurably affects the practical quality of healthcare and social service navigation." (Future Research) | Precision-quality tradeoff metric proposal. |
| MNI-30 Core effectiveness measure | **Supports** | "The more a system can accomplish with less precision, the more it has honored the person behind the coordinates." (Core Principle) | Effectiveness measured by capability-per-precision, not data richness. |
