# BIBO and KASA — Calibration Case Studies

This file records project-specific evidence and the lessons an evaluator should carry into future UI/UX competitions. It is not a claim that either project represents every competition or that their outcomes reveal the judges' exact reasoning.

## 1. Why these cases are included

BIBO and KASA provide two useful but different reference points:

- **BIBO**: an accessible reading-learning application concept for children with dyslexia. The project was recognized with a third-place result. The project owner has also reported that BIBO had one of the two highest report scores but finished third overall. This illustrates that report strength and final placement can differ; it does not prove why the final rank differed.
- **KASA**: an inclusive employment-search mobile application prototype for job seekers with disabilities. KASA received an official total score of 69.5/100 in the MIA 2026 preliminary round and did not qualify for the grand final. Its official category scores identify UX and Impact/Implementability as the largest relative scoring opportunities.

The evaluator must use these cases for calibration, not for copying a fixed formula. BIBO and KASA addressed different users, problem domains, accessibility needs, and competition contexts.

## 2. BIBO — project evidence visible in the submitted deck

### 2.1 Project identity and problem

The BIBO deck describes **BIBO: Aplikasi Belajar Membaca Khusus Anak dengan Gejala Disleksia**. The central user problem concerns children who experience difficulty reading, including confusion between letters such as b/d/p/q, loss of focus during long text, and discomfort or frustration during conventional reading activities.

The presentation frames existing alternatives as having limitations:

- teacher/therapist or personal support can be useful but may be costly or difficult to access outside major cities;
- conventional reading books provide basic learning material but may be insufficiently adaptive;
- general reading applications may be interactive but are not necessarily designed around dyslexia-related reading needs;
- general digital education platforms may contain many materials but may not focus on dyslexia-specific accessibility.

These statements are the project's framing. A future evaluator must still check the sources and avoid repeating any statistic or clinical assertion without verifying the original source.

### 2.2 Solution concept and feature architecture

BIBO organizes the core solution around three memorable pillars:

1. **Read** — multisensory reading through professional audio narration and synchronized text highlighting.
2. **Simplify** — breaking down or simplifying longer stories into shorter, more digestible text.
3. **Practice** — interactive learning or gamified practice intended to reduce pressure and create a safer practice experience.

The deck also describes supporting functions:

- OpenDyslexic font mode;
- repeated-word highlighting;
- story simplification;
- progress and statistics for parents;
- educational news and tips for parents;
- game-like exercises and reward elements;
- parent monitoring and learning support.

The useful lesson is the compact feature narrative: the three core verbs help the audience remember the solution. The evaluator should nevertheless test whether every supporting feature is justified by research and whether the claimed reading benefits are scientifically supported.

### 2.3 Personas and emotional journey

The deck presents two personas:

- **Rafi**, a seven-year-old primary-school student who experiences reading difficulty and may confuse b/d/p/q or lose focus when reading longer text.
- **Melissa**, a 34-year-old parent who wants to support her child's independent reading and monitor progress, while facing limitations in time and cost and difficulty finding dyslexia-friendly tools.

The user journey emphasizes the child's emotional state during learning. It frames mascot Bibo as an emotionally supportive companion, with the intention of helping the child move toward greater confidence and independence. This is a useful lesson in designing for emotional experience, not only task completion.

Evaluator caution: a persona should distinguish observed/researched attributes from fictional details used to make the persona concrete. The deck's existence of personas does not, by itself, demonstrate that every persona detail was validated.

### 2.4 Design and accessibility choices shown

BIBO's presentation includes:

- OpenDyslexic as a dyslexia-oriented typeface choice;
- audio narration and word/line highlighting;
- pastel color choices and a calmer visual direction;
- a component-oriented design system;
- Low-Fidelity, Mid-Fidelity, and High-Fidelity design progression;
- a specific explanation of why the team selected a typography and visual direction.

The deck explicitly presents an accessibility slide with OpenDyslexic, a color-contrast result labelled WCAG AAA, and audio/highlighted text. It also contains later slides explaining the neuro-inclusive design system and interface.

Evaluator caution: do not automatically accept a claim that a font prevents letter reversal, reduces visual stress, or improves reading outcomes merely because the slide says so. Distinguish a design rationale from a validated clinical or educational effect. Verify any neuro-linguistic or medical claim against reliable sources and user testing. A visual contrast result does not prove full WCAG conformance of the whole interface.

### 2.5 Prototype testing and iteration reported

The BIBO deck reports:

- 100% task success rate;
- 0% drop-off;
- 11.7% average misclick rate;
- SUS score of 88.8, labelled Excellent/Acceptable in the deck.

