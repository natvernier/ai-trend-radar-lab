# Example: agent risk signal

**Status:** Filled example, fictionalized
**Template:** [`linkedin-trend-note-template.md`](../linkedin-trend-note-template.md)
**Built with:** [`fictionalized-transform-template.md`](../experiments/fictionalized-transform-template.md)

This note is not based on one post. It rebuilds a pattern from several observations as an archetype case. No authors, companies, wording or dates from real posts are used.

# LinkedIn Trend Note

## Metadata

Date captured: week 1 (example)
Review date: week 5 (example)
Captured by: radar owner
Review owner: AI governance contact

## Observation

Signal title: Agent permissions moving from a technical detail to an ownership question

One-line observation: Several practitioners describe AI agents in internal tools that can send messages, edit documents or book meetings, and nobody in their organisation can say who approved those permissions.

Topic cluster: AI agents, permissions, internal tools

Source archetype: enterprise AI lead; cybersecurity practitioner; internal communication leader

Source reference: none stored (fictionalized pattern)

Reference handling: no links, names or screenshots kept; pattern described in own words

## Classification

Interest trigger: risk plus everyday relevance. The examples come from ordinary office tools, not from labs.

Primary signal type: Expert debate

Secondary signal type: Operational pressure

Maturity level: 3. Expert debate

Maturity rationale: Security and governance practitioners discuss the risk openly and give concrete examples. Vendors mention agent permissions mostly as a feature, and there is little published guidance yet. Teams already report pressure to switch agents on.

Source diversity: multiple distinct source archetypes

Missing source archetypes: public institution; standards body; HR or learning leader

## Evidence

Evidence status: partial

Evidence summary: The practitioner examples describe the same structure: an agent inherits the user's access rights, acts in several systems, and its actions are logged as the user's actions.

Evidence gaps: no figures on how common this is; no vendor documentation reviewed yet; no guidance from regulators or standards bodies found yet.

External evidence links: none yet

External evidence needed: vendor documentation on agent permissions and logging for the tools in use; current security guidance on AI agents; the organisation's own access-rights policy.

## Interpretation

Likely bias or agenda: security practitioners may overweight the risk; enterprise AI leads may underweight it because they are measured on rollout speed.

Interpretation note: The useful part of the signal is not "agents are risky". It is the gap in ownership: permissions are granted per user, while the agent acts across systems and teams.

Noise risk: medium

Organizational implication: Before agents get write access in internal tools, someone has to own the permission decision and the review of what agents did.

## Questions

Governance question: Who approves an agent's permissions, and is that recorded in a decision log?

Adoption question: Do teams know which agent actions need a human confirmation before they happen?

Content question: Would a short internal explainer ("what your assistant can do on your behalf") reduce uncertainty?

Vendor evaluation question: Can agent actions be logged separately from the user's own actions, and can permissions be limited per action?

## Action

Recommended next action: governance question

Action rationale: The ownership gap can be checked inside the organisation now, without waiting for more external evidence. The external evidence task runs in parallel.

Review status: needs evidence

Retention status: review

Retention rationale: The signal is time-sensitive; check again at the review date and archive if nothing new appears.

Access level: shareable fictionalized example

## AI-assisted processing

AI-assisted processing used: yes, for structuring the note from own notes

AI input minimized: yes; no post texts, names or links were given to the AI tool

AI review needed: yes; the radar owner checked classification and wording
