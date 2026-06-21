# Privacy-Aware Source Mapping

A method for building LinkedIn source maps without turning trend radar work into unnecessary personal-data collection, profiling or uncontrolled processing.

## Purpose

This document defines how teams, organizations, agencies or AI-assisted workflows can build source maps for LinkedIn-based trend radar work in a privacy-aware, data-minimizing and governance-conscious way.

The goal is to make LinkedIn useful as a professional signal environment without creating unnecessary risks around personal data, profiling, platform misuse, employee monitoring or uncontrolled AI processing.

This document should be read before building or operationalizing a LinkedIn source map.

## Core idea

A LinkedIn source map should help an organization understand which kinds of sources produce which kinds of signals.

It should not automatically become a database of people.

The safest and most reusable version of a source map starts with:

```
source archetypes
topic clusters
signal types
bias patterns
reliability criteria
evidence value
review cadence
non-identifying examples
```

A working source map may contain more specific references if the organization has a clear purpose, appropriate access controls, data minimization rules and review processes.

The method should be usable without exposing the underlying working dataset.

## Method documentation vs working data

A LinkedIn Trend Radar should separate the method from the working data.

The method describes:

- how sources are classified
- how signals are evaluated
- which fields are used
- which governance rules apply
- which risks must be reviewed
- how observations move into trend notes, governance questions or content workflows

The working data contains:

- actual source references
- signal observations
- saved links
- review notes
- source-map entries
- maturity assessments
- internal decisions
- handoff status

These layers should not be treated the same.

The method can often be shared, reused, audited or adapted more broadly.

The working data may require access control, minimization, retention rules, deletion logic and legal, privacy or compliance review, especially when it includes identifiable people, profile URLs, comments, reactions, employee observations or exported connection data.

A privacy-aware implementation should make the method reusable without exposing the underlying source map or signal records.

## Implementation layers

A source-mapping system can be implemented in different environments: local files, SharePoint, Confluence, Notion, GitHub, internal wikis, secure databases, approved AI workspaces or future agent-readable systems.

The important distinction is not the tool.

The important distinction is the layer.

| Layer | Purpose | Typical location | Privacy posture |
| --- | --- | --- | --- |
| Method documentation layer | Explains the workflow, criteria, templates and guardrails | Internal wiki, GitHub, SharePoint, Confluence, Notion, documentation system | Can be shared if it contains no real source records |
| Operational working layer | Stores actual source map entries, signal notes and review decisions | Local files, secure workspace, approved database, team knowledge base | Access-controlled and minimized |
| Evidence layer | Stores external sources used to verify LinkedIn-discovered signals | Research database, bookmarks, Zotero, knowledge base, approved AI research workspace | Prefer public external evidence over copied platform content |
| Governance layer | Documents permissions, review rules, retention, escalation and accountability | Policy documents, governance toolkit, risk register, compliance workspace | Should be reviewed by legal, privacy, security or compliance where relevant |
| Agent / automation layer | Supports classification, summarization or routing of approved inputs | Local AI, approved enterprise AI, controlled workflow system | Only use minimized and approved inputs |

This separation allows an organization to operationalize LinkedIn intelligence without exposing more data than necessary.

## Why this matters

LinkedIn is built around identifiable people, companies and professional interactions.

A source map can quickly become sensitive if it stores:

- names
- profile URLs
- job titles
- employer information
- opinions
- comments
- reactions
- inferred reliability scores
- source rankings
- network relationships
- exported connection data
- notes about behavior, views or influence

Even if the original information is visible on LinkedIn, copying, structuring, scoring, storing or processing it in another system may create new privacy, governance and trust questions.

The radar should therefore be designed around the minimum information needed to understand signals.

## Important note

This document is not legal advice.

It provides privacy-aware design principles for LinkedIn-based trend radar and intelligence work.

Organizations should involve legal, privacy, compliance, security, HR and works council stakeholders where appropriate, especially before using exported data, employee-submitted observations, named-person source maps, AI tools, shared databases or automated processing.

## Personal data caution

A LinkedIn connection export, profile-based source list or named-person source map may contain personal data.

Personal data is not limited to private information.

It can include information relating to an identified or identifiable person, including names, professional roles, online identifiers or combinations of attributes.

For this reason, a LinkedIn source map should not assume that information is risk-free simply because it was visible on a platform.

The question is not only:

> Can the organization see this?
> 

The better question is:

> Does the organization need to store, structure, analyze, score or share this?
> 

