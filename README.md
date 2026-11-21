# UI/UX Competition Evaluator — Skill Pack

A detailed, evidence-led agent skill for reviewing UI/UX competition projects from the first reading of the guidebook through final submission. It is designed for competitions where the main deliverable is research, interface design, user experience, an interactive prototype, a proposal/report, and a pitch—not necessarily a coded production product.

## Contents

### Core instruction
- `SKILL.md` — role, principles, workflow, evidence labels, severity, scoring protocol, output format, and operating constraints.

### Reference modules
- `references/00-bibo-kasa-case-studies.md` — detailed calibration history and lessons from BIBO and KASA.
- `references/01-competition-brief-and-rubric.md` — guidebook extraction, compliance, rubric interpretation, and eligibility audit.
- `references/02-research-and-evidence-quality.md` — research methods, sampling, survey quality, interviews, statistics, and evidence discipline.
- `references/03-problem-to-design-traceability.md` — insight-to-feature traceability, feature prioritization, HMW, and design rationale.
- `references/04-ux-architecture-and-flows.md` — persona, journey, IA, flows, navigation, forms, and edge cases.
- `references/05-accessibility-and-inclusive-design.md` — design-level accessibility versus implemented assistive-technology validation.
- `references/06-ui-and-design-system.md` — visual hierarchy, consistency, responsive behavior, components, and handoff.
- `references/07-prototype-and-interaction-quality.md` — Figma prototype audit, interaction coverage, simulation boundaries, and demo paths.
- `references/08-usability-testing-and-metrics.md` — Maze/task testing, SUS, metrics, participants, analysis, and iteration.
- `references/09-innovation-and-competitor-analysis.md` — defensible differentiation, market gap, competitor audit, and innovation claims.
- `references/10-impact-and-implementability.md` — stakeholder value, service blueprint, implementation logic, feasibility, risk, and impact metrics.
- `references/11-report-pitch-and-submission.md` — report quality, pitch structure, demo, citations, and final checks.
- `references/12-scoring-calibration-and-readiness.md` — scoring approach, uncertainty, prioritization, and readiness gates.

### Templates
- `templates/evidence-ledger.md`
- `templates/brief-compliance-matrix.md`
- `templates/problem-solution-traceability.md`
- `templates/participant-profile-and-test-plan.md`
- `templates/accessibility-test-plan.md`
- `templates/competitor-evidence-matrix.md`
- `templates/impact-and-service-blueprint.md`
- `templates/rubric-scorecard.md`
- `templates/final-round-readiness-gate.md`
- `templates/judge-question-bank.md`

## How to use

1. Place this folder in the location your AI agent uses for skills or project instructions.
2. Make the agent read `SKILL.md` first.
3. Provide the official guidebook, problem brief, rubric, proposal, deck, prototype, and available research/testing evidence.
4. Ask for an initial compliance and evidence audit before requesting rewrites or visual improvements.
5. Ask the agent to load the relevant reference modules and fill the templates.
6. Re-run the evaluation after substantive revisions.

The folder follows the common `SKILL.md` plus `references/` and `templates/` convention. Different AI platforms may require a different installation path or metadata format; adapt the folder location without changing the evidence rules.

## Important scope boundary

The evaluator distinguishes design intent, Figma simulation, accessibility specification, validated user experience, coded functionality, and operational service delivery. It must not demand a production backend from a design-only competition unless the official brief requires one. It must also not overclaim that a prototype demonstrates real assistive-technology compatibility or live organizational integration.

## Case-study provenance

The BIBO and KASA case-study file distinguishes facts visible in the submitted materials from user-reported competition outcomes and evaluator interpretations. The BIBO final placing and report-rank context are attributed to the project owner where no official scoring sheet was available. The KASA score breakdown comes from the official transparency sheet supplied in the conversation.
