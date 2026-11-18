# Module 3 — Analyzing Information and Drafting Reports

**Shared instructor–participant handout**  
**Time:** 3:15–3:50 PM · **Duration:** 35 minutes  
[Guide](../GUIDE.md) · [Previous](Module02.md) · [Next](Module04.md)

## Purpose and timing

Learn to check source consistency, calculate defensible measures, and draft a report that separates facts from recommendations. Bring the S1–S5 packet, INTAKE-v1, and a calculator. You will produce CALC-v1 and REPORT-v1.

| Clock | Minutes | Work |
|---|---:|---|
| 3:15–3:22 | 7 | Concepts and stage handoffs |
| 3:22–3:28 | 6 | Work through examples |
| 3:28–3:45 | 17 | Complete the final exercise |
| 3:45–3:50 | 5 | Compare results and save |

## Key concepts

Before interpreting data, check periods, units, definitions, and whether categories reconcile. A source table can be internally consistent without proving that the underlying business records are complete. The workshop packet contains aggregates, not individual initiative records.

Portfolio completion uses **total completed / total initiatives**, not the unweighted average of function percentages. Compare rates using percentage points; calculate before rounding. Annualized estimated hours are not realized monthly savings or cash benefits.

If working from a dashboard image, verify transcribed numbers against the image or obtain its underlying table. The supplied use-case PowerPoint contains image-based dashboards; an upload alone does not prove all labels were extracted correctly.

## Worked examples

### Example 1 — Choose the correct denominator

**Input:** Two fictional teams: A completed 1 of 2 initiatives; B completed 9 of 10.

**Inappropriate prompt:** “Average their completion percentages for the portfolio.”

**Inappropriate result:** (50% + 90%)/2 = 70% portfolio completion.

**Why it fails:** The teams have different numbers of initiatives. An unweighted average gives each team equal weight rather than each initiative.

**Appropriate prompt — copy and run:**

```text
Synthetic input: Team A completed 1 of 2 initiatives; Team B completed 9 of 10.
Calculate portfolio completion using summed counts. Show the formula and
explain why averaging team percentages would give a different answer.
Do not infer causes or targets. Leave the calculation for human checking.
```

**Expected result:** (1 + 9)/(2 + 10) × 100 = **83.3%**. Verify 10/12 independently.

### Example 2 — Separate estimates and proposals from facts

