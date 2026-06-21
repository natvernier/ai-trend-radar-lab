# Source Classification

A classification framework for source archetypes, source value, signal contribution and interpretation risks in LinkedIn-based trend radar work.

## Purpose

This document defines a reusable classification system for sources used in LinkedIn-based trend radar workflows.

It helps teams, organizations, agencies and AI-assisted workflows classify source archetypes consistently before evaluating signals, trends, governance implications, adoption relevance or content opportunities.

The purpose is not to rank people or create influence scores.

The purpose is to make source assumptions explicit.

A source classification system helps answer:

* What kind of source produced the signal?
* What kind of signal is this source likely to reveal?
* What bias, agenda or limitation should be considered?
* What evidence value can be expected?
* What is the best use of this source type?
* Does this source type support weak-signal detection, evidence checking, governance review, adoption work or content strategy?
* Does the source type create review needs around privacy, proportionality, access or retention?

## Core idea

Different source types reveal different things.

A vendor founder, AI security researcher, regulator, product leader, internal communication expert and critical AI voice may all discuss the same topic, but they do not produce the same kind of signal.

The source classification framework separates:

```txt id="it11oa"
source archetype
→ source role
→ typical signal value
→ evidence value
→ likely bias or agenda
→ best use
→ review needs
```

This makes the radar more interpretable.

## Relationship to the source map

The `linkedin-source-map.md` document defines the structure of the source map.

This document defines the classification logic used inside that map.

Use this document when deciding how to classify a source archetype, candidate source or signal origin.

Recommended sequence:

```txt id="4y7sr4"
1. Define radar purpose
2. Identify source archetypes
3. Classify source type
4. Map expected signal value
5. Document bias and evidence value
6. Add source category or approved reference to the source map
7. Review regularly
```

## What this classification is

This classification is:

* a taxonomy for source archetypes
* a signal-interpretation support tool
* a bias-awareness tool
* a feed-curation support tool
* a source-diversity review tool
* a governance-aware classification layer
* a reusable standard for teams and AI-assisted workflows

## What this classification is not

This classification is not:

* a people-ranking system
* a trustworthiness score for individuals
* a lead-scoring model
* an employee-monitoring tool
* a scraping target list
* a replacement for legal, privacy or platform-policy review
* a guarantee that a source is accurate
* a guarantee that a source is representative

The classification should be applied to the source’s expected value for a defined radar purpose, not to the person or organization as such.

## Classification dimensions

A source can be classified across several dimensions.

| Dimension           | Question                                                        |
| ------------------- | --------------------------------------------------------------- |
| Source archetype    | What kind of source is this?                                    |
| Source role         | What role does this source play in the radar?                   |
| Topic cluster       | Which radar topics does this source support?                    |
| Signal contribution | What kind of signal does this source usually reveal?            |
| Evidence value      | Does this source point to verifiable material?                  |
| Bias / agenda       | What perspective, incentive or limitation may shape the signal? |
| Noise risk          | How likely is this source to create low-value input?            |
| Best use            | How should the radar use this source type?                      |
| Review need         | Does the source type require additional governance review?      |
| Retention need      | Is ongoing monitoring necessary and proportionate?              |

These dimensions can be used in a spreadsheet, database, wiki, knowledge base, local file, internal tool or AI-assisted workflow.

## Primary source archetypes

The following source archetypes can be used as a starting taxonomy.

Organizations should adapt them to their radar purpose.