A separate improvement slide states that the team enlarged hit areas on some elements in response to the 11.7% average misclick rate and improved prototype interaction flow. It also describes a splash-screen transition fix, thumb-reach improvements, softer gradients, and consistent Auto Layout.

This is a valuable process lesson: testing should lead to a visible design change. A test report is stronger when it shows the observed problem, the design iteration, and ideally retest evidence.

Important evidence limitation: the deck extracts reviewed here do not clearly state the sample size and demographic/disability profile for the reported BIBO usability and SUS metrics. Do not invent it. An evaluator should request the underlying report, participant breakdown, tasks, and SUS calculation before assigning high confidence to the figures.

### 2.6 Competitor, market, roadmap, and communication elements

BIBO's deck includes competitor comparison against Duolingo ABC and Dyslexia Quest across gamification, dyslexia-friendly font, audio/highlight reading, parent monitoring, dyslexia focus, story simplification, and calm/adaptive UI.

It also includes TAM/SAM/SOM estimates and a roadmap for product improvement, adaptive learning, interactive experience, and ecosystem expansion.

Evaluator caution:

- Verify competitor feature claims and date them. A check mark or cross needs a source or documented product audit.
- Verify every TAM/SAM/SOM input, calculation, and source. A market slide can improve business communication but can harm credibility if the assumptions are not defensible.
- Treat future AI, speech recognition, therapist consultation, multi-platform expansion, and school collaboration as proposed roadmap items—not current functionality or proven impact.

### 2.7 BIBO result context

Known project-owner context:

- BIBO finished **third place** in a UI/UX competition with approximately 100 participating teams.
- The project owner has reported that the report score was among the **top two**, but the final placement was third.
- The project was developed by a three-person team, with the project owner serving as team leader.

What is not known from the materials currently available:

- the complete official scoring breakdown;
- the exact report score and overall score;
- the scoring of other finalists;
- judge comments;
- the exact reason the report rank and final placing differed;
- how much of the final result was affected by pitch, demo, Q&A, or another stage.

Do not claim that BIBO placed third because of the pitch, design, research, or any single factor. The evidence only establishes that the report-rank and final-rank outcomes differed, based on the project owner's account.

### 2.8 Lessons to carry forward from BIBO

1. **A simple, memorable solution architecture helps judges understand the product.** BIBO's Read/Simplify/Practice pillars are easier to recall than an unprioritized list of features.
2. **Emotional experience can be a meaningful UX dimension.** For child-focused products, anxiety, confidence, motivation, and caregiver needs may matter as much as navigation.
3. **Show iteration, not only final screens.** BIBO visibly described improvements made after usability observations.
4. **Testing numbers need participant context.** Strong results without a sample profile, task definitions, and calculation evidence are less persuasive.
5. **Accessibility claims require evidence.** A typeface, pastel palette, or contrast screenshot is not proof of improved reading or full accessibility.
6. **Competitor and market claims need substantiation.** A visually clear matrix can still be methodologically weak.
7. **Do not infer rank causality.** A high report rank does not guarantee the same final placement, and no evaluator should invent why the outcome differed.

## 3. KASA — project evidence visible in proposal and official score sheet

### 3.1 Project identity and problem

KASA means **Karier Aksesibel, Setara, dan Adil** and is described as an inclusive, accessible mobile job-search prototype for job seekers with disabilities.

The proposal frames the problem through employment access, availability of workplace-accessibility information, recruitment barriers, accommodation, and workplace adaptation. It cites WHO and ILO material, Indonesian ULD regulations, and an August 2026 ULD optimization guide. The proposal's initial research includes three stakeholder groups:

- 5 job seekers with disabilities;
- 5 HRD representatives;
- 6 ULD companions.

Examples of reported findings include:

- 4 of 5 job seekers rarely or never found accessibility-facility filters on job platforms;
- 4 of 5 had encountered an interview problem or cancellation due to inaccessible facilities or recruitment processes;
- all 5 expressed concern about being judged by physical condition before their skills were considered;
- 3 of 5 HRD respondents reported difficulty reaching suitable candidates with disabilities;
- 4 of 5 HRD respondents reported limited coordination channels with ULD companions;
- all 6 ULD companions reported relying on manual coordination through WhatsApp or email.

These are exploratory survey findings with small samples. They must be presented as findings from the surveyed respondents, not national prevalence estimates or representative population statistics.

### 3.2 Scope and stakeholder boundary