## Pseudonymization caution

Pseudonymization can reduce risk, but it does not automatically make data anonymous.

If a source ID can still be linked back to a person through another table, URL, note, context or organizational memory, the data should still be treated as potentially personal data.

Example:

```
Source A = identifiable person in a private lookup table
```

This may be acceptable in some controlled working environments, but it is not the same as anonymization.

Pseudonymized working data still needs purpose definition, access control, retention logic and review.

## Anonymization caution

Anonymization is stronger than pseudonymization, but it can be difficult to guarantee in professional contexts.

A person may remain identifiable through a combination of role, geography, employer, topic expertise or unique language.

A note like this may still be identifying:

```
A German AI governance lawyer at a specific institution repeatedly posts about EU AI Act risk categories.
```

A safer non-identifying version would be:

```
AI governance lawyer
→ posts about regulation and risk classification
→ useful for policy and compliance signals
```

When in doubt, reduce specificity.

## Source archetypes before named sources

The recommended default is to start with source archetypes.

A source archetype describes the kind of signal a source may provide without naming a person.

Example archetypes:

| Source archetype | What to watch | Typical risk |
| --- | --- | --- |
| AI security researcher | New threat patterns, prompt injection, agent failures | Highly technical or edge-case focused |
| AI governance lawyer | Regulation, liability, compliance language | Jurisdiction-specific complexity |
| Enterprise AI lead | Adoption reality, implementation lessons | Company-specific bias |
| Vendor founder | Product direction, market claims | Commercial bias |
| Critical AI voice | Blind spots, harms, ethical concerns | May overcorrect against hype |
| Public institution | Formal policy direction, guidance, standards | Slow signal |
| Cybersecurity practitioner | Practical attack surface, controls, tooling | Can be alarmist or niche |
| Internal communication leader | Employee expectations, adoption pressure | Less technical |
| Analyst or consultant | Framing, executive language, market packaging | May recycle buzzwords |
| Technical builder | Tool limits, implementation details, developer reality | May miss organizational context |

Source archetypes make the method reusable across teams, organizations and tools without requiring public or broadly shared lists of named individuals.

## Source identity vs source value

The source map should separate identity from value.

A source may be useful because of:

- topic expertise
- signal quality
- novelty
- evidence discipline
- practical implementation perspective
- critical perspective
- regulatory perspective
- vendor positioning value
- recurring language shifts
- access to early communities
- ability to reveal adoption pressure

A person does not need to be broadly identifiable for the source value to be understood.

In many cases, the organization only needs to know:

```
source archetype
topic cluster
signal type
bias pattern
evidence value
best use
```

This is often enough for trend radar work.

## Recommended method-layer fields

The method documentation layer should be non-identifying.

Recommended fields:

| Field | Purpose |
| --- | --- |
| Source archetype | Describes the kind of source without naming a person |
| Topic cluster | Shows which trend areas this archetype helps monitor |
| Signal type | Describes what kind of signal this archetype tends to produce |
| Evidence value | Indicates whether this archetype tends to point to evidence |
| Bias or agenda | Makes likely perspective visible |
| Noise risk | Helps avoid over-weighting certain source types |
| Best use | Explains how to use the source type in radar work |
| Review cadence | Defines how often to revisit this source category |

Example:

| Source archetype | Topic cluster | Signal type | Bias / agenda | Best use |
| --- | --- | --- | --- | --- |
| AI security researcher | AI security, agents | weak signal, expert debate, risk signal | technical risk focus | early warning, governance questions |
| Vendor founder | agents, RAG, automation | vendor push, product narrative | commercial | identify market claims and evaluation questions |
| Internal communication leader | adoption, leadership | operational pressure, expectation signal | organizational communication focus | detect employee-facing narratives |

## Recommended working-layer fields

A controlled working source map may include more detail, but it should still be minimized.

Recommended fields:

| Field | Purpose |
| --- | --- |
| Source archetype | Researcher, vendor, practitioner, regulator, critic, etc. |
| Source reference | Link or note, if necessary and approved |
| Topic clusters | AI security, governance, agents, RAG, adoption, etc. |
| Signal type | Weak signal, expert debate, vendor push, operational pressure, etc. |
| Evidence level | Primary, secondary, anecdotal, promotional, unknown |
| Bias / agenda | Commercial, academic, regulatory, activist, employer-branding, unknown |
| Signal value | Value for this radar use case |
| Novelty value | Does this source reveal early or unusual signals? |
| Translation value | Can this source help generate useful research, governance or content questions? |
| Noise risk | Low, medium or high |
| Best use | Watch, compare, challenge, cite, content idea, vendor question |
| Review cadence | Weekly, monthly, quarterly |
| Last reviewed | Date |
| Retention status | Keep, review, archive, delete |
| Notes | Minimal and factual |

