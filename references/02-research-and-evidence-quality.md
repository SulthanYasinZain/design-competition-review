# User Research and Evidence Quality Audit

## 1. Purpose

Evaluate whether the project understands a real problem experienced by the intended users and whether its proposed design decisions are supported by credible evidence. The evaluator must distinguish exploratory research from representative research, stakeholder opinion from observed behavior, and a user quote from a validated pattern.

## 2. Research foundation

Start by identifying the decisions research is expected to inform:

- selection of the target user;
- definition of the core problem;
- prioritization of user needs;
- choice of product concept;
- feature prioritization;
- interaction and accessibility requirements;
- success criteria for testing.

If research does not influence any decision, question why it was conducted or why its outputs are not visible.

## 3. Research inventory

Inventory each method separately:

| Method | What it can reveal | Evidence to inspect |
|---|---|---|
| Desk research | Existing facts, context, prior studies, regulations | Source quality, date, population, method, original publication |
| Survey | Self-reported patterns and preferences | Instrument, sample, response counts, question wording, distribution |
| Interview | Motivation, context, detailed experiences | Interview guide, participant context, notes/transcripts, coding |
| Observation | Actual behavior and environmental constraints | Setting, task, observation protocol, researcher notes |
| Diary study | Experience across time | Duration, prompts, participant completion, synthesis |
| Co-design/workshop | Ideas and reactions from participants | Participant roles, activities, outputs, facilitation notes |
| Usability test | Ability to use a design for specified tasks | Prototype version, tasks, participants, metrics, recordings, findings |
| Accessibility evaluation | Conformance or usability with accessibility needs | Test method, standard/version, devices, assistive technology, findings |

Do not assume a method was conducted merely because it is listed in a process diagram.

## 4. Research question quality

Inspect survey/interview questions for:

- leading wording;
- double-barrelled questions;
- ambiguous terms;
- response options that force an answer;
- unclear time frames;
- mixing frequency with severity;
- asking respondents to predict behavior rather than describe past behavior;
- asking non-experts to assess technical accessibility they may not understand;
- collecting sensitive information without a clear purpose and consent.

A question such as “Would you use this innovative and helpful application?” is leading. Better questions ask about the user's recent behavior, workarounds, failures, and decision criteria before introducing the proposed solution.

## 5. Sampling and participant fit

Do not apply one universal sample-size rule. Evaluate whether the sample is appropriate for the purpose and claims.

### 5.1 Exploratory research

A small sample can be useful to discover early patterns, especially with a hard-to-reach population. Label it as exploratory. Avoid presenting percentages from a very small sample as population prevalence.

### 5.2 Survey interpretation

For every percentage, show:

- numerator and denominator;
- question wording;
- response options or threshold used;
- whether responses were single-select or multi-select;
- how missing responses were handled;
- the exact participant group.

For example, “4 of 5 respondents (80%) in our exploratory sample” is more honest than “80% of people with disabilities”.

### 5.3 Segment fit

Record whether participants match the target population in terms relevant to the design:

- user role;
- age/life stage, when relevant;
- experience level;
- device/platform familiarity;
- disability or accessibility needs, when relevant and consented;
- geographic/contextual constraints;
- frequency of the task/problem;
- whether they are a primary user or supporting stakeholder.

Do not assume all users in a broad category have identical needs. “People with disabilities”, “children”, “older adults”, “teachers”, or “small businesses” are not homogeneous segments.

### 5.4 Stakeholder versus primary user

A project may include several stakeholder groups, but this does not mean all are direct users of the same prototype. Identify:

- primary users who perform the main tasks;
- secondary users with separate interfaces or tasks;
- beneficiaries affected by the service;
- operational stakeholders who must deliver the service;
- decision-makers or gatekeepers.

Do not conflate an HR representative surveyed about needs with an HR user who has tested a dashboard that does not exist in the prototype.

## 6. Research data integrity

Check:

- duplicate responses;
- missing values;
- inconsistent denominators;
- mismatched figures between the report and appendix;
- qualitative comments quoted without consent or attribution rules;
- charts whose axis or categories are misleading;
- percentages that do not add up because of multi-select options;
- selective reporting of favorable responses;
- data copied from secondary sources but described as primary research.

For small samples, raw counts are often more useful than percentages alone.

## 7. Synthesis quality

A finding is not the same as a raw data point. Inspect the synthesis chain:

1. Raw observation/response.
2. Pattern across participants.
3. Insight explaining why the pattern matters.
4. User need or unmet need.
5. Design implication.

Example structure:

- **Evidence:** 4/5 participants said they rarely found accessibility information on vacancy platforms.
- **Pattern:** Accessibility information is difficult to locate before applying.
- **Insight:** Users may spend time applying to workplaces that cannot meet their basic access needs.
- **Need:** Users need comparable, understandable accessibility information before deciding to apply.
- **Design implication:** Show clear accessibility attributes in listing and detail screens; provide filters tied to user needs.

Do not convert correlation into causation. Do not infer emotional states from a survey unless participants expressed them or the study method supports the interpretation.

## 8. Persona audit

A useful persona should include:

- role and context;
- relevant goals;
- tasks and motivations;
- pain points;
- needs;
- constraints and environment;
- technology/assistive needs where relevant;
- evidence links to participant data;
- confidence level and assumptions.

Ask:

- Is this persona based on research or entirely invented?
- Does it represent a meaningful pattern or one individual?
- Are demographic details relevant to design decisions?
- Are goals and pain points distinct from generic product feature requests?
- Does the persona include constraints that affect flow and accessibility?
- Does the team use it later, or is it decorative?

A persona is not improved by adding more biographical detail that has no design consequence.

## 9. Statistics and desk-research audit

For every external statistic verify:

- original source;
- publication date and data-collection year;
- geographic scope;
- target population and definitions;
- unit and denominator;
- whether the source is primary, secondary, or media reporting;
- whether the claim in the report accurately represents the source.

Do not blend data from different populations or years into one implied statistic. If the source measures “persons with disabilities employed” and another estimates “population living with disability”, do not multiply or subtract them unless the methodologies are compatible.

For medical, psychological, educational, and accessibility claims, seek authoritative primary or review sources. Be especially cautious with claims that a particular font, color, game, or interface “treats”, “prevents”, or clinically improves a condition.

## 10. Research limitations and honest framing

A high-quality submission acknowledges limitations that affect interpretation:

- small or convenience sample;
- geographic concentration;
- under-representation of a disability group;
- self-reported rather than observed behavior;
- prototype rather than production test;
- limited accessibility technology testing;
- short test exposure;
- unvalidated market assumptions.

Limitations do not automatically make a project weak. Hiding limitations or making claims beyond the evidence does.

## 11. Required output

Produce:

1. Research inventory.
2. Participant/segment profile table.
3. Question-quality audit.
4. Evidence and insight table.
5. Unsupported/overgeneralized claim list.
6. Research limitation statement.
7. High-priority missing evidence.
8. Design decisions that should change or be tested because of the findings.