The proposal identifies job seekers with disabilities as the primary users. HRD and ULD are supporting stakeholders whose perspectives inform the design, but they are not direct users of the submitted prototype. The proposal states that HRD recruitment management, ULD monitoring, and external-system integrations are outside the prototype scope.

This is a legitimate scope decision for a UI/UX competition. The evaluator must not penalize the team simply because the Figma prototype does not contain a fully functioning HRD/ULD backend.

However, the evaluator should check that the proposal, appendix, screen designs, pitch deck, and spoken claims maintain the same boundary. In KASA's submitted materials, parts of the research appendix describe HRD/ULD dashboards and real-time monitoring as design decisions, while the main scope says those stakeholder interfaces are not in the prototype. This is a consistency issue to flag, not proof that the project lacked a design rationale.

### 3.3 Main features represented in the proposal

The KASA proposal describes four main features:

1. **Pencarian Kerja** — vacancy discovery based on skills, preferences, and accessibility needs, with facility information displayed for users to assess workplace suitability before applying.
2. **Akomodasi Kerja** — a user-facing workflow for submitting workplace or system adjustment needs, such as document accessibility, physical facilities, or communication methods.
3. **Check-in Adaptasi** — a user-facing way to record conditions and difficulties during workplace adaptation, with user-controlled decisions about who may access the notes.
4. **Komunitas** — a space for sharing experiences, questions, and peer support about accommodation, recruitment, and workplace adaptation.

ULD support appears in the broader information architecture and support flows. Do not silently replace the proposal's four-feature list with a different four-feature list in a pitch deck. If a presentation reclassifies ULD support as a standalone feature or omits Community, flag the inconsistency and ask which version is authoritative.

### 3.4 UX and design process documented

The 41-page proposal includes:

- a primary persona, Nadia Putri, a 23-year-old fresh graduate and wheelchair user;
- stakeholder personas for HRD and ULD companions;
- user flow and information architecture;
- a six-stage User Journey Map;
- four HMW problem directions;
- Low-Fidelity, Medium-Fidelity, and High-Fidelity wireframes;
- design system documentation;
- color-contrast evidence;
- feature screens and an interactive Figma prototype;
- Maze testing and SUS results;
- competitor analysis, SWOT, roadmap, and conclusion.

This is a substantial design process. The evaluator should assess how rigorously the process was executed, not simply count the number of artifacts.

### 3.5 Accessibility claims and their limit

The proposal describes a design system for users with physical, visual, hearing, and neurodivergent needs. It documents Inter typography, an OpenDyslexic option, labelled navigation icons, large touch targets (the prototype section refers to targets greater than 48dp), and color-contrast tests.

The proposal's contrast evidence states that tested combinations passed WCAG Level AA and AAA for normal and large text, and Level AA for graphical objects and user-interface components.

This is useful visual accessibility evidence, but it does not independently prove:

- correct TalkBack or VoiceOver behavior;
- full keyboard accessibility;
- meaningful accessible names and focus order in a coded app;
- compatibility with all assistive technologies;
- complete WCAG conformance across every screen and state;
- accessibility for every disability group discussed in the proposal.

For a UI/UX competition, it is acceptable to present these as design intentions/specifications and validated visual checks, provided the proposal does not imply implemented compatibility that was not tested.

### 3.6 Testing results documented

The KASA proposal reports 25 respondents for Maze testing and 25 for SUS.

Maze task scenarios:

1. Filter and find a job matching physical facility needs.
2. Submit a workplace accommodation form.
3. Access ULD support/coordination.
4. Perform a workplace adaptation check-in and monitor application status.

Reported Maze metrics:

- task success rate: 100%;
- drop-off rate: 0%;
- average misclick rate: 7.85%;
- task-level misclick values reported: UAT 1 = 7%, UAT 2 = 14.9%, UAT 3 = 0%, UAT 4 = 9.5%.

The proposal reports a SUS average of **87.1**, described as Excellent/Acceptable (Grade A+ in the document).

These metrics support the claim that tested users could navigate the simulated prototype tasks and rated the perceived usability positively. They do not prove that:

- the production service works;
- every task would succeed in a deployed application;
- the 25 participants were all job seekers with disabilities;
- the interface is accessible to each disability group;
- accommodation requests are actually received by HRD;
- ULD coordination is operational.

The participant breakdown for the 25 Maze/SUS respondents is not clearly established in the reviewed proposal. The evaluator should flag this as `NOT DOCUMENTED` and avoid asserting that the result represents all relevant user groups. Also note that the proposal calls the test UAT; because the tested artifact is an interactive Figma prototype using Maze, a precise description such as `prototype task-based usability testing` may be clearer unless the organizer or team has a specific reason to retain UAT terminology.

