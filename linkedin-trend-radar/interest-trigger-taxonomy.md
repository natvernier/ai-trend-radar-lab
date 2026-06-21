# Interest Trigger Taxonomy

A classification system for identifying why a LinkedIn-based observation was noticed, saved or routed into trend radar work.

## Purpose

This document defines a reusable taxonomy for classifying the reason an observation entered the LinkedIn Trend Radar.

The interest trigger captures what made a post, discussion, phrase, source pattern or external reference worth noticing.

It helps teams, organizations, agencies and AI-assisted workflows distinguish between:

```txt id="sbo7vv"
why something caught attention
why it may matter as a signal
what evidence is available
what action should follow
```

These are related, but they are not the same.

A post can be inspiring without being strategically relevant.

A signal can be important without being emotionally engaging.

A vendor claim can be useful for market narrative tracking without being evidence of real adoption.

The interest trigger taxonomy makes this distinction explicit.

## Core idea

The first reason a signal enters a radar is often human attention.

Someone notices something because it feels new, useful, irritating, elegant, risky, repeated, practical, emotionally charged or strategically relevant.

That initial attention should be captured, but not overinterpreted.

The interest trigger answers:

> What made this worth capturing?

It does not answer:

> Is this trend real?

That requires source classification, signal detection, maturity assessment and evidence review.

## What this taxonomy is

This taxonomy is:

* a classification layer for human attention
* a bridge between observation and signal detection
* a support tool for trend notes
* a way to distinguish analytical value from editorial value
* a way to capture why a signal may become content later
* a way to identify source discovery and evidence leads
* a reusable structure for teams and AI-assisted workflows

## What this taxonomy is not

This taxonomy is not:

* evidence assessment
* sentiment analysis by default
* maturity classification
* content scoring
* a popularity score
* a personal preference log
* a replacement for external evidence
* a replacement for governance or adoption review

The interest trigger should be used as one field in the signal workflow, not as the main basis for action.

## Relationship to other module documents

This taxonomy connects to:

```txt id="92qf1t"
linkedin-feed-as-radar.md
source-discovery-workflow.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
external-evidence-layer.md
```

Recommended placement in the workflow:

```txt id="0b84su"
observation
→ interest trigger
→ source archetype
→ signal type
→ maturity level
→ evidence status
→ organizational implication
→ next action
```

## Why interest triggers matter

Interest triggers matter because trend radar work is not purely mechanical.

Teams often capture observations because something feels:

* new
* repeated
* useful
* risky
* surprising
* annoying
* clarifying
* strategically relevant
* emotionally resonant
* operationally relevant
* suitable for content or explanation

If these reasons are not captured, useful context is lost.

If they are over-weighted, the radar may confuse attention with importance.

The taxonomy helps preserve the initial reason for capture while keeping later review structured.

## Interest trigger vs signal type

Interest trigger and signal type should be separate fields.

| Field            | Question                                | Example                      |
| ---------------- | --------------------------------------- | ---------------------------- |
| Interest trigger | Why was this noticed?                   | Strong framing               |
| Signal type      | What kind of signal may this represent? | Management hype              |
| Maturity level   | How mature is the trend?                | 6. Management hype           |
| Evidence status  | How well is it supported?               | Needs external evidence      |
| Next action      | What should happen next?                | Content idea + evidence task |

Example:

```txt id="r3zsrg"
Interest trigger:
Strong framing

Signal type:
Vendor push

Maturity level:
5. Vendor push

Evidence status:
Partial

Next action:
Vendor evaluation question + external evidence task
```

The trigger explains attention.

The other fields determine interpretation and action.

## Trigger categories

The taxonomy uses the following primary trigger categories.