If scoring is used, the score should refer to the value of the source for the radar use case, not to the worth, trustworthiness or reputation of a person.

Better:

```
Signal value for AI security radar: high
```

Avoid:

```
Person is trustworthy / untrustworthy
```

## Fields to avoid by default

Avoid fields such as:

```
political orientation
health information
religious affiliation
private life details
personal weaknesses
personality judgments
emotional state
family information
sensitive inferred attributes
network influence score
trustworthiness as a person
employee monitoring status
```

Also avoid turning the map into a hidden reputation database.

The source map should support signal interpretation, not personal evaluation.

## Minimal capture principle

When capturing a LinkedIn-based signal, use the minimum needed information.

Preferred minimal capture:

```
Date:
One-line observation:
Source archetype:
Topic cluster:
Signal type:
Interest trigger:
Maturity level:
External evidence needed:
Next action:
```

Avoid copying full post text unless there is a clear need and appropriate permission basis.

Avoid screenshots unless necessary.

Avoid storing comments or reactions by default.

Avoid bulk collection.

Avoid collecting data just because it is technically available.

## Working with exported LinkedIn data

LinkedIn allows users to export certain account data, including connection data, through its data download process.

However, the fact that data can be exported does not automatically mean it should be uploaded, shared, published, imported into a team system or processed by AI tools.

A connection export may include names, professional metadata and other personal data.

If an export is used at all, treat it as a controlled diagnostic input.

Recommended approach:

```
1. Download locally or into an approved controlled environment.
2. Do not upload raw exports to public repositories or shared systems by default.
3. Do not upload raw exports to cloud AI tools without review.
4. Inspect the fields before processing.
5. Extract only aggregate, non-identifying insights where possible.
6. Use the result to identify source mix gaps.
7. Avoid named-person scoring unless clearly necessary and reviewed.
8. Define retention, deletion or archival rules.
```

Better output from an export:

```
Source diversity insight:
- strong network in UX and communication
- weak network in AI security
- weak network in public institutions
- medium vendor exposure
```

Avoid output like:

```
Named list of first-degree contacts scored by radar value
```

## Source diversity gap analysis

A privacy-aware alternative to a named source map is a source diversity gap analysis.

Example:

| Source category | Current strength | Gap | Action |
| --- | --- | --- | --- |
| UX / product | high | no major gap | maintain |
| Internal communication | high | no major gap | maintain |
| AI security | low | missing technical risk sources | add source archetypes |
| AI governance law | low | missing legal interpretation | add governance sources |
| Public institutions | low | missing formal policy signal | add institutional sources |
| Vendor founders | medium | risk of commercial bias | balance with critics and practitioners |
| Technical builders | low | missing implementation reality | add builders |
| Critical voices | medium | useful counterweight | maintain balance |

This gives useful radar guidance without exposing a named-person database.

## AI-assisted use

An AI assistant may help classify source archetypes, signal types, maturity levels, interest triggers and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Safer AI inputs:

```
source archetypes
fictionalized examples
minimal signal notes
aggregated observations
external public evidence
non-identifying topic clusters
```

Higher-risk AI inputs:

```
raw connection exports
named source lists
profile URLs
copied post text
comments and reactions
employee observations involving third parties
person-level reliability scores
```

Before using AI, ask:

- Does the input contain personal data?
- Is the data necessary for the task?
- Can names, URLs or identifiers be removed?
- Can source archetypes be used instead?
- Is the AI tool approved for this type of data?
- Is there a data-processing agreement where needed?
- Is the input retained or used for training?
- Could the output expose or infer personal information?

## Shareable examples should be fictionalized

Examples used in documentation, training material, workshops or public explanations should be fictionalized or archetype-based.

Good example:

```
Source archetype:
AI security researcher

Signal:
Multiple technical posts discuss agent tool misuse and indirect prompt injection.

Maturity:
Expert debate

Possible handoff:
Governance question for agentic workflows.
```

Avoid example:

```
Real name:
[Named person]

Profile URL:
[LinkedIn URL]

Signal:
[Copied post text]
```

