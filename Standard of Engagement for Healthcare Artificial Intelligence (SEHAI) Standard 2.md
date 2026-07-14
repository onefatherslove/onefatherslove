# Standard 2: Purpose Transparency

## Definition of the Principle

Purpose Transparency establishes that a healthcare artificial intelligence system must explain, in plain and accessible language, why any given piece of information is being requested and how it will be used, at the point the request is made — not buried in a separate policy document, not disclosed only on request, and not deferred until after disclosure has already occurred.

This principle is the direct operational partner of Minimum Necessary Information. MNI determines *whether* a request is justified. Purpose Transparency determines whether that justification is actually communicated to the individual in a way they can understand and act on. A system can technically satisfy MNI — asking only for information that is genuinely necessary — and still fail the individual if it never explains why. Necessity that is not explained is functionally indistinguishable, from the individual's point of view, from an arbitrary demand.

Under SEHAI, transparency is not a disclosure obligation satisfied by the existence of a privacy policy or terms-of-service document. It is a real-time communicative act, tied to the specific moment of the specific request. The standard is not "the reason exists and could be found." The standard is "the reason was given, here, now, in words the individual could understand without needing to search for it."

## Ethical Foundation

The ethical foundation of Purpose Transparency rests on the relationship between disclosure and consent. Meaningful consent requires that the person consenting understand what they are consenting to. An individual who provides information without understanding why it was requested has not meaningfully consented to its collection — they have complied, which is a different thing entirely, particularly when the individual is in a position of need, urgency, or vulnerability and reasonably believes that withholding information may cost them access to help.

This connects to a long-standing principle in medical ethics: informed consent is not satisfied by a signature or an affirmative click. It is satisfied by comprehension. The same standard, applied to AI-mediated healthcare interaction, requires that comprehension precede disclosure — not follow it, and not remain permanently unavailable behind a hyperlink the individual is unlikely to read.

There is also a trust-based foundation. Systems that explain themselves invite scrutiny; systems that do not explain themselves function, whether intentionally or not, on the individual's assumption that compliance is the price of assistance. An AI system practicing genuine transparency treats the individual as a participant in the interaction rather than a source of data to be processed. This distinction matters most for populations already accustomed to being asked for information without explanation — a common experience in social services, emergency care, and eligibility-based assistance programs, where forms are frequently completed without any accompanying rationale.

Finally, transparency serves an accountability function independent of the individual interaction. A system that must articulate, at the point of each request, why the information is needed cannot quietly drift into collecting information it cannot justify. The discipline of explanation is itself a check on scope creep.

## Relationship to Privacy, Autonomy, and Informed Choice

Purpose Transparency is what makes autonomy exercisable in practice. Autonomy — the person's right to decide what to disclose and what to withhold — is meaningless if the person cannot evaluate what they are being asked to trade. A person cannot weigh the cost of disclosure against the benefit of assistance if they do not know what the disclosure is for.

This principle also reframes privacy protection as an active, not passive, practice. Privacy is often discussed in terms of what a system does *not* do — does not sell data, does not retain it indefinitely, does not share it without authorization. Purpose Transparency adds an active requirement: the system must affirmatively state its purpose, rather than simply refraining from bad behavior. Silence about purpose is not neutral; it shifts the burden onto the individual to assume the best, ask questions they may not know to ask, or simply comply out of urgency.

Informed choice, under this principle, becomes a structural feature of the interaction rather than a footnote. Each request for information should be paired with its rationale as a single unit — not "we need your address" followed, if the individual searches for it, by a general statement somewhere that addresses are used for service-matching. The explanation travels with the request.

## Implications for AI System Design

System design under Purpose Transparency requires that every information request be paired, at the point of the request, with a short, plain-language statement of purpose. This has several concrete consequences.

**Inline justification.** Rather than front-loading a general disclosure ("we may use your information for the following purposes") at the start of an interaction, systems should generate purpose statements contextually, tied to the specific field being requested at that specific moment: "We're asking for your ZIP code so we can show clinics near you."

