# Fictionalization Transform Template

**Belongs to:** LinkedIn as input radar
**Artifact type:** Transformation template
**Release phase:** Phase 2 — Make it richer and usable
**Status:** Template
**Data posture:** Fictionalized / shareable after review

## Purpose

This template transforms a real manually observed LinkedIn post, discussion or post pattern into a fictionalized, minimized and archetype-based case.

The goal is to preserve the signal logic without copying the original post or exposing real personal data.

Use this template when a real post inspires an example, but the final artifact must be safe to share, reuse or publish as documentation.

## Core principle

Do not rewrite the original post.

Extract the signal mechanics and rebuild a new case.

Preserve:

```txt
source archetype
topic cluster
signal type
interest trigger
tension
claim pattern
organizational implication
evidence need
next action
```

Change or remove:

```txt
author identity
company names
profile details
specific wording
recognizable phrasing
personal anecdotes
unique examples
traceable details
timelines
locations
comments
reactions
screenshots
```

## Transformation workflow

```txt
1. Manually observe the original LinkedIn post.
2. Do not copy the full post into the repo.
3. Capture only the minimal signal logic.
4. Replace the author with a source archetype.
5. Replace the specific case with a realistic fictional scenario.
6. Remove distinctive wording and traceable details.
7. Classify the interest trigger.
8. Classify the signal type.
9. Assign maturity level.
10. Identify evidence status and evidence gaps.
11. Decide next action.
12. Review traceability risk.
13. Approve as fictionalized example or discard.
```

## Transformation metadata

| Field                  | Entry                                                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------------------- |
| Transform title        |                                                                                                      |
| Date transformed       |                                                                                                      |
| Transformer / reviewer |                                                                                                      |
| Related experiment     |                                                                                                      |
| Related weekly log     |                                                                                                      |
| Related topic cluster  |                                                                                                      |
| Target example file    |                                                                                                      |
| Transformation status  | Raw observation / Minimized observation / Fictionalized case / Example-ready / Discarded             |
| Shareability           | Internal only / Team working note / Shareable fictionalized example / External publication candidate |

## Original observation handling

### Original source handling

| Field                                | Entry                                                                 |
| ------------------------------------ | --------------------------------------------------------------------- |
| Original source retained?            | No / Controlled working layer only / External evidence only           |
| Original post text copied?           | No / Yes, requires deletion or review                                 |
| Original URL stored?                 | No / Yes, controlled working layer only / Yes, external evidence only |
| Screenshot stored?                   | No / Yes, requires review                                             |
| Comments or reactions stored?        | No / Yes, requires deletion or review                                 |
| Contains identifiable personal data? | No / Yes / Unknown                                                    |
| Requires further minimization?       | Yes / No                                                              |

### Minimal private observation

Use only a short operational description.

```txt
One-line original observation:

```

Example:

```txt
A vendor-oriented source frames AI agents as a way to remove coordination work from enterprise workflows, but does not explain review ownership or failure handling.
```

## Signal mechanics extraction

### What is the post doing?

Choose one or more:

```txt
introducing a new term
making a vendor claim
describing implementation friction
sharing a practical example
raising a risk
challenging a dominant narrative
simplifying a topic for leaders
reacting to regulation
showing operational pressure
revealing a content opportunity
pointing to external evidence
```

### Source archetype

Replace the real author with one or more source archetypes.

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
standards body
open-source maintainer
executive leader
procurement or vendor-management voice
```

Selected source archetype:

```txt
```

### Topic cluster

```txt
AI agents
AI security
AI governance
responsible AI
AI adoption
RAG and knowledge systems
vendor narratives
leadership pressure
operational pressure
internal communication
organizational change
employee experience
digital transformation
public debate around AI
```

Selected topic cluster:

```txt
```

### Interest trigger

Choose one or more:

```txt
new concept
repeated signal
strong framing
contrarian angle
practical example
risk signal
vendor claim
leadership pressure
adoption friction
language shift
emotional resonance
content inspiration
source discovery
evidence lead
governance cue
culture cue
format pattern
reputation cue
```

Selected interest trigger:

```txt
```

### Signal type

Choose one primary signal type and optional secondary signal type.

```txt
noise
weak signal
emerging pattern
expert debate
early adopter use case
vendor push
management hype
operational pressure
governance requirement
mainstream expectation
```

Primary signal type:

```txt
```

Secondary signal type:

```txt
```

### Maturity level

```txt
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

Maturity level:

```txt
```

Maturity rationale:

```txt
```

## Traceability reduction

### Remove or generalize

