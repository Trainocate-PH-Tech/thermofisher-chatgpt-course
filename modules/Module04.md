# Module 4 — Verifying Accuracy and Correcting Errors

**Shared instructor–participant handout**  
**Time:** 3:50–4:15 PM · **Duration:** 25 minutes  
[Guide](../GUIDE.md) · [Previous](Module03.md) · [Next](Module05.md)

## Purpose and timing

Learn to audit five error categories, correct a report, and record an honest human review decision. Bring original S1–S5, checked CALC-v1, REPORT-v1, and a calculator. You will produce REVIEW-v1 and corrected REPORT-v2.

| Clock | Minutes | Work |
|---|---:|---|
| 3:50–3:55 | 5 | Review concepts and version control |
| 3:55–3:59 | 4 | Work through examples |
| 3:59–4:11 | 12 | Complete the final exercise |
| 4:11–4:15 | 4 | Compare answers and record the decision |

## Key concepts

ChatGPT can identify suspected errors; people verify against original evidence and independent calculations. A second model response is not independent evidence. A source ID is useful only if you inspect what that source actually says.

| Error category | What to inspect |
|---|---|
| Factual | Date, scope, source, status, and definitions |
| Numerical | Denominator, total, units, and rounding |
| Logical | Unsupported causal inference, target, or commitment |
| Language | Grammar, ambiguity, and unexplained acronyms |
| Presentation | Scale, labels, qualifications, and source/date footer |

Prioritize errors that would change a decision. A grammatically correct report can still contain a false savings claim. If a source changes, recalculate affected measures and review affected claims; approval does not automatically transfer to a new version.

## Worked examples

### Example 1 — Proofreading does not verify facts

**Input:** S1–S5 says 4,000 estimated annual hours, with no cash benefit or AI-causation evidence.

**Inappropriate prompt:** “Make this sound professional: We saved 4,000 hours in October because of AI.”

**Inappropriate output:** “AI enabled 4,000 hours of operational savings during October.”

**Why it fails:** It improves grammar while retaining unsupported period and causal claims.

**Appropriate prompt — paste S1–S5 first:**

```text
Audit “We saved 4,000 hours in October because of AI” against S1–S5.
Return exact claim, issue category, source, correction, and independent human
check needed. Preserve estimate and period qualifications. Do not invent
supporting evidence or treat your audit as human approval.
```

**Expected correction:** “Completed initiatives represent 4,000 estimated annual hours saved [S1–S2]. AI attribution and realized October savings are not established [S2, S4].” Independently sum the function values and inspect the definitions.

### Example 2 — Fix the statement without rewriting the evidence

**Input:** Fictional source A says 46 completed; source B says 48. Neither has been identified as authoritative.

**Inappropriate prompt:** “Use 48 because it makes the result look better.”

**Inappropriate output:** “48 completed; verified.”

**Why it fails:** The model resolves an evidence conflict by preference and invents verification.

**Appropriate prompt — copy and run:**

```text
Two fictional sources conflict: A reports 46 completed, B reports 48.
No authoritative source or explanation is supplied. Log the discrepancy,
identify the question for the data owner, and mark completion-based claims
pending resolution. Do not choose a count or invent approval.
```

**Expected result:** An unresolved discrepancy with a request to confirm period, definitions, and authoritative count. This is a separate mini-example; do not add source B to the workshop's S1–S5 packet.

## Workflow instructions

Select the installed reporting Skill with `@`, or use the explicit REVIEW instructions in the exercise. Keep original sources, checked calculations, and drafts in separate labeled blocks. Audit REPORT-v1 against S1–S5, not against a summary derived from the draft.

Save findings as REVIEW-v1. After resolving them with source checks, create REPORT-v2 and a change list. A human records the version checked and decision. “Ready for workshop storyboard” is not authorization for corporate distribution.

**Instructor tip:** Explain the review categories and version change within the existing five-minute instruction block. Spend four minutes comparing the worked examples; do not perform an additional full audit before practice.

## Final exercise — audit, correct, and decide

**Scenario:** A polished PPI draft contains misleading claims. Find its errors, then apply the review method to your own Module 3 draft.