| Source archetype                       | Typical role                                                        | Typical signal value                            | Typical limitation                               |
| -------------------------------------- | ------------------------------------------------------------------- | ----------------------------------------------- | ------------------------------------------------ |
| AI security researcher                 | Identifies technical risks and early failure modes                  | weak signal, expert debate, governance question | may focus on edge cases or technical depth       |
| Cybersecurity practitioner             | Shows operational security reality                                  | practical risk signal, mitigation pattern       | may be niche, tool-specific or alarmist          |
| AI governance lawyer                   | Interprets regulation, liability and accountability                 | governance requirement, legal signal            | jurisdiction-specific and complex                |
| Public institution                     | Provides formal guidance, policy and standards                      | policy signal, governance requirement           | slow signal and formal language                  |
| Research lab                           | Produces technical papers, benchmarks and research direction        | evidence lead, weak technical signal            | may be difficult to translate into operations    |
| Technical builder                      | Shows implementation details, tool limits and developer reality     | implementation friction, early use case         | may underweight governance or change constraints |
| Enterprise AI lead                     | Shows adoption reality and scaling lessons                          | operational pressure, early adopter use case    | company-specific context                         |
| Product leader                         | Interprets user needs, workflows and product direction              | adoption implication, product framing           | product-centric perspective                      |
| Vendor founder                         | Shows market claims and category creation                           | vendor push, language shift                     | commercial bias                                  |
| Product marketer                       | Shows positioning, messaging and buyer narratives                   | vendor push, management hype                    | promotional framing                              |
| Analyst or consultant                  | Converts signals into executive language                            | management hype, strategic framing              | may simplify or recycle buzzwords                |
| Critical AI voice                      | Highlights risks, harms and blind spots                             | risk signal, counter-narrative                  | may overcorrect against hype                     |
| Internal communication leader          | Reveals employee-facing narratives and adoption pressure            | content need, operational pressure              | less technical depth                             |
| HR or learning leader                  | Reveals workforce, skills and capability expectations               | capability signal, adoption readiness           | may focus on training over operating model       |
| Journalist or editor                   | Shows public framing and mainstream debate                          | mainstream expectation, narrative shift         | may simplify technical complexity                |
| Conference speaker                     | Shows emerging language and community themes                        | emerging pattern, language shift                | event-driven and sometimes promotional           |
| Community moderator                    | Reveals recurring practitioner questions and pain points            | adoption friction, informal signal              | anecdotal and community-specific                 |
| Investor or VC                         | Shows market bets and funding narratives                            | vendor push, category formation                 | financial and growth bias                        |
| Standards body                         | Shows formalization of practices and expectations                   | governance requirement, mainstreaming           | slow signal                                      |
| Open-source maintainer                 | Shows technical direction, adoption friction and ecosystem movement | implementation signal, technical weak signal    | may be technical and community-specific          |
| Procurement or vendor-management voice | Reveals evaluation, buying and risk questions                       | vendor evaluation signal, governance question   | may be less visible on LinkedIn                  |
| Executive leader                       | Shows management interpretation and urgency                         | management hype, leadership pressure            | may simplify operational complexity              |

## Source role categories

A source archetype can also be classified by the role it plays in the radar.

| Source role              | Function                                                        |
| ------------------------ | --------------------------------------------------------------- |
| Early warning source     | Detects weak signals before mainstream awareness                |
| Evidence source          | Points to papers, documentation, standards or formal guidance   |
| Implementation source    | Reveals practical use, friction, failure or scaling problems    |
| Governance source        | Reveals policy, risk, compliance or accountability implications |
| Narrative source         | Shows how a topic is framed publicly                            |
| Vendor narrative source  | Shows how a market category is being sold                       |
| Counter-signal source    | Challenges dominant assumptions or hype                         |
| Adoption pressure source | Shows leadership, employee or workflow pressure                 |
| Content framing source   | Helps translate a topic into language and formats               |
| Source discovery source  | Leads to further people, institutions, papers or communities    |

A single source archetype can play more than one role.

Example:

```txt id="jr39gg"
AI security researcher
→ early warning source
→ evidence source
→ governance source
```

## Signal contribution categories

The source classification should connect sources to expected signal contribution.

| Signal contribution    | Meaning                                                     | Typical source archetypes                                 |
| ---------------------- | ----------------------------------------------------------- | --------------------------------------------------------- |
| Weak signal            | Early clue with uncertain future relevance                  | researchers, builders, niche practitioners                |
| Emerging pattern       | Repeated signal across contexts                             | practitioners, analysts, conference speakers              |
| Expert debate          | Disagreement or refinement among specialists                | researchers, lawyers, security experts                    |
| Early adopter use case | Practical use before mainstream adoption                    | enterprise AI leads, product teams, technical builders    |
| Vendor push            | Commercial framing or category creation                     | vendors, founders, product marketers, VCs                 |
| Management hype        | Simplified executive pressure or urgency                    | executives, consultants, analysts                         |
| Operational pressure   | Implementation demand, employee use or process friction     | operators, internal comms, HR, product owners             |
| Governance requirement | Need for policy, review, controls or accountability         | legal, compliance, security, regulators                   |
| Mainstream expectation | Topic becomes broadly assumed or expected                   | business media, executives, HR, professional communities  |
| Language shift         | New terms, metaphors or categories enter discourse          | consultants, vendors, conference speakers, journalists    |
| Evidence lead          | Signal points to verifiable external material               | researchers, public institutions, standards bodies        |
| Content opportunity    | Signal can become a useful explainer, post, briefing or FAQ | analysts, communicators, practitioners, strong explainers |