The method can be demonstrated without exposing the organization’s working source map or raw signal records.

## Privacy-aware source map workflow

Use this workflow:

```
1. Define radar purpose
2. Define topic clusters
3. Define source archetypes
4. Identify source gaps
5. Add specific sources only where necessary
6. Capture minimal source value
7. Avoid unnecessary identifiers
8. Use external evidence for validation
9. Define access, retention and review rules
10. Share only method, archetypes or fictionalized examples unless broader sharing is approved
```

## Review questions before creating a named source map

Before creating a source map with names or profile URLs, ask:

### Necessity

- Why are named sources needed?
- Can source archetypes achieve the same purpose?
- Can names remain local or access-controlled?
- Can aggregate source diversity be used instead?

### Purpose

- What is the purpose of the map?
- Is it personal learning, team intelligence, content planning, governance review or organizational monitoring?
- Is the purpose documented?
- Is the purpose proportionate to the data being stored?

### Data minimization

- What is the minimum information needed?
- Can profile URLs be avoided?
- Can copied post text be avoided?
- Can comments and reactions be excluded?
- Can observations be captured at pattern level instead of person level?

### Legal and governance review

- Does this involve personal data?
- Does this involve employees?
- Does this involve third parties?
- Does this require legal, privacy, compliance or works council review?
- Does this respect LinkedIn platform rules?
- Does this create profiling or monitoring risks?

### Storage

- Where will the map be stored?
- Who has access?
- Is it local, private, shared or organization-wide?
- What is the retention period?
- How will old records be deleted or archived?
- Who owns the review process?

### AI use

- Will the source map be uploaded to an AI tool?
- Can the input be minimized first?
- Are names and URLs necessary?
- Is the AI tool approved for this data?
- Will the AI output be reviewed by a human?

## Recommended storage levels

### Level 1: Method documentation

Use for:

```
source archetypes
fictionalized examples
templates
method notes
guardrails
generic workflows
```

Avoid:

```
real source names
profile URLs
connection exports
screenshots
copied posts
comments
private notes
```

### Level 2: Personal or small-team working layer

May include:

```
minimal notes
manually saved links
source archetype tags
topic clusters
review status
```

Use caution with:

```
raw exports
named profiles
AI uploads
bulk links
person-level scoring
```

### Level 3: Shared team or departmental system

Requires stronger rules:

```
access control
purpose definition
minimal fields
retention rules
review owner
legal/privacy review where needed
no unnecessary personal data
```

### Level 4: Organization-ready system

Requires formal governance:

```
documented legal basis
platform-policy review
privacy impact review where appropriate
works council review where appropriate
approved tools
role-based access
retention and deletion logic
incident handling
AI tool governance
```

## What can usually be documented broadly

The following can usually be documented more broadly if no real source records are included:

- source archetype models
- source classification logic
- signal type definitions
- privacy-aware templates
- fictionalized examples
- aggregate source diversity models
- feed curation method
- governance guardrails
- external evidence workflow

## What should stay controlled

The following should usually remain local, private or access-controlled unless reviewed and approved:

- real source lists
- named source scores
- profile URLs
- exported connection data
- copied LinkedIn posts
- screenshots of people’s posts
- comments and reactions
- private source notes
- employee-submitted observations involving identifiable third parties
- internal review notes
- source reliability assessments tied to named people

## Connection to the LinkedIn Source Map

The `linkedin-source-map.md` document should implement the principles defined here.

It should include:

```
source map structure
working-layer fields
source archetype table
source value criteria
bias and reliability criteria
fictionalized examples
review cadence
```

It should not become a broadly shared people database.

## Connection to the broader intelligence system

Privacy-aware source mapping supports the full signal-to-action cycle:

```
Trend radar
→ governance question
→ adoption implication
→ content or communication action
```

A privacy-aware source map can feed:

| Area | Use |
| --- | --- |
| Trend radar | Identify weak signals and source gaps |
| Governance | Surface privacy, vendor, risk or accountability questions |
| Adoption | Detect operational pressure or adoption posture |
| Content strategy | Identify content needs and audience signals |
| Publication bridge | Inform public content only after review and evidence checks |

## Working principle

The goal is to understand signals.

A good source map helps the radar see better.

A bad source map becomes a risky people database.

A privacy-aware LinkedIn Trend Radar should therefore start with:

```
source archetypes
minimal observations
privacy-aware fields
external evidence
human review
controlled working data
fictionalized shareable examples
```
