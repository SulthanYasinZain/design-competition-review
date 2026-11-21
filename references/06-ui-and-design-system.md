# UI and Design System Quality Audit

## 1. Purpose

Evaluate visual communication and interface quality against user needs, brand intent, platform constraints, and the competition rubric. Do not score based on personal preference for a color, trend, or aesthetic style. Ask whether the visual system helps users understand, decide, and act.

## 2. Visual hierarchy

Inspect whether each screen communicates:

- what page or task the user is on;
- the most important information;
- the primary action;
- secondary actions;
- relationships between content;
- current state or status;
- next step.

Red flags:

- several elements compete equally for attention;
- primary CTA is visually weak or ambiguous;
- decorative visuals overpower task information;
- headings do not describe content;
- repeated cards lack meaningful hierarchy;
- status is conveyed only through color;
- important constraints appear below the fold without signposting.

## 3. Typography system

Check:

- font family suitability;
- heading/body/label scale;
- consistent weight use;
- readable line height;
- line length;
- truncation behavior;
- large text and scaling;
- localization and long-text behavior;
- consistent capitalization and punctuation.

Do not assume a specialized font is better for every user. Evaluate legibility in actual screen context.

## 4. Color system

Check:

- primary, secondary, neutral, and semantic colors;
- light/dark or surface variations if relevant;
- text and non-text contrast;
- accessible status colors;
- selected/disabled/error states;
- color use consistency;
- whether color semantics are intuitive and consistent.

A brand palette may be distinctive but should not compromise readability. Psychological color claims should be treated as hypotheses unless researched and validated.

## 5. Spacing, grid, and layout

Inspect:

- spacing scale;
- alignment;
- consistent margins;
- card padding;
- density and whitespace;
- relationship between labels and controls;
- responsive reflow;
- scroll length;
- thumb reach for mobile primary actions;
- safe areas and platform conventions.

Do not penalize an intentionally dense professional interface merely because it is not minimal. Judge whether the density suits the task and user.

## 6. Components and states

Audit whether important components have appropriate states:

- default;
- hover, when relevant;
- focus;
- pressed/active;
- selected;
- disabled;
- loading/submitting;
- success;
- warning/error;
- empty;
- read/unread;
- expanded/collapsed.

For Figma work, these may be represented as variants or connected states. They need not be coded unless the brief asks for code. The absence of a state matters when it creates ambiguity in the intended interaction.

## 7. Design system completeness

A design system should support consistency and iteration. Inspect:

- foundations: color, typography, spacing, radius, elevation;
- components: buttons, inputs, cards, navigation, modals, alerts;
- variants and states;
- naming conventions;
- layout constraints;
- reusable patterns;
- icon style and labels;
- illustration/image rules;
- accessibility annotations;
- responsive rules;
- documentation sufficient for another designer/developer to use it.

A screenshot of component examples is useful but does not establish system completeness. Check whether actual prototype screens use the defined components consistently.

## 8. Responsive and platform quality

For mobile apps, inspect:

- common device sizes;
- safe areas;
- keyboard overlap;
- scrolling behavior;
- fixed versus sticky controls;
- one-handed reach;
- orientation assumptions;
- system status/navigation bars;
- text scaling.

For responsive web apps, inspect breakpoints, navigation changes, content reflow, tables/cards, and mobile form usability. Do not assume a design works on all devices because one desktop and one mobile screenshot exist.

## 9. Visual storytelling

For competition decks and reports, assess:

- one key message per slide/page;
- clear title and evidence hierarchy;
- legible screenshots at presentation scale;
- consistent product identity;
- visual continuity between problem, design process, and solution;
- controlled text density;
- captions and annotations that help interpretation.

Do not recommend adding decorative mockups or stock images when the real prototype screen would provide stronger evidence.

## 10. UI scoring evidence

Strong evidence includes:

- actual high-fidelity screens;
- consistent component usage;
- documented visual design tokens;
- measured contrast tests that map to real screen colors;
- responsive variants or behavior notes;
- state coverage;
- clear accessibility cues;
- direct links between visual decisions and user needs.

Weak evidence includes:

- an attractive cover with inconsistent product screens;
- a design-system slide not reflected in the UI;
- claims of “modern” or “professional” without observable rationale;
- visual accessibility claims based only on palette selection;
- screens that cannot be read at the pitch projection size.

## 11. Required output

For each screen or representative screen group, report:

- strengths tied to task/user context;
- hierarchy issues;
- consistency issues;
- accessibility concerns;
- missing states;
- responsive concerns;
- high-impact changes;
- optional polish changes.
