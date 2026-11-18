# Thermo Fisher — Shared Workshop Handout Guide

**Duration:** 3 hours · **Schedule:** 2:00–5:00 PM, local workshop time  
**Audience:** Managers; approximately 70% beginner and 30% intermediate users  
**Main tool:** ChatGPT Enterprise · **Format:** short teaching segments, demonstrations, paired practice, and human review

## Workshop outcome

Participants will use ChatGPT to turn supplied information into a concise management report and a three-slide executive storyboard. They will practice the human-in-the-loop (HITL) approach: people frame the question, check the evidence, independently verify material calculations, and approve the result.

Every output is assessed against the requirements' three standards: **Accurate**, **Easy to Understand**, and **Free from Errors**. AI-generated work remains a draft until a person has reviewed it. Passing a workshop checklist does not guarantee that a real business report is error-free.

### Materials and source boundaries

- [REQUIREMENTS.md](REQUIREMENTS.md) supplies the audience, objectives, module order, and exact schedule.
- [Use-case PowerPoint](<Used Cases - Thermo Fisher.pptx>) supplies organizational context: CC&T/training (slide 4), internal communications (slides 6–7), PPI (slide 9 and appendix slides 13–16), and IT operations (slide 11). Slide numbers count from the beginning of the deck. Some substantive content is embedded as images.
- [Colors.png](Colors.png) supplies the presentation palette. Module 5 translates it into practical design instructions.
- The common exercise uses **invented PPI data**, not actual company performance. It is embedded in [Module 2's source packet](modules/Module02.md#copyable-source-packet), with stable source IDs S1–S5.
- Each module is a shared instructor–participant handout with explanations, inappropriate/appropriate examples, workflow instructions, and a final exercise. Suggested answers follow each exercise under **Compare after completing**. They are readable in Markdown or print; there is no separate instructor edition.

## The workflow participants will build

The workshop organizes context before asking for output. Participants keep four labeled parts: **BRIEF** (audience, decision, period, stage), **RULES** (reusable method), **SOURCES** (dated evidence), and **OUTPUTS** (versioned work and human review). A Skill can hold RULES; it does not replace current evidence or a human approval record.

| Module | Workflow stage | Artifact handed to the next module |
|---|---|---|
| 1 | Frame the work and assign human checkpoints | Evidence/claim distinction |
| 2 | Organize context and run INTAKE | PPI-2026-10-v1 brief, sources, INTAKE-v1, outline, Skill reference/fallback |
| 3 | ANALYZE, human check, then DRAFT | CALC-v1 and REPORT-v1 |
| 4 | REVIEW, correct, and record human decision | REVIEW-v1 and reviewed REPORT-v2 |
| 5 | PRESENT and peer-review | STORYBOARD-v1 with sources and qualifications |

These names are teaching conventions, not product commands. Typing a filename or source ID does not upload its content. New conversations need the relevant evidence and handoff pasted or attached again. A revised source requires renewed checks of affected calculations and claims.

**Delivery rule:** Keep PPI as the one live end-to-end case. The training, communications, and IT workflow cards in Module 3 are reference/take-home adaptations. Discuss key concepts within the instruction blocks, walk through the paired examples during demonstrations, and complete each final exercise during practice. Do not read the whole handout aloud. No additional activity or minutes are added.

## Exact run of show

| Clock | Minutes | Session | Required output |
|---|---:|---|---|
| 2:00–2:05 | 5 | Opening and setup | Participants understand the outcome and review standards |
| 2:05–2:20 | 15 | [Module 1: Human-in-the-Loop](modules/Module01.md) | Three reviewed claims |
| 2:20–2:55 | 35 | [Module 2: Structured Prompting](modules/Module02.md) | Organized context packet, INTAKE-v1, and Skill reference/fallback |
| 2:55–3:15 | 20 | Break | Save work before leaving |
| 3:15–3:50 | 35 | [Module 3: Analysis and Drafting](modules/Module03.md) | Draft report, calculations, and limitations |
| 3:50–4:15 | 25 | [Module 4: Verification](modules/Module04.md) | Error log and human review record |
| 4:15–4:40 | 25 | [Module 5: Presentation Readiness](modules/Module05.md) | Three-slide storyboard with peer review |
| 4:40–4:55 | 15 | Q&A | Questions resolved or assigned follow-up |
| 4:55–5:00 | 5 | Closing | Individual next-use commitment |
| **Total** | **180** | **Includes all transitions, practice, break, and Q&A** | |

Module time totals **135 minutes**. Required hands-on activities total **61 minutes** (5 + 15 + 17 + 12 + 12), already included in the module time. Demonstrations and debriefs are also included, not additional sessions.

## How to use the shared handouts

Each module ends with a comprehensive exercise covering that module's concepts. Follow its input instructions before sending a prompt. Bracketed placeholders require the named packet, output, or actual reviewer feedback; they are not automatic file references. For staged exercises, send continuation prompts only after doing the stated human checks.

| Module | Inappropriate/appropriate comparisons | Final answer comparison |
|---|---|---|
| 1 | Satisfaction versus adoption; AI self-approval versus human checking | [Reviewed communications claims](modules/Module01.md#compare-after-completing) |
| 2 | Balanced brief; selected Skill and supplied evidence; explicit Markdown template versus vague formatting | [Intake and outline](modules/Module02.md#compare-after-completing) |
| 3 | Averaged percentages versus weighted rate; invented cash/commitments versus qualified facts/proposals | [Calculations and report](modules/Module03.md#compare-after-completing) |
| 4 | Proofreading versus evidence audit; preferred count versus unresolved source conflict | [Error key and review record](modules/Module04.md#compare-after-completing) |
| 5 | Misleading savings title versus qualified headline; distorted chart versus honest comparison | [Three-slide storyboard](modules/Module05.md#compare-after-completing) |

**For participants:** Work with your partner, inspect the sources, record corrections, and compare answers after attempting the task. Keep the original evidence with the outputs.

**For instructors:** Use the handout's pacing table and short tips. Answer comparisons are visible rather than hidden, so ask participants not to consult them early. For print distribution, supply all five handouts so linked source packets are available. The Skills fallback and offline examples support the same learning objectives.

## Preparation checklist

### Before the workshop

- [ ] Distribute these Markdown materials and make the source packet easy to copy.
- [ ] Confirm participants can sign in to the intended Enterprise workspace and send a prompt.
- [ ] Check Skills availability with a representative participant account, not just an administrator account. Test creation and use if permitted; prepare the ordinary-prompt fallback regardless.
- [ ] Prepare one working PPI Reporting Assistant Skill for demonstration if access permits. Sharing or publishing to the workspace is not required.
- [ ] Check whether file upload is available if the facilitator wants to demonstrate it. Core exercises use pasted text and do not depend on file uploads or connected apps.
- [ ] Ask participants to bring a laptop and a calculator or spreadsheet for independent arithmetic checks. Pair beginners with intermediate users where practical.
- [ ] Keep the provided illustrative outputs accessible in case of network, login, or generation delays.
- [ ] Review the source packet and recalculate the answer key. Prepare a visible timer.
- [ ] Follow the organization's approved data-handling practices. Participants need no real confidential operational data for this workshop.
- [ ] Recheck the official Skills documentation shortly before delivery; product interfaces and workspace availability may change.

### Room and facilitation setup

Use pairs with one operator and one reviewer; switch roles in Module 3. In remote delivery, use pairs in breakout rooms with the same timer. The reviewer checks source evidence and calculations while the operator works with ChatGPT. Both participate in the final approval decision.

Participants and instructor use the same handout. Read the short concepts, compare the labeled inappropriate and appropriate examples, then complete the final exercise before consulting **Compare after completing**. Instructor tips explain pacing and fallbacks; participants may read them too. Model wording can vary: evaluate evidence and behavior rather than exact phrasing. Inappropriate examples are deliberately flawed teaching material, not recommendations.

## Opening: 2:00–2:05 PM

| Minutes | Facilitator action |
|---|---|
| 0–2 | Introduce the outcome: a useful, verified report and presentation storyboard. Explain the three reporting standards. |
| 2–4 | Confirm pairs and access; point everyone to the source packet and copyable prompts. |
| 4–5 | Explain that all exercise data is synthetic, introduce operator/reviewer roles, and begin Module 1 on time. |

**Suggested opening:** “Today we will use ChatGPT to accelerate reporting while keeping human judgment and accountability. You will leave with a reusable prompt, a reviewed report, and a three-slide storyboard. Our test is whether each output is accurate, easy to understand, and checked for errors.”

## Modules and required activities

### Module 1 — Human-in-the-Loop, 15 minutes

**Teaching:** What AI can draft, what people must check, and how to distinguish evidence from unsupported inference.

**Final exercise 1, 5 minutes:** Use the fictional newsletter source card. Classify three claims, ask ChatGPT for an audit, independently compute the rates, and write corrected statements. The source card and prompt are in [Module 1](modules/Module01.md#final-exercise--review-a-communications-update).

**Success check:** Participants identify 75.0% latest open rate, 66.7% prior open rate, +8.3 percentage points (12.5% relative increase), and no demonstrated productivity effect.

**Handoff:** Carry the source-checking habit into the shared PPI case.

### Module 2 — Structured Prompting, 35 minutes

**Teaching:** Task, audience, sources, constraints, format, and verification. Include simple Markdown headings, emphasis, lists, tables, and review checkboxes; distinguish a rendered report from a raw reusable template. Demonstrate prompt improvements, the supplied formatting example, and Skill selection within the existing seven-minute demonstration.

**Final exercise 2, 15 minutes:** Organize S1–S5 into the four context parts (3 minutes), create/reuse and reference a Skill or use ordinary instructions and run intake (5), check intake and create the Markdown report outline TEMPLATE-v1 (4), then peer-review formatting and save the outputs (3). Full instructions and creation prompt are in [Module 2](modules/Module02.md#final-exercise--build-and-run-a-reporting-brief).

**Success check:** All six prompt components and four context labels appear; the source inventory matches the supplied packet. The outline preserves the synthetic label and distinguishes facts from proposals. The Skill or fallback flags missing evidence and retains human review.

**Handoff:** Save the packet, prompt, INTAKE-v1, and Markdown outline TEMPLATE-v1 before the 20-minute break. Do not let setup overrun 2:55.

### Module 3 — Analysis and Drafting, 35 minutes

**Teaching:** Source consistency, weighted portfolio rates, percentage-point comparisons, and qualified benefit statements.

**Final exercise 3, 17 minutes:** Independently check inputs (3 minutes), run and inspect analysis (5), draft the report (5), then revise and save (4). Use the prompts and calculation key in [Module 3](modules/Module03.md#final-exercise--analyze-and-draft-a-leadership-report).

**Success check:** Report prose is at most 250 words, with a calculation appendix and human checklist outside that limit. It includes a decision request, evidence-based observations, proposed actions, and limitations.

**Handoff:** Save CALC-v1 and REPORT-v1, labeled “Draft — human review pending,” for Module 4. Use the supplied example if a pair falls behind.

### Module 4 — Verification, 25 minutes

**Teaching:** Factual, numerical, logical, language, and presentation checks. AI auditing is a support tool; source inspection and independent calculations establish verification.

**Final exercise 4, 12 minutes:** Read the deliberately flawed report (2 minutes), audit and recalculate (3), compare/correct (3), then audit and correct the pair's own draft and record its review (4). The flawed report, complete answer key, and release checklist are in [Module 4](modules/Module04.md#final-exercise--audit-correct-and-decide).

**Success check:** Identify at least six issues including the weighted rate, hours-period mistake, and an unsupported claim. Reveal and correct the full error list before reuse. Record reviewer, corrections, unresolved issues, and the decision to proceed or revise.

**Handoff:** Transfer REPORT-v2 and its human review record to Module 5. If needed, use the corrected Module 3 example after checking its headline calculations.

### Module 5 — Presentation Readiness, 25 minutes

**Teaching:** Message-led titles, honest charts, clear decision requests, and the supplied color palette.

**Final exercise 5, 12 minutes:** Choose the message (2 minutes), generate a three-slide storyboard (4), peer-review its numbers and presentation instructions (3), then correct and rehearse a 60-second summary (3). See the prompt and full example in [Module 5](modules/Module05.md#final-exercise--create-and-review-the-executive-storyboard).

**Success check:** Three slides, one main message each, a 0–100% completion chart with counts/rates, source/date footers, clear estimate/proposal labels, and a human peer-review record. White, red, and dark gray form the base palette; accents are sparse and red is not tinted pink.

**Handoff:** Begin Q&A at 4:40. Creating a PowerPoint file is optional later practice, not an additional in-session requirement.

## Shared PPI answer key

These values apply only to the **synthetic workshop packet** in Module 2.

| Measure | Expected value |
|---|---|
| Total / completed / in progress / awaiting validation | 70 / 46 / 15 / 9 |
| Open initiatives | 24 |
| Function completion: RTR / OTC / PTP / Customer Care | 60.0% / 60.0% / 80.0% / 50.0% |
| Weighted portfolio completion | 46 / 70 = 65.7% |
| September completion | 40 / 70 = 57.1% |
| Change in completion rate | +8.6 percentage points |
| Relative increase in completion rate | 15.0%; not needed in the main report |
| Net increase in completed count | 6; do not describe 46 as October completions |
| Estimated annual hours from completed initiatives | 4,000; not realized monthly hours or cash savings |

Full formulas are in [Module 3](modules/Module03.md#compare-after-completing). The misleading unweighted average is 62.5%. No supplied evidence establishes targets, AI causation, the reason for Customer Care's rate, financial returns, or approved review deadlines.

## Skills in ChatGPT Enterprise

**Verified against official documentation on 18 November 2026:** Skills are supported for eligible Enterprise users, with availability controlled by product and workspace settings. This verifies product support, not the configuration of Thermo Fisher's tenant. See [OpenAI: Skills in ChatGPT](https://help.openai.com/en/articles/20001066-skills-in-chatgpt).

The workshop uses a conversational creation example, a short test, and reuse across the reporting workflow. Module 2 includes the full instructions and the fallback. A Skill provides reusable instructions; it does not provide missing source data, confer access to external systems, or eliminate human accountability. [OpenAI: Skills and plugins](https://learn.chatgpt.com/docs/skills-and-plugins)

Use the documented Skills interface available to the account. ChatGPT Work also documents `@skill-creator`; do not substitute Codex-specific `$skill-creator` syntax in participant ChatGPT instructions. [OpenAI: Build skills](https://learn.chatgpt.com/docs/build-skills)

## Referencing Skills and adapting workflows

In a supported ChatGPT composer, type **`@` and select the installed Skill**. Then specify the run, stage, source IDs, output, and stop condition. Use the actual available picker entry; the names below are proposed custom Skills, not preinstalled features. See [Module 2's invocation walkthrough](modules/Module02.md#how-to-reference-a-skill-in-a-working-prompt) and [OpenAI's invocation documentation](https://learn.chatgpt.com/docs/build-skills#how-codex-uses-skills).

```text
@PPI Reporting Assistant
Run PPI-2026-10-v1; stage ANALYZE only.
Use original S1–S5 and the checked INTAKE-v1 supplied here.
Return CALC-v1 with formulas, source IDs, and limitations.
Stop for my independent checks before drafting.
```

The first line illustrates the selected mention. Merely pasting the name does not establish that a Skill was installed or invoked. If the Skill is missing, paste the reusable workflow instructions instead and label the run as the plain-prompt path. Pro facilitators can use this path without assuming Enterprise Skills availability.

| Use case | Proposed Skill | Context and critical check | End product |
|---|---|---|---|
| PPI portfolio | PPI Reporting Assistant | S1–S5, weighted completion, annualized estimates | Report and storyboard |
| CC&T / training | Training and Change Update | Attendance, survey denominators, missing adoption evidence | Sponsor brief and proposed follow-up |
| Internal communications | Communications Performance Brief | Comparable recipients and open definitions; percentage points | Leadership brief and measurement proposal |
| IT operations | IT Operations Update | Queue scope, backlog reconciliation, separate SLA evidence | Operations brief and evidence requests |

[Module 3's reference cards](modules/Module03.md#reference-cards--transfer-the-workflow-to-other-use-cases) contain reusable rules, synthetic input packets, explicit Skill-reference examples, expected calculations, next-stage prompts, and human gates for the three additional use cases. They need no participant data to rehearse later. Create only the PPI Skill during the timed workshop; other Skill creation is take-home practice.

For recurring use, follow [Module 5's next-period restart](modules/Module05.md#take-home-reference--restart-the-workflow-next-reporting-period). Reuse the method, supply fresh evidence, and reset approval status. The workflow does not automatically schedule itself or distribute reports.

## Manual Skill editing reference

Module 2 now supplies the [complete baseline Skill](modules/Module02.md#baseline-skill--exact-content-to-paste) and ordered manual edits: stored Markdown conventions; replacement rules for PowerPoint/PDF selection and generation; saved palette/image guidance; and the evidence check. Participants copy Skill content directly into their editable instructions rather than asking the model to interpret an update request. Keep any editor-managed metadata outside the instructions body.

Use the baseline and Markdown addition during core practice if Skills are enabled. The file-output, palette, and evidence extensions are take-home/reference work or replace an existing optional extension; they add no required workshop minutes. The handout does not install or update an account's Skill. Participants must save their edits and run the supplied tests themselves.

## Optional advanced challenge: evidence before execution

[Module 2's context-check challenge](modules/Module02.md#advanced-challenge--require-appropriate-evidence-before-running) provides an exact context-check section to paste into the Skill and six tests: an empty request, palette-only evidence, an inaccessible filename, pressure to invent results, a valid synthetic source card, and a partially complete source card. The expected behavior is to stop unsupported work, explain the specific gap, and let the user supply context and select the next stage.

Use this as take-home work or instead of the existing intermediate extension, not an additional timed activity. Record actual results; the materials do not install or test a Skill in participants' accounts. Passing the context check does not establish factual accuracy or human approval.

## Contingencies and time control

| Situation | Facilitator response |
|---|---|
| Skills missing or setup takes over two minutes | Use the ordinary instruction block; complete the same test and output. |
| Login or network failure | Pair with a working user or use the printed source packet and illustrative outputs for manual review. |
| File uploads unavailable | Paste the source packet; no required exercise needs an uploaded file. |
| Model response takes over a minute | Move to the supplied example and continue the review; inspect the live result only if it arrives within the current segment. |
| Draft contains wrong calculations | Recompute from S1–S3, correct the calculation table, and regenerate or manually revise affected claims. |
| Context lost or a fresh conversation is opened | Repaste S1–S5 and the current task instructions; do not assume earlier context is available. |
| Pair falls behind | Use the supplied report/storyboard example as its review input. Preserve the human verification step. |
| Intermediate learners finish early | Use the module's extension within its existing practice time or take it home. |
| Discussion expands | Capture the question for 4:40 Q&A; move at the scheduled boundary. |

Do not shorten the scheduled break or silently add extra activities. All transitions and role changes occur within the stated module segments.

## Q&A: 4:40–4:55 PM

- **First 10 minutes:** Address participants' questions using examples from the modules and deck use cases.
- **Next 3 minutes:** Discuss applying the workflow to one participant reporting task, using only a description of the task if source material is not approved for use.
- **Final 2 minutes:** Record unresolved questions and the appropriate follow-up contact or evidence needed; do not invent product capabilities or company policy.

Useful prompts: “Which claim would you verify first?” “What source would resolve this?” “Would a reusable Skill help, or is a saved prompt sufficient?”

## Closing: 4:55–5:00 PM

1. **2 minutes:** Revisit Accurate, Easy to Understand, and Free from Errors using the completed artifacts.
2. **2 minutes:** Each participant writes: “For my next report, I will use ChatGPT to ___; I will independently verify ___; the human approver is ___.”
3. **1 minute:** Point participants to the module prompts and close at 5:00.

### Final assessment

| Standard | Evidence from participant work |
|---|---|
| Accurate | Correct weighted completion and hours total; sources and limitations retained; unsupported claims removed |
| Easy to Understand | Concise report, three message-led slides, meaningful chart labels, explicit decision request |
| Free from Errors | Completed error log and review records; corrected numerical, logical, wording, and presentation issues |
| Reusable workflow | Organized context packet, explicit Skill reference or fallback, named stage outputs, and human handoff records |

Participants leave with the source packet, reusable instructions, report, calculation appendix, review record, and storyboard. Retain the synthetic label on all practice outputs.