Signal contribution should be validated through observation over time.

## Evidence value categories

Evidence value describes whether a source tends to support claims with verifiable material.

| Evidence value | Meaning                                                             | Typical examples                                          |
| -------------- | ------------------------------------------------------------------- | --------------------------------------------------------- |
| High           | Regularly links to primary or credible external sources             | papers, documentation, standards, official guidance       |
| Medium         | Provides examples, experience, case studies or secondary references | implementation notes, conference summaries, use cases     |
| Low            | Mostly opinion, positioning, narrative or promotional content       | thought leadership posts, sales posts, general commentary |
| Unknown        | Evidence pattern has not yet been reviewed                          | new candidate source                                      |

Evidence value does not determine whether a source is useful.

A low-evidence vendor post may still be useful for detecting vendor push.

But it should not be treated as proof without external evidence.

## Bias and agenda categories

Bias and agenda should be documented as interpretation context.

| Bias / agenda      | Typical source types                                   | Interpretation note                                |
| ------------------ | ------------------------------------------------------ | -------------------------------------------------- |
| Commercial         | vendors, founders, product marketers, VCs              | useful for market and category narratives          |
| Academic           | researchers, labs, universities                        | useful for evidence and early technical signals    |
| Regulatory         | public institutions, regulators, standards bodies      | useful for formalization and compliance signals    |
| Legal              | lawyers, compliance experts                            | useful for liability and governance interpretation |
| Practitioner       | builders, operators, enterprise leads                  | useful for implementation reality                  |
| Critical           | critics, ethicists, civil society voices               | useful for blind spots and counter-narratives      |
| Employer branding  | company leaders, corporate pages                       | useful with caution; may frame selectively         |
| Consultant framing | analysts, consultants, advisors                        | useful for executive language and management hype  |
| Community-driven   | moderators, niche communities, open-source maintainers | useful for informal early signals                  |
| Media logic        | journalists, editors, media outlets                    | useful for mainstream narrative shifts             |
| Unknown            | newly discovered or unclear sources                    | requires review before weighting heavily           |

Bias documentation should not be used as a disqualification by default.

It indicates how to read the signal.

## Noise risk categories

Noise risk describes the likelihood that a source type creates low-value, repetitive or misleading input.

| Noise risk | Indicators                                                      | Operational response                      |
| ---------- | --------------------------------------------------------------- | ----------------------------------------- |
| Low        | specific, evidence-aware, topic-relevant, consistent            | keep and review periodically              |
| Medium     | useful but mixed with promotion, repetition or broad commentary | keep with weighting and cadence           |
| High       | generic, viral, unsupported, engagement-driven or repetitive    | reduce weight, mute, archive or limit use |
| Unknown    | insufficient observation history                                | review after a defined period             |

Noise risk should be reviewed over time.

A source type can shift from useful to noisy as a topic becomes popular.

## Best-use categories

A source classification should define how the source type is best used.

| Best use         | Meaning                                                        |
| ---------------- | -------------------------------------------------------------- |
| Watch            | Useful for ongoing monitoring                                  |
| Verify           | Useful for finding evidence or primary material                |
| Challenge        | Useful for counter-perspective or risk review                  |
| Compare          | Useful for comparing narratives across source types            |
| Cite             | Useful when linked external evidence is credible               |
| Question         | Useful for governance, adoption or vendor-evaluation questions |
| Translate        | Useful for explaining complex topics                           |
| Content idea     | Useful for identifying angles, formats or narratives           |
| Source discovery | Useful for identifying further sources                         |
| Archive          | No longer useful enough for active monitoring                  |

A source can have multiple best uses.

## Classification table

A working source classification table may use the following structure.

| Field                        | Purpose                                                |
| ---------------------------- | ------------------------------------------------------ |
| Source archetype             | Classifies the source type                             |
| Source role                  | Defines the role in the radar                          |
| Topic clusters               | Connects the source type to radar topics               |
| Expected signal contribution | Defines what signals this source type may reveal       |
| Evidence value               | Indicates whether the source tends to support claims   |
| Bias / agenda                | Makes likely interpretation context visible            |
| Noise risk                   | Helps manage feed quality                              |
| Best use                     | Defines how the radar should use the source type       |
| Review need                  | Flags whether additional governance review is required |
| Review cadence               | Defines how often the category is reassessed           |
| Retention status             | Keep, review, archive or delete                        |

If a specific source reference is included in a controlled working environment, apply necessity, minimization, access control, retention and review.

