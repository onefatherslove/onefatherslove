
# SEHAI Mapping — Standard 6: Safety First vs. Standard 1 (MNI)

**Verdict legend:** Supports · Partially supports · Silent · Contradicts

**Score:** Supports 12 · Partially supports 13 · Silent 5 · Contradicts 0 (of 30)

## Findings

**1. Still zero contradictions across the suite — and S6 explains why.** Standard 6 had every opportunity to collide with MNI (safety vs. minimization is the classic privacy conflict), but it is explicitly drafted as a *bounded exception that imports MNI's own necessity standard*: "the minimum disclosure necessary to address the specific safety concern identified, consistent with the same necessity standard applied throughout this framework." The exception is defined in MNI's terms, so it cannot contradict MNI without self-contradiction.

**2. The reconciliation of the queued tensions:**
- *Autonomy (S3) vs. Safety:* resolved — S6 is "the single, bounded exception to that default," high threshold, calibrated response, escalation-not-replacement.
- *Location (S5) vs. mandatory reporting:* resolved — "minimum disclosure necessary," routed to human professionals (forward-referenced to Std 12).
- *MNI-07 sufficiency vs. safety probing:* **partially resolved — the one genuinely open operational question.** S6 requires conservative false-negative design yet forbids broadening intake. How much inquiry is "sufficient to detect risk" without violating minimization is left to "ongoing refinement." Flag for v1.1.

**3. New instruments and governance content:** Safety Threshold Benchmark (direct analog of MNI-26); mandatory documentation + reviewability of every override; no-safety-as-collection-justification clause.

**4. Testing-protocol consequence:** the MNI Evaluation Benchmark (TI-2) is not scoreable as-is in crisis interactions — it needs a documented crisis-exception annotation field, or every genuine safety override will score as an MNI failure.

## New obligations S6 adds (synthesis ledger)
- Override documentation: specific risk identified, documented, reviewable.
- Calibrated response (proportionate to actual risk).
- Escalation to human professional, not automated crisis resolution (bridges to Std 12).
- Transparency about escalation wherever it does not increase risk.
- Safety Threshold Benchmark (TI-9); safety-override metrics (false positive/negative rates, post-intervention trust).

## Candidate revisions for MNI v1.1
- **MNI-07:** add a safety-sufficiency proviso.
- **TI-2:** add crisis-exception annotation field.
- **MNI-18:** clarify whether consent withdrawal reverts automatically post-crisis.

## Row-by-row mapping

| MNI Req | Verdict | Evidence | Notes |
|---|---|---|---|
| MNI-01 Collection scope | **Partially supports** | "It permits the minimum disclosure necessary to address the specific safety concern identified, consistent with the same 'necessity' standard applied throughout this framework." | Bounded exception: only the minimum, under MNI's own necessity standard. |
| MNI-02 Goal before info | **Silent** | — | |
| MNI-03 Burden of justification | **Supports** | "Justified by a specific identified risk, documented and reviewable, rather than a general policy of caution." (Q2) | Burden heightened for overrides. |
| MNI-04 No "more is better" | **Supports** | "A general safety rationale cannot substitute for the specific, demonstrable necessity required elsewhere." | Forecloses "safety" as collection excuse. |
| MNI-05 Comprehensive assessment OK w/ rationale | **Supports** | "Safety takes precedence, but only to the degree the actual risk requires." | Formalizes rationale-gated exception. |
| MNI-06 Necessity gate | **Supports** | "Should not be used as a rationale to expand data collection beyond what the specific risk actually requires." | The gate survives the exception. |
| MNI-07 Sufficiency of inquiry | **Partially supports** | "Designed conservatively with respect to false negatives... while remaining disciplined against false positives." | Safety-side sufficiency introduced; calibration question unresolved. |
| MNI-08 Dual violation rule | **Supports** | "Should not apply crisis-level intervention to situations of ordinary difficulty." | Dual-harm doctrine re-run in safety domain. |
| MNI-09 Progressive gathering | **Partially supports** | Crisis response "temporarily setting aside the original request." | Bounded non-progressive exception. |
| MNI-10 Goal-first sequence | **Partially supports** | "Temporarily setting aside the original request" in crisis. | First sanctioned sequence override. |
| MNI-11 Moment-of-request justification | **Supports** | "Tell the individual what it is doing and why, rather than acting unilaterally and silently." | Justification extends to overrides. |
| MNI-12 Capability ≠ entitlement | **Supports** | "Does not grant a general license to prioritize its own judgment whenever it perceives risk." | Restraint applied to override power. |
| MNI-13 Pre-collection privacy | **Partially supports** | "Does not suspend privacy obligations generally; permits the minimum disclosure necessary." | Minimization survives except minimum safety disclosure. |
| MNI-14 State need first | **Partially supports** | "Still respecting... the individual's own judgment... wherever not immediately dangerous." | Preserved outside crisis. |
| MNI-15 Right to understand | **Supports** | "Safety concerns do not eliminate the individual's right to be informed." | Survives escalation. |
| MNI-16 No coercion | **Partially supports** | Override only for "genuine, serious, imminent risk." | Only standard that can override MNI-16; self-limits. |
| MNI-17 Least-precise data | **Silent** | — | |
| MNI-18 Continuing consent | **Partially supports** | Crisis override may limit withdrawal in the moment. | Post-crisis reversion unstated — flag. |
| MNI-19 Purpose-bound fields | **Supports** | "The minimum disclosure necessary to address the specific safety concern identified." | Safety disclosures purpose-bound. |
| MNI-20 Less-sensitive alternative | **Partially supports** | "Response should be proportionate to the actual risk identified." | Response-scoped, not request-scoped. |
| MNI-21 Path-adaptive intake | **Silent** | — | |
| MNI-22 Purpose limitation & retention | **Partially supports** | Details "may need to be shared with an appropriate human professional." | Bounded human-professional channel opens. |
| MNI-23 Resource-first | **Silent** | — | |
| MNI-24 No history-before-browsing | **Silent** | — | |
| MNI-25 MNI Benchmark | **Partially supports** | Crisis cases answer Q1/Q5 differently. | Needs crisis-exception annotation field. |
| MNI-26 Human Interaction Benchmark | **Supports** | "Would a reasonable, trained human professional treat this as an emergency... or is caution easier to justify than trust?" | Same instrument, safety domain. |
| MNI-27 Measurable review | **Supports** | "Deliberately narrow, documented, and reviewable." | Strongest governance language in suite. |
| MNI-28 Data-element review | **Partially supports** | Q2's documented-and-reviewable standard. | Applied to risk determinations, not elements. |
| MNI-29 Measurement framework | **Partially supports** | False pos/neg calibration, post-escalation trust. | Adds safety metrics to ledger. |
| MNI-30 Core effectiveness | **Supports** | "Used rarely, narrowly, and only where the risk genuinely demands it." | Helping remains the measure. |

---
