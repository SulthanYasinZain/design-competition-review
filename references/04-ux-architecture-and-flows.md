# UX Architecture, Journey, and Flow Audit

## 1. Purpose

Evaluate how users understand the product, find relevant information, navigate between areas, complete important tasks, and recover when something goes wrong. Focus on the intended users and primary scenarios—not on whether the architecture resembles a familiar app pattern.

## 2. Persona and journey connection

A persona should influence the journey. A journey should influence priorities. A feature should address a specific moment in that journey.

For a user journey map, check:

- clearly defined persona and scenario;
- beginning and ending states;
- stages that follow an actual task or experience;
- user actions;
- user thoughts/needs;
- emotional state, when supported by evidence;
- pain points;
- opportunities/design implications;
- moments of truth or high-risk steps;
- backstage/support processes where relevant.

Avoid journey maps that are a generic timeline with invented emotions or features inserted into every column. An emotional curve should have a rationale.

## 3. Information architecture

Evaluate whether categories and labels match the user's mental model.

Check:

- information grouping;
- hierarchy and depth;
- menu naming and discoverability;
- duplication across sections;
- whether essential information appears at the right time;
- search/filter structure;
- content relationships;
- user role separation where multiple roles exist;
- growth potential without overcomplicating the current scope.

Do not reward a large sitemap just because it contains many branches. Simplicity and clear task grouping are often better.

## 4. User flow audit

For each core flow, identify:

- entry point;
- user intent;
- action;
- system feedback;
- decision/branch;
- validation step;
- success state;
- failure state;
- recovery path;
- exit or continuation.

Check if the diagram matches the actual prototype. A diagram is not enough if users cannot follow the same path in the prototype.

### 4.1 Decision points

A decision point should represent a meaningful user choice or system condition. Examples:

- Does the user meet the selected criteria?
- Is the required information available?
- Does the user want to continue or save for later?
- Is consent provided?

Do not add decorative diamonds for every tap. Avoid false branching where one option simply leads to the same next screen without a meaningful decision.

### 4.2 Primary versus secondary flows

Prioritize:

1. primary user goal;
2. most common supporting task;
3. high-risk or high-consequence task;
4. error/recovery flow;
5. secondary or future flows.

Do not try to demonstrate every conceivable scenario in a short competition video. Select the flow that best proves the value proposition.

## 5. Navigation and interaction logic

Review:

- persistent versus contextual navigation;
- back behavior;
- breadcrumb/step indicators where appropriate;
- tab consistency;
- active/selected states;
- destructive action confirmation;
- clear labels and affordances;
- state persistence;
- user feedback after important actions.

Look for “dead ends”: pages with no clear next step or way back. Also look for “false affordances”: elements that look clickable but do nothing.

## 6. Forms and data entry

For each form inspect:

- labels that persist after text entry;
- input types and examples;
- required/optional indication;
- field grouping;
- validation timing;
- error message clarity;
- correction path;
- disabled/submitting/success states;
- sensitive information minimization;
- accessibility of field errors;
- form length and cognitive burden.

For a prototype, demonstrate the intended states even if no data is saved to a backend. Clearly label the interaction as simulated if needed.

## 7. Content and information clarity

Check:

- plain language;
- short, meaningful headings;
- consistent terminology;
- explanation of unfamiliar terms;
- useful empty states;
- actionable error messages;
- confirmation messages that say what happened and what comes next;
- no unexplained jargon;
- no generic placeholder copy in final screens.

## 8. Edge cases and recovery

At least consider:

- no search results;
- no internet or unavailable content;
- invalid input;
- expired session;
- permission denied;
- user declines optional request;
- upload failure;
- repeated submission;
- ambiguous status;
- no available service partner;
- user changes their mind;
- user needs assistance.

A competition prototype does not need every backend edge case, but the main interaction should not imply a perfect world where nothing ever fails.

## 9. Multi-role and service UX

When the concept involves a primary user and operational stakeholders, distinguish interfaces from service dependencies.

For each role define:

- goals;
- tasks;
- data visible;
- permissions;
- actions available;
- responsibility outside the product;
- handoff points;
- consent and privacy boundaries.

If only one role is prototyped, state that clearly. A user-facing screen that says “HRD has received your request” is a simulated service result unless there is a real integration. The evaluator should ask whether the prototype clearly communicates the conceptual handoff and whether the proposal explains the future operational requirement.

## 10. Required output

For each primary scenario, provide:

- flow summary;
- number and type of steps;
- unclear points;
- missing states;
- navigation consistency issues;
- accessibility concerns;
- recommended flow simplification;
- a testable task statement.
