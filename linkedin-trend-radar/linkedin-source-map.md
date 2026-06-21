# LinkedIn Source Map

A reusable structure for mapping LinkedIn-related source archetypes, source value, signal types and review criteria for trend radar work.

## Purpose

This document defines how a LinkedIn Source Map can be structured and maintained by teams, organizations, agencies or AI-assisted workflows.

The source map supports LinkedIn-based trend radar work by making the source mix visible, reviewable and aligned with a defined radar purpose.

It helps answer:

* Which source archetypes are useful for this radar?
* Which topic clusters does each source category support?
* What kind of signal does each source type usually produce?
* Which sources help detect weak signals?
* Which sources mainly reveal vendor narratives?
* Which sources provide external evidence?
* Which sources introduce noise or bias?
* Which source gaps need to be closed?
* Which signals should become trend notes, governance questions, adoption questions or content inputs?

The source map is not the whole radar. It is the source-awareness layer that supports signal detection.

## Core idea

A LinkedIn feed is not a neutral intelligence system.

It is shaped by:

* followed people and pages
* connection structure
* platform ranking
* engagement behavior
* topic interests
* language preferences
* professional communities
* recency and virality
* previous interactions
* muted or unfollowed sources

A source map helps make this input layer more intentional.

The source map does not need to start with named individuals.

In many implementations, it should start with source archetypes, topic clusters and source value criteria.

```txt id="2muxdk"
Source archetype
→ topic cluster
→ expected signal type
→ bias / agenda
→ evidence value
→ best use
→ review cadence
```

## Relationship to other module documents

This document should be used together with:

```txt id="czb8ga"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
```

Recommended order:

```txt id="5h5ycn"
1. Define the radar method
2. Define authorized signal paths
3. Define privacy-aware source-mapping rules
4. Discover required source archetypes
5. Build or update the source map
6. Use the source map during signal detection
```

## What this source map is

The LinkedIn Source Map is:

* a source-awareness tool
* a source-diversity review tool
* a feed-curation support tool
* a signal-quality support tool
* a bias-awareness tool
* a handoff support tool
* a governance-aware documentation structure
* a reusable operating artifact for LinkedIn-based radar work

It helps the radar team understand which kinds of inputs shape its view of emerging topics.

## What this source map is not

The LinkedIn Source Map is not:

* a scraping target list
* a lead-generation database
* an influence-ranking table
* a personal reputation scorecard
* an employee-monitoring tool
* a bulk profile dataset
* a replacement for legal or privacy review
* a guarantee that a source is accurate or representative

The source map should support signal interpretation through necessity, proportionality, minimization, access control, retention and review.

## Implementation layers

A source map can exist in different forms depending on the organization’s use case and governance maturity.

| Layer             | Purpose                               | Typical content                                      | Control needs                                  |
| ----------------- | ------------------------------------- | ---------------------------------------------------- | ---------------------------------------------- |
| Method layer      | Defines the source-map logic          | archetypes, fields, criteria, examples               | can be broadly shared if non-identifying       |
| Working layer     | Supports actual radar work            | source categories, selected references, review notes | access control and minimization                |
| Evidence layer    | Links signals to external support     | papers, reports, docs, standards, official sources   | evidence quality and citation discipline       |
| Governance layer  | Documents use limits and review needs | authorized paths, yellow/red flags, retention rules  | legal/privacy/compliance review where relevant |
| AI-assisted layer | Supports classification and routing   | minimized inputs, archetypes, signal notes           | approved inputs and tool controls              |

The same method can be implemented in a local file, spreadsheet, database, internal wiki, SharePoint, Confluence, Notion, GitHub, approved AI workspace or dedicated intelligence tool.

The tool is secondary.

The operating rules are primary.

## Source map levels

A source map can be built at different levels of specificity.

### Level 1: Archetype map

Uses only source categories.

Example:

```txt id="j9vuv3"
AI security researcher
Vendor founder
Public institution
Enterprise AI lead
Critical AI voice
```

Suitable for:

* method documentation
* workshops
* early MVPs
* privacy-sensitive environments
* public or broadly shared training material
* AI-assisted classification

### Level 2: Source category map

Adds topic clusters and signal value.

Example:

| Source archetype       | Topic cluster | Expected signal            |
| ---------------------- | ------------- | -------------------------- |
| AI security researcher | agent risks   | expert debate, weak signal |
| Vendor founder         | automation    | vendor push                |
| Enterprise AI lead     | adoption      | operational pressure       |

Suitable for:

* team radar setup
* source-gap review
* feed curation planning
* trend radar design

### Level 3: Controlled working map

May include selected references if necessary and approved.

Example:

| Source archetype       | Topic cluster | Source reference     | Best use          | Review cadence |
| ---------------------- | ------------- | -------------------- | ----------------- | -------------- |
| AI security researcher | agent risks   | controlled reference | early risk signal | monthly        |

Suitable for:

* internal radar operations
* controlled team workflows
* approved research processes

Requires:

* purpose definition
* access control
* minimization
* retention rules
* review ownership

### Level 4: Organization-ready source system

May connect to approved tools, workflows, evidence systems or internal governance structures.

Suitable for:

* regulated organizations
* enterprise communication teams
* AI governance teams
* strategy teams
* compliance-aware intelligence workflows

Requires:

* documented roles
* approved tools
* data governance
* retention and deletion rules
* privacy and legal review where relevant
* AI tool governance where applicable

## Recommended source archetype table

The source map should start with archetypes.

| Source archetype              | What to watch                                                     | Typical signal value                            | Typical limitation                            |
| ----------------------------- | ----------------------------------------------------------------- | ----------------------------------------------- | --------------------------------------------- |
| AI security researcher        | technical risks, agent failures, prompt injection, tool misuse    | weak signal, expert debate, governance question | may focus on edge cases or technical depth    |
| Cybersecurity practitioner    | controls, vulnerabilities, attack surface, operational security   | practical risk signal, mitigation pattern       | may be niche or alarmist                      |
| AI governance lawyer          | regulation, liability, compliance language, accountability        | governance requirement, policy signal           | jurisdiction-specific complexity              |
| Public institution            | standards, formal guidance, regulatory direction                  | formal policy signal, mainstream movement       | slow signal, formal language                  |
| Research lab                  | papers, benchmarks, technical advances                            | early technical signal, evidence lead           | may be difficult to translate into operations |
| Technical builder             | tool limits, implementation detail, developer practice            | implementation reality, technical friction      | may underweight organizational constraints    |
| Enterprise AI lead            | adoption lessons, workflow integration, internal scaling          | operational pressure, early adopter use case    | company-specific bias                         |
| Product leader                | use cases, product strategy, user needs, workflow design          | adoption implication, product framing           | product-centric view                          |
| Vendor founder                | market claims, product narratives, category creation              | vendor push, language shift                     | commercial bias                               |
| Analyst or consultant         | market categories, executive framing, strategic language          | management hype, content framing                | may recycle buzzwords                         |
| Critical AI voice             | harms, blind spots, social risks, ethical concerns                | risk signal, counter-narrative                  | may overcorrect against hype                  |
| Internal communication leader | employee expectations, change narratives, leadership messaging    | adoption pressure, content need                 | less technical depth                          |
| HR or learning leader         | skills, training needs, role changes, capability development      | capability signal, adoption readiness           | may focus on skills over system design        |
| Journalist or editor          | public debate, controversies, mainstream framing                  | mainstream expectation, narrative shift         | may simplify technical detail                 |
| Conference speaker            | emerging discourse, event themes, community language              | emerging pattern, language shift                | event-driven and sometimes promotional        |
| Community moderator           | recurring questions, practitioner pain points, informal discourse | adoption friction, implementation signal        | may be anecdotal                              |

The exact archetypes should be adapted to the radar purpose.

## Source value criteria

Each source archetype or controlled source reference can be evaluated through operational criteria.

| Criterion         | Question                                                               | Possible values                               |
| ----------------- | ---------------------------------------------------------------------- | --------------------------------------------- |
| Radar relevance   | Does this source support the defined radar purpose?                    | low / medium / high                           |
| Topic fit         | Which topic clusters does this source support?                         | one or multiple clusters                      |
| Signal value      | What type of signal does this source usually produce?                  | weak signal, vendor push, expert debate, etc. |
| Evidence value    | Does this source point to verifiable external material?                | low / medium / high                           |
| Novelty value     | Does this source reveal early or uncommon signals?                     | low / medium / high                           |
| Translation value | Can this source support governance, adoption or content questions?     | low / medium / high                           |
| Bias visibility   | Is the likely agenda or incentive clear?                               | clear / unclear / needs review                |
| Noise risk        | Does this source generate low-value or promotional noise?              | low / medium / high                           |
| Review need       | Does this source require additional privacy, legal or platform review? | no / maybe / yes                              |
| Retention need    | Is continued tracking necessary and proportionate?                     | keep / review / archive / delete              |

