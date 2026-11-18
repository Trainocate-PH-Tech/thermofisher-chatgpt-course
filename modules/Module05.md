# Module 5 — Making Reports Easy to Understand and Presentation-Ready

**Shared instructor–participant handout**  
**Time:** 4:15–4:40 PM · **Duration:** 25 minutes  
[Guide](../GUIDE.md) · [Previous](Module04.md)

## Purpose and timing

Learn to transform a reviewed report into a clear executive storyboard using honest charts and the supplied palette. Bring S1–S5, checked calculations, REPORT-v2, and its human review record. You will produce and peer-review STORYBOARD-v1.

| Clock | Minutes | Work |
|---|---:|---|
| 4:15–4:20 | 5 | Message, evidence, and visual principles |
| 4:20–4:24 | 4 | Work through examples |
| 4:24–4:36 | 12 | Complete the final exercise |
| 4:36–4:40 | 4 | Compare and finish peer review |

## Key concepts

A leadership presentation should answer three questions: **What happened? What needs attention? What decision is needed?** Give each slide one main message. Keep evidence, interpretations, and proposed actions distinct when shortening a report.

A horizontal bar chart is suitable for comparing function completion rates. Use a 0–100% scale and label both percentages and completed/total counts. Completion rate alone does not explain causes or establish team efficiency. Dense dashboards can be references rather than opening slides.

| Role | Supplied color | Practical use |
|---|---|---|
| Primary red | `#E71316` | Title accent or one highlighted point |
| Dark red | `#A6192E` | Optional secondary emphasis |
| Dark gray | `#54585A` | Body text and labels |
| White | `#FFFFFF` | Main background |
| Optional teal | `#00677F` | Sparse secondary accent |

Follow [Colors.png](../Colors.png): red, white, and gray are foundational; accents are sparse and reds should not be tinted pink. Use readable contrast and direct labels, not color alone. This handout specifies the design; it does not create a PowerPoint theme.

## Worked examples

### Example 1 — A shorter headline must retain meaning

**Input:** S1–S2 support 4,000 estimated annual hours associated with completed initiatives.

**Inappropriate prompt:** “Make the result impressive. Remove qualifications and show monthly savings.”

**Inappropriate title:** “4,000 hours saved this month.”

**Why it fails:** Removing “estimated annual” changes the period and certainty of the claim.

**Appropriate prompt — copy and run:**

```text
Synthetic fact: completed initiatives represent 4,000 estimated annual hours
saved, not realized monthly hours or cash savings. Write a leadership slide
title of at most 12 words that preserves this meaning. Add one explanatory
bullet and a synthetic-data/source footer. Source: S1–S2, 31 October 2026.
```

**Expected title:** “Completed initiatives represent 4,000 estimated annual hours saved.” The bullet explains what is not measured; the footer preserves date and source.

### Example 2 — Visual emphasis must not distort the comparison

**Input:** Procure to Pay 20/25; Record to Report 12/20; Order to Cash 9/15; Customer Care 5/10.

**Inappropriate prompt:** “Start the bars at 50% so the difference looks dramatic; label Customer Care a failed team.”

**Inappropriate result:** A truncated bar chart and an unsupported performance judgment.

**Why it fails:** It exaggerates differences and supplies a cause/target judgment absent from the evidence.

**Appropriate prompt — copy and run:**

```text
Use these synthetic completion counts: Procure to Pay 20/25; Record to Report
12/20; Order to Cash 9/15; Customer Care 5/10. Specify a horizontal bar chart
with a 0–100% axis, direct rate and count labels, white background, and dark
gray text. Red may highlight a follow-up question, not an unprovided target.
Give a factual title; do not infer causes or team capability. Source: S1–S2.
```

**Expected result:** 80.0%, 60.0%, 60.0%, 50.0%, each with its denominator. A suitable title is “Completion rates vary; causes need investigation.”

## Workflow instructions

Select **PPI Reporting Assistant** with `@` and request PRESENT, or use the explicit exercise instructions. Supply REPORT-v2 and its actual review record, checked calculations, original S1–S5, and visual rules. Do not include obsolete drafts as competing factual inputs.

A transformation can introduce a new error, so review the storyboard even when the report was checked. A missing review record should trigger a request or draft label, never invented approval. Creating a PowerPoint file is optional later work, not part of this timed activity.