### 3.7 Competitor analysis and innovation

The proposal compares KASA with Difalink and Kerjabilitas. Its table uses check marks and crosses for vacancy support, community/forum, accommodation requests, adaptation check-ins, ULD access, and accessibility features.

The evaluator should not assume a red cross is accurate unless the team has reviewed reliable, current public evidence. A competitor may offer an item through a separate program, service, or workflow rather than the same named interface feature. Preferred labels include:

- `Verified available`;
- `Not identified in reviewed public materials`;
- `Partially available / different delivery model`;
- `Not applicable`.

KASA's more defensible differentiator is the intended integration of job discovery, accessibility information, user-initiated accommodation, adaptation check-ins, and peer support in one job-seeker-oriented experience—not an unsupported assertion that competitors have none of those capabilities.

### 3.8 Impact and implementability

KASA's social problem and stakeholder value proposition are meaningful. The rubric also asked about the potential for real implementation by an industry partner, alignment with the brief, and value proposition to the target audience.

The proposal included a 2027 roadmap and recognized limitations such as lack of real implementation, company readiness, and data protection. It did not provide evidence of an actual company/ULD pilot commitment in the reviewed material. That is a legitimate gap under an implementation-oriented rubric, but not a reason to demand a fully coded system from a UI/UX competition entry.

A stronger design-stage implementation argument could have included:

- a service blueprint showing job seeker, KASA, employer, and ULD responsibilities;
- a vacancy accessibility-verification process;
- a consent and data-access model for adaptation notes;
- a proposed pilot workflow with one company or ULD;
- partner feedback, a documented discussion, or a letter of interest if genuinely obtained;
- implementation dependencies and measurable outcomes.

### 3.9 Official MIA 2026 result

The official transparency sheet supplied for KASA records:

| Criterion | Maximum | Score | Percentage of criterion maximum |
|---|---:|---:|---:|
| Theme & Brief | 15 | 12 | 80.0% |
| User Experience (UX) | 30 | 18.5 | 61.7% |
| User Interface (UI) | 20 | 14 | 70.0% |
| Innovation & Creativity | 15 | 11.5 | 76.7% |
| Impact & Implementability | 20 | 13.5 | 67.5% |
| **Total** | **100** | **69.5** | **69.5%** |

The official sheet states that KASA did not qualify for the MIA 2026 grand final. Its UX description includes flow, navigation, usability, user research, persona, user journey, accessibility, and inclusivity. Its Impact description includes potential for real implementation by an industry partner, alignment with the problem brief, and value proposition to the target audience.

### 3.10 Lessons to carry forward from KASA

1. **A broad, relevant social problem is not enough.** The proposal must show exactly how each user need changes the experience.
2. **Do not confuse deliverable count with UX quality.** A persona, journey, HMW, flow, and test report should form one connected argument.
3. **Describe participant composition.** Testing metrics need sample profiles and task context.
4. **Treat accessibility as an interaction-design concern.** Contrast checks are useful but do not establish comprehensive accessibility.
5. **Keep scope consistent.** Distinguish the primary-user prototype from supporting stakeholders and future interfaces.
6. **Use precise testing language.** Prototype task success is not the same as live service acceptance.
7. **Competitor comparisons require evidence.** Unsupported crosses weaken credibility.
8. **Impact and implementability need a service model.** For a UI/UX competition, this can be a design-stage blueprint and credible partner validation; it does not require a production backend unless the brief says so.
9. **A future roadmap is not proof of feasibility.** Make dependencies, responsible actors, risks, and validation steps visible.
10. **A score is diagnostic, not an identity.** KASA's 69.5 is one competition outcome, not proof that the idea is inherently weak.

## 4. Cross-case calibration rules

When evaluating another project, carry these principles forward:

- BIBO shows the benefit of a memorable core solution architecture and an explicit iteration story.
- KASA shows the importance of participant characterization, accessibility evidence, scope consistency, competitor substantiation, and a credible implementation model.
- Neither case establishes a universal ideal number of survey respondents, ideal SUS score, ideal feature count, or guaranteed path to qualification.
- Do not copy BIBO's or KASA's metrics, wording, feature architecture, colors, or report structure into a new project without a user-based reason.
- Do not claim that BIBO's third-place result or KASA's non-qualification was caused by any particular rubric weakness unless judge feedback or score evidence establishes that cause.
- Always distinguish `documented case fact`, `project-owner-reported context`, and `evaluator interpretation`.
