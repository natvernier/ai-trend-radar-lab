# LinkedIn Trend Note Template

A reusable template for capturing, classifying and routing LinkedIn-discovered signals into evidence checks, trend notes, governance questions, adoption work or content workflows.

## Purpose

This template helps teams, organizations, agencies and AI-assisted workflows turn LinkedIn-based observations into structured trend notes.

A trend note is not a copied post.

A trend note is a minimized, classified and reviewable record of a possible signal.

It should help answer:

* What was observed?
* Why is it relevant?
* What kind of source produced the signal?
* What topic cluster does it belong to?
* What signal type does it represent?
* What maturity level does it indicate?
* What evidence is available or missing?
* What organizational implication may follow?
* What next action is necessary and proportionate?

The template can be used in a local file, spreadsheet, database, internal wiki, SharePoint, Confluence, Notion, GitHub, approved AI workspace or dedicated intelligence system.

## When to use this template

Use this template when an observation is more than casual interest and may require structured review.

Suitable cases:

* a topic appears repeatedly across source archetypes
* a vendor narrative starts to become visible
* experts begin debating a risk or capability
* practitioners describe implementation friction
* public institutions or regulators use new language
* leaders amplify a simplified narrative
* employees or teams may face operational pressure
* a post points to external evidence worth reviewing
* a signal may become a governance, adoption or content question

Do not use the full template for every post.

For low-value or unclear input, use a minimal watchlist entry instead.

## Minimal watchlist entry

Use this when a signal is too early, unclear or not yet worth a full trend note.

```md
# Watchlist Entry

Date captured:
Topic cluster:
One-line observation:
Source archetype:
Possible signal type:
Why this was noticed:
Evidence needed:
Review date:
Next action:
```

A watchlist entry can later become a full trend note if repetition, source diversity or evidence increases.

---

# Trend Note Template

## 1. Signal title

```md
Signal title:
```

Use a short descriptive title.

Examples:

```txt
Agent tool permissions becoming a governance concern
Vendor push around autonomous workflow agents
RAG quality shifting from technical issue to ownership problem
AI sovereignty moving from policy debate to procurement question
```

Avoid vague titles such as:

```txt
Interesting AI post
LinkedIn trend
New AI thing
```

## 2. Date captured

```md
Date captured:
Review date:
```

Use the date when the observation was captured.

Add a review date if the signal is not ready for action.

## 3. Captured by / owner

```md
Captured by:
Review owner:
```

Use only where needed.

For team or organization workflows, ownership helps clarify who reviews the signal, checks evidence or decides the next action.

## 4. One-line observation

```md
One-line observation:
```

Write a short summary of what was observed.

The observation should be minimal and specific.

Example:

```txt
Several practitioners describe unclear ownership for RAG knowledge-base quality and hallucination review.
```

Avoid copying full post text unless there is a documented need and approved handling process.

## 5. Source archetype

```md
Source archetype:
```

Classify the source type, not the person.

Examples:

```txt
AI security researcher
cybersecurity practitioner
AI governance lawyer
public institution
research lab
technical builder
enterprise AI lead
product leader
vendor founder
product marketer
analyst or consultant
critical AI voice
internal communication leader
HR or learning leader
journalist or editor
conference speaker
community moderator
investor or VC
standards body
open-source maintainer
executive leader
```

If more than one source type is involved, list all relevant archetypes.

## 6. Source reference

```md
Source reference:
Reference handling:
```

Use only the minimum reference needed for review.

Possible values for `Reference handling`:

```txt
no reference stored
manual note only
public link stored
external evidence link stored
controlled internal reference
requires review before storage
```

Avoid storing unnecessary identifiers, copied post text, screenshots, comments or reactions.

If a direct reference is used, confirm that storage is necessary, proportionate and access-controlled where required.

## 7. Topic cluster

```md
Topic cluster:
```

Choose one or more topic clusters.

Examples:

```txt
AI security
agent risks
AI governance
responsible AI
AI adoption
internal communication
cybersecurity basics for AI adoption
local AI
RAG and knowledge systems
AI sovereignty
leadership pressure
organizational change
vendor narratives
public debate around AI
employee experience
digital transformation
```

## 8. Interest trigger

```md
Interest trigger:
```

Classify why the observation was noticed.

Possible values:

