# Usability Testing, Accessibility Testing, and Metric Interpretation

## 1. Purpose

Assess whether the design has been tested appropriately, whether the metrics are calculated and interpreted correctly, and whether test findings led to meaningful changes. Strong metrics are useful, but they are not a substitute for good methodology.

## 2. Define what is being tested

State explicitly whether the object is:

- a paper sketch;
- a clickable low-fidelity prototype;
- a high-fidelity Figma prototype;
- an implemented application;
- a live end-to-end service.

The method and claims must match the object. Task completion in a Figma prototype is evidence about the tested prototype flow, not proof of a live business process.

## 3. Test plan requirements

A test plan should define:

- objective;
- research questions;
- participant criteria;
- participant count and rationale;
- participant role and relevant characteristics;
- prototype version;
- environment/device;
- task scenarios;
- task success criteria;
- observed metrics;
- consent/privacy handling;
- analysis plan;
- limitations.

Tasks should be realistic and neutral. Avoid telling participants exactly where to tap if the test is intended to evaluate discoverability.

## 4. Participant reporting

For a competition submission, report enough context to interpret the results without exposing personal data. Useful fields include:

- total participants;
- role/segment breakdown;
- relevant experience level;
- disability/accessibility needs, only when voluntarily disclosed and appropriate;
- device familiarity;
- recruitment method;
- inclusion/exclusion criteria.

If the participant mix is unknown, label it `NOT DOCUMENTED`. Never state that the sample represents a target group without evidence.

## 5. Task design and task success

For every task:

- define the user goal;
- define acceptable completion states;
- distinguish complete success from partial success;
- record help/assistance required;
- record critical error or workaround;
- specify whether the prototype allows an actual click-through or merely asks for a verbal opinion.

A high success rate is meaningful only when the task is realistic, the success criteria are clear, and the test setup does not reveal the answer.

## 6. Core metrics

### 6.1 Task success rate

Common calculation:

`Task success rate = (number of successful task attempts / total valid task attempts) × 100%`.

Clarify whether the denominator is participants, task attempts, or total tasks. If 25 participants perform four tasks, do not ambiguously say “100% of users completed everything” unless the records support that exact claim.

### 6.2 Time on task

Report median or distribution where possible, not only average, because a small number of long attempts can distort the mean. Compare tasks with similar conditions. A faster task is not necessarily better if users skip important information.

### 6.3 Misclick/error rate

State the tool's definition of a misclick and the denominator. A misclick may not mean the same thing across analytics tools. Identify which screen/task produced the most errors and inspect why. Avoid unsupported universal thresholds such as “0–14.9% is low” unless a recognized benchmark and its context are cited.

### 6.4 Drop-off rate

Define whether it refers to leaving the test, abandoning a task, or failing to complete a flow. A 0% drop-off is useful but does not prove that the flow is intuitive; participants may continue despite confusion or may be required to finish by the testing setup.

### 6.5 Error severity

Classify errors:

- minor: hesitation or recoverable mis-tap;
- moderate: user needs to backtrack or use an unintended route;
- critical: task cannot be completed, user loses data, or an unsafe/irreversible action occurs.

### 6.6 SUS (System Usability Scale)

If using SUS, check that:

- all 10 standard items are used without changing their meaning;
- response scale is correct;
- positive/odd and negative/even item scoring is applied correctly;
- each response is converted correctly;
- sum is multiplied by 2.5 for a 0–100 score;
- average is computed over valid participants;
- missing answers are handled consistently;
- raw respondent scores or an auditable calculation are available.

Common standard scoring:

- odd-numbered items: response minus 1;
- even-numbered items: 5 minus response;
- sum adjusted item scores per respondent;
- multiply by 2.5.

SUS is a perceived-usability measure. It is not a direct accessibility conformance test, task-success metric, satisfaction diagnosis, or measure of social impact. Interpret grades and adjective ratings using the cited benchmark, not as a universal absolute.

## 7. Qualitative evidence

Capture:

- participant quotes (with consent and anonymization);
- observed hesitation;
- misunderstood labels;
- wrong assumptions;
- workarounds;
- confidence or frustration expressed by participants;
- suggestions and their context.

Do not make a quote look representative of all users. Explain whether it is one person's experience or a repeated pattern.

## 8. Accessibility testing is distinct

Usability testing with general participants does not validate accessibility for every disability group. Design accessibility tests around relevant needs and methods, such as:

- contrast inspection;
- text scaling/reflow;
- screen-reader test in an implemented environment;
- keyboard/focus test where relevant;
- caption/transcript review;
- target-user task observation;
- accessibility expert review.

For a Figma-only competition, some tests can be specified but not executed. State what is validated now and what is planned for implementation.

## 9. Iteration evidence

An excellent testing story has four stages:

1. **Observation:** what failed, caused hesitation, or created unnecessary effort?
2. **Diagnosis:** why did it happen?
3. **Design change:** what specific component/flow changed?
4. **Re-test:** did the change improve the experience?

If no re-test was done, state that. Do not claim a measured improvement when only the design was changed.

BIBO provides a useful example of a documented response to misclick findings: the deck describes enlarging hit areas and improving interaction flow after reporting an 11.7% average misclick rate. The evidence of a redesign is useful; the reviewer should still request the underlying participant profile and retest data before claiming the fix measurably improved outcomes.

## 10. Result interpretation rules

- 100% task success does not mean the interface is perfect.
- 0% drop-off does not mean there was no confusion.
- A high SUS score does not prove accessibility.
- Low misclick does not necessarily prove efficiency.
- Small samples can still reveal usability problems but limit generalization.
- A test of the prototype cannot validate a real-world service handoff.
- Do not hide unfavorable tasks in an average.
- Do not average incompatible metrics or test populations.

## 11. Required output

Provide:

1. test-method appropriateness;
2. participant profile and limitations;
3. scenario quality;
4. metric formula/denominator audit;
5. result interpretation;
6. qualitative findings;
7. iteration evidence;
8. accessibility validation boundary;
9. corrected, defensible wording for the report;
10. next test recommendations.
