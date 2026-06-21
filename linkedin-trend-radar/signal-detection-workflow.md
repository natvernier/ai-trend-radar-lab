# Signal Detection Workflow

A workflow for turning LinkedIn-based observations into classified signals, evidence tasks, trend notes and organizational follow-up actions.

## Purpose

This document defines how teams, organizations, agencies and AI-assisted workflows can detect and classify signals from LinkedIn-based observations.

The workflow helps determine whether an observed post, discussion, repeated phrase, source pattern or public narrative is:

* noise
* a weak signal
* an emerging pattern
* expert debate
* early adopter evidence
* vendor push
* management hype
* operational pressure
* governance requirement
* mainstream expectation

The goal is to prevent two common errors:

```txt id="9nw5ff"
overreacting to isolated posts
underreacting to repeated early signals
```

Signal detection creates a structured path from observation to action.

## Core idea

A signal is not the same as a post.

A post is an input.

A signal is an interpreted observation that may indicate a relevant change, pattern, pressure, risk, opportunity or narrative shift.

```txt id="7n81et"
post / discussion / source pattern
→ observation
→ signal classification
→ maturity assessment
→ evidence check
→ next action
```

The workflow is designed to keep human judgment in the loop while making classification repeatable.

## What this workflow is

This workflow is:

* an observation-to-signal process
* a maturity classification process
* an evidence-routing process
* a handoff mechanism for trend, governance, adoption and content work
* a quality control layer before trend notes are created
* a reusable workflow for teams and AI-assisted systems

## What this workflow is not

This workflow is not:

* a scraping workflow
* a method for bulk extraction
* a popularity ranking system
* a sentiment analysis tool by default
* a replacement for expert review
* a replacement for evidence checking
* a substitute for legal, privacy or platform-policy review

Signal detection should use minimal, approved and proportionate inputs.

## Relationship to other module documents

This workflow relies on:

```txt id="pg6tdf"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

Recommended sequence:

```txt id="dp46v3"
1. Define radar purpose
2. Curate and classify source mix
3. Reduce feed noise
4. Capture minimal observations
5. Detect and classify signals
6. Assign maturity level
7. Add evidence task if needed
8. Decide next action
```

## Workflow overview

The signal detection workflow has ten steps:

```txt id="d9fsik"
1. Capture minimal observation
2. Identify source archetype
3. Identify topic cluster
4. Classify interest trigger
5. Classify signal type
6. Assign maturity level
7. Check repetition and source diversity
8. Check evidence needs
9. Assess organizational implication
10. Decide next action
```

The workflow can be used during weekly radar reviews, monthly synthesis sessions, editorial planning, governance triage, adoption planning or AI-assisted research workflows.

## Step 1: Capture minimal observation

Start with a minimal observation.

A minimal observation should capture the signal without copying more data than needed.

Recommended fields:

```txt id="09xc0l"
Date:
One-line observation:
Source archetype:
Topic cluster:
Signal type:
Interest trigger:
Maturity level:
Evidence needed:
Next action:
```

Example:

```txt id="eisgsy"
Date:
2026-06-22

One-line observation:
Several practitioner posts describe problems with agent tool permissions and unclear human oversight.

Source archetype:
technical builder / cybersecurity practitioner

Topic cluster:
agent risks

Signal type:
expert debate / operational pressure

Maturity level:
3. Expert debate

Evidence needed:
technical documentation, security reports, governance examples

Next action:
external evidence task + governance question
```

Do not start by copying full post text, comments or reactions unless there is a documented need and approved handling process.

## Step 2: Identify source archetype

Classify the source type before interpreting the signal.

Examples:

```txt id="66gr16"
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

The source archetype helps interpret bias, evidence value, expected signal type and next action.

Example:

```txt id="yyb7bs"
Vendor founder
→ useful for vendor push, category creation and market narratives
→ not sufficient as evidence of adoption success

Cybersecurity practitioner
→ useful for practical risk signals
→ may need external validation and context

Public institution
→ useful for policy direction and governance requirements
→ may be slower but higher evidence value
```

## Step 3: Identify topic cluster

Assign the observation to one or more radar topic clusters.

Example topic clusters:

```txt id="oooa5x"
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

Topic clusters help route the signal.

Example:

| Topic cluster          | Likely handoff                                   |
| ---------------------- | ------------------------------------------------ |
| AI security            | governance, security, evidence layer             |
| AI adoption            | adoption operating model                         |
| Vendor narratives      | vendor evaluation, governance                    |
| Internal communication | content lab, communication strategy              |
| Leadership pressure    | adoption, governance, executive briefing         |
| RAG quality            | knowledge systems, governance, content explainer |

## Step 4: Classify interest trigger

The interest trigger explains why the observation was captured.

This is different from signal type.

Interest trigger answers:

> What made this worth noticing?

Possible triggers:

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

Interest triggers are useful for editorial and sensemaking work.

They should not replace evidence assessment.

## Step 5: Classify signal type

Signal type describes what kind of movement the observation may represent.

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

A single observation can have more than one possible signal type.

If uncertain, assign a primary and secondary classification.

Example:

```txt id="v2ro1s"
Primary:
vendor push