**Input:** S1–S5 from [Module 2](Module02.md#copyable-source-packet).

**Inappropriate prompt:** “Convert the 4,000-hour benefit into confirmed cash savings and say owners will finish all reviews by 7 November.”

**Inappropriate output:** “Confirmed savings are $200,000; reviews will finish by 7 November.”

**Why it fails:** The cost rate, realized cash benefit, and agreed deadline are absent.

**Appropriate prompt — paste S1–S5 first:**

```text
Using S1–S5 only, write a two-sentence benefit-and-action statement for
leadership. Preserve the estimated annual-hours qualification. Label actions,
roles, and timing as proposals. Identify missing evidence needed for a cash
benefit claim or a committed deadline. Cite source IDs.
```

**Expected result:** “Completed initiatives represent 4,000 estimated annual hours saved [S1–S2]. Proposed: ask process owners to schedule evidence reviews next month, pending agreement [S4–S5].” No cash estimate or commitment is invented.

## Workflow instructions

Select **PPI Reporting Assistant** through `@`, or use the explicit rules in the exercise prompts. See [Skill selection](Module02.md#how-to-reference-a-skill-in-a-working-prompt). Run ANALYZE first, independently check CALC-v1, then request DRAFT. A request to draft is not a declaration that the finished report is approved.

| Input | Output | Human check |
|---|---|---|
| Original S1–S5 and checked INTAKE-v1 | CALC-v1 | Reconcile statuses and reproduce formulas |
| Sources, checked CALC-v1, outline | REPORT-v1 | Check claims, qualifications, and proposed actions |

In a new conversation, paste the sources and relevant outputs again. A summary of an earlier draft cannot replace the original evidence.

**Instructor tip:** Use six minutes to compare the two examples and check one calculation manually. The following reference cards are for later practice or existing Q&A; do not add them to the live exercise.

## Reference cards — transfer the workflow to other use cases

**Use after class or during existing Q&A.** All figures below are synthetic. The named Skills are suggested custom Skills to create, not built-in features or Skills already installed by these materials. For each, use Module 2's creation approach with the reusable rules below, then select the actual installed Skill through `@`. Without Skills, paste the rules followed by the invocation's task and sources as one ordinary prompt.

### Training and Change Update — CC&T, deck slide 4

**Trigger:** A sponsor needs a training and change-readiness update.

**Context organization:** BRIEF = sponsor decision and cohort; RULES = definitions for attendance, survey response, satisfaction, and adoption; SOURCES = attendance record T1, survey T2, adoption evidence T3; OUTPUTS = intake, metric table, sponsor brief, human review.

**Reusable Skill instructions:** Check cohort and period alignment. Calculate response and satisfaction rates with their respective denominators. Separate delivery, feedback, and observed adoption. If adoption evidence is absent, request it and avoid claiming rollout success. Produce a maximum 150-word sponsor brief with a proposed follow-up. Stop at the requested stage for review.

**Example Skill reference and run**

```text
@Training and Change Update
Run TRAINING-2026-10-v1; stage ANALYZE only.
Audience: change sponsor. Decision: what evidence is needed before expanding rollout?
T1: Synthetic October cohort: 50 attendees.
T2: Same cohort: 20 survey respondents, 19 satisfied.
T3: Adoption outcomes not collected.
Return TRAINING-CALC-v1: formulas, results, limitations, and missing evidence.
Stop before drafting the sponsor brief.
```

**Expected result:** 40.0% response rate and 95.0% satisfaction among respondents; adoption unknown. **Next prompt after human checks:** “Using T1–T3 and checked TRAINING-CALC-v1, draft TRAINING-BRIEF-v1. Propose an adoption-measurement follow-up, not a conclusion that adoption succeeded.” **Human gate:** Validate cohort membership and denominators before the brief; sponsor reviews the proposed follow-up.

### Communications Performance Brief — internal communications, deck slide 7

**Trigger:** A communications manager needs a comparable campaign update.

**Context organization:** BRIEF = edition comparison and decision; RULES = unique-open definition and comparable audience; SOURCES = edition counts C1/C2 and outcome limits C3; OUTPUTS = comparison table, leadership brief, review record.

**Reusable Skill instructions:** Confirm metric definition, periods, and audience comparability. Calculate each open rate, percentage-point difference, and relative change separately. Distinguish reach/engagement from business impact. Draft a factual brief with a proposed next measurement. Stop for human review between stages.

```text
@Communications Performance Brief
Run COMMS-2026-10-v1; stage ANALYZE only.
Decision: what should the next newsletter evaluation measure?
C1: Synthetic October edition: 90 unique opens among 120 recipients.
C2: Synthetic September edition: 80 unique opens among the same 120 recipients.
C3: Same open definition; no productivity or behavior-change measures.
Return COMMS-CALC-v1 with rates, percentage-point change, and limitations.
Stop for my comparison with the source counts.
```

**Expected result:** 75.0% vs 66.7%; +8.3 percentage points; 12.5% relative increase. **Next prompt after checks:** “Draft COMMS-BRIEF-v1 from C1–C3 and checked COMMS-CALC-v1, with one proposed outcome measure. Do not claim a productivity effect.” **Human gate:** Confirm comparable recipients and definitions; review interpretation and message.

### IT Operations Update — IT COE, deck slide 11

**Trigger:** An IT manager needs a weekly workload and incident update.

**Context organization:** BRIEF = week, scope, and operational decision; RULES = ticket status definitions and reconciliation; SOURCES = backlog I1, scope notes I2, SLA evidence I3; OUTPUTS = reconciliation, operations brief, exceptions for review.

**Reusable Skill instructions:** Reconcile opening backlog plus opened minus resolved against closing backlog only when adjustments are ruled out. Keep ticket volume separate from incident severity and SLA attainment. Surface inconsistencies. Draft a maximum 150-word update with proposed follow-up; pause for human review before moving stages.

```text
@IT Operations Update
Run IT-2026-W44-v1; stage ANALYZE only.
Audience: site operations lead. Decision: what follow-up is needed on open work?
I1: Synthetic week ending 30 October 2026: opening backlog 30;
80 tickets opened; 90 resolved; closing backlog 20.
I2: Same queue and definitions; no transfers, merges, or reopened tickets.
I3: No SLA thresholds, eligible-ticket counts, or severity data supplied.
Return IT-CALC-v1: reconciliation, supported observations, and missing evidence.
Stop before drafting; do not infer service quality from ticket counts alone.
```

**Expected result:** 30 + 80 − 90 = 20; backlog fell by 10. SLA compliance and severity impact remain unknown. **Next prompt after checks:** “Draft IT-BRIEF-v1 using I1–I3 and checked IT-CALC-v1. Propose reviewing remaining tickets by age and priority once those fields are supplied.” **Human gate:** Check scope/adjustments against the queue records; verify any SLA claim against actual SLA data.

## Final exercise — analyze and draft a leadership report

**Scenario:** Prepare the October PPI portfolio update so leaders can choose follow-up priorities.

**Time:** 17 minutes practice + 5 minutes comparison.  
**Inputs:** [Complete S1–S5 packet](Module02.md#copyable-source-packet), INTAKE-v1 and outline from Module 2. If you missed Module 2, read the packet and its suggested intake answer before continuing.  
**Deliverables:** CALC-v1 plus REPORT-v1, labeled “Draft — human review pending.”

### Steps

1. **3 minutes:** Confirm source inventory; independently check status totals and weighted completion.
2. **5 minutes:** Run the analysis prompt and inspect formulas and limits.
3. **5 minutes:** After human checks, run the drafting continuation.
4. **4 minutes:** Review the draft with your partner, correct unsupported wording, and save.

### Comprehensive sample prompt — analysis stage

Select the reporting Skill if available. This prompt also supplies the rules for the ordinary-prompt path. Replace both placeholders with the named materials.

```text
BRIEF
Run PPI-2026-10-v1; stage ANALYZE. Audience: site leadership.
Decision: choose next month's follow-up priorities. Snapshot: 31 October 2026.
RULES
Use only S1–S5. Distinguish cumulative counts from monthly completions.
Use summed counts for portfolio completion. Round percentages to one decimal
place after calculation. Preserve estimated annual hours and the synthetic
label. Do not invent targets, cash benefits, causes, or agreed actions.
SOURCES
[Paste complete S1–S5 from Module 2.]
OUTPUTS
[Paste the checked INTAKE-v1 and outline.]

Return CALC-v1 with metric, formula using source values, result, source ID,
and interpretation limit. Include totals for all statuses, open initiatives,
each function's completion, weighted portfolio completion, prior completion,
percentage-point change, net increase in completed count, and annual hours.
Check that status totals reconcile. Flag conflicts rather than choosing a value.
Stop for independent human checks before drafting.
```

### Continuation — send only after checking CALC-v1

```text
I checked CALC-v1 against S1–S5 and independent arithmetic.
Corrections: [enter corrections or “none”]. Apply them before using the values.
Stage DRAFT: produce REPORT-v1 for site leadership, titled
“PPI portfolio: 31 October 2026”. Retain SYNTHETIC WORKSHOP DATA — NOT THERMO
FISHER RESULTS and Draft — human review pending.
Keep report prose at or below 250 words; calculations and checklist are outside
that limit. Include a factual headline, KPI table, two observations, two
proposed actions, limitations, and one decision request. Cite source IDs.
Expand acronyms on first use. Label suggested roles/timing as proposals.
Do not infer causes, financial benefits, targets, or approved deadlines.
Add a human-review checklist. Stop before approval or presentation creation.
```

### Success checklist

- [ ] Counts reconcile and weighted completion is independently checked.
- [ ] Snapshot, units, estimates, and percentage-point change are correct.
- [ ] Claims cite evidence; recommendations are labeled as proposals.
- [ ] Report prose meets the limit and includes limitations and a decision request.
- [ ] Draft remains pending review; original evidence is retained.

### Compare after completing

| Metric | Calculation | Result | Evidence |
|---|---|---:|---|
| Total initiatives | 20 + 15 + 25 + 10 | 70 | S1 |
| Completed | 12 + 9 + 20 + 5 | 46 | S1 |
| In progress | 5 + 4 + 3 + 3 | 15 | S1 |
| Awaiting validation | 3 + 2 + 2 + 2 | 9 | S1 |
| Open initiatives | 15 + 9 | 24 | S1–S2 |
| RTR completion | 12 / 20 × 100 | 60.0% | S1–S2 |
| OTC completion | 9 / 15 × 100 | 60.0% | S1–S2 |
| PTP completion | 20 / 25 × 100 | 80.0% | S1–S2 |
| Customer Care completion | 5 / 10 × 100 | 50.0% | S1–S2 |
| Portfolio completion | 46 / 70 × 100 | 65.7% | S1–S2 |
| Prior completion | 40 / 70 × 100 | 57.1% | S2–S3 |
| Change | (46 / 70 − 40 / 70) × 100 | +8.6 percentage points | S1–S3 |
| Net increase in completed count | 46 − 40 | 6 | S1, S3 |
| Estimated annual hours | 1200 + 600 + 1800 + 400 | 4,000 | S1–S2 |

**Human check:** Status totals reconcile: 46 + 15 + 9 = 70. The unweighted function average is 62.5%, which is **not** the portfolio rate. Completion increased by six in net terms; the packet does not establish a gross count of individual completion events or reopenings during October.

#### Suggested report

**SYNTHETIC WORKSHOP DATA — NOT THERMO FISHER RESULTS**  
**Draft — human review pending**  
**PPI portfolio: 31 October 2026**

##### Completion reached 65.7%; nine initiatives await validation

| KPI | Result |
|---|---|
| Completed / total | 46 / 70 (65.7%) [S1–S2] |
| Change from 30 September | +8.6 percentage points [S1–S3] |
| In progress / awaiting validation | 15 / 9 [S1] |
| Estimated annual hours from completed initiatives | 4,000 [S1–S2] |

**Observations:** Procure to Pay (PTP) has the highest completion rate at 80.0%; Customer Care has the lowest at 50.0%. The packet does not explain the difference. [S1–S2, S4] Three Record to Report (RTR) initiatives await process-owner validation of evidence. [S4]

**Proposed actions:** Ask process owners to schedule evidence reviews next month, beginning with the three RTR cases. Ask the Customer Care lead to review open initiatives and identify barriers before the next leadership discussion. Roles and timing are proposals pending agreement. [S4–S5]

**Limitations:** Hours are annualized estimates, not realized monthly or cash savings. Targets and causes of differences are not supplied. [S2, S4]

**Decision requested:** Agree whether to prioritize validation reviews and a Customer Care status review, then confirm owners and dates.

**Instructor tip:** Allow two minutes to compare calculations and three to discuss report choices and save. Wording may vary; evidence and qualifications should not. If a pair falls behind, let it use the suggested report as REPORT-v1 for Module 4 after checking the calculations. Optional challenge within the same time: identify a useful metric whose inputs are missing.

**Handoff:** Keep S1–S5, checked CALC-v1, and REPORT-v1 separate. Begin verification at 3:50.