| Interest trigger    | Meaning                                                              |
| ------------------- | -------------------------------------------------------------------- |
| New concept         | Introduces a term, model, capability or issue not previously tracked |
| Repeated signal     | Confirms something observed elsewhere                                |
| Strong framing      | Offers a useful way to explain a complex topic                       |
| Contrarian angle    | Challenges the dominant narrative                                    |
| Practical example   | Shows a real use case, workflow, failure or implementation detail    |
| Risk signal         | Reveals a possible failure mode, liability issue or blind spot       |
| Vendor claim        | Shows how vendors position a topic                                   |
| Leadership pressure | Indicates management urgency or expectation                          |
| Adoption friction   | Shows where implementation may get stuck                             |
| Language shift      | Reveals new wording, metaphors or categories                         |
| Emotional resonance | Indicates high audience reaction or professional tension             |
| Content inspiration | Could become an explainer, post, briefing, carousel or article       |
| Source discovery    | Leads to another useful source archetype or evidence trail           |
| Evidence lead       | Points to a paper, report, regulation, standard or external source   |

The interest trigger captures why the signal entered the radar.

It does not determine whether the signal is valid.

## 9. Signal type

```md
Primary signal type:
Secondary signal type:
```

Choose a primary signal type.

Use a secondary signal type where helpful.

| Signal type            | Meaning                                                    |
| ---------------------- | ---------------------------------------------------------- |
| Noise                  | Isolated, vague or low-value input without clear relevance |
| Weak signal            | Early clue with uncertain future relevance                 |
| Emerging pattern       | Repeated signal across sources or contexts                 |
| Expert debate          | Specialists are discussing, refining or disagreeing        |
| Early adopter use case | Practical implementation before mainstream adoption        |
| Vendor push            | Commercial framing, category creation or market claim      |
| Management hype        | Simplified leadership urgency or strategic pressure        |
| Operational pressure   | Implementation demand, employee use or workflow friction   |
| Governance requirement | Need for policy, review, control or accountability         |
| Mainstream expectation | Topic becomes broadly assumed or expected                  |

Example:

```md
Primary signal type: Vendor push
Secondary signal type: Language shift
```

## 10. Maturity level

```md
Maturity level:
Maturity rationale:
```

Use the trend maturity scale.

| Level | Name                   |
| ----: | ---------------------- |
|     0 | Noise                  |
|     1 | Weak signal            |
|     2 | Emerging pattern       |
|     3 | Expert debate          |
|     4 | Early adopter use case |
|     5 | Vendor push            |
|     6 | Management hype        |
|     7 | Operational pressure   |
|     8 | Governance requirement |
|     9 | Mainstream expectation |

Explain why the maturity level was chosen.

Example:

```txt
Maturity level: 5. Vendor push

Maturity rationale:
The signal is currently strongest in vendor and product-marketing sources. Practitioner evidence and governance guidance are not yet sufficient.
```

## 11. Source diversity

```md
Source diversity:
```

Choose one:

```txt
single source archetype
multiple similar source archetypes
multiple distinct source archetypes
cross-domain source pattern
unknown / needs review
```

Optional detail:

```md
Source archetypes observed:
Missing source archetypes:
```

Example:

```txt
Source diversity:
multiple distinct source archetypes

Source archetypes observed:
vendor founder, enterprise AI lead, AI security researcher

Missing source archetypes:
public institution, governance lawyer
```

## 12. Evidence status

```md
Evidence status:
Evidence summary:
Evidence gaps:
```

Possible values:

```txt
none
anecdotal only
partial
external evidence available
sufficient for trend note
sufficient for content review
sufficient for governance review
needs expert review
```

Evidence status should match the intended next action.

A signal can be useful with low evidence if it stays on watchlist.

A signal needs stronger evidence before informing governance, policy, procurement or external publication.

## 13. External evidence

```md
External evidence links:
External evidence needed:
```

Use external evidence to test the signal.

Possible evidence sources:

```txt
research paper
official documentation
public institution
regulation
standard
security report
vendor documentation
analyst report
conference material
GitHub repository
technical blog
case study
reputable journalism
internal approved evidence
```

Core rule:

```txt
LinkedIn reveals the signal.
External evidence tests the claim.
```

## 14. Bias / agenda review

```md
Likely bias or agenda:
Interpretation note:
```

Possible categories:

```txt
commercial
academic
regulatory
legal
practitioner
critical
employer branding
consultant framing
community-driven
media logic
unknown
```

Example:

```txt
Likely bias or agenda:
commercial

Interpretation note:
Useful for vendor narrative tracking, but not sufficient as evidence of implementation success.
```

Bias review should support interpretation.

It should not become personal evaluation.

## 15. Noise risk

```md
Noise risk:
Noise note:
```

Possible values:

```txt
low
medium
high
unknown
```

Example:

```txt
Noise risk:
medium

Noise note:
The topic is relevant, but current visibility is driven mostly by repetitive vendor claims.
```

## 16. Organizational implication

```md
Organizational implication:
```

Choose one or more:

```txt
strategy
governance
adoption
content
vendor evaluation
security
privacy
legal
culture
employee experience
leadership
operations
learning / capability building
reputation
```

Add a short explanation.

Example:

```txt
Organizational implication:
governance, adoption, vendor evaluation

Explanation:
The signal may affect how teams evaluate autonomous-agent claims and define human oversight before workflow deployment.
```

## 17. Governance question

```md
Governance question:
```

Use when the signal creates a risk, accountability, review, privacy, security, vendor or compliance question.

Example:

```txt
Which agent workflows require human review, tool-access limits or security testing before deployment?
```

Leave blank if not relevant.

## 18. Adoption question

```md
Adoption question:
```

Use when the signal may affect workflows, roles, decision rights, capability needs or operating routines.

Example:

```txt
Who owns the quality and maintenance of the knowledge base behind AI-supported answers?
```

Leave blank if not relevant.

## 19. Content question

```md
Content question:
```

Use when the signal may require explanation, internal communication, public positioning, FAQ, briefing, carousel, article or training material.

Example:

```txt
How can the organization explain the difference between AI agent hype and governed workflow automation?
```

Leave blank if not relevant.

## 20. Vendor evaluation question

```md
Vendor evaluation question:
```

Use when the signal is driven by market claims, tool positioning or procurement pressure.

Example:

```txt
Which parts of the vendor claim are supported by implementation evidence, and which require testing before adoption?
```

Leave blank if not relevant.

## 21. Recommended next action

```md
Recommended next action:
```

Choose one:

```txt
discard
watchlist
source map update
feed noise review
external evidence task
trend note
technical literacy note
governance question
adoption question
vendor evaluation question
content idea
publication bridge
expert review
legal / privacy / security review
archive
delete
```

Add a short rationale.

Example:

```txt
Recommended next action:
external evidence task + vendor evaluation question

Rationale:
The signal is currently vendor-heavy and not sufficiently supported for trend-note publication.
```

## 22. Review status

```md
Review status:
```

Possible values:

```txt
open
needs evidence
needs source diversity
needs expert review
needs governance review
reviewed
escalated
converted to trend note
converted to content idea
archived
deleted
```

## 23. Retention status

```md
Retention status:
Retention rationale:
```

Possible values:

```txt
keep
review
archive
delete
```

Use `keep` only when continued retention is necessary and proportionate.

Use `review` when the signal is unclear or time-limited.

Use `archive` when the signal has historical value but no active follow-up.

Use `delete` when the record is no longer needed or not proportionate to retain.

## 24. Access level

```md
Access level:
```

Possible values:

```txt
individual working note
team working note
controlled internal record
governance review record
shareable fictionalized example
external publication candidate
```

Access level should reflect sensitivity, evidence status and data-minimization requirements.

## 25. AI-assisted processing

```md
AI-assisted processing used:
AI input minimized:
AI review needed:
```

Possible values:

```txt
none
classification only
summary support
evidence search support
trend note drafting
handoff routing
content drafting
```

Use only minimized and approved inputs.

Do not include unnecessary identifiers, copied posts, raw exports, comments or reactions.

---

# Compact template

Use this version for operational work.

```md
# LinkedIn Trend Note

## Metadata

Date captured:
Review date:
Captured by:
Review owner:

## Observation

Signal title:
One-line observation:
Topic cluster:
Source archetype:
Source reference:
Reference handling:

## Classification

Interest trigger:
Primary signal type:
Secondary signal type:
Maturity level:
Maturity rationale:
Source diversity:
Missing source archetypes:

## Evidence

Evidence status:
Evidence summary:
Evidence gaps:
External evidence links:
External evidence needed:

## Interpretation

Likely bias or agenda:
Interpretation note:
Noise risk:
Organizational implication:

## Questions

Governance question:
Adoption question:
Content question:
Vendor evaluation question:

## Action

Recommended next action:
Action rationale:
Review status:
Retention status:
Retention rationale:
Access level:

## AI-assisted processing

AI-assisted processing used:
AI input minimized:
AI review needed:
```