| Trigger             | Use when the observation was captured because it...                                        |
| ------------------- | ------------------------------------------------------------------------------------------ |
| New concept         | Introduces a term, model, capability or issue not previously tracked                       |
| Repeated signal     | Confirms something observed elsewhere                                                      |
| Strong framing      | Provides a useful way to explain or structure a topic                                      |
| Contrarian angle    | Challenges a dominant narrative or expectation                                             |
| Practical example   | Shows implementation, use, failure, workflow or operational detail                         |
| Risk signal         | Reveals a possible failure mode, liability issue, security risk or blind spot              |
| Vendor claim        | Shows how vendors position a topic, product, category or market promise                    |
| Leadership pressure | Indicates executive urgency, simplified mandates or management expectation                 |
| Adoption friction   | Shows where implementation may get stuck                                                   |
| Language shift      | Reveals new wording, metaphors, categories or discourse patterns                           |
| Emotional resonance | Indicates professional tension, inspiration, anxiety, humor or audience reaction           |
| Content inspiration | Could become an explainer, briefing, article, post, carousel, FAQ or training asset        |
| Source discovery    | Leads to another useful source archetype, institution, expert, community or evidence trail |
| Evidence lead       | Points to a paper, report, regulation, standard, documentation or external source          |
| Governance cue      | Suggests a need for policy, review, control, accountability or escalation                  |
| Culture cue         | Reveals organizational norms, resistance, expectations or social dynamics                  |
| Format pattern      | Reveals a repeatable communication format, narrative structure or content style            |
| Reputation cue      | Indicates public perception, brand risk, trust issue or stakeholder concern                |

Organizations can adapt this list to their radar purpose.

## Trigger category details

### New concept

Use when the observation introduces a concept, term, model or capability that is not yet part of the radar vocabulary.

Examples:

```txt id="81vxxl"
agentic workflow governance
synthetic knowledge worker
AI-native operating model
model behavior monitoring
prompt injection surface
```

Typical next actions:

```txt id="bzj0kk"
technical literacy note
source discovery
external evidence task
watchlist
```

Review questions:

* Is this a genuinely new concept or a renamed existing idea?
* Which source archetype introduced it?
* Is it used by multiple source types?
* Does it require a terminology note?
* Does it need external evidence before being used?

### Repeated signal

Use when the observation confirms something seen before.

Examples:

```txt id="9zjppp"
multiple practitioners describe the same RAG quality problem
several vendors use the same agent narrative
different sources mention the same governance concern
```

Typical next actions:

```txt id="6xkc3d"
trend note
source diversity review
maturity reassessment
external evidence task
```

Review questions:

* How often has this appeared?
* Which source archetypes repeat it?
* Is repetition caused by real movement or repost dynamics?
* Does the maturity level need to change?

### Strong framing

Use when the observation offers a useful way to explain a topic.

Examples:

```txt id="6pttk9"
a simple distinction between automation and delegation
a useful metaphor for AI governance
a clear explanation of RAG failure modes
a concise definition of human oversight
```

Typical next actions:

```txt id="p0epl4"
content idea
briefing input
terminology note
communication question
```

Review questions:

* Is the framing accurate?
* Is it oversimplified?
* Does it need evidence?
* Could it help internal communication or leadership alignment?

### Contrarian angle

Use when the observation challenges a dominant narrative.

Examples:

```txt id="hjtspi"
agents are not autonomous enough to govern like employees
AI adoption is slowed by unclear ownership, not user resistance
open-source AI may increase governance complexity instead of reducing it
```

Typical next actions:

```txt id="b24m5s"
watchlist
expert review
content idea
governance question
evidence task
```

Review questions:

* What dominant assumption does this challenge?
* Is the argument evidence-based?
* Which source types support or oppose it?
* Is this useful friction or low-value provocation?

### Practical example

Use when the observation shows implementation detail, a workflow, a case, a failure, an operational workaround or a real use pattern.

Examples:

```txt id="0chhdq"
a team describes how it reviews AI-generated reports
a company shares lessons from deploying an internal chatbot
a practitioner explains why a workflow broke after automation
```

Typical next actions:

```txt id="2sjgbz"
trend note
adoption question
governance question
case example
external evidence task
```

Review questions:

* What exactly was implemented?
* What context matters?
* Is the example transferable?
* Which operating-model question does it raise?