| Original detail type | Transform into                            |
| -------------------- | ----------------------------------------- |
| Real person          | Source archetype                          |
| Real company         | Organization type                         |
| Real tool name       | Tool category                             |
| Exact quote          | New neutral wording                       |
| Personal anecdote    | Fictionalized operational scenario        |
| Specific metric      | Approximate or remove unless necessary    |
| Specific location    | Remove or generalize                      |
| Unique timeline      | Generalize                                |
| Comment thread       | Aggregate signal only                     |
| Screenshot           | Do not store; describe signal minimally   |
| Employer detail      | Remove unless necessary and fictionalized |

### Traceability risk review

| Field                              | Entry                              |
| ---------------------------------- | ---------------------------------- |
| Unique wording removed?            | Yes / No                           |
| Names removed?                     | Yes / No                           |
| Company identifiers removed?       | Yes / No                           |
| Profile details removed?           | Yes / No                           |
| Screenshots avoided?               | Yes / No                           |
| Comments and reactions avoided?    | Yes / No                           |
| Specific timelines generalized?    | Yes / No                           |
| Unusual anecdotes generalized?     | Yes / No                           |
| Could the source recognize itself? | Low risk / Medium risk / High risk |
| Further anonymization needed?      | Yes / No                           |

## Fictionalized case draft

### Signal title

```txt
```

### One-line fictionalized observation

```txt
```

Example:

```txt
Several vendor-oriented sources describe agentic systems as a way to reduce manual handoffs across internal workflows, but provide limited evidence for review ownership, accountability or failure recovery.
```

### Fictionalized scenario

Write a realistic but non-identifying scenario.

```txt
```

Guidelines:

```txt
Use source archetypes.
Use realistic organizational language.
Do not imitate the original wording.
Do not preserve unique story structure.
Do not include real names or profile details.
Do not include copied post text.
Preserve the signal logic, not the source identity.
```

## Classification of fictionalized case

| Field                     | Entry                                                                                                                                      |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Source archetype          |                                                                                                                                            |
| Topic cluster             |                                                                                                                                            |
| Interest trigger          |                                                                                                                                            |
| Primary signal type       |                                                                                                                                            |
| Secondary signal type     |                                                                                                                                            |
| Maturity level            |                                                                                                                                            |
| Source diversity          | Single source archetype / Multiple similar source archetypes / Multiple distinct source archetypes / Cross-domain source pattern / Unknown |
| Missing source archetypes |                                                                                                                                            |
| Evidence status           | None / Anecdotal only / Partial / External evidence available / Needs expert review                                                        |
| Noise risk                | Low / Medium / High / Unknown                                                                                                              |
| Likely bias or agenda     | Commercial / Academic / Regulatory / Legal / Practitioner / Critical / Consultant framing / Media logic / Unknown                          |

## Evidence review

### Evidence summary

```txt
```

### Evidence gaps

```txt
```

### External evidence needed

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

Selected evidence needed:

```txt
```

## Organizational interpretation

### Organizational implication

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

Selected implication:

```txt
```

### Interpretation note

```txt
```

## Handoff questions

### Governance question

```txt
```

### Adoption question

```txt
```

### Content question

```txt
```

### Vendor evaluation question

```txt
```

## Recommended next action

Choose one or more:

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

Recommended next action:

```txt
```

Action rationale:

```txt
```

## Final fictionalized trend note block

Use this block when the case is ready to become an example.

```md
# LinkedIn Trend Note Example

## Metadata

Date captured:
[fictional date]

Review date:
[fictional review date]

Captured by:
[team / role]

Review owner:
[team / role]

## Observation

Signal title:

One-line observation:

Topic cluster:

Source archetype:

Source reference:
manual note only

Reference handling:
no direct post text stored

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
shareable fictionalized example

## AI-assisted processing

AI-assisted processing used:

AI input minimized:
yes

AI review needed:

## Fictionalization note

This example is fictionalized and archetype-based. It does not include real names, profile links, copied LinkedIn post text, screenshots, comments or reactions.
```

## Approval checklist

```txt
- [ ] The original post text was not copied into the repo.
- [ ] The original author is replaced by a source archetype.
- [ ] Names and profile links are removed.
- [ ] Company names are removed or fictionalized.
- [ ] Recognizable wording is removed.
- [ ] Unique anecdotes are generalized or replaced.
- [ ] Comments and reactions are not stored.
- [ ] Screenshots are not stored by default.
- [ ] The signal logic is preserved.
- [ ] Evidence status is defined.
- [ ] Next action is defined.
- [ ] Retention status is defined.
- [ ] Access level is defined.
- [ ] Traceability risk is low.
- [ ] The example is safe to share as fictionalized documentation.
```

## Final decision

Choose one:

```txt
approve as fictionalized example
needs further anonymization
keep as internal working note only
convert to evidence task
discard
delete original working note
```

Decision rationale:

```txt
```
