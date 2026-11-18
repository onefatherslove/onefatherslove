Standard 11 mapped: **Supports 6 · Partially supports 5 · Silent 19 · Contradicts 0.** Full content, pasted directly:

---

# SEHAI Mapping — Standard 11: Respect and Dignity vs. Standard 1 (MNI)

**Score:** Supports 6 · Partially supports 5 · Silent 19 · Contradicts 0 (of 30)

## Findings

**1. The posture standard — 19 silences by design.** S11 governs the manner in which all other standards are carried out, not any procedural step: "the difference between a system that processes a person and one that treats them as a person." Its text states the key testability insight directly: a system can "technically satisfy Minimum Necessary Information, Purpose Transparency, and Individual Autonomy and Control while still communicating disrespect through tone, pacing, or subtle skepticism." Every procedural test in the matrix can pass while S11 fails.

**2. The failure mode it targets is structural, not incidental:** "bias in AI systems is rarely a single dramatic failure; it is far more often a pattern of small, cumulative differences." This is the aggregate-failure pattern (first seen in S9's burden argument) recast for tone — it defeats per-instance auditing. The instrument answer is differential testing: same request, varied circumstances, compare outputs.

**3. The S10–S11 interlock — the suite's enforcement pair.** S10 sets parity as policy; S11 names the risk that parity fails in practice "even where it is formally upheld in policy" — training-data encodings of "credible / deserving / truthful" — and supplies the detection mechanism (bias audits). S10 is the rule; S11 is the rule's police. This pairing is a model of how the suite self-enforces and deserves a subsection in the thesis.

**4. Zero contradictions.** The overcorrection risk (generic neutrality) is bounded by the MNI-07 sufficiency anchor — the suite keeps reusing MNI-07 as its tiebreaker, further confirming MNI's load-bearing role.

**5. New instrument — the Dignity Benchmark (TI-14):** the circumstance-swap test. Fourth member of the trusted-professional instrument family (after TI-4, TI-9, TI-13).

## New obligations S11 adds (synthesis ledger)
- No implicit credibility discounting (anti-skepticism rule for hardship-correlated patterns).
- Bias auditing: periodic, simulated, demographically-varied differential testing.
- Dignity-preserving language: neutral, non-stigmatizing framing.
- Equal thoroughness regardless of communication polish.
- Dignity Benchmark (TI-14): circumstance-swap test.

## Candidate revisions for MNI v1.1
- **Test protocol:** TI-2's transcript audit gains a tone/manner dimension — "procedurally compliant but disrespectful" must be a scoreable failure mode.
- **MNI-29:** add tone-disparity and thoroughness-variance metrics.
- **MNI-16:** decline-path testing gains a language check (neutral acceptance, not judgment).

## Row-by-row mapping

| MNI Req | Verdict | Evidence (Standard 11) | Notes |
|---|---|---|---|
| MNI-01 Collection scope | **Silent** | — | |
| MNI-02 Goal before info | **Silent** | — | |
| MNI-03 Burden of justification | **Partially supports** | "Asking only necessary questions, but asking them in a way that implies doubt about the individual's honesty." | Manner of justification regulated. |
| MNI-04 No "more is better" | **Silent** | — | |
| MNI-05 Comprehensive assessment w/ rationale | **Silent** | — | |
| MNI-06 Necessity gate | **Silent** | — | |
| MNI-07 Sufficiency of inquiry | **Supports** | "Differential treatment be justified by genuine relevance to the individual's need, consistent with Minimum Necessary Information's Sufficiency of Inquiry." (Limitations) | MNI-07 cited as anchor for legitimate differential treatment. |
| MNI-08 Dual violation rule | **Silent** | — | |
| MNI-09 Progressive gathering | **Silent** | — | |
| MNI-10 Goal-first sequence | **Silent** | — | |
| MNI-11 Moment-of-request justification | **Partially supports** | "A system can technically satisfy MNI, Purpose Transparency, and Individual Autonomy... while still communicating disrespect through tone, pacing, or subtle skepticism." | Substantively correct ≠ experientially respectful. |
| MNI-12 Capability is not entitlement | **Supports** | "Circumstance is information the system may need. It is never a basis for how much care the person deserves." (Core Principle) | Entitlement doctrine. |
| MNI-13 Pre-collection privacy | **Silent** | — | |
| MNI-14 State need first | **Silent** | — | |
| MNI-15 Right to understand | **Silent** | — | |
| MNI-16 No coercion | **Supports** | "Respecting a decision to decline, but doing so with language that conveys judgment rather than neutral acceptance." | Decline-respect at tone level. |
| MNI-17 Least-precise data | **Silent** | — | |
| MNI-18 Continuing consent | **Silent** | — | |
| MNI-19 Purpose-bound fields | **Silent** | — | |
| MNI-20 Less-sensitive alternative test | **Silent** | — | |
| MNI-21 Path-adaptive intake | **Silent** | — | |
| MNI-22 Purpose limitation & retention | **Silent** | — | |
| MNI-23 Resource-first ordering | **Silent** | — | |
| MNI-24 No history-before-browsing | **Silent** | — | |
| MNI-25 MNI Evaluation Benchmark | **Partially supports** | Five Implementation questions + Dignity Benchmark as parallel instrument; bias auditing adds differential-testing dimension. | Adds TI-14. |
| MNI-26 Human Interaction Benchmark | **Supports** | "If this exact request had come from someone in a materially different life circumstance, would the system's tone, thoroughness, and responsiveness have been any different?" | Circumstance-swap variant. |
| MNI-27 Measurable review process | **Supports** | "Periodically test system outputs across demographically and circumstantially varied simulated interactions." | Mandatory periodic bias audit. |
| MNI-28 Data-element 5-question review | **Partially supports** | Bias audits as per-variation review of output behavior. | |
| MNI-29 Measurement framework | **Partially supports** | "Methods for reliably detecting subtle tone and thoroughness disparities." | Tone-disparity metrics. |
| MNI-30 Core effectiveness measure | **Supports** | "Every individual who reaches this system is owed the same respect, regardless of what brought them to it." (Core Principle) | Person-scoped effectiveness. |

---

**Why this standard matters most for your *testing* thesis specifically.** Standard 11 exposes the limit of every procedural compliance test, including the 30-row matrix we built: a system can pass all of them and still treat people badly. That's not a bug in the matrix — it's the thesis argument in miniature. Your framework claims MNI is testable; S11 proves that testability is layered: *procedural* testability (MNI's rows) and *relational* testability (tone parity via differential simulation). A complete evaluation methodology for SEHAI needs both layers, and the differential-test design (same request × varied circumstances × compare outputs) is directly borrowable as your empirical method.

Also note for the synthesis: MNI-07 (Sufficiency of Inquiry) has now been cited by S6, S8(?), S9, and S11 as the tiebreaker for legitimate differentiation. It's quietly become the suite's conflict-resolution clause — worth its own paragraph when we write up the architecture chapter.

Suite status: 11 of 13 mapped, **zero contradictions across 330 rows**, 14 test instruments. Ready for Standard 12 (Human Escalation and Appropriate Handoff — which S6 already forward-referenced twice).
