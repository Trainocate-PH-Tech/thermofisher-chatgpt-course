# Module 1 — The Human-in-the-Loop Approach

**Shared instructor–participant handout**  
**Time:** 2:05–2:20 PM · **Duration:** 15 minutes  
[Guide](../GUIDE.md) · [Next](Module02.md)

## Purpose and timing

Learn to distinguish evidence from inference, assign human review responsibilities, and correct misleading claims. You need ChatGPT or the printed examples and a calculator. You will produce three reviewed statements.

| Clock | Minutes | Work |
|---|---:|---|
| 2:05–2:10 | 5 | Read the concepts and workflow |
| 2:10–2:13 | 3 | Walk through the examples |
| 2:13–2:18 | 5 | Complete the final exercise |
| 2:18–2:20 | 2 | Compare answers and hand off |

## Key concepts

Human-in-the-loop (HITL) means people remain responsible for the question, evidence, verification, and release decision. ChatGPT can organize, calculate, draft, and suggest corrections. Fluent wording is not evidence that a claim is correct.

| Reporting standard | Your review question | Evidence of completion |
|---|---|---|
| Accurate | Can I trace and reproduce the claim? | Source references and independent calculations |
| Easy to Understand | Is the message and decision clear? | Plain language and qualified, labeled measures |
| Free from Errors | Have I checked facts, logic, numbers, language, and presentation? | Review checklist and named human reviewer |

“Free from Errors” is a review standard, not a guarantee from the model. A second AI response is not independent evidence. Inspect sources and recompute important figures yourself.

## Worked examples

All figures in this handout are synthetic, not Thermo Fisher results. Inappropriate examples are deliberately flawed; do not reuse them as correct claims.

### Example 1 — Satisfaction does not establish adoption

**Input:** 50 training attendees; 20 survey respondents; 19 satisfied respondents; no adoption measurement.

**Inappropriate prompt:** “Write that our 95% satisfaction proves the rollout succeeded.”

**Inappropriate output:** “The rollout succeeded because 95% of attendees were satisfied.”

**Why it fails:** The denominator is respondents, not attendees, and satisfaction does not establish rollout success.

**Appropriate prompt — copy and run:**

```text
Review this fictional training evidence for a change sponsor:
50 attendees; 20 survey respondents; 19 satisfied respondents;
no adoption or rollout outcome measurement.
Calculate satisfaction among respondents and response rate among attendees.
Draft two sentences separating observed feedback from unmeasured outcomes.
Show formulas and identify what a human should check before sharing.
```

**Expected result:** 19/20 = 95.0% satisfaction among respondents; 20/50 = 40.0% response rate. “Among 20 respondents, 19 were satisfied. Adoption and rollout success have not been measured.” Check survey records and cohort membership.

### Example 2 — A reviewer must actually check

**Input:** A fictional newsletter had 90 unique opens among 120 recipients. Its draft says “90% open rate.”

**Inappropriate prompt:** “Check your previous answer and mark the report approved.”

**Inappropriate output:** “I checked it; the 90% figure is approved.”

**Why it fails:** The arithmetic is wrong and the model cannot supply a human approval decision.

**Appropriate prompt — copy and run:**

```text
Source C1: a fictional newsletter had 90 unique opens among 120 recipients.
Draft claim: “The open rate was 90%.”
Show the formula, correct the claim, and list the human check required.
Do not mark it approved. Leave a blank for the human reviewer's decision.
```

**Expected result:** 90/120 × 100 = 75.0%. The reviewer independently checks the division and the meaning of “unique opens,” then records their decision.

## Workflow instructions

Use `brief + evidence → intake → calculations → draft → human review → presentation`. A human checks the inputs before drafting and checks the output before release.

| Context part | Keep here | Example |
|---|---|---|
| BRIEF | Audience, decision, reporting period, current task | Prepare a leadership update |
| RULES | Reusable definitions, format, review method | Show numerator and denominator |
| SOURCES | Dated evidence with IDs | October counts |
| OUTPUTS | Labeled drafts, calculations, and review records | Report v1, review pending |

These labels organize a message; they are not ChatGPT commands. A Skill can store reusable RULES, but current SOURCES still need to be supplied. Module 2 explains how to select a Skill. An earlier AI draft must not become evidence merely because it is in the conversation.

**Instructor tip:** Ask participants which claims they would check first. Spend the existing five-minute teaching block on these concepts, rather than reading every sentence aloud.

## Final exercise — review a communications update

**Scenario:** A communications manager wants to brief leadership on newsletter engagement. Work in pairs: one operator uses ChatGPT; the reviewer checks sources and arithmetic.

**Time:** 5 minutes practice + 2 minutes comparison.  
**Deliverable:** Three corrected claims, their source references, and a human review record.

### Inputs and sample prompt

This complete prompt includes the evidence; no file upload or Skill is needed.

```text
BRIEF
Review a fictional newsletter update for site leadership. Help distinguish
observed engagement from unmeasured business outcomes.
RULES
Use only the evidence below. Classify each claim as approve, qualify, or reject.
Distinguish percentage points from relative percentage change. Do not invent
causal evidence. Preserve the label SYNTHETIC WORKSHOP DATA.
SOURCES
C1: Latest edition: 90 unique opens among 120 recipients.
C2: Previous edition: 80 unique opens among the same 120 recipients;
the same definition of unique open applies.
C3: No productivity or behavior-change measure was collected.
OUTPUTS TO REVIEW
1. “The latest open rate was 75%.”
2. “Open rate improved by 8.3%.”
3. “The newsletter increased employee productivity.”

Return a table: claim, approve/qualify/reject, source ID, formula, corrected
wording, and human check required. End with a blank reviewer/decision record.
Do not claim human approval or distribute the result.
```

### Steps

1. **1 minute:** Classify the claims before running the prompt.
2. **2 minutes:** Run it and inspect the suggested corrections.
3. **1 minute:** Independently calculate the two rates and their difference.
4. **1 minute:** Agree the corrected wording and complete a review record.

### Success checklist

- [ ] All three claims have a source reference and a justified decision.
- [ ] Rates and percentage-point change are independently checked.
- [ ] No unsupported productivity claim remains.
- [ ] A person records the review decision.

### Compare after completing

| Claim | Suggested answer |
|---|---|
| Latest rate 75% | Approve: 90/120 = 75.0%, C1 |
| Improvement 8.3% | Correct to +8.3 percentage points: (90/120 − 80/120) × 100. Previous rate = 66.7%. Relative increase is 12.5%, C1–C2. |
| Increased productivity | Reject: no productivity evidence, C3. “Opens increased; productivity impact was not measured.” |

Review record: **Reviewer ____ · Calculation checked ____ · Correction ____ · Decision ____**.

**Instructor tip:** Use the two-minute comparison to discuss the denominator and unsupported causal claim. If access fails, review the printed examples. Stop at 2:20.

**Handoff:** Bring the evidence/claim distinction into Module 2. Optional challenge within the same time: name the evidence needed to investigate a productivity effect.
