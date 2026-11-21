# Prototype and Interaction Quality Audit

## 1. Purpose

Evaluate whether the interactive prototype convincingly demonstrates the intended user experience. A prototype is a model of behavior, not necessarily a working product. The evaluator should inspect what the prototype communicates, what it simulates, where it stops, and whether its limitations are clearly explained.

## 2. Prototype fidelity

Identify which aspects are represented:

- visual fidelity;
- interaction fidelity;
- content fidelity;
- data/state fidelity;
- platform fidelity;
- accessibility behavior;
- service/operational fidelity.

A prototype may be high-fidelity visually but low-fidelity in data behavior. That is acceptable when its purpose is to evaluate navigation and layout, but it should not be used as proof of functioning business processes.

## 3. Core prototype flow audit

For each user scenario:

1. Start from the correct entry screen.
2. Follow the intended user goal.
3. Click each visible interactive element.
4. Confirm the expected next state.
5. Check back navigation and escape routes.
6. Check whether inputs accept plausible content or are represented through a realistic simulation.
7. Check feedback after selection/submission.
8. Check success, failure, and confirmation states.
9. Check that navigation remains consistent across screens.
10. Record any dead, misleading, or broken interaction.

If the prototype URL cannot be accessed, do not claim to have inspected it. Review only the exported screenshots and explicitly state the limitation.

## 4. Interaction patterns

Inspect:

- buttons versus text links;
- tabs versus navigation destinations;
- dropdown and filter behavior;
- modal/drawer behavior;
- form input and validation;
- search and result filtering;
- selection and deselection;
- save/favorite behavior;
- confirmation and cancellation;
- status transitions;
- notifications;
- chat or community interaction;
- onboarding and permission prompts.

A visual element is not interactive merely because it looks like a button. Conversely, decorative elements should not falsely imply clickability.

## 5. Prototype completeness

Do not demand every possible screen. Require enough screens and states to demonstrate the core problem-solving value and validate the most important assumptions.

Minimum high-value coverage often includes:

- entry/onboarding where relevant;
- primary dashboard/home;
- core discovery or task initiation;
- detail/decision screen;
- main action form or interaction;
- confirmation/status;
- recovery/empty/error state for a high-risk task;
- relevant settings/accessibility control if central to the value proposition.

Choose scope based on the brief, not a fixed screen count.

## 6. Interaction realism without backend requirements

A Figma prototype can use predefined states, overlays, variables, and linked frames to simulate workflows. Evaluate whether the simulation is coherent.

Acceptable in a design competition:

- a mock vacancy list with selectable filters;
- a simulated accommodation form with a confirmation screen;
- a status screen showing a proposed state;
- a demo ULD support request journey;
- a fake loading/success state labelled as a prototype interaction.

Not acceptable as an unsupported claim:

- “The employer receives the request in real time” when no integration exists;
- “The application verifies facility information” when the prototype only displays sample labels;
- “The service monitors adaptation” when the prototype only records a local sample entry;
- “The screen reader works” based only on visual annotation.

The evaluator should recommend precise wording: “simulates”, “proposes”, “is designed to”, or “future integration” as appropriate.

## 7. Demo-path audit

Build a demonstration route with:

- start screen;
- scenario introduction;
- 3–5 key interaction moments depending on time;
- one meaningful decision or user control;
- a visible outcome;
- a short explanation of why it matters.

Avoid demoing every menu. A strong demo proves the core value proposition, not the total number of screens.

Test the path before recording or presenting:

- all links work;
- overlays close correctly;
- correct screen loads after each tap;
- cursor/finger positions do not obscure content;
- screen recordings are readable;
- prototype loads within the time limit;
- backup video/screenshots exist if the live link fails.

## 8. Cross-artifact consistency

Compare prototype against:

- user flow;
- information architecture;
- feature list;
- wireframes;
- design system;
- proposal description;
- pitch deck;
- test scenarios.

Flag any screen, feature, role, or status that appears in one artifact but not another. Distinguish intentional future scope from inconsistency.

## 9. Required output

Produce:

- prototype access status;
- inspected flows and screens;
- interaction pass/fail list;
- missing states;
- misleading or nonfunctional elements;
- fidelity/limitation note;
- highest-priority changes before demo;
- recommended demo path.