## Example classification table

| Source archetype              | Source role              | Expected signal                              | Evidence value | Bias / agenda        | Noise risk | Best use                |
| ----------------------------- | ------------------------ | -------------------------------------------- | -------------- | -------------------- | ---------- | ----------------------- |
| AI security researcher        | early warning, evidence  | weak signal, expert debate                   | high           | technical risk focus | low        | watch, verify, question |
| Vendor founder                | vendor narrative         | vendor push, language shift                  | medium         | commercial           | medium     | compare, question       |
| Enterprise AI lead            | implementation source    | operational pressure, early adopter use case | medium         | company-specific     | low        | watch, translate        |
| Public institution            | governance source        | governance requirement, policy signal        | high           | regulatory           | low        | verify, cite            |
| Analyst / consultant          | narrative source         | management hype, strategic framing           | medium         | consultant framing   | medium     | compare, translate      |
| Critical AI voice             | counter-signal source    | risk signal, counter-narrative               | medium         | critical             | medium     | challenge, question     |
| Internal communication leader | adoption pressure source | content need, employee expectation           | low / medium   | communication focus  | medium     | translate, content idea |

## Source diversity review

Classification should support source diversity review.

A radar can become distorted if it overweights one source type.

Common imbalances:

| Imbalance                  | Risk                                             | Adjustment                                              |
| -------------------------- | ------------------------------------------------ | ------------------------------------------------------- |
| Too many vendors           | vendor push mistaken for market reality          | add practitioners, researchers and critics              |
| Too many executives        | management hype mistaken for adoption readiness  | add operators and implementation sources                |
| Too many technical experts | organizational implications may be missed        | add adoption, governance and communication sources      |
| Too many critics           | risk signals may dominate opportunity assessment | add practitioners and evidence sources                  |
| Too many consultants       | framing may become generic                       | add primary sources and implementation evidence         |
| Too many media sources     | mainstream narrative may hide weak signals       | add researchers and builders                            |
| Too many internal voices   | external shifts may be missed                    | add public institutions, researchers and market sources |

Source diversity is not a quantity target.

It is a visibility check.

## Classification by radar purpose

Different radar purposes require different source weighting.

| Radar purpose          | Prioritize                                                                        | Reduce over-reliance on                 |
| ---------------------- | --------------------------------------------------------------------------------- | --------------------------------------- |
| AI security radar      | researchers, cybersecurity practitioners, technical builders, public institutions | generic AI influencers                  |
| Governance radar       | legal experts, regulators, standards bodies, security teams, public institutions  | vendor-only sources                     |
| Adoption radar         | enterprise AI leads, operators, HR, internal communication, product owners        | executive hype sources                  |
| Content radar          | communicators, analysts, journalists, practitioners, strong explainers            | low-evidence viral posts                |
| Vendor narrative radar | vendors, founders, product marketers, analysts, procurement voices                | treating vendor claims as evidence      |
| AI literacy radar      | educators, explainers, researchers, practitioners                                 | overly technical or promotional sources |
| Reputation radar       | media, executives, community voices, employees, public institutions               | isolated anecdotes                      |

Classification should follow the radar purpose.

## Classification by maturity stage

Source types are useful at different trend maturity stages.

| Maturity stage         | Useful source types                                                 |
| ---------------------- | ------------------------------------------------------------------- |
| Noise                  | broad scan, pattern filters, noise review                           |
| Weak signal            | researchers, builders, niche practitioners, open-source maintainers |
| Emerging pattern       | practitioners, analysts, conference speakers, communities           |
| Expert debate          | researchers, lawyers, security experts, technical writers           |
| Early adopter use case | enterprise leads, product teams, implementation teams               |
| Vendor push            | vendors, founders, product marketers, analysts                      |
| Management hype        | executives, consultants, leadership influencers                     |
| Operational pressure   | operators, HR, internal communication, product owners               |
| Governance requirement | legal, compliance, security, regulators, standards bodies           |
| Mainstream expectation | business media, executives, HR, general professional communities    |

The source mix should shift as a topic matures.

## Review criteria before adding a source type

Before adding a source type or controlled source reference, ask:

```txt id="tesfro"
Does this source type support the radar purpose?
Which topic cluster does it improve?
Which signal type is expected?
Does it add a missing perspective?
Is the evidence value known?
Is the likely bias or agenda visible?
Is the noise risk acceptable?
Is a specific source reference necessary?
Can an archetype be used instead?
What review cadence is appropriate?
What retention status should apply?
```