Secondary:
language shift
```

## Step 6: Assign maturity level

Use the trend maturity scale.

```txt id="b0f36q"
0. Noise
1. Weak signal
2. Emerging pattern
3. Expert debate
4. Early adopter use case
5. Vendor push
6. Management hype
7. Operational pressure
8. Governance requirement
9. Mainstream expectation
```

Maturity level should be based on evidence of movement, not personal interest.

### Maturity level criteria

| Level                     | Criteria                                                                  |
| ------------------------- | ------------------------------------------------------------------------- |
| 0. Noise                  | Isolated, vague, unsupported or not relevant to radar purpose             |
| 1. Weak signal            | Early clue from one or few relevant sources                               |
| 2. Emerging pattern       | Similar signals appear across multiple sources or contexts                |
| 3. Expert debate          | Specialists discuss, refine or disagree on the issue                      |
| 4. Early adopter use case | Practical implementation appears in specific organizations or communities |
| 5. Vendor push            | Vendors package, sell or claim the topic as a category                    |
| 6. Management hype        | Executives or consultants simplify and amplify the topic                  |
| 7. Operational pressure   | Teams, employees or workflows feel pressure to act                        |
| 8. Governance requirement | Policies, controls, reviews or accountability become necessary            |
| 9. Mainstream expectation | The topic becomes broadly expected or taken for granted                   |

Maturity is not always linear.

A topic can be at different maturity levels in different industries, geographies or functions.

## Step 7: Check repetition and source diversity

A signal becomes stronger when it appears across different source archetypes.

Review:

* Has the observation appeared before?
* Did it appear across different source types?
* Is it only visible in vendor content?
* Is it repeated by practitioners?
* Is it discussed by experts?
* Is there public institution or regulatory movement?
* Is leadership or management language appearing?
* Is operational pressure visible?
* Are employees, teams or implementers affected?

Example source diversity pattern:

```txt id="pjz9c3"
Vendor founder
+ product marketer
= vendor push

Vendor founder
+ enterprise AI lead
+ technical builder
= possible emerging pattern

AI security researcher
+ cybersecurity practitioner
+ public institution
= stronger governance signal