**Plain language by default.** Purpose statements should avoid legal, clinical, or technical phrasing. A justification that requires the individual to interpret jargon has not achieved transparency; it has relocated the burden of understanding onto a person least equipped, in the moment, to do that work.

**Consistency between stated and actual use.** A system's purpose statements must accurately reflect actual downstream use. If information collected for one stated purpose is later used for another (e.g., service matching versus internal analytics), the system has violated this principle regardless of whether that secondary use was disclosed elsewhere in a broader policy document.

**Right to ask "why" at any point.** Individuals should be able to ask, at any point in the interaction, why a particular piece of information is being requested, and receive a direct answer rather than a deflection or a reference to a policy document.

## Examples in Healthcare Navigation and Social Care

**Requesting location.** A system helping someone find a food pantry might ask for a ZIP code. Under Purpose Transparency, it should state: "This helps us find pantries close to you — we won't use it for anything else." This differs meaningfully from simply requesting the field with a label reading "ZIP Code" and no accompanying explanation.

**Requesting eligibility information.** If an individual expresses interest in a specific assistance program with income-based eligibility, the system might need to ask about household income. The system should explain: "This program has an income requirement, so we need this to check if you qualify — it won't affect any other resources we've shown you." This distinguishes eligibility-specific requests from general navigation, and reassures the individual that declining does not forfeit access to the options already provided.

**Requesting health information.** A system offering guidance on managing a chronic condition might ask about current medications. Rather than a bare field, it should explain: "Knowing your current medications helps us avoid suggesting something that could interact poorly with them."

In each case, the explanation is short, specific, and tied to an outcome the individual can recognize as relevant to their own goal — not to the organization's internal processes.

## Implementation Considerations

Organizations and system designers implementing Purpose Transparency should evaluate each information request against the following:

1. Is a purpose statement presented at the same time as the request, rather than only in a separate policy?
2. Is the stated purpose specific to this request, rather than a general or boilerplate statement?
3. Is the language understandable without specialized knowledge?
4. Does actual downstream use match the stated purpose?
5. Can the individual ask "why" at any point and receive a direct, specific answer?

A **Transparency Benchmark** question for evaluation: *Could the individual, immediately after being asked for information, correctly explain to someone else why it was requested?* If not, the transparency requirement has not been met, regardless of what documentation exists elsewhere.

## Limitations and Tradeoffs

There is a tension between brevity and completeness. Purpose statements must be short enough to be read and understood in the flow of an interaction, but complex healthcare or eligibility rules sometimes resist simple explanation. A system may need to balance a short inline statement with an optional path to greater detail for individuals who want it, without making the detailed explanation a prerequisite for proceeding.

There is also a risk of transparency becoming performative — technically present but generic enough to convey no real information ("we use this to help you" attached to every field regardless of actual purpose). A purpose statement that could apply to any request is not a meaningful purpose statement. Evaluation of this principle must distinguish genuine, specific justification from formulaic disclosure that merely simulates compliance.

Finally, transparency does not resolve situations where the individual disagrees with the stated purpose or considers it unjustified. This principle guarantees that a reason is given and given honestly; it does not by itself guarantee the individual will find that reason sufficient. That determination belongs to the individual, exercised through the autonomy this principle is designed to support.

## Future Research Opportunities

Future work should examine whether inline, contextual purpose statements measurably increase individuals' willingness to disclose accurate information, whether they reduce abandonment during intake processes, and whether they improve individuals' subjective sense of control and trust compared to conventional upfront-disclosure models. Comparative research between systems using contextual transparency and systems relying on general privacy policies would help establish whether the format of disclosure — not merely its existence — meaningfully affects outcomes.

## Core Principle

An AI system does not earn the right to ask by having the technical ability to ask. It earns that right by explaining, honestly and specifically, why the answer matters to the person being asked.

---

Ready for Standard 3 (Individual Autonomy and Control) whenever you are.
