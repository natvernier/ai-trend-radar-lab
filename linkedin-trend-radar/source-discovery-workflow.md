# Source Discovery Workflow

A workflow for identifying, evaluating and maintaining the source mix needed for LinkedIn-based trend radar work.

## Purpose

This document defines how teams, organizations and AI-assisted workflows can discover and maintain useful source categories for a LinkedIn Trend Radar.

The goal is to avoid treating the LinkedIn feed as a random stream.

A good radar starts before the feed review.

It starts with a deliberate source mix.

The source discovery workflow helps answer:

* Which topics should the radar monitor?
* Which source archetypes are needed?
* Which perspectives are missing?
* Which sources may create bias or noise?
* Which sources are useful for early signals?
* Which sources are useful for external evidence?
* Which sources should inform trend notes, governance questions, adoption work or content strategy?

## Core idea

Source discovery is not the same as collecting profiles.

The purpose is to improve the radar’s ability to detect relevant signals.

A mature source mix should include different perspectives:

```txt id="yce8t2"
research
practice
governance
security
regulation
vendor positioning
implementation reality
critical perspectives
leadership discourse
organizational adoption
```

The radar becomes stronger when the source mix is intentional, balanced and reviewed over time.

## What this workflow is

This workflow is:

* a method for defining radar interests
* a method for identifying source gaps
* a method for selecting source archetypes
* a method for improving feed quality
* a method for supporting privacy-aware source mapping
* a method for making source discovery repeatable
* a method for preparing better trend notes and handoffs

## What this workflow is not

This workflow is not:

* a scraping method
* a profile-harvesting method
* a lead-generation workflow
* a method for ranking people
* a method for employee monitoring
* a replacement for legal, privacy or platform-policy review
* a guarantee that a source is reliable or representative

Source discovery should support signal interpretation, not uncontrolled data collection.

## Workflow overview

The source discovery workflow has nine steps:

```txt id="2b0ca9"
1. Define radar purpose
2. Define radar topic clusters
3. Identify required source archetypes
4. Review current source mix
5. Identify source gaps
6. Discover candidate sources
7. Evaluate candidate sources
8. Update the source map
9. Review the source mix regularly
```

The workflow can be used by an individual, a small team, an agency, an internal communication function, a strategy team, a governance team or an approved AI-assisted workflow.

## Step 1: Define radar purpose

Before identifying sources, define why the radar exists.

Example radar purposes:

| Radar purpose          | Typical focus                                                                 |
| ---------------------- | ----------------------------------------------------------------------------- |
| Trend radar            | Detect weak signals, emerging patterns and maturity movement                  |
| Governance radar       | Identify risks, compliance questions, vendor claims and accountability gaps   |
| Adoption radar         | Detect leadership pressure, employee expectations and implementation friction |
| Content radar          | Identify themes, narratives, language shifts and content opportunities        |
| Reputation radar       | Understand public discourse around topics, brands or professional communities |
| Vendor narrative radar | Track how vendors frame emerging capabilities and market promises             |
| AI literacy radar      | Identify concepts that need explanation for employees or leaders              |

A source mix should match the purpose of the radar.

A governance radar needs different sources than a content inspiration radar.

## Step 2: Define radar topic clusters

Define the topic areas the radar should observe.

Example topic clusters:

```txt id="i47scq"
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

Topic clusters should be specific enough to guide source discovery.

Too broad:

```txt id="gx9f41"
AI
```

Better:

```txt id="nmj3sw"
AI governance for organizational adoption
agent risks in enterprise workflows
RAG and knowledge-system quality
```

## Step 3: Identify required source archetypes

Source archetypes describe the type of perspective needed.

They are useful because they allow a radar to be designed before specific names, profiles or accounts are added.

Example source archetypes:

| Source archetype              | Typical signal value                                           | Typical bias or limitation                        |
| ----------------------------- | -------------------------------------------------------------- | ------------------------------------------------- |
| AI security researcher        | Early risk signals, technical warnings, threat models          | May focus on edge cases or technical depth        |
| AI governance lawyer          | Legal interpretation, liability questions, regulatory shifts   | Jurisdiction-specific and complex                 |
| Enterprise AI lead            | Implementation lessons, adoption friction, operational reality | Company-specific context                          |
| Vendor founder                | Product narratives, market claims, commercial direction        | Commercial bias                                   |
| Product leader                | Workflow changes, user needs, tool adoption                    | Product-centric view                              |
| Technical builder             | Implementation details, tooling limits, developer reality      | May underweight organizational constraints        |
| Public institution            | Formal guidance, policy direction, standards                   | Slow signal and formal language                   |
| Cybersecurity practitioner    | Practical risks, controls, attack surface                      | Can be alarmist or niche                          |
| Internal communication leader | Employee expectations, message framing, adoption pressure      | Less technical                                    |
| Analyst or consultant         | Executive framing, market categories, business language        | May recycle buzzwords                             |
| Critical AI voice             | Blind spots, harms, ethical concerns                           | May overcorrect against hype                      |
| Research lab                  | Scientific development, technical benchmarks, papers           | May be hard to translate into operations          |
| Conference speaker            | Emerging discourse, community language, upcoming themes        | Event-driven and sometimes promotional            |
| Journalist or editor          | Public narrative, controversy, mainstream framing              | May simplify technical complexity                 |
| HR or learning leader         | Skills, roles, training needs, workforce adoption              | May focus on capability rather than system design |

A strong radar rarely depends on one source archetype.

It combines perspectives.

## Step 4: Review current source mix

Review the current source mix before adding more.

This review can be manual and qualitative.

Questions:

* Which source archetypes are already visible?
* Which topic clusters appear often?
* Which perspectives dominate?
* Which perspectives are missing?
* Is the feed too vendor-heavy?
* Is the feed too executive-heavy?
* Is the feed too academic?
* Is the feed too content-marketing driven?
* Is there enough implementation reality?
* Is there enough legal or governance perspective?
* Is there enough technical depth?
* Is there enough critical perspective?
* Is there enough external evidence?

The result should be a source mix assessment.

Example:

| Source category        | Current strength | Gap                            | Action                                     |
| ---------------------- | ---------------: | ------------------------------ | ------------------------------------------ |
| UX / product           |             high | no major gap                   | maintain                                   |
| Internal communication |             high | no major gap                   | maintain                                   |
| AI security            |              low | missing technical risk signals | add security researchers and practitioners |
| AI governance law      |              low | missing legal interpretation   | add governance/legal archetypes            |
| Public institutions    |              low | missing formal policy signals  | add institutional sources                  |
| Vendor founders        |           medium | risk of commercial bias        | balance with practitioners and critics     |
| Technical builders     |              low | missing implementation detail  | add builders                               |
| Critical voices        |           medium | useful counterweight           | maintain balance                           |

## Step 5: Identify source gaps

Source gaps are areas where the radar cannot yet see enough.

A gap may be thematic:

```txt id="zspxvp"
Not enough sources on AI security.
```

A gap may be functional:

```txt id="sil2p1"
Not enough sources that reveal implementation reality.
```

A gap may be positional:

```txt id="k5otvb"
Too many vendor voices and not enough public institutions.
```

A gap may be maturity-related:

```txt id="q81jaf"
The radar detects vendor push, but not early expert debate.
```

A gap may be content-related:

```txt id="m1q6zl"
The radar captures topics, but not strong language shifts or explanatory frames.
```

Source gaps should be documented before adding new sources.

## Step 6: Discover candidate sources

Candidate sources can be discovered manually, through external research, through internal recommendations or with AI assistance.

Possible discovery paths:

| Discovery path              | Use                                                                        |
| --------------------------- | -------------------------------------------------------------------------- |
| LinkedIn manual search      | Find people, pages, hashtags, organizations or posts around topic clusters |
| Existing network review     | Identify whether the current network already contains relevant archetypes  |
| External source search      | Find papers, institutions, conferences, newsletters, labs or public bodies |
| Conference programs         | Identify speakers, panels and recurring themes                             |
| Research papers             | Identify authors, labs and communities                                     |
| Vendor ecosystem review     | Identify recurring commercial narratives                                   |
| Public institution review   | Identify regulators, agencies and policy bodies                            |
| Team recommendations        | Capture sources known by employees, experts or advisors                    |
| AI-assisted source strategy | Generate source archetype suggestions, not scraped source lists            |

Candidate discovery should be guided by radar purpose and topic clusters.

It should not become indiscriminate collection.

## Step 7: Evaluate candidate sources

Before adding a candidate source to a working source map, evaluate its potential value.

Recommended evaluation criteria:

| Criterion         | Question                                                                        |
| ----------------- | ------------------------------------------------------------------------------- |
| Relevance         | Does this source relate to the radar topic clusters?                            |
| Signal value      | Does this source reveal useful early signals or patterns?                       |
| Evidence value    | Does this source point to research, documentation or primary material?          |
| Perspective value | Does this source add a missing viewpoint?                                       |
| Novelty value     | Does this source reveal something not already visible?                          |
| Translation value | Can this source help create governance, adoption or content questions?          |
| Bias awareness    | What agenda, incentive or limitation may shape the signal?                      |
| Noise risk        | Does this source produce too much low-value or promotional content?             |
| Review need       | Does this source require privacy, legal or platform review before being stored? |

A source does not need to be neutral to be useful.

Vendor sources, for example, can be valuable for detecting market narratives.

But their signals should be interpreted as commercially positioned.

## Step 8: Update the source map

After evaluation, update the source map in the appropriate layer.

For method documentation, use source archetypes and non-identifying examples.

For controlled working environments, use only the minimum fields needed.

Recommended working fields:

| Field            | Purpose                                                    |
| ---------------- | ---------------------------------------------------------- |
| Source archetype | Describes the type of source                               |
| Topic cluster    | Shows which trend area the source supports                 |
| Signal type      | Defines the kind of signal expected                        |
| Evidence value   | Indicates whether the source points to verifiable material |
| Bias / agenda    | Makes likely perspective visible                           |
| Noise risk       | Helps manage feed quality                                  |
| Best use         | Watch, compare, challenge, cite, question, verify          |
| Review cadence   | Defines how often to reassess the source                   |
| Retention status | Keep, review, archive or delete                            |

Additional identifiers or direct source references should be used only where necessary and approved.

## Step 9: Review the source mix regularly

Source discovery is not a one-time task.

The radar source mix should be reviewed regularly.

Recommended cadence:

| Cadence                 | Review focus                                                                                |
| ----------------------- | ------------------------------------------------------------------------------------------- |
| Weekly                  | Did any new useful source archetype appear? Did a signal reveal a source gap?               |
| Monthly                 | Are repeated signals visible across different source types? Is the feed becoming noisy?     |
| Quarterly               | Is the source mix still aligned with radar interests? Are any perspectives overrepresented? |
| After major topic shift | Does the radar need new topic clusters or source archetypes?                                |

Review questions:

* Which sources produced useful signals?
* Which source archetypes produced noise?
* Which topic clusters are undercovered?
* Which signals lacked external evidence?
* Which sources repeatedly led to useful handoffs?
* Which sources caused overreaction or bias?
* Which source categories should be reduced?
* Which source categories should be added?

## Source discovery loop

The workflow is cyclical.

```txt id="zktw8f"
Radar interests
→ source archetypes
→ source gap review
→ candidate source discovery
→ source evaluation
→ source map update
→ feed review
→ signal detection
→ trend notes
→ handoffs
→ updated radar interests
```

The output of signal detection should inform the next source discovery cycle.

If a trend note repeatedly lacks technical evidence, add technical sources.

If a topic becomes vendor-heavy, add practitioners and critical voices.

If public debate starts influencing internal expectations, add leadership and communication sources.

## Source mix balance

A healthy LinkedIn Trend Radar should balance different types of signal.

| Signal need            | Helpful source archetypes                                                |
| ---------------------- | ------------------------------------------------------------------------ |
| Early technical risk   | AI security researchers, cybersecurity practitioners, technical builders |
| Regulatory direction   | public institutions, governance lawyers, policy analysts                 |
| Vendor narrative       | vendor founders, product marketers, analyst firms                        |
| Implementation reality | enterprise AI leads, product leaders, internal operators                 |
| Adoption pressure      | executives, internal communication leaders, HR and learning leaders      |
| Critical perspective   | critics, ethicists, civil society voices, independent researchers        |
| Content framing        | analysts, journalists, communication leaders, strong explainers          |
| Evidence discovery     | researchers, labs, public institutions, standards bodies                 |
| Language shift         | consultants, conference speakers, content creators, community voices     |

Balance does not mean equal quantity.

It means the radar can see enough of each relevant perspective to avoid blind spots.

## Source discovery by radar maturity stage

Different maturity stages require different source types.

| Maturity stage         | Useful sources                                                           |
| ---------------------- | ------------------------------------------------------------------------ |
| Noise                  | broad feed awareness, topic scanning, pattern filtering                  |
| Weak signal            | researchers, builders, niche practitioners, technical communities        |
| Emerging pattern       | practitioners, analysts, conference speakers, newsletters                |
| Expert debate          | researchers, legal experts, security experts, technical writers          |
| Early adopter use case | enterprise leads, product teams, case studies, implementation teams      |
| Vendor push            | vendors, founders, product marketers, analyst firms                      |
| Management hype        | executives, consultants, leadership influencers                          |
| Operational pressure   | employees, operators, internal communication leaders, HR, product owners |
| Governance requirement | legal, compliance, security, regulators, public institutions             |
| Mainstream expectation | business media, executives, HR, professional communities                 |

This helps avoid a common radar mistake:

```txt id="nmw9u2"
Only watching vendor push and mistaking it for the whole trend.
```

## Privacy-aware source discovery

Source discovery should follow privacy-aware principles.

Recommended principles:

```txt id="aaoai2"
start with source archetypes
document source value, not personal judgments
use minimal working fields
avoid unnecessary identifiers
avoid bulk collection
avoid copying post text by default
avoid storing comments and reactions by default
prefer external evidence where available
define access and retention rules
review higher-risk use cases
```

The source discovery workflow should connect to:

```txt id="fq7f6y"
privacy-aware-source-mapping.md
authorized-linkedin-intelligence-paths.md
linkedin-source-map.md
```

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* suggesting missing source archetypes for a topic cluster
* identifying source mix gaps from non-identifying summaries
* classifying candidate source types
* suggesting likely bias patterns by source archetype
* mapping source archetypes to signal types
* generating source discovery questions
* drafting a source diversity gap analysis
* suggesting external evidence categories
* helping decide whether a signal needs governance, adoption or content follow-up

Avoid using AI for:

* processing raw connection exports without review
* profiling named individuals
* ranking people by influence or trustworthiness
* inferring sensitive attributes
* extracting posts or comments at scale
* turning personal observations into uncontrolled datasets

## Example: source discovery for agent risks

### Radar purpose

Detect emerging organizational risks around AI agents.

### Topic clusters

```txt id="a1dgly"
agent security
tool use
workflow automation
human oversight
prompt injection
governance requirements
enterprise adoption
```

### Required source archetypes

| Source archetype           | Reason                                             |
| -------------------------- | -------------------------------------------------- |
| AI security researcher     | Early warning on technical attack patterns         |
| Cybersecurity practitioner | Practical control and mitigation perspective       |
| Technical builder          | Implementation reality and tooling constraints     |
| Vendor founder             | Market narrative and product promises              |
| Enterprise AI lead         | Adoption and operating-model implications          |
| Governance lawyer          | Accountability, liability and compliance questions |
| Critical AI voice          | Risk framing and blind-spot detection              |

### Source gap finding

```txt id="yp5jtq"
Current source mix is vendor-heavy and lacks technical security depth.
```

### Action

```txt id="mfg8pw"
Add AI security researchers, cybersecurity practitioners and technical builders before writing trend notes on agent risks.
```

## Example: source discovery for AI adoption pressure

### Radar purpose

Detect when public AI discourse creates internal leadership or employee pressure.

### Topic clusters

```txt id="nrlhxn"
AI adoption
leadership expectations
employee experience
internal communication
shadow AI
workflow change
management hype
```

### Required source archetypes

| Source archetype              | Reason                                        |
| ----------------------------- | --------------------------------------------- |
| Executive voice               | Reveals management interpretation             |
| Internal communication leader | Reveals employee-facing narratives            |
| HR or learning leader         | Reveals capability and training expectations  |
| Enterprise AI lead            | Reveals implementation friction               |
| Governance professional       | Reveals policy and control concerns           |
| Critical voice                | Reveals social and organizational blind spots |
| Vendor founder                | Reveals pressure-producing promises           |

### Source gap finding

```txt id="exi5u5"
Current source mix detects management hype, but not operational pressure.
```

### Action

```txt id="l74cic"
Add sources closer to implementation, employee communication and workflow ownership.
```

## Output of this workflow

The output of source discovery is not a large source database.

The output is a better radar source mix.

Typical outputs:

* updated source archetype list
* source diversity gap analysis
* candidate source review
* source map update
* feed curation action
* external evidence search task
* source-risk note
* governance review flag
* updated radar interests

## Handoffs

Source discovery can create handoffs to other parts of the intelligence system.

| Finding                                  | Handoff                             |
| ---------------------------------------- | ----------------------------------- |
| Missing governance perspective           | Governance source gap               |
| Vendor-heavy topic                       | Vendor evaluation question          |
| Weak external evidence                   | External evidence task              |
| High privacy risk                        | Privacy or legal review             |
| Repeated signal across archetypes        | Trend note                          |
| Strong content framing                   | Content idea                        |
| Operational pressure visible             | Adoption question                   |
| Source map contains identifiable records | Privacy-aware source mapping review |

## Review checklist

Before completing a source discovery cycle, ask:

```txt id="czak41"
Have radar interests been defined?
Are topic clusters specific enough?
Are source archetypes balanced?
Are important perspectives missing?
Is the source mix too vendor-heavy?
Is there enough technical and governance depth?
Are sources being evaluated by signal value rather than popularity?
Are identifiable records minimized?
Are higher-risk source records controlled?
Is external evidence available?
Has the next review cadence been defined?
```

## Related module documents

```txt id="ls2aja"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
external-evidence-layer.md
```

## Working principle

Source discovery defines what the radar is able to see.

A responsible source discovery workflow improves signal quality by making the source mix intentional, balanced, privacy-aware and aligned with the organization’s radar purpose.