---

# Example 1: Vendor push around autonomous agents

```md
# LinkedIn Trend Note

## Metadata

Date captured:
2026-06-22

Review date:
2026-07-22

Captured by:
[team / role]

Review owner:
[team / role]

## Observation

Signal title:
Vendor push around autonomous workflow agents

One-line observation:
Several vendor founders and product marketers describe autonomous agents as a way to replace workflow coordination and manual operational tasks.

Topic cluster:
AI agents, workflow automation, vendor narratives

Source archetype:
vendor founder, product marketer

Source reference:
manual note only

Reference handling:
no direct post text stored

## Classification

Interest trigger:
vendor claim, language shift

Primary signal type:
Vendor push

Secondary signal type:
Management hype

Maturity level:
5. Vendor push

Maturity rationale:
The topic is highly visible in vendor and product-positioning sources, but practitioner evidence and governance guidance are not yet sufficient.

Source diversity:
multiple similar source archetypes

Missing source archetypes:
enterprise AI lead, AI security researcher, governance lawyer, technical builder

## Evidence

Evidence status:
partial

Evidence summary:
Vendor documentation and public marketing examples exist, but implementation evidence is limited.

Evidence gaps:
enterprise case studies, security guidance, workflow-governance examples

External evidence links:
[to be added]

External evidence needed:
security documentation, implementation case studies, governance guidance

## Interpretation

Likely bias or agenda:
commercial

Interpretation note:
Useful for tracking market narrative and procurement pressure, not sufficient as evidence of adoption success.

Noise risk:
medium to high

Organizational implication:
vendor evaluation, governance, adoption

## Questions

Governance question:
Which agent workflows require human review, tool-access limits or security testing before deployment?

Adoption question:
Which workflow tasks could be supported by agents under controlled conditions, and which should remain human-owned?

Content question:
How can the organization explain the difference between agent hype and governed workflow automation?

Vendor evaluation question:
Which parts of the vendor claim are supported by implementation evidence, and which require testing?

## Action

Recommended next action:
external evidence task + vendor evaluation question

Action rationale:
The signal is relevant but vendor-heavy and requires external evidence before trend-note or content use.

Review status:
needs evidence

Retention status:
review

Retention rationale:
Keep temporarily for market narrative tracking and reassess after evidence review.

Access level:
team working note

## AI-assisted processing

AI-assisted processing used:
classification support

AI input minimized:
yes

AI review needed:
yes, after external evidence is added
```

---

# Example 2: RAG quality becomes an ownership issue

```md
# LinkedIn Trend Note

## Metadata

Date captured:
2026-06-22

Review date:
2026-07-22

Captured by:
[team / role]

Review owner:
[team / role]

## Observation

Signal title:
RAG quality shifting from technical issue to ownership problem

One-line observation:
Several practitioners describe RAG quality problems as issues of knowledge ownership, review routines and maintenance responsibility rather than only retrieval technology.

Topic cluster:
RAG and knowledge systems, AI adoption, governance

Source archetype:
enterprise AI lead, product owner, technical builder

Source reference:
manual note only

Reference handling:
no direct post text stored

## Classification

Interest trigger:
adoption friction, practical example

Primary signal type:
Operational pressure

Secondary signal type:
Governance requirement

Maturity level:
7. Operational pressure

Maturity rationale:
The signal reflects implementation friction in organizational workflows and raises ownership questions for quality, maintenance and review.

Source diversity:
multiple distinct source archetypes

Missing source archetypes:
knowledge-management expert, governance reviewer

## Evidence

Evidence status:
partial

Evidence summary:
Practitioner observations are visible, but external evidence and structured case examples are needed.

Evidence gaps:
knowledge-management frameworks, RAG quality patterns, governance examples

External evidence links:
[to be added]

External evidence needed:
technical documentation, case studies, knowledge-management references

## Interpretation

Likely bias or agenda:
practitioner

Interpretation note:
Useful for adoption and governance work because it links technical performance to organizational ownership.

Noise risk:
low to medium

Organizational implication:
adoption, governance, content, operations

## Questions

Governance question:
Who is accountable for quality, review and maintenance of knowledge sources used by AI-supported answers?

Adoption question:
Which team owns the workflow for improving source quality when AI outputs fail?

Content question:
How can employees understand why AI answer quality depends on knowledge-system quality?

Vendor evaluation question:
How does a vendor support knowledge governance, source freshness and review workflows?

## Action

Recommended next action:
trend note + governance question + adoption question

Action rationale:
The signal has operational relevance and should be connected to knowledge ownership, workflow design and review routines.

Review status:
needs evidence

Retention status:
keep

Retention rationale:
Signal is directly relevant to adoption and governance work.

Access level:
team working note

## AI-assisted processing

AI-assisted processing used:
classification support, question drafting

AI input minimized:
yes

AI review needed:
yes, before any publication or decision use
```