### Risk signal

Use when the observation points to a risk, failure mode, blind spot or control requirement.

Examples:

```txt id="nbfqlo"
agent tool access creates security exposure
employees use unapproved AI tools for confidential work
AI-generated answers appear without source review
vendors overstate automation reliability
```

Typical next actions:

```txt id="dxryu5"
governance question
security review
privacy review
external evidence task
vendor evaluation question
```

Review questions:

* What risk category is involved?
* Is the risk technical, legal, operational, cultural or reputational?
* Is external evidence available?
* Does this require escalation?

### Vendor claim

Use when the observation is mainly valuable because it reveals how vendors are positioning a topic.

Examples:

```txt id="9w7jzw"
autonomous agents will replace workflow coordination
AI copilots will eliminate documentation work
RAG platform claims enterprise knowledge accuracy
```

Typical next actions:

```txt id="i1a3mc"
vendor evaluation question
external evidence task
source diversity review
market narrative tracking
```

Review questions:

* What is being claimed?
* What evidence is provided?
* Which assumptions are hidden?
* What would need to be tested?
* Is this vendor push or validated adoption?

### Leadership pressure

Use when the observation reveals management urgency, simplified mandates or executive expectation.

Examples:

```txt id="zjvffn"
leaders ask why the organization is not using agents yet
executives frame AI adoption as speed race
management expects productivity gains without workflow redesign
```

Typical next actions:

```txt id="ggiczw"
adoption question
leadership briefing
governance question
content idea
```

Review questions:

* What expectation is being created?
* Is the expectation operationally realistic?
* Which teams may feel pressure?
* Does governance need to respond?

### Adoption friction

Use when the observation reveals where implementation may get stuck.

Examples:

```txt id="t8acxs"
unclear role ownership
insufficient review routines
low trust in outputs
knowledge-base quality issues
tool access restrictions
works council uncertainty
lack of training
```

Typical next actions:

```txt id="g8szrv"
adoption question
workflow review
operating-model note
content explainer
governance question
```

Review questions:

* What friction is visible?
* Which workflow or role is affected?
* Is the friction technical, organizational, cultural or governance-related?
* Does this connect to an adoption KPI or signal?

### Language shift

Use when the observation shows new words, metaphors, phrases or categories entering professional discourse.

Examples:

```txt id="b82osd"
AI workforce
agentic organization
sovereign AI stack
human-in-the-loop governance
model risk ownership
```

Typical next actions:

```txt id="0cr5lv"
terminology note
trend note
content idea
source monitoring
management hype review
```

Review questions:

* Who uses the language?
* Is it vendor-led, expert-led, management-led or regulator-led?
* Does the wording clarify or obscure the topic?
* Does it indicate maturity movement?

### Emotional resonance

Use when the observation triggers strong professional reaction, enthusiasm, anxiety, frustration, humor or tension.

Examples:

```txt id="jn9jw5"
employees express anxiety about AI replacement
professionals celebrate a new tool as a breakthrough
comment threads show frustration with unrealistic AI expectations
humor reveals a common workplace tension
```

Typical next actions:

```txt id="0453am"
content idea
culture cue
communication question
watchlist
reputation review
```

Review questions:

* What reaction is visible?
* Is it isolated or repeated?
* Does it reveal expectation, anxiety or misunderstanding?
* Does it require internal communication?

### Content inspiration

Use when the observation could become a useful content format, explanation, post, carousel, FAQ, briefing or training asset.

Examples:

```txt id="ge78lp"
a clear misconception that needs correction
a strong analogy for governance
a recurring question that could become FAQ
a topic suitable for a slider or internal explainer
```

Typical next actions:

```txt id="1ad1gq"
content idea
publication bridge
briefing outline
FAQ
explainer
```

Review questions:

* Is the content idea evidence-supported?
* Is the topic mature enough for publication?
* Does it need governance or legal review?
* Is it internal, external or both?

### Source discovery

Use when the observation leads to another relevant source category, institution, community or evidence path.