These criteria should be applied to source value, not to personal worth or reputation.

## Signal types supported by sources

The source map should connect source types to expected signal types.

| Signal type            | Meaning                                               | Often visible through                                          |
| ---------------------- | ----------------------------------------------------- | -------------------------------------------------------------- |
| Noise                  | Isolated, vague or low-evidence content               | generic influencers, viral posts, repost chains                |
| Weak signal            | Early indicator with unclear future relevance         | researchers, builders, niche practitioners                     |
| Emerging pattern       | Repeated signal across source types                   | practitioners, analysts, conferences, newsletters              |
| Expert debate          | Disagreement or refinement among specialists          | researchers, lawyers, security experts                         |
| Early adopter use case | Practical implementation before mainstream adoption   | enterprise AI leads, product teams, case studies               |
| Vendor push            | Commercial framing or category creation               | vendors, founders, product marketers                           |
| Management hype        | Executive pressure or simplified strategic narrative  | executives, consultants, leadership voices                     |
| Operational pressure   | Implementation demand, employee use, process friction | operators, product owners, internal comms, HR                  |
| Governance requirement | Need for policy, review, control or accountability    | legal, compliance, security, regulators                        |
| Mainstream expectation | Topic becomes broadly expected or assumed             | business media, HR, executives, general professional discourse |

The same source can produce more than one signal type.

## Bias and agenda criteria

Bias does not make a source useless.

It makes interpretation necessary.

Common bias or agenda categories:

| Bias / agenda      | What it may indicate                                    | Use                                             |
| ------------------ | ------------------------------------------------------- | ----------------------------------------------- |
| Commercial         | Source may promote a product, service or category       | useful for vendor narrative tracking            |
| Academic           | Source may privilege research precision or novelty      | useful for evidence and early technical signals |
| Regulatory         | Source may focus on formal requirements and compliance  | useful for governance and policy direction      |
| Practitioner       | Source may emphasize practical friction and constraints | useful for adoption reality                     |
| Critical           | Source may foreground harms, risks or blind spots       | useful for risk review and counter-narrative    |
| Employer branding  | Source may frame work positively for reputation         | useful with caution                             |
| Consultant framing | Source may simplify complexity into executive language  | useful for management hype detection            |
| Community-driven   | Source may reflect niche community concerns             | useful for weak signals                         |
| Unknown            | Source agenda is unclear                                | review before relying on it                     |

A source map should make bias visible so signals can be interpreted in context.

## Evidence value criteria

Not every source needs to provide evidence.

But the radar should know whether a source tends to point toward verifiable material.

| Evidence value | Meaning                                                 | Example                                              |
| -------------- | ------------------------------------------------------- | ---------------------------------------------------- |
| High           | Regularly links to primary or credible external sources | papers, official docs, standards, technical reports  |
| Medium         | Provides practical examples or secondary references     | case studies, implementation notes, conference decks |
| Low            | Mostly opinion, narrative or promotional content        | thought leadership, sales posts, engagement posts    |
| Unknown        | Evidence pattern not yet reviewed                       | new candidate source                                 |

Evidence value should influence next actions.

A low-evidence but interesting signal may require an external evidence task before it becomes a trend note or content input.

## Noise risk criteria

Noise risk describes how likely a source category or source reference is to produce low-value material.

| Noise risk | Indicators                                           | Action                             |
| ---------- | ---------------------------------------------------- | ---------------------------------- |
| Low        | specific, evidence-aware, topic-relevant, consistent | keep                               |
| Medium     | useful but mixed with promotion or repetition        | review periodically                |
| High       | generic, repetitive, unsupported, engagement-driven  | reduce, mute, archive or limit use |

Noise risk is not permanent.

It should be reviewed over time.

## Best-use categories

Each source should have a defined best use.