## Review criteria before weighting a source heavily

Before relying heavily on a source type, ask:

```txt id="7j407z"
Is the signal repeated across other source types?
Is there external evidence?
Is the source commercially or reputationally incentivized?
Is the signal anecdotal or supported?
Is the topic still early, or already management hype?
Does the source reveal reality or mainly language?
Does this signal need governance, adoption, evidence or content follow-up?
```

Heavy weighting should be based on signal quality and evidence, not popularity.

## Retention and review

Source classification should be reviewed regularly.

Recommended cadence:

| Cadence                 | Review focus                                                 |
| ----------------------- | ------------------------------------------------------------ |
| Weekly                  | New source types noticed during signal review                |
| Monthly                 | Source usefulness, noise risk and signal contribution        |
| Quarterly               | Source diversity, weighting, retention and radar purpose fit |
| After major topic shift | New archetypes needed, old categories retired                |

Retention statuses:

| Status  | Meaning                                           |
| ------- | ------------------------------------------------- |
| Keep    | Still useful and proportionate                    |
| Review  | Usefulness or necessity unclear                   |
| Archive | Not actively used but retained with justification |
| Delete  | No longer needed or not proportionate to retain   |

If working data includes identifiable references, retention and access control should be explicit.

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* assigning a source archetype from a minimized description
* suggesting likely signal contribution
* mapping source types to maturity stages
* identifying possible bias or agenda categories
* drafting source diversity reviews
* suggesting missing source archetypes for a radar purpose
* routing signals to governance, adoption, content or evidence follow-up

Avoid using AI for:

* profiling named individuals
* ranking people by trustworthiness
* processing raw connection exports without review
* extracting profile data
* inferring sensitive attributes
* storing unnecessary identifiers
* turning source classification into personal evaluation

## Example: classifying a vendor-heavy topic

### Scenario

A team sees many posts about autonomous AI agents.

Most posts come from vendors, founders and product marketers.

### Classification

| Dimension                 | Classification                                                                   |
| ------------------------- | -------------------------------------------------------------------------------- |
| Dominant source archetype | vendor founder, product marketer                                                 |
| Expected signal           | vendor push, language shift                                                      |
| Evidence value            | low to medium                                                                    |
| Bias / agenda             | commercial                                                                       |
| Noise risk                | medium to high                                                                   |
| Best use                  | compare, question, vendor evaluation                                             |
| Missing sources           | AI security researcher, enterprise AI lead, governance lawyer, technical builder |

### Operational conclusion

The topic should not be treated as validated market reality based on vendor signals alone.

Recommended next actions:

```txt id="4q40z2"
add technical and governance source archetypes
open external evidence task
create vendor evaluation questions
watch for operational pressure signals
```

## Example: classifying an implementation-heavy topic

### Scenario

Several enterprise AI leads and product owners describe friction with RAG quality, knowledge-base ownership and hallucination review.

### Classification

| Dimension                 | Classification                                                         |
| ------------------------- | ---------------------------------------------------------------------- |
| Dominant source archetype | enterprise AI lead, product owner                                      |
| Expected signal           | operational pressure, early adopter use case                           |
| Evidence value            | medium                                                                 |
| Bias / agenda             | company-specific, practitioner                                         |
| Noise risk                | low to medium                                                          |
| Best use                  | adoption question, governance question, content explainer              |
| Missing sources           | knowledge-management expert, AI governance reviewer, technical builder |

### Operational conclusion

The topic may be relevant for adoption and governance work.

Recommended next actions:

```txt id="yvedtq"
write trend note
add external evidence
create governance question around knowledge ownership
create adoption question around workflow responsibility
```

## Review checklist

Before using the source classification framework, check:

```txt id="fr27j6"
Is the radar purpose defined?
Are source archetypes used before named references where possible?
Is source value separated from personal evaluation?
Are topic clusters specific enough?
Are expected signal types documented?
Is evidence value visible?
Is likely bias or agenda documented?
Is noise risk reviewed?
Is source diversity checked?
Is weighting based on signal quality rather than popularity?
Are identifiable references minimized and access-controlled where used?
Is retention status defined for working records?
Are AI-assisted steps limited to minimized and approved inputs?
```

## Related module documents

```txt id="nklmzt"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
linkedin-source-map.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

## Working principle

Source classification improves the radar by making source type, signal value, evidence level, bias, noise risk and best use explicit.

The classification should help teams interpret signals more consistently, adjust the source mix over time and decide when a signal needs evidence, governance review, adoption work or content translation.
