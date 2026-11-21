# Problem-to-Design Traceability Audit

## 1. Purpose

Determine whether the solution is genuinely derived from user needs and whether each important interface decision has a defensible reason. This module prevents feature accumulation, decorative research artifacts, and “solution-first” projects that retrofit pain points after designing the interface.

## 2. The traceability chain

Use this chain as the central audit model:

`Evidence → Pattern → Insight → User need → Problem statement → HMW/opportunity → Design principle → Feature → Screen/interaction → Test task → Result → Iteration`

Every core feature should be traceable backward to evidence and forward to a testable experience.

### 2.1 Backward traceability

For each feature, ask:

- Which user need does it address?
- Which research finding supports that need?
- Which participant segment does the finding apply to?
- Is the feature a direct response, a hypothesis, or a stakeholder request?
- Is the feature required by the problem brief?
- Does the feature duplicate an existing service without a clear benefit?

### 2.2 Forward traceability

For each high-priority user need, ask:

- Which design principle responds to it?
- Which screen or interaction implements that principle?
- Is the interaction included in the prototype?
- Is there a task scenario to test it?
- Is there an observable success condition?
- What finding would trigger a design iteration?

## 3. Problem statement quality

A useful problem statement identifies:

- who experiences the problem;
- in what context;
- what goal they are trying to achieve;
- what barrier or unmet need occurs;
- why the barrier matters;
- what evidence supports the statement.

Avoid problem statements that are merely feature descriptions, such as “Users need an AI application” or “Users need a dashboard”. Avoid defining a problem so broadly that it cannot guide feature priorities.

## 4. HMW quality

A strong How Might We question:

- is rooted in a validated user need;
- is neither too broad nor too solution-specific;
- opens room for multiple possible solutions;
- describes a user outcome rather than a technology;
- is distinct from other HMW statements;
- can be connected to an eventual design decision.

Weak: “How might we create an AI chatbot?”

Stronger: “How might we help first-time users understand which next step is appropriate when they encounter an unfamiliar process?”

The exact wording depends on research. Do not reuse examples as project findings.

## 5. Feature prioritization

Evaluate feature priority using:

- user impact/severity of the problem;
- frequency of the task or problem;
- importance to the competition brief;
- evidence strength;
- design feasibility within the project time;
- dependency on another role or service;
- risk of confusing the primary journey;
- ability to demonstrate the feature in a prototype.

Useful methods include MoSCoW, impact/effort, opportunity scoring, or a simple evidence-weighted priority matrix. State which method is used. Do not make priority scores look scientifically precise when they are subjective team judgments.

## 6. Feature scope audit

For each feature classify it as:

- `CORE`: required to complete the primary user outcome;
- `SUPPORTING`: improves the experience or helps a secondary need;
- `FUTURE`: valuable but outside the current prototype;
- `OUT OF SCOPE`: intentionally excluded;
- `UNJUSTIFIED`: no credible evidence or brief requirement found.

Red flags:

- too many features for the available time;
- features that serve stakeholders who are not represented in the prototype;
- advanced technology added only to appear innovative;
- repeated features with unclear distinction;
- a feature that cannot be reached from the main flow;
- a feature described in the proposal but not visible in the prototype;
- a feature visible in the prototype but not explained in the report.

## 7. Design rationale quality

For each important design decision, require a compact rationale:

- **Finding:** what evidence or requirement triggered it?
- **Decision:** what did the team design?
- **Reason:** why is this decision appropriate?
- **Trade-off:** what downside or constraint exists?
- **Validation:** how will the team know it works?

Avoid vague rationale such as “to improve user experience”, “for modern appearance”, or “to be more innovative”.

## 8. Traceability scoring

Use qualitative labels:

- `STRONG`: clear evidence-to-feature connection and testable outcome;
- `PARTIAL`: reasonable rationale but weak evidence, missing interaction, or no test;
- `WEAK`: feature appears largely assumed or disconnected;
- `CONTRADICTORY`: feature conflicts with the problem, scope, or user research;
- `NOT APPLICABLE`: feature is intentionally outside the project's scope.

Do not automatically penalize future features as missing if the submission clearly labels them as future scope and the rubric does not require them in the prototype.

## 9. Required output

Create a traceability matrix with columns:

`Evidence | Insight | User need | HMW/problem | Design decision | Feature | Prototype frame | Test task | Result/iteration | Traceability status`.

Then identify:

- high-priority needs without a design response;
- features without evidence;
- design decisions with no validation;
- scope contradictions;
- features that should be removed, merged, deferred, or tested.