Examples:

```txt id="k5y995"
a post references a research lab
a comment mentions a standard
a practitioner points to a niche community
a conference speaker list reveals missing source archetypes
```

Typical next actions:

```txt id="x3hp5d"
source map update
source discovery task
external evidence task
```

Review questions:

* What source type was discovered?
* Does it fill a source gap?
* Is it necessary to store a reference?
* Can the source be captured as an archetype?

### Evidence lead

Use when the observation points to external material that can verify or contextualize the signal.

Examples:

```txt id="9v0x58"
paper
regulation
standard
security report
vendor documentation
case study
official guidance
technical repository
```

Typical next actions:

```txt id="rd17xq"
external evidence task
trend note
governance question
technical literacy note
```

Review questions:

* What evidence is available?
* Is it primary or secondary?
* Is it current?
* Is it relevant to the organization’s context?
* Does it confirm or weaken the signal?

### Governance cue

Use when the observation suggests a need for policy, review, control, accountability or escalation.

Examples:

```txt id="6ks8r7"
unclear responsibility for AI outputs
need for human review
tool access and permission concerns
data exposure risk
vendor claim requiring evaluation
```

Typical next actions:

```txt id="dinppb"
governance question
risk review
vendor evaluation
security review
privacy review
```

Review questions:

* Which governance area is affected?
* Is the signal specific enough to review?
* Is evidence available?
* Who would own the next decision?

### Culture cue

Use when the observation reveals norms, resistance, expectations, trust issues or behavioral patterns.

Examples:

```txt id="a2r1ae"
employees quietly using AI tools before policy exists
leaders demanding AI adoption without operating support
professionals mocking unrealistic productivity claims
people framing governance as bureaucracy
```

Typical next actions:

```txt id="wbmtko"
adoption question
communication question
leadership briefing
content idea
culture review
```

Review questions:

* What behavior or expectation is visible?
* Does this affect adoption readiness?
* Is this internal, external or both?
* Does it require communication or operating-model work?

### Format pattern

Use when the observation reveals a repeatable communication format, narrative structure or content pattern.

Examples:

```txt id="5c6a9x"
before / after AI workflow posts
myth vs reality posts
AI maturity matrices
agent capability carousels
regulation explainer threads
```

Typical next actions:

```txt id="c40k7l"
content format idea
publication bridge
pattern library update
content evaluation
```

Review questions:

* Does the format clarify or oversimplify?
* Is it useful for the intended audience?
* Can it support internal or external communication?
* Does it need evidence or governance review?

### Reputation cue

Use when the observation may indicate public perception, trust risk, brand risk or stakeholder concern.

Examples:

```txt id="cn5jug"
public criticism of AI use in customer service
concerns about automation and job loss
vendor controversy
privacy concern around AI tools
negative reaction to corporate AI messaging
```

Typical next actions:

```txt id="izqlo0"
reputation review
governance question
content question
leadership briefing
external evidence task
```

Review questions:

* Which stakeholder group may be affected?
* Is the concern repeated or isolated?
* Does this create reputational risk?
* Does it require internal alignment before communication?

## Primary vs secondary trigger

A trend note can contain a primary and secondary interest trigger.

Example:

```txt id="j6kjdj"
Primary trigger:
Risk signal

Secondary trigger:
Evidence lead
```

Another example:

```txt id="bz9zp3"
Primary trigger:
Strong framing

Secondary trigger:
Content inspiration
```

Use a secondary trigger only when it adds operational value.

Avoid over-classifying.

## Trigger-to-action map

The trigger can suggest possible next actions, but should not determine them alone.

