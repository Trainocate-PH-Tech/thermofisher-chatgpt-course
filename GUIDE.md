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

**Delivery rule:** Keep PPI as the one live end-to-end case. The training, communications, and IT workflow cards in Module 3 are reference/take-home adaptations. Discuss key concepts within the instruction blocks, walk through the paired examples during demonstrations, and complete each final exercise during practice. Do not read the whole handout aloud. In Modules 3–5, Skill creation/editing replaces the earlier prompt-only practice; baseline demonstrations and manual-edit walkthroughs fit existing demonstration slots. No additional activity or minutes are added.

## Inventory of reusable Skills

Create separate entries; do not keep overwriting the Module 2 Skill. Each name below is a proposed custom Skill, not a built-in feature. If installation is unavailable, retain the instructions as separately named reusable prompts.

| Module | Skill and exact content | Required inputs | Output and boundary |
|---|---|---|---|
| 2 | [PPI Reporting Assistant](modules/Module02.md#baseline-skill--exact-content-to-paste) | Reporting brief and current evidence | Broad staged workflow; use INTAKE during this workshop |
| 3 | [PPI Analysis and Report Builder](modules/Module03.md#build-your-skill--ppi-analysis-and-report-builder) | Sources/definitions, period, audience, decision; checked calculations before DRAFT | CALC-v1 and REPORT-v1; stops for human checks |
| 4 | [PPI Report Verifier](modules/Module04.md#build-your-skill--ppi-report-verifier) | Specific report version and original evidence; calculations as an aid | REVIEW-v1 findings and blank human record; does not rewrite/approve |
| 5 | [PPI Presentation Builder](modules/Module05.md#build-your-skill--ppi-presentation-builder) | Specific report, evidence, audience, and actual human review confirmation | STORYBOARD-v1; optional PowerPoint/PDF/HTML ZIP; does not approve/distribute |

**Edit–run–compare:** Each of Modules 3–5 contains a complete baseline Skill, exact manual edits, a short usage prompt after every edit, and an observation table. Save revisions and select the intended Skill with `@` in a fresh conversation for comparisons. Reuse the same evidence. Do not repeat the stored rules in the short prompt; use the comprehensive prompt only as a reference/fallback. A baseline may already give good results; compare consistent compliance, not cosmetic novelty.

### Explicit handoffs between Skills

Selecting a Skill does not transfer files, retrieve another conversation, run another Skill, or provide human confirmation. Paste or attach the named materials when they are not already accessible. Use the actual output version labels.

1. **Builder → Verifier:** Supply S1–S5, checked CALC-v1, and REPORT-v1 to PPI Report Verifier. Request: `Review REPORT-v1 against S1–S5; return findings only.`
2. **Verifier → Builder:** After inspecting findings yourself, supply original sources, checked calculations, draft, and confirmed corrections to PPI Analysis and Report Builder. Request: `Run DRAFT to revise REPORT-v1 using my confirmed corrections; return REPORT-v2 and a change list.` Include your actual confirmation that the calculations were independently checked.
3. **Human → Presentation Builder:** Inspect the corrected report and record the actual decision against REPORT-v2. Supply that report, original sources, and the completed review record to PPI Presentation Builder. Request: `Create a leadership storyboard from the supplied reviewed REPORT-v2.`

If the decision is **Revise**, resolve the issues and review the new version before presentation. A verifier's findings—even “no issues found”—are not a human decision. Keep the original evidence and human record with each artifact.

## Exact run of show

| Clock | Minutes | Session | Required output |
|---|---:|---|---|
| 2:00–2:05 | 5 | Opening and setup | Participants understand the outcome and review standards |
| 2:05–2:20 | 15 | [Module 1: Human-in-the-Loop](modules/Module01.md) | Three reviewed claims |
| 2:20–2:55 | 35 | [Module 2: Structured Prompting](modules/Module02.md) | Organized context packet, INTAKE-v1, and Skill reference/fallback |
| 2:55–3:15 | 20 | Break | Save work before leaving |
| 3:15–3:50 | 35 | [Module 3: Analysis and Drafting](modules/Module03.md) | Saved analysis/report Skill, calculations, and draft |
| 3:50–4:15 | 25 | [Module 4: Verification](modules/Module04.md) | Saved verifier Skill, findings, and human record |
| 4:15–4:40 | 25 | [Module 5: Presentation Readiness](modules/Module05.md) | Saved presentation Skill and peer-reviewed storyboard |
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

**For instructors:** Use the timing tables and facilitation notes in this guide. Answer comparisons are visible rather than hidden, so ask participants not to consult them early. For print distribution, supply all five handouts so linked source packets are available. The Skills fallback and offline examples support the same learning objectives.

## Preparation checklist

### Before the workshop

- [ ] Distribute these Markdown materials and make the source packet easy to copy.
- [ ] Confirm participants can sign in to the intended Enterprise workspace and send a prompt.
- [ ] Check Skills availability with a representative participant account, not just an administrator account. Test creation and use if permitted; prepare the ordinary-prompt fallback regardless.
- [ ] Prepare demonstration copies of the four Skills if access permits, and verify the save/select workflow before class. Participants create their own separate entries. Sharing or publishing is not required.
- [ ] Check whether file upload is available if the facilitator wants to demonstrate it. Core exercises use pasted text and do not depend on file uploads or connected apps.
- [ ] Ask participants to bring a laptop and a calculator or spreadsheet for independent arithmetic checks. Pair beginners with intermediate users where practical.
- [ ] Keep the provided illustrative outputs accessible in case of network, login, or generation delays.
- [ ] Review the source packet and recalculate the answer key. Prepare a visible timer.
- [ ] Follow the organization's approved data-handling practices. Participants need no real confidential operational data for this workshop.
- [ ] Recheck the official Skills documentation shortly before delivery; product interfaces and workspace availability may change.

### Room and facilitation setup

Use pairs with one operator and one reviewer; switch roles in Module 3. In remote delivery, use pairs in breakout rooms with the same timer. The reviewer checks source evidence and calculations while the operator works with ChatGPT. Both participate in the final approval decision.

Participants and instructor use the same handout. Read the short concepts, compare the labeled inappropriate and appropriate examples, then complete the final exercise before consulting **Compare after completing**. Timing, pacing tips, and facilitation fallbacks are kept in this guide rather than in the module handouts. Model wording can vary: evaluate evidence and behavior rather than exact phrasing. Inappropriate examples are deliberately flawed teaching material, not recommendations.

## Instructor timing and pacing notes

Keep this guide for facilitation. The module handouts omit session times, exercise durations, and pacing notes. Use the schedule above and the breakdowns below to keep the workshop within three hours. Dates and proposed business deadlines inside examples describe the reporting case, not the workshop schedule.

### Module 1: detailed pacing

| Clock | Minutes | Work |
|---|---:|---|
| 2:05–2:10 | 5 | Read the concepts and workflow |
| 2:10–2:13 | 3 | Walk through the examples |
| 2:13–2:18 | 5 | Complete the final exercise |
| 2:18–2:20 | 2 | Compare answers and hand off |

**Practice steps:**

1. **1 minute:** Classify the claims before running the prompt.
2. **2 minutes:** Run it and inspect the suggested corrections.
3. **1 minute:** Independently calculate the two rates and their difference.
4. **1 minute:** Agree the corrected wording and complete a review record.

**Facilitation notes:**

Ask participants which claims they would check first. Spend the existing five-minute teaching block on these concepts, rather than reading every sentence aloud.

Use the two-minute comparison to discuss the denominator and unsupported causal claim. If access fails, review the printed examples. Stop at 2:20.

### Module 2: detailed pacing

| Clock | Minutes | Work |
|---|---:|---|
| 2:20–2:28 | 8 | Context/source briefing (5 min) and Markdown basics (3 min) |
| 2:28–2:35 | 7 | Prompt comparisons (2 min), formatting example (2 min), Skill demonstration (3 min) |
| 2:35–2:50 | 15 | Complete the final exercise |
| 2:50–2:55 | 5 | Compare answers, save, and prepare for break |

**Practice steps:**

1. **3 minutes:** Copy S1–S5 and identify the brief, rules, evidence, and two limitations.
2. **5 minutes:** Create/reuse and select the Skill, or use ordinary instructions. Allow at most two minutes for setup; use the remaining time to run intake.
3. **4 minutes:** Check the inventory and use the continuation prompt to build TEMPLATE-v1 using Markdown notation.
4. **3 minutes:** Inspect heading levels, table syntax, and unchecked review items with your partner; save the outputs for Module 3.

**Facilitation notes:**

In the three-minute basics segment, demonstrate `#`, `##`, `**bold**`, a bullet, and a table separator. Treat the remaining notation as a reference participants can consult during the final exercise.

Within the seven-minute demonstration, use two minutes for the first two prompt comparisons, two for the formatting example, and three for Skill selection. Do not read every reference item aloud. If Skill setup takes more than two minutes during practice, switch to the plain-prompt path.

Ask participants to explain why the refusal is useful: it exposes a missing input and returns the next decision to the user. These are behavioral instructions to test, not a deterministic security boundary or a guarantee that a model cannot make mistakes. Fix the Skill and rerun failed cases before relying on it.

During comparison, ask one pair to explain how it referenced the Skill and another to demonstrate the fallback. Optional challenge within the same time: introduce a note claiming 48 completed and check that the conflicting count is surfaced, not silently accepted. Remove that test note before Module 3.

### Module 3: detailed pacing

| Clock | Minutes | Work |
|---|---:|---|
| 3:15–3:22 | 7 | Concepts and stage handoffs |
| 3:22–3:28 | 6 | Baseline Skill demo, examples, and edit walkthrough |
| 3:28–3:45 | 17 | Create Skill, edit, run, compare, and complete handoff |
| 3:45–3:50 | 5 | Compare results and save |

**Practice steps:**

1. **3 minutes:** Create and save the baseline Skill; prepare S1–S5 and INTAKE-v1.
2. **3 minutes:** Run the short baseline ANALYZE request and save its output.
3. **5 minutes:** Apply edits 1 and 2, save, and repeat ANALYZE with the same inputs in a fresh conversation. Compare results using the table above.
4. **6 minutes:** Independently check the latest calculations, request DRAFT using the short post-edit prompt, and inspect/save REPORT-v1.

**Facilitation notes:**

Use the six-minute demonstration to compare the worked examples, show a baseline Skill run, and explain the two exact edits. Participants apply them during practice. The following reference cards are for later practice or existing Q&A; do not add them to the live exercise.

Allow two minutes to compare calculations and three to discuss report choices and save. Wording may vary; evidence and qualifications should not. If a pair falls behind, let it use the suggested report as REPORT-v1 for Module 4 after checking the calculations. Optional challenge within the same time: identify a useful metric whose inputs are missing.

### Module 4: detailed pacing

| Clock | Minutes | Work |
|---|---:|---|
| 3:50–3:55 | 5 | Review concepts and version control |
| 3:55–3:59 | 4 | Baseline Skill demo, examples, and edit walkthrough |
| 3:59–4:11 | 12 | Create Skill, edit, run, compare, and complete handoff |
| 4:11–4:15 | 4 | Compare answers and record the decision |

**Practice steps:**

1. **3 minutes:** Create/save the baseline verifier, supply S1–S5 and FLAWED-EXAMPLE, and run the short baseline audit.
2. **4 minutes:** Apply edits 1 and 2; retest in fresh conversations using the short missing-evidence and recovery prompts. Compare findings with the baseline.
3. **5 minutes:** Inspect findings against the answer key, audit your own REPORT-v1, and pass confirmed corrections to the report builder. Review affected claims in REPORT-v2 and complete its human record.

**Facilitation notes:**

Explain the review categories and version change within the existing five-minute instruction block. Use the four-minute demonstration to compare the examples, show the verifier baseline, and explain the manual edits. The full audit belongs to practice.

Use the four-minute comparison to reveal missed errors and finish the record. If needed, supply the Module 3 suggested report, have the pair check its headline calculations, and record its review before moving on. Optional challenge: explain why relative change uses unrounded counts, (46−40)/40 = 15.0%.

### Module 5: detailed pacing

| Clock | Minutes | Work |
|---|---:|---|
| 4:15–4:20 | 5 | Message, evidence, and visual principles |
| 4:20–4:24 | 4 | Baseline Skill demo, examples, and edit walkthrough |
| 4:24–4:36 | 12 | Create Skill, edit, run, compare, and complete handoff |
| 4:36–4:40 | 4 | Compare and finish peer review |

**Practice steps:**

1. **3 minutes:** Create/save the baseline Skill, supply the report/evidence/human-review packet, and run the short storyboard request.
2. **5 minutes:** Apply edits 1 and 2, save, and retest the same request in a fresh conversation without restating the layout or palette. Record differences.
3. **4 minutes:** Peer-review the latest storyboard against the checked report and source packet, correct any issues, and save. File-generation edit 3 and interactive-HTML edit 4 remain take-home work.

**Facilitation notes:**

Use the five-minute teaching block for one-message slides, chart honesty, and context selection; use four minutes to compare examples, show the baseline storyboard, and explain the two required edits.

Use two minutes to compare a participant output with the example and two to finish the checklist. Optional extension within the existing practice time: write a two-sentence email introducing the storyboard without adding claims.

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

**Teaching:** Create a separate analysis/report Skill. Store reproducible calculations, explicit ANALYZE/DRAFT stages, and Markdown reporting conventions; demonstrate baseline behavior and the two edits.

**Final exercise 3, 17 minutes:** Create/save the baseline Skill (3 minutes), run baseline analysis (3), edit/save and retest (5), then independently check calculations and draft/save the report (6). Use the prompts and calculation key in [Module 3](modules/Module03.md#final-exercise--analyze-and-draft-a-leadership-report).

**Success check:** Report prose is at most 250 words, with a calculation appendix and human checklist outside that limit. It includes a decision request, evidence-based observations, proposed actions, and limitations.

**Handoff:** Save CALC-v1 and REPORT-v1, labeled “Draft — human review pending,” for Module 4. Use the supplied example if a pair falls behind.

### Module 4 — Verification, 25 minutes

**Teaching:** Create a separate verifier Skill. Add structured findings and explicit evidence/version checks. AI auditing supports human source inspection and independent calculations; it does not supply human approval.

**Final exercise 4, 12 minutes:** Create/save and run the baseline audit (3 minutes), edit/retest the verifier (4), then inspect findings, pass confirmed corrections to the report builder, and record the actual human decision against the revision (5). The flawed report, complete answer key, and release checklist are in [Module 4](modules/Module04.md#final-exercise--audit-correct-and-decide).

**Success check:** Identify at least six issues including the weighted rate, hours-period mistake, and an unsupported claim. Reveal and correct the full error list before reuse. Record reviewer, corrections, unresolved issues, and the decision to proceed or revise.

**Handoff:** Transfer REPORT-v2 and its human review record to Module 5. If needed, use the corrected Module 3 example after checking its headline calculations.

### Module 5 — Presentation Readiness, 25 minutes

**Teaching:** Create a separate presentation Skill. Add stored slide/document structures and brand conventions while preserving version-specific human review. File-generation instructions are an optional third edit; interactive HTML reporting and ZIP packaging are an optional fourth edit.

**Final exercise 5, 12 minutes:** Create/save and run the baseline storyboard (3 minutes), edit/save and retest stored structure and palette (5), then peer-review and compare the transformed output (4). See the prompt and full example in [Module 5](modules/Module05.md#final-exercise--create-and-review-the-executive-storyboard).

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

[Module 3's reference cards](modules/Module03.md#reference-cards--transfer-the-workflow-to-other-use-cases) contain reusable rules, synthetic input packets, explicit Skill-reference examples, expected calculations, next-stage prompts, and human gates for the three additional use cases. They need no participant data to rehearse later. The core exercises create the four Skills in the inventory above. The training, communications, and IT variants are optional practice.

For recurring use, follow [Module 5's next-period restart](modules/Module05.md#take-home-reference--restart-the-workflow-next-reporting-period). Reuse the method, supply fresh evidence, and reset approval status. The workflow does not automatically schedule itself or distribute reports.

## Manual Skill editing reference

Module 2 now supplies the [complete baseline Skill](modules/Module02.md#baseline-skill--exact-content-to-paste) and ordered manual edits: stored Markdown conventions; replacement rules for PowerPoint/PDF selection and generation; saved palette/image guidance; and the evidence check. Participants copy Skill content directly into their editable instructions rather than asking the model to interpret an update request. Keep any editor-managed metadata outside the instructions body.

Each edit includes a short usage test and observable success criteria. Participants reuse S1–S5, compare saved outputs, test fresh-conversation palette persistence, and record missing-evidence refusal plus recovery in the evolution table. Edits A/B/C of the file-output addition are saved together before their behavior is tested.

Use the baseline and Markdown addition during core practice if Skills are enabled. The file-output, palette, and evidence extensions are take-home/reference work or replace an existing optional extension; they add no required workshop minutes. The handout does not install or update an account's Skill. Participants must save their edits and run the supplied tests themselves.

## Optional advanced challenge: evidence before execution

[Module 2's context-check challenge](modules/Module02.md#advanced-challenge--require-appropriate-evidence-before-running) provides an exact context-check section to paste into the Skill and six tests: an empty request, palette-only evidence, an inaccessible filename, pressure to invent results, a valid synthetic source card, and a partially complete source card. The expected behavior is to stop unsupported work, explain the specific gap, and let the user supply context and select the next stage.

Use this as take-home work or instead of the existing intermediate extension, not an additional timed activity. Record actual results; the materials do not install or test a Skill in participants' accounts. Passing the context check does not establish factual accuracy or human approval.

## Advanced take-home: vibe-code an interactive report

[Module 5 edit 4](modules/Module05.md#edit-4--optional-interactive-html-report-and-portable-package) adds exact manual Skill changes for static web reports using HTML5, CSS3/Bootstrap, vanilla JavaScript, and Chart.js. Participants supply the reviewed report and evidence, request an interactive HTML report, and receive a portable ZIP when tools permit. The Skill stores navigation, chart/filter behavior, brand styling, local dependencies, and deployment documentation.

Participants compare All functions, PTP, Customer Care, and Reset against supplied expected values, test offline operation, then request focused revisions in plain language. Prior comparisons must become unavailable when function-level historical evidence is absent. The exercise ends with an inspected package and a human deployment decision—not automatic publication. Actual deployment requires a separate explicit request and an appropriate host.

This extension is take-home work, not an additional required activity within the 180-minute session. It provides teaching instructions, test prompts, and package acceptance criteria; no web application is built by editing this handout.

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
| Reusable workflow | Four separately named Skills or instruction fallbacks, edit/run comparison records, organized evidence, and explicit human handoffs |

Participants leave with an inventory of four reusable Skills (or instruction fallbacks), the source packet, revision comparisons, report, calculation appendix, review record, and storyboard. Retain the synthetic label on all practice outputs.