---

# Example 3: Technical warning around agent security

```md
# LinkedIn Trend Note

## Metadata

Date captured:
2026-06-22

Review date:
2026-07-22

Captured by:
[team / role]

Review owner:
[team / role]

## Observation

Signal title:
Agent tool access emerging as a security review topic

One-line observation:
AI security researchers and cybersecurity practitioners are discussing risks around agent tool permissions, indirect prompt injection and uncontrolled action execution.

Topic cluster:
AI security, agent risks, governance

Source archetype:
AI security researcher, cybersecurity practitioner

Source reference:
external evidence links preferred

Reference handling:
external sources should be stored instead of copied LinkedIn content

## Classification

Interest trigger:
risk signal, evidence lead

Primary signal type:
Expert debate

Secondary signal type:
Governance requirement

Maturity level:
3. Expert debate

Maturity rationale:
The signal is currently strongest among technical and security experts, with potential governance implications for enterprise workflows.

Source diversity:
multiple distinct source archetypes

Missing source archetypes:
public institution, governance lawyer, enterprise AI lead

## Evidence

Evidence status:
external evidence available / needs review

Evidence summary:
Technical sources and security discussions appear available, but they require review and translation into organizational controls.

Evidence gaps:
enterprise governance examples, tool-access policy examples, implementation case studies

External evidence links:
[to be added]

External evidence needed:
security reports, technical documentation, governance controls

## Interpretation

Likely bias or agenda:
technical risk focus

Interpretation note:
Useful for early governance design, but organizational relevance depends on actual agent workflow design and tool access.

Noise risk:
low

Organizational implication:
security, governance, adoption

## Questions

Governance question:
Which agent workflows require tool-access limits, input validation, logging, human review or security testing before deployment?

Adoption question:
Which tasks should not be delegated to agents without defined control points?

Content question:
How can non-technical stakeholders understand the risk of tool access in agentic workflows?

Vendor evaluation question:
How does a vendor prevent indirect prompt injection and uncontrolled tool execution?

## Action

Recommended next action:
external evidence review + governance question

Action rationale:
The signal may become relevant for future AI workflow governance and should be reviewed before adoption decisions.

Review status:
needs evidence and governance review

Retention status:
keep

Retention rationale:
Relevant for AI security and governance radar work.

Access level:
controlled internal record if specific source references are stored

## AI-assisted processing

AI-assisted processing used:
classification support

AI input minimized:
yes

AI review needed:
yes, with security or governance expertise
```

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* converting a minimal observation into a draft trend note
* suggesting source archetype classification
* suggesting signal type and maturity level
* identifying possible evidence gaps
* drafting governance, adoption, content or vendor questions
* suggesting next action and review status
* identifying whether a signal should remain on watchlist
* summarizing repeated minimized observations

Avoid using AI for:

* processing raw connection exports without review
* extracting LinkedIn posts at scale
* profiling named individuals
* ranking people by trustworthiness
* inferring sensitive attributes
* storing unnecessary identifiers
* turning comments or reactions into uncontrolled datasets

## Review checklist

Before finalizing a trend note, check:

```txt
Is the observation minimal and specific?
Is the source archetype classified?
Is the topic cluster defined?
Is the interest trigger documented?
Is the signal type assigned?
Is the maturity level justified?
Is source diversity visible?
Is the evidence status clear?
Are evidence gaps documented?
Is the organizational implication specific enough?
Are governance, adoption, content or vendor questions needed?
Is the next action necessary and proportionate?
Is access level appropriate?
Is retention status defined?
Are AI-assisted steps limited to minimized and approved inputs?
```

## Related module documents

```txt
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

## Working principle

A LinkedIn Trend Note turns a professional observation into a reviewable intelligence record.

It should capture only what is needed to classify the signal, assess evidence, determine organizational relevance and decide the next action.