| Interest trigger    | Possible next action                       |
| ------------------- | ------------------------------------------ |
| New concept         | terminology note, watchlist, evidence task |
| Repeated signal     | trend note, maturity reassessment          |
| Strong framing      | content idea, briefing input               |
| Contrarian angle    | evidence task, expert review               |
| Practical example   | adoption question, case note               |
| Risk signal         | governance question, security review       |
| Vendor claim        | vendor evaluation question                 |
| Leadership pressure | adoption question, leadership briefing     |
| Adoption friction   | workflow review, adoption note             |
| Language shift      | terminology note, trend note               |
| Emotional resonance | communication question, culture cue        |
| Content inspiration | content idea, publication bridge           |
| Source discovery    | source map update                          |
| Evidence lead       | external evidence task                     |
| Governance cue      | governance workflow                        |
| Culture cue         | adoption or communication review           |
| Format pattern      | content pattern library                    |
| Reputation cue      | reputation or governance review            |

The final action should also consider evidence status, maturity level, source diversity and organizational implication.

## Trigger quality criteria

Before keeping an interest trigger, review:

| Criterion       | Question                                                        |
| --------------- | --------------------------------------------------------------- |
| Specificity     | Is the reason for capture clear?                                |
| Relevance       | Does the trigger relate to the radar purpose?                   |
| Actionability   | Does the trigger help define a next step?                       |
| Evidence need   | Does it require external evidence before use?                   |
| Source context  | Which source archetype produced the trigger?                    |
| Proportionality | Is continued tracking justified?                                |
| Retention       | Should this observation be kept, reviewed, archived or deleted? |

A trigger should help interpret the observation.

If it does not affect classification, review or next action, it may not need to be recorded.

## Trigger combinations

Some combinations are especially useful.

| Trigger combination                     | Possible interpretation              |
| --------------------------------------- | ------------------------------------ |
| Repeated signal + practical example     | possible emerging pattern            |
| Vendor claim + language shift           | vendor-led category creation         |
| Risk signal + evidence lead             | governance-relevant signal           |
| Leadership pressure + adoption friction | operational pressure                 |
| Strong framing + content inspiration    | communication opportunity            |
| Contrarian angle + expert debate        | issue needs deeper review            |
| Emotional resonance + culture cue       | possible expectation or trust issue  |
| Source discovery + evidence lead        | source map and evidence layer update |

Trigger combinations should support review, not replace it.

## Trigger misuse patterns

Avoid using interest triggers as shortcuts.

| Misuse                                           | Why it creates risk                                   |
| ------------------------------------------------ | ----------------------------------------------------- |
| Treating emotional resonance as evidence         | Strong reaction does not prove trend relevance        |
| Treating content inspiration as maturity         | A good post idea may still be based on weak evidence  |
| Treating vendor claim as market validation       | Commercial positioning needs external review          |
| Treating repeated signal as proof                | Repetition may come from repost chains or shared hype |
| Treating contrarian angle as insight             | Provocation needs evidence and context                |
| Treating strong framing as accuracy              | Elegant language may oversimplify                     |
| Treating source discovery as permission to store | New sources still require minimization and review     |

## Working fields

Recommended fields for operational use:

| Field                      | Purpose                                                         |
| -------------------------- | --------------------------------------------------------------- |
| Primary interest trigger   | Main reason the observation was captured                        |
| Secondary interest trigger | Optional supporting reason                                      |
| Trigger note               | Short explanation                                               |
| Related source archetype   | Type of source that produced the trigger                        |
| Related signal type        | Signal classification                                           |
| Evidence need              | Whether the trigger requires external evidence                  |
| Possible next action       | Watchlist, trend note, evidence task, governance question, etc. |
| Retention status           | Keep, review, archive or delete                                 |

Example:

```md id="eft8q0"
Primary interest trigger:
Vendor claim

Secondary interest trigger:
Language shift

Trigger note:
Several vendors describe agents as digital coworkers rather than workflow automation tools.

Related source archetype:
vendor founder, product marketer

Related signal type:
vendor push

Evidence need:
external evidence needed

Possible next action:
vendor evaluation question

Retention status:
review
```

## AI-assisted use

An AI assistant may help classify interest triggers, source archetypes, signal types, maturity levels and next actions if the input has already been minimized and approved.

The AI assistant should not request, infer or store unnecessary personal data.

The AI assistant should work from source archetypes, minimal signal notes and external evidence whenever possible.