| Best use         | Meaning                                                        |
| ---------------- | -------------------------------------------------------------- |
| Watch            | Useful for ongoing observation                                 |
| Verify           | Useful for evidence or source checking                         |
| Challenge        | Useful as counter-perspective                                  |
| Compare          | Useful to compare narratives across source types               |
| Cite             | Useful when the source points to credible external material    |
| Question         | Useful for generating governance, adoption or vendor questions |
| Translate        | Useful for explaining complex topics                           |
| Content idea     | Useful for identifying narratives or formats                   |
| Source discovery | Useful for finding additional sources                          |
| Archive          | No longer useful enough to monitor                             |

A source can have more than one best use.

## Recommended working map structure

A working LinkedIn Source Map may use the following fields.

| Field                | Purpose                                                            |
| -------------------- | ------------------------------------------------------------------ |
| Source archetype     | Classifies the kind of source                                      |
| Topic cluster        | Connects the source to radar interests                             |
| Expected signal type | Defines likely signal contribution                                 |
| Evidence value       | Indicates whether the source tends to point to verifiable material |
| Bias / agenda        | Makes likely perspective visible                                   |
| Noise risk           | Helps manage feed quality                                          |
| Best use             | Defines how the source should be used                              |
| Review need          | Flags whether additional review is required                        |
| Review cadence       | Defines how often the source category or reference is reassessed   |
| Last reviewed        | Tracks maintenance                                                 |
| Retention status     | Keep, review, archive or delete                                    |
| Notes                | Minimal operational notes                                          |

Optional fields for controlled environments:

| Field             | Use only if                                                                       |
| ----------------- | --------------------------------------------------------------------------------- |
| Source reference  | A specific source must be retained for the radar purpose and access is controlled |
| Linked evidence   | The signal points to external material needed for verification                    |
| Owner             | A team member is responsible for reviewing this source category                   |
| Handoff relevance | The source regularly informs governance, adoption, content or evidence work       |

The working map should avoid unnecessary identifiers and broad access to identifiable records.

## Example: archetype-based source map

| Source archetype              | Topic cluster  | Expected signal type                         | Evidence value | Bias / agenda        | Noise risk | Best use                        | Review cadence |
| ----------------------------- | -------------- | -------------------------------------------- | -------------- | -------------------- | ---------- | ------------------------------- | -------------- |
| AI security researcher        | agent risks    | weak signal, expert debate                   | high           | technical risk focus | low        | watch, verify, question         | monthly        |
| Vendor founder                | AI agents      | vendor push, language shift                  | medium         | commercial           | medium     | compare, question, content idea | monthly        |
| Enterprise AI lead            | AI adoption    | operational pressure, early adopter use case | medium         | company-specific     | low        | watch, translate, question      | monthly        |
| Public institution            | AI governance  | governance requirement, policy signal        | high           | regulatory           | low        | verify, cite, question          | quarterly      |
| Internal communication leader | adoption       | leadership pressure, content need            | low / medium   | communication focus  | medium     | translate, content idea         | monthly        |
| Critical AI voice             | responsible AI | risk signal, counter-narrative               | medium         | critical perspective | medium     | challenge, question             | monthly        |

This version can be used without identifying specific people.

## Example: source-gap view

| Topic cluster          | Current source strength | Missing perspective                                  | Action                                      |
| ---------------------- | ----------------------: | ---------------------------------------------------- | ------------------------------------------- |
| Agent risks            |                  medium | governance lawyer, enterprise security practitioner  | add legal and security archetypes           |
| AI adoption            |                    high | technical builder                                    | add implementation-focused sources          |
| Local AI               |                     low | privacy/security expert, infrastructure practitioner | add technical and governance sources        |
| RAG quality            |                  medium | knowledge-management expert                          | add KM and information architecture sources |
| AI sovereignty         |                     low | public institutions, policy analysts                 | add institutional sources                   |
| Internal communication |                    high | no major gap                                         | maintain and review noise                   |

This view helps improve the radar before more signals are captured.

## Example: source review view

| Source archetype              | Last reviewed | Signal usefulness | Noise risk | Action                                    |
| ----------------------------- | ------------- | ----------------: | ---------- | ----------------------------------------- |
| Vendor founder                | 2026-06       |            medium | high       | reduce weight, compare with practitioners |
| AI security researcher        | 2026-06       |              high | low        | maintain                                  |
| Analyst / consultant          | 2026-06       |            medium | medium     | keep for management-hype detection        |
| Public institution            | 2026-06       |              high | low        | maintain                                  |
| Internal communication leader | 2026-06       |              high | medium     | maintain, check evidence needs            |