Executive leader
+ internal communication leader
+ employee-facing discussion
= leadership pressure / adoption pressure
```

Source diversity does not prove validity.

It improves the basis for review.

## Step 8: Check evidence needs

A signal should be routed to evidence review when claims are important, uncertain, risky or likely to inform decisions.

Evidence may be needed when:

```txt id="df9x16"
the signal may influence strategy
the signal may influence governance
the signal may influence external content
the signal includes a technical claim
the signal includes a legal or regulatory claim
the signal comes mainly from vendors
the signal is viral but unsupported
the signal could create reputational risk
the signal may affect employees or internal workflows
```

Evidence sources may include:

* research papers
* official documentation
* regulations
* standards
* security reports
* vendor documentation
* analyst reports
* public institutions
* conference materials
* GitHub repositories
* technical blogs
* case studies
* reputable journalism

Core rule:

```txt id="0j9n93"
LinkedIn can reveal a signal.
External sources should test claims before the signal informs decisions or publication.
```

## Step 9: Assess organizational implication

A signal is only useful if its relevance can be assessed.

Review possible implications:

| Implication area  | Question                                                                    |
| ----------------- | --------------------------------------------------------------------------- |
| Strategy          | Does this affect priorities, positioning or investment logic?               |
| Governance        | Does this create risk, accountability, review or compliance questions?      |
| Adoption          | Does this create workflow, capability, leadership or employee pressure?     |
| Content           | Does this need explanation, communication or public positioning?            |
| Vendor evaluation | Does this create procurement, tool or claim-assessment questions?           |
| Security          | Does this affect data, access, agents, tooling or attack surface?           |
| Culture           | Does this create anxiety, resistance, misunderstanding or expectation gaps? |
| Operations        | Does this change how work is done or governed?                              |

The implication does not need to be final.

It only needs to determine next action.

## Step 10: Decide next action

Every signal should end with a next action.

| Signal assessment         | Next action                   |
| ------------------------- | ----------------------------- |
| Not relevant              | discard                       |
| Interesting but unclear   | watchlist                     |
| Source imbalance found    | source map update             |
| Low evidence              | external evidence task        |
| Repeated pattern          | trend note                    |
| Technical concept unclear | technical literacy note       |
| Vendor-heavy              | vendor evaluation question    |
| Risk-heavy                | governance question           |
| Adoption-relevant         | adoption question             |
| Communication-relevant    | content idea                  |
| Strong public narrative   | publication bridge            |
| High sensitivity          | legal/privacy/security review |
| No longer useful          | archive or delete record      |

Next action should be documented in the working layer.

## Signal quality criteria

Before creating a trend note, check signal quality.

| Criterion                  | Question                                                   |
| -------------------------- | ---------------------------------------------------------- |
| Relevance                  | Does this signal support the radar purpose?                |
| Specificity                | Is the signal concrete enough to evaluate?                 |
| Repetition                 | Has it appeared more than once?                            |
| Source diversity           | Does it appear across different source archetypes?         |
| Evidence value             | Is external evidence available or needed?                  |
| Maturity clarity           | Can maturity level be assigned with reasonable confidence? |
| Organizational implication | Is there a plausible internal relevance?                   |
| Bias awareness             | Is the source’s likely agenda visible?                     |
| Actionability              | Is a next action clear?                                    |
| Proportionality            | Is further tracking justified?                             |

If several criteria are weak, the signal should remain on watchlist or be discarded.

## Evidence threshold by next action

Different actions require different evidence levels.

| Next action                | Evidence threshold                                              |
| -------------------------- | --------------------------------------------------------------- |
| Watchlist                  | low; minimal observation may be enough                          |
| Source map update          | low to medium; based on source mix review                       |
| Trend note                 | medium; needs repetition, source diversity or external evidence |
| Governance question        | medium to high; risk relevance must be clear                    |
| Vendor evaluation question | medium; vendor claim plus potential relevance                   |
| Adoption question          | medium; operational implication should be plausible             |
| Content idea               | medium; claims need verification before publication             |
| External publication       | high; requires evidence, context and review                     |
| Policy or decision input   | high; requires verified evidence and stakeholder review         |

This prevents low-evidence observations from becoming high-impact decisions too quickly.

## Handling uncertainty

A signal does not need to be fully understood immediately.

Use explicit uncertainty labels.

| Label                    | Meaning                                                       |
| ------------------------ | ------------------------------------------------------------- |
| Unclear                  | Not enough information to classify                            |
| Watch                    | Potentially relevant, but too early                           |
| Needs evidence           | Claim or implication requires external support                |
| Needs source diversity   | Current signal comes from too narrow a source mix             |
| Needs expert review      | Topic requires specialist interpretation                      |
| Needs governance review  | Risk, compliance or accountability implications are possible  |
| Needs adoption review    | Workflow, people or operating-model implications are possible |
| Ready for trend note     | Enough structure exists to document the signal                |
| Ready for content review | Signal may become a communication asset after evidence check  |

Uncertainty should be documented rather than hidden.

## Signal detection table

A working signal detection table may use the following fields.

| Field                      | Purpose                                                            |
| -------------------------- | ------------------------------------------------------------------ |
| Date captured              | When the observation was recorded                                  |
| One-line observation       | Minimal summary of the signal                                      |
| Source archetype           | Type of source that produced the observation                       |
| Topic cluster              | Radar topic area                                                   |
| Interest trigger           | Why the observation was noticed                                    |
| Signal type                | Type of signal                                                     |
| Maturity level             | Trend maturity classification                                      |
| Evidence status            | none, partial, sufficient, needs review                            |
| Source diversity           | single source type, multiple source types, cross-domain            |
| Organizational implication | strategy, governance, adoption, content, vendor, security, culture |
| Next action                | watch, evidence task, trend note, governance question, etc.        |
| Review status              | open, reviewed, escalated, archived, deleted                       |
| Retention status           | keep, review, archive, delete                                      |

Additional identifiers or source references should be used only where necessary, proportionate and approved.

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* suggesting signal type from a minimal observation
* identifying possible maturity levels
* suggesting evidence needs
* mapping signal to governance, adoption, content or vendor questions
* checking whether a signal is likely noise, weak signal or emerging pattern
* drafting trend note fields from approved inputs
* identifying missing source archetypes
* creating review questions
* summarizing repeated signals across minimized notes

Avoid using AI for:

* extracting LinkedIn posts at scale
* processing raw connection exports without review
* profiling named individuals
* ranking people by trustworthiness
* inferring sensitive attributes
* storing unnecessary identifiers
* turning comments or reactions into uncontrolled datasets

## Example: vendor claim becomes vendor evaluation question

### Observation

Several vendor founders claim that autonomous agents can replace large parts of internal workflow coordination.

### Classification

| Field                      | Value                                               |
| -------------------------- | --------------------------------------------------- |
| Source archetype           | vendor founder, product marketer                    |
| Topic cluster              | AI agents, workflow automation                      |
| Interest trigger           | vendor claim, language shift                        |
| Signal type                | vendor push                                         |
| Maturity level             | 5. Vendor push                                      |
| Evidence status            | needs external evidence                             |
| Source diversity           | narrow; vendor-heavy                                |
| Organizational implication | vendor evaluation, governance, adoption             |
| Next action                | vendor evaluation question + external evidence task |

### Output

```txt id="sfli1h"
Question:
Which workflow coordination tasks can agents support under controlled conditions, and which claims require evidence before procurement or adoption decisions?
```

## Example: practitioner friction becomes adoption question

### Observation

Several enterprise AI leads describe friction around RAG quality, knowledge ownership and hallucination review.

### Classification

| Field                      | Value                                                      |
| -------------------------- | ---------------------------------------------------------- |
| Source archetype           | enterprise AI lead, product owner                          |
| Topic cluster              | RAG, knowledge systems, AI adoption                        |
| Interest trigger           | adoption friction, practical example                       |
| Signal type                | operational pressure                                       |
| Maturity level             | 7. Operational pressure                                    |
| Evidence status            | partial; needs external examples                           |
| Source diversity           | practitioner-heavy; needs governance and technical sources |
| Organizational implication | adoption, governance, content                              |
| Next action                | trend note + governance question + adoption question       |

### Output

```txt id="ss7f7e"
Adoption question:
Who owns the quality, maintenance and review logic of the knowledge base behind AI-supported answers?
```

## Example: technical warning becomes governance signal

### Observation

AI security researchers and cybersecurity practitioners discuss indirect prompt injection risks in agentic workflows.

### Classification

| Field                      | Value                                                                      |
| -------------------------- | -------------------------------------------------------------------------- |
| Source archetype           | AI security researcher, cybersecurity practitioner                         |
| Topic cluster              | AI security, agent risks                                                   |
| Interest trigger           | risk signal, evidence lead                                                 |
| Signal type                | expert debate / governance requirement                                     |
| Maturity level             | 3. Expert debate, possibly 8. Governance requirement in high-risk contexts |
| Evidence status            | external evidence available / needs review                                 |
| Source diversity           | technical and security sources; governance source needed                   |
| Organizational implication | security, governance, adoption                                             |
| Next action                | external evidence review + governance question                             |

### Output

```txt id="t3bhvf"
Governance question:
Which agent workflows require input validation, tool-access limits, human review or security testing before deployment?
```

## Example: viral framing remains noise

### Observation

A viral post claims that “AI will replace all managers within five years” without evidence or operational detail.

### Classification

| Field                      | Value                                                                      |
| -------------------------- | -------------------------------------------------------------------------- |
| Source archetype           | executive influencer / viral creator                                       |
| Topic cluster              | leadership, AI adoption                                                    |
| Interest trigger           | emotional resonance, management hype                                       |
| Signal type                | noise / management hype                                                    |
| Maturity level             | 0. Noise, or 6. Management hype if repeated by relevant leadership sources |
| Evidence status            | none                                                                       |
| Source diversity           | low                                                                        |
| Organizational implication | possible communication need if repeated internally                         |
| Next action                | discard individual post; watch for repetition                              |

### Output

```txt id="p2ph2z"
No trend note. Watch only if similar claims start shaping leadership expectations or employee concerns.
```

## Review cadence

Signal detection should be reviewed regularly.

| Cadence           | Review focus                                                                                  |
| ----------------- | --------------------------------------------------------------------------------------------- |
| Weekly            | Capture observations, classify signals, identify immediate evidence tasks                     |
| Monthly           | Review repeated signals, create trend notes, update source map                                |
| Quarterly         | Reassess maturity movement, radar purpose, source diversity and handoff quality               |
| After major event | Reclassify signals affected by regulation, platform change, security incident or market event |

Review cadence should match the radar purpose and organizational risk level.

## Review checklist

Before completing a signal detection cycle, ask:

```txt id="brfscm"
Is the observation minimal and proportionate?
Is the source archetype classified?
Is the topic cluster defined?
Is the interest trigger documented?
Is the signal type assigned?
Is the maturity level justified?
Is source diversity visible?
Is evidence sufficient for the next action?
Is the organizational implication clear enough?
Is the next action documented?
Are access, retention and AI-use rules respected?
Should the record be kept, reviewed, archived or deleted?
```

## Related module documents

```txt id="6k9dsl"
linkedin-feed-as-radar.md
authorized-linkedin-intelligence-paths.md
privacy-aware-source-mapping.md
source-discovery-workflow.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

## Working principle

Signal detection turns observations into actionable intelligence by applying source classification, maturity assessment, evidence review and next-action routing.

A signal should move forward only when the next step is necessary, proportionate and clear enough to support review, evidence work, governance, adoption or content decisions.