Useful AI-assisted tasks include:

* suggesting an interest trigger from a minimal observation
* distinguishing interest trigger from signal type
* identifying possible trigger combinations
* suggesting next actions based on trigger, signal type and maturity
* identifying when a trigger needs external evidence
* clustering observations by trigger category
* detecting overuse of certain triggers in the radar workflow

Avoid using AI for:

* processing raw connection exports without review
* extracting posts or comments at scale
* profiling named individuals
* inferring sensitive attributes
* ranking people by influence or trustworthiness
* storing unnecessary identifiers
* turning emotional reactions into personal evaluation

## Example 1: Strong framing vs evidence

### Observation

A post explains AI governance as “decision rights for machine-supported work.”

### Classification

| Field                | Value                           |
| -------------------- | ------------------------------- |
| Primary trigger      | Strong framing                  |
| Secondary trigger    | Content inspiration             |
| Source archetype     | governance consultant / analyst |
| Signal type          | language shift                  |
| Evidence need        | medium                          |
| Possible next action | terminology note + content idea |

### Review note

The framing may be useful for communication, but it should be checked against governance and accountability models before being used in formal material.

## Example 2: Vendor claim as market signal

### Observation

Several vendors describe autonomous agents as a way to replace workflow coordination.

### Classification

| Field                | Value                                               |
| -------------------- | --------------------------------------------------- |
| Primary trigger      | Vendor claim                                        |
| Secondary trigger    | Language shift                                      |
| Source archetype     | vendor founder / product marketer                   |
| Signal type          | vendor push                                         |
| Evidence need        | high                                                |
| Possible next action | vendor evaluation question + external evidence task |

### Review note

The signal is useful for tracking market narratives. It is not sufficient as implementation evidence.

## Example 3: Adoption friction

### Observation

Practitioners describe difficulties maintaining knowledge bases for RAG systems.

### Classification

| Field                | Value                                   |
| -------------------- | --------------------------------------- |
| Primary trigger      | Adoption friction                       |
| Secondary trigger    | Practical example                       |
| Source archetype     | enterprise AI lead / product owner      |
| Signal type          | operational pressure                    |
| Evidence need        | medium                                  |
| Possible next action | adoption question + governance question |

### Review note

The trigger indicates implementation relevance. The next review should clarify ownership, maintenance and review routines.

## Example 4: Emotional resonance

### Observation

A discussion about AI replacing junior roles produces strong reactions from employees, managers and recruiters.

### Classification

| Field                | Value                                                            |
| -------------------- | ---------------------------------------------------------------- |
| Primary trigger      | Emotional resonance                                              |
| Secondary trigger    | Culture cue                                                      |
| Source archetype     | HR leader / employee voice / executive voice                     |
| Signal type          | management hype or operational pressure, depending on repetition |
| Evidence need        | medium                                                           |
| Possible next action | culture review + communication question                          |

### Review note

The strong reaction may indicate expectation or trust issues. It should not be treated as evidence of actual workforce change without external support.

## Review checklist

Before using an interest trigger in a trend note, check:

```txt id="2rb4qy"
Is the trigger specific?
Is the trigger separate from signal type?
Is the trigger separate from evidence status?
Is the source archetype known?
Does the trigger support a next action?
Does the trigger require external evidence?
Is the observation minimized?
Is retention necessary and proportionate?
Is access appropriate for the working record?
Are AI-assisted steps limited to minimized and approved inputs?
```

## Related module documents

```txt id="l9p71k"
linkedin-feed-as-radar.md
source-discovery-workflow.md
linkedin-source-map.md
source-classification.md
feed-noise-reduction.md
signal-detection-workflow.md
linkedin-trend-note-template.md
linkedin-radar-review-routine.md
post-patterns-to-watch.md
external-evidence-layer.md
```

## Working principle

Interest triggers explain why an observation entered the radar.

They should preserve useful context for human sensemaking while remaining separate from signal classification, maturity assessment, evidence review and next-action decisions.
