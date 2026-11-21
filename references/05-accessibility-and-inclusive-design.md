# Accessibility and Inclusive Design Audit for UI/UX Competitions

## 1. Purpose and boundary

Evaluate whether accessibility is considered in the actual user experience—not merely named in a theme statement or design-system slide. For a design-only competition, evaluate design decisions, specifications, and prototype simulations. Do not demand a functioning screen reader implementation or production code unless the competition explicitly requires it.

Use a layered model:

1. Accessibility intent — the team identifies relevant user needs.
2. Design specification — screens/components are designed to support accessible behavior.
3. Prototype representation — the interactive prototype communicates the intended interaction.
4. Design validation — relevant users or experts test the design.
5. Implementation validation — coded product behavior is tested with assistive technologies and relevant standards.

Do not collapse these levels into a single word such as “accessible”.

## 2. Understand the user and task first

Do not assume one accessibility feature supports every disability. Map relevant needs to specific tasks and barriers.

Consider, where relevant:

- visual: low vision, blindness, color perception, glare, contrast, text scaling;
- auditory: deafness, hearing loss, captions, text alternatives, visual notifications;
- motor: reach, dexterity, touch target, gesture alternatives, time limits;
- cognitive/learning: comprehension, memory load, predictable navigation, plain language, reduced distraction;
- speech/communication: alternative input/output, text options, communication preference;
- situational: low bandwidth, bright environments, one-handed use, temporary injury, noisy surroundings.

Do not infer a person's needs from a diagnosis alone. Ask what task they are trying to perform and what barrier they experience.

## 3. Visual accessibility

Inspect:

- text contrast;
- non-text contrast for meaningful components and graphics;
- font size and scaling behavior;
- line spacing and paragraph width;
- text alignment and readability;
- information conveyed by color alone;
- focus/selection states;
- error, warning, and success differentiation;
- zoom/reflow at enlarged text sizes;
- icon clarity and label support.

If a contrast checker result is provided, inspect the exact foreground/background pair, text size/weight, component type, WCAG version/level, and whether the tested colors match the actual screens. A sample contrast screenshot does not prove every screen passes.

Avoid treating color psychology as accessibility evidence. A calm color palette may be a design choice, but it does not automatically reduce anxiety, visual stress, or fatigue for every user.

## 4. Typography and reading accessibility

Check:

- readable base font;
- adequate sizing and scaling;
- clear hierarchy;
- distinguishable characters;
- spacing and line length;
- support for user text preferences where appropriate;
- no reliance on decorative fonts for essential information.

Specialized fonts (including OpenDyslexic) should be treated as optional design choices unless strong evidence supports a stronger claim. Do not claim a typeface prevents letter reversal, treats dyslexia, or improves comprehension for all dyslexic readers without reliable supporting evidence and appropriate testing. Offer user preference and test readability with target users rather than assuming a single font is universally superior.

## 5. Motor and touch accessibility

Review:

- touch target size and spacing;
- avoidance of controls that require precise gestures;
- alternatives to drag-only or multi-finger interaction;
- reachable primary actions;
- sufficient time to complete tasks;
- consistent placement of controls;
- prevention of accidental destructive actions;
- appropriate keyboard/focus behavior in a coded implementation or an explicit design specification in a prototype.

If a team claims touch targets meet a specific standard, request measured dimensions and evidence across the relevant screens—not a general statement.

## 6. Screen reader and assistive-technology-aware design

For UI/UX design, check whether the team has specified:

- semantic roles for controls;
- meaningful accessible names;
- logical reading/focus order;
- labels for icon-only actions;
- status announcements for state changes;
- error associations with form fields;
- text alternatives for non-text information;
- heading hierarchy;
- content order that remains meaningful without visual layout;
- non-color cues for status.

A Figma prototype can illustrate labels and states, but it cannot prove TalkBack/VoiceOver behavior in a native app. Use wording such as “designed with screen-reader support in mind” or “accessibility annotations specified” unless actual testing has been conducted.

## 7. Hearing and communication accessibility

Check, where relevant:

- captions/transcripts for audio or video;
- visual alternatives to audio notifications;
- text-based communication options;
- clear distinction between sender/recipient and status;
- support for communication preferences;
- no audio-only instruction for essential tasks.

Do not add text-to-speech, transcription, sign-language, or other features solely as decorative inclusion claims. Verify that the feature addresses a researched task and that its limitations are clear.

## 8. Cognitive and neurodiversity-related design

Evaluate:

- plain, direct language;
- predictable structure;
- low unnecessary cognitive load;
- clear task progression;
- chunked information;
- helpful defaults;
- limited simultaneous choices;
- recoverable mistakes;
- consistent terms and icon meanings;
- optional personalization rather than forced modes;
- no unnecessary time pressure;
- clear feedback and confirmation.

Do not assume that animation, gamification, simplified text, or a particular color palette is automatically beneficial. Test with intended users and respect individual differences.

## 9. Accessibility and privacy

Inclusive design often collects sensitive information about disability, health, accommodations, or support needs. Review:

- data minimization;
- explicit consent;
- who can see information;
- why information is shared;
- ability to revoke or change permission;
- private versus shared notes;
- safe defaults;
- retention and deletion concept;
- avoiding unnecessary disclosure during recruitment.

The prototype should communicate user control and privacy expectations where those are central to the service.

## 10. Accessibility test plan

For each relevant requirement, record:

- user need;
- design requirement;
- screen/component;
- method (inspection, contrast check, assistive-tech test, user test, expert review);
- test environment;
- expected outcome;
- observed result;
- severity;
- remediation;
- re-test result.

Use the right test method. A color checker is not a screen-reader test. A screen-reader test is not a cognitive usability study. A general SUS score is not a WCAG audit.

## 11. Claim calibration language

Prefer:

- “The tested text/background combinations met the stated contrast criterion.”
- “The prototype includes labels and states intended to support screen-reader implementation.”
- “The design was reviewed against selected WCAG criteria.”
- “Further assistive-technology testing is required during implementation.”

Avoid:

- “Fully WCAG compliant” based on a color screenshot;
- “Works with TalkBack” without a working implementation and test;
- “Accessible to all disabilities” based on one or two personas;
- “OpenDyslexic cures/prevents dyslexia-related reading problems”;
- “The app is inclusive” without specifying for whom and which interactions.

## 12. Required output

Produce an accessibility coverage matrix, unverified-claim list, design-level recommendations, and a staged validation plan. Explicitly distinguish what can be validated in the competition prototype from what must wait until implementation.