**Instructor tip:** Use the five-minute teaching block for one-message slides, chart honesty, and context selection; use four minutes for the two worked examples.

## Take-home reference — restart the workflow next reporting period

Save the reusable method separately from each run's evidence and outputs. These are suggested local folder/document labels, not folders automatically created in ChatGPT:

```text
Reporting workflow/
  Reusable rules and template
  2026-10/ brief, sources, calculations, report, review, storyboard
  2026-11/ new brief and new sources; outputs pending
```

Start a new run with the same installed Skill or pasted instructions. Supply the new period's sources explicitly; retain the old report only as a style example or clearly identified comparator. Do not imply cross-chat memory or file access merely by naming an old artifact.

```text
[Select PPI Reporting Assistant using @, or paste the workflow instructions.]
Start run PPI-2026-11-v1, stage INTAKE only.
Use the new evidence pasted below. The October report is a style example only;
do not carry forward its counts, conclusions, deadlines, or approval status.
Return a source inventory, missing definitions, and valid comparison options.
If prior data is needed but absent, ask for it. Stop for my review.
[Paste new brief, definitions, and sources with dates and IDs.]
```

**Handoff to a new conversation:** Include the run ID, requested stage, source packet, relevant checked output, human review record, and unresolved questions. A handoff summary helps navigation but does not replace evidence. This is a repeatable, human-driven workflow; scheduling, external-system access, and automatic distribution require separate capabilities and are not configured by these prompts.

## Final exercise — create and review the executive storyboard

**Scenario:** Deliver a three-minute leadership update using the verified workshop report. This exercise combines context organization, source-grounded analysis, human review, and presentation design from the whole workshop.