Source review should focus on radar usefulness and proportionality.

## How to add a source category

Use this process:

```txt id="7t1h7e"
1. Identify a source gap
2. Define the needed source archetype
3. Clarify the topic cluster
4. Define expected signal type
5. Assess evidence value
6. Assess likely bias or agenda
7. Assess noise risk
8. Define best use
9. Define review cadence
10. Decide whether any specific source reference is necessary
```

If a specific source reference is not necessary, keep the source map at archetype level.

## How to review a source category

Use this process:

```txt id="6gi973"
1. Check whether the source category produced useful signals
2. Check whether those signals led to evidence, trend notes or handoffs
3. Check whether the category created noise or overreaction
4. Check whether it introduced bias
5. Check whether the radar still needs it
6. Update best use, review cadence or retention status
```

Review should be based on operational usefulness.

## Retention status

A source map should include retention logic.

| Retention status | Meaning                                                                      |
| ---------------- | ---------------------------------------------------------------------------- |
| Keep             | Source category or reference remains useful and proportionate                |
| Review           | Usefulness, risk or necessity is unclear                                     |
| Archive          | No longer actively used, but may be kept for historical context if justified |
| Delete           | No longer needed or not proportionate to retain                              |

Retention should apply especially when the working layer contains identifiable references.

## Integration with signal detection

The source map supports signal detection.

When a signal is captured, the source map helps answer:

* What kind of source produced this signal?
* Is this source type likely to overstate or understate the topic?
* Is the signal supported by evidence?
* Is the signal repeated across source types?
* Does the source type indicate weak signal, vendor push, operational pressure or governance requirement?
* Does the signal need external verification?
* Should the signal become a trend note?

A signal becomes stronger when it appears across different source archetypes.

Example:

```txt id="logvut"
AI security researcher
+ enterprise AI lead
+ public institution
= stronger signal than vendor claim alone
```

## Integration with feed noise reduction

The source map also supports feed hygiene.

If the radar becomes too noisy, review:

* which source archetypes create most noise
* which topic clusters are overrepresented
* whether vendor sources dominate
* whether engagement-driven sources distort attention
* whether critical voices are missing
* whether technical evidence is missing
* whether the feed is optimized for virality rather than signal quality

Noise reduction should be based on documented source review, not impulse.

## Integration with external evidence

The source map should indicate whether a source tends to point toward external evidence.

If a source has low evidence value but high signal value, the next action may be:

```txt id="9cd74k"
external evidence task
```

If a source has high evidence value, the next action may be:

```txt id="ynf003"
trend note with source support
```

If a source is mostly promotional, the next action may be:

```txt id="4zgpdp"
vendor evaluation question
```

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* mapping source archetypes to topic clusters
* identifying source mix gaps from non-identifying summaries
* suggesting likely signal types
* suggesting bias or agenda categories by source archetype
* generating review questions
* drafting source diversity gap analyses
* routing signal notes to governance, adoption, content or evidence tasks

Avoid using AI for:

* processing raw connection exports without review
* profiling named individuals
* ranking people by influence or trustworthiness
* extracting profile data
* inferring sensitive attributes
* processing comments or reactions at scale
* storing unnecessary identifiers

## Review checklist

Before using or updating a LinkedIn Source Map, check:

```txt id="3gfi82"
Is the radar purpose defined?
Are topic clusters specific enough?
Are source archetypes documented?
Is the source mix balanced?
Are important perspectives missing?
Is the source map limited to necessary fields?
Are identifiable references minimized?
Are higher-risk records access-controlled?
Is there a review cadence?
Is there a retention status?
Are evidence needs visible?
Are noise risks documented?
Are AI-assisted steps limited to approved inputs?
```

## Related module documents

```txt id="d8tmc8"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

## Working principle

The LinkedIn Source Map improves radar quality by making source assumptions visible.

A useful source map shows which perspectives shape the radar, where the source mix is biased or incomplete, which signals need external evidence and which source categories should be reviewed, reduced or expanded.