**Time:** 12 minutes practice + 4 minutes comparison.  
**Inputs:** [S1–S5](Module02.md#copyable-source-packet), checked CALC-v1, REPORT-v1, and the flawed example below. If you missed Module 3, use its [suggested report](Module03.md#suggested-report) after checking its calculation key.  
**Deliverables:** Flawed-example error log, REVIEW-v1 for your report, corrected REPORT-v2, and human review record.

### Deliberately flawed input — not a correct report

Label this **FLAWED-EXAMPLE**. Never overwrite REPORT-v1 with it or treat it as source evidence.

```text
PPI October 2026 Results — Approved for circulation

Our portfolio is 62.5% complete: 46 of 70 initiatives. Completion rose from
57.1% to 65.7%, an improvement of 8.6%. We completed 46 initiatives in October.
We saved 4,000 hours this month, worth $200,000 in confirmed cost savings.
AI caused the improvement. Customer Care is underperforming because its team
resists change, while PTP exceeded the corporate target.

All nine validation cases are in RTR. The nine initiatives awaiting validation
is already complete and may be added to the 46 completed initiatives.
The process owners have agreed to finish every review by 7 November.

Suggested slide: use an unlabeled bar chart, start its vertical axis at 50%,
omit the source and snapshot date, and show “4,000 hours saved” as the headline.
```

### Steps

1. **2 minutes:** Mark errors in FLAWED-EXAMPLE before running ChatGPT.
2. **3 minutes:** Run the sample audit; independently check completion and hours.
3. **3 minutes:** Compare the key and resolve the material errors.
4. **4 minutes:** Audit REPORT-v1, apply source-supported corrections, and record the decision against REPORT-v2.

### Comprehensive sample prompt — audit stage

Select the reporting Skill if available. Replace the source and draft placeholders with the specified text.

```text
BRIEF
Run PPI-2026-10-v1; stage REVIEW. Audience: site leadership.
Check FLAWED-EXAMPLE for accurate, understandable, error-free reporting.
RULES
Use original S1–S5 as evidence; the draft is not a source. Check factual,
numerical, logical, language, and presentation errors. Do not invent missing
facts or approvals. Preserve the synthetic label and snapshot qualifications.
SOURCES
[Paste complete S1–S5 from Module 2.]
OUTPUT TO AUDIT: FLAWED-EXAMPLE
[Paste the deliberately flawed report above.]

Return an error log: quoted claim, category, source ID, formula/check,
proposed correction, and human check required. Flag every unsupported cause,
financial benefit, target, commitment, and approval. Check chart instructions.
Stop before rewriting so I can resolve findings against the sources.
```

### Continuation — review your own draft

```text
Now audit REPORT-v1 below using the same method and original S1–S5.
Use the independently checked CALC-v1 as a calculation aid, not a replacement
for sources. Return REVIEW-v1; keep it separate from the flawed-example log.
[Paste CALC-v1 and your REPORT-v1 from Module 3.]
Stop for my review of discrepancies before producing REPORT-v2.
```

After checking the findings, send:

```text
I checked REVIEW-v1 against S1–S5. Resolved corrections: [list corrections,
or state no corrections needed]. Unresolved items: [list, or “none”].
Apply only supported corrections. Produce REPORT-v2 with a change list,
retaining the original report structure, synthetic label, source IDs, and
material limitations. Flag unresolved issues. Leave release status pending
my review; provide a blank human review record naming REPORT-v2.
```

### Success checklist

- [ ] Identify at least six flawed-example issues, including weighted rate, hours period, and an unsupported claim.
- [ ] Correct all remaining material errors revealed by the key before reusing any text.
- [ ] Independently check calculations and source definitions.
- [ ] Preserve proposals, limitations, source IDs, and the synthetic label.
- [ ] Record the actual human decision against the corrected version.

### Compare after completing

| Error | Correction / evidence |
|---|---|
| “Approved for circulation” | No human approval exists yet; mark draft. S5 and workshop review process. |
| “62.5% complete” | 46 / 70 = 65.7%; 62.5% is the unweighted mean of function rates. S1–S2. |
| “Improvement of 8.6%” | +8.6 **percentage points**; relative increase is 15.0%. S1–S3. |
| “Completed 46 initiatives in October” | 46 is cumulative at the snapshot; completed count increased by six net. S1, S3. |
| “4,000 hours this month” | 4,000 estimated annual hours from completed initiatives. S1–S2. |
| “$200,000 confirmed cost savings” | No cost rate or verified cash benefit is supplied; remove. S2. |
| “AI caused the improvement” | Causal evidence is absent; remove. S4. |
| Customer Care “resists change” | Unsupported explanation; request evidence about barriers. S4. |
| PTP “exceeded the corporate target” | No target is supplied; report its 80.0% completion without target claims. S1–S2. |
| “All nine validation cases are in RTR” | RTR has three; the portfolio has nine. S1, S4. |
| Awaiting validation counted as complete | Statuses are mutually exclusive; keep nine separate from 46. S1–S2. |
| “Initiatives … is” | Subject–verb agreement: “initiatives … are”; also correct the underlying claim. |
| “Agreed … by 7 November” | Calendar is not finalized; any role/date must be labeled a proposal. S4–S5. |
| Chart scale and missing context | Use a labeled 0–100% completion axis; include values, denominators, source, and date. |
| “4,000 hours saved” headline | Preserve “estimated annual” and “completed initiatives”; retain synthetic label. S1–S2, S5. |
| Unexpanded acronyms | Expand Record to Report and Procure to Pay on first use. S5. |

A suitable corrected passage is: “At 31 October, 46 of 70 initiatives were complete (65.7%), up 8.6 percentage points from September. Completed initiatives represent 4,000 estimated annual hours saved, not realized monthly or confirmed cash savings. Nine await validation, including three in Record to Report. Review dates remain proposals. [S1–S5]” The remaining narrative must also avoid invented causes and targets.

Your own report may have fewer errors than FLAWED-EXAMPLE. Do not manufacture findings to reach a quota. Record what you actually checked.

```text
Reviewer: ____________________   Review date: ____________________
Version checked: REPORT-v2     Sources checked: ___________________
Independent calculations: ________________________________________
Corrections made: ________________________________________________
Unresolved items: ________________________________________________
Decision: Ready for workshop storyboard / Revise before storyboard
```

**Instructor tip:** Use the four-minute comparison to reveal missed errors and finish the record. If needed, supply the Module 3 suggested report, have the pair check its headline calculations, and record its review before moving on. Optional challenge: explain why relative change uses unrounded counts, (46−40)/40 = 15.0%.

**Handoff:** Carry original S1–S5, checked calculations, REPORT-v2, and its human review record to Module 5. Stop at 4:15.