**Time:** 12 minutes practice + 4 minutes comparison.  
**Inputs:** [S1–S5](Module02.md#copyable-source-packet), checked CALC-v1, REPORT-v2, and its human review record. If you missed earlier work, use the Module 3 [suggested report](Module03.md#suggested-report), check it using Module 4, and record your decision before continuing.  
**Deliverable:** STORYBOARD-v1 with three slides, chart data, presentation narration, source footers, and a peer-review record.

### Steps

1. **2 minutes:** Choose the core message and decision from the reviewed report.
2. **4 minutes:** Run the comprehensive prompt.
3. **3 minutes:** Compare every number, title, axis, qualification, and source with the reviewed inputs.
4. **3 minutes:** Correct the storyboard and rehearse a 60-second summary with your partner.

### Comprehensive sample prompt

Select the reporting Skill using `@` if available. Replace each input placeholder; do not assume a new conversation can retrieve prior work.

```text
BRIEF
Run PPI-2026-10-v1; stage PRESENT. Audience: site leadership.
Create STORYBOARD-v1 for a three-minute update about next month's priorities.
RULES
Use only the supplied sources and human-reviewed report. Do not add facts,
targets, causal claims, financial benefits, approved owners, or deadlines.
Preserve estimated annual-hours wording and proposed-action labels.
If the report, sources, or actual human review record is missing, ask for it.
SOURCES
[Paste complete S1–S5 from Module 2.]
REVIEWED OUTPUTS
[Paste checked CALC-v1, REPORT-v2, and its human review record.]

Produce exactly three slides:
1. Portfolio progress and material limitations.
2. Function completion comparison and evidence-based follow-up needs.
3. Proposed actions and the leadership decision requested.
For each: message-led title (at most 12 words), at most three short bullets,
visual specification with exact data/units/labels, 40–60 words of narration,
and a footer with SYNTHETIC WORKSHOP DATA — NOT THERMO FISHER RESULTS,
snapshot 31 October 2026, and source IDs.
Use a 0–100% horizontal completion bar chart with completed/total counts.
Use white #FFFFFF backgrounds, dark gray #54585A text, red #E71316 emphasis,
and optional dark red #A6192E or teal #00677F sparingly. No pink tints or
color-only meaning. Keep text and labels readable.
End with a peer-review checklist covering facts, calculations, logic, wording,
visual design, and source traceability. Stop for human review; do not publish.
```

### Continuation after peer review

```text
Revise STORYBOARD-v1 using this human feedback: [paste specific corrections].
Preserve checked figures, source IDs, date, synthetic label, estimate/proposal
qualifications, and the 0–100% scale. Name the revision STORYBOARD-v2 and list
changes. Flag anything unresolved; leave the final decision to the reviewer.
```

### Success checklist

- [ ] Three slides with one message each and an explicit leadership decision.
- [ ] All claims trace to original evidence and the reviewed report.
- [ ] Chart values, counts, scale, and footers are correct.
- [ ] No material qualification was lost when shortening text.
- [ ] Color and labeling follow the supplied guidance.
- [ ] A person has checked the transformed output and recorded remaining issues.

### Compare after completing

The following is one acceptable storyboard. Match its evidence and qualifications, not necessarily its exact wording.

#### Output slide 1: Completion reached 65.7%, up 8.6 percentage points

**Bullets**

- 46 of 70 initiatives completed at the October snapshot.
- Nine await validation; 15 remain in progress.
- Completed initiatives represent 4,000 estimated annual hours saved.

**Visual specification:** Three directly labeled KPI cards: “46/70 · 65.7% complete”; “+8.6 percentage points vs 30 September”; “4,000 estimated annual hours · completed initiatives.” Red title accent, dark gray text, white background. No unlabeled savings icon or currency symbol.

**Suggested presentation narration:** “Completion is 65.7% across the same 70-initiative portfolio, compared with 57.1% in September. The completed count increased by six net. The 4,000-hour figure is an annualized estimate associated with completed initiatives; it is not a measurement of hours realized in October or confirmed financial savings.”

**Footer:** SYNTHETIC WORKSHOP DATA — NOT THERMO FISHER RESULTS · Snapshot: 31 October 2026 · S1–S3.

#### Output slide 2: Completion rates vary; causes need investigation

**Bullets**

- Procure to Pay has the highest completion rate at 80.0%.
- Customer Care is at 50.0%; the packet does not establish why.
- Three Record to Report initiatives await evidence validation.

**Visual specification:** Horizontal bars, axis 0–100%, ordered as below. Use gray bars with direct labels; optionally highlight Customer Care in red to indicate a follow-up question, not a failed target. No target line is supplied.

| Function | Completed / total | Rate |
|---|---:|---:|
| Procure to Pay | 20 / 25 | 80.0% |
| Record to Report | 12 / 20 | 60.0% |
| Order to Cash | 9 / 15 | 60.0% |
| Customer Care | 5 / 10 | 50.0% |

**Suggested presentation narration:** “These rates compare completion status, not efficiency or team capability. The functions have different portfolio sizes, so the labels show both counts and rates. We should investigate Customer Care's open work before explaining its rate. Separately, the notes identify three Record to Report cases awaiting process-owner evidence validation.”

**Footer:** SYNTHETIC WORKSHOP DATA — NOT THERMO FISHER RESULTS · Snapshot: 31 October 2026 · S1–S2, S4.

#### Output slide 3: Agree follow-up priorities, then confirm owners and dates

**Bullets**

- Proposed: schedule evidence reviews, beginning with the three RTR cases.
- Proposed: review Customer Care's open work to identify barriers.
- Decision requested: agree priorities and confirm responsible roles and dates.

**Visual specification:** A simple action table, not a chart.

| Proposed action | Proposed responsible role | Proposed timing |
|---|---|---|
| Schedule validation evidence reviews | Relevant process owners | Next month, pending agreement |
| Review Customer Care open initiatives | Customer Care lead | Before next leadership discussion, pending agreement |

**Suggested presentation narration:** “These actions are recommendations for discussion, not recorded commitments. The review calendar is not finalized. Leadership can decide whether to prioritize the evidence reviews and Customer Care review, then assign responsibility and agree dates. We should avoid promising a completion deadline until the relevant owners confirm feasibility.”

**Footer:** SYNTHETIC WORKSHOP DATA — NOT THERMO FISHER RESULTS · Snapshot: 31 October 2026 · S4–S5 · Actions are proposals.

**Peer-review record:** Reviewer ____ · Version checked ____ · Correction made ____ · Remaining issue ____ · Ready for workshop presentation / Revise ____.

**Instructor tip:** Use two minutes to compare a participant output with the example and two to finish the checklist. Optional extension within the existing practice time: write a two-sentence email introducing the storyboard without adding claims.

**Handoff:** Save the report, sources, calculations, review record, and storyboard. Begin Q&A at 4:40; the closing remains 4:55–5:00.
