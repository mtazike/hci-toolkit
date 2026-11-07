# HCI Research Quality Gate

A Claude Skill that helps you design and write HCI studies that hold up in peer review. It checks your work at two points:

- **Gate 1, before IRB and data collection:** catches problems that become expensive or impossible to fix once data exist. Examples: users who never shaped design decisions, measures that can't support the claims, conditions that differ in several ways at once.
- **Gate 2, before submission:** checks contribution framing, claim–evidence alignment, transparency, discussion depth, limitations and venue fit. It adapts to full papers, journal articles, short papers, posters and late-breaking work, and to resubmissions.

## What you get

Three short tables, organized by the parts of your study (Gate 1) or the sections of your paper (Gate 2):

| Level | Meaning |
|---|---|
| **Must:** fix before you start (or submit) | Skipping it could make the main result meaningless, or stop the study from running, and it can't be fixed afterwards |
| **Should:** fix if you can | The main result still stands; reviewers may ask, and you can explain it in the limitations |
| **Optional** | Nice to have |

Each row gives **what to include** and the **simplest widely accepted HCI solution**. A detailed per-issue critique is available on request.

## How to use it

**In Claude**
- Add this folder (`SKILL.md`, plus `references/` if you want them) as a custom skill. The folder name must stay `hci-research-quality-gate`.
- In Claude Code, place the folder in `~/.claude/skills/`.
- Then, in any chat, attach your study plan or draft and say *"check this with my HCI research quality gate"*, or type `/hci-research-quality-gate`.

**In ChatGPT or other assistants**
- Upload `SKILL.md` as a knowledge file in a Custom GPT, with an instruction like *"Follow the attached HCI research quality gate file exactly when reviewing study plans or drafts."*
- Or paste its text at the start of a chat.
- It was written and tested for Claude, so other assistants may apply the Must/Should rules less precisely.

## Files

| File | Purpose |
|---|---|
| `SKILL.md` | The Skill. Self-contained: the checks, rules, venue expectations and output format. |
| `references/pre_irb_checklist.md` | The full Gate 1 checklist, with red flags and fix options. |
| `references/pre_submission_checklist.md` | The full Gate 2 checklist. |

`SKILL.md` controls the output format. The reference checklists give more detail for the same checks.

## Where it is strong, and where to adapt it

**Strong for:** prototype or system evaluations, controlled comparisons, interview and observation studies, surveys and ratings, rubric or LLM-output evaluations, and mixed methods, at venues such as CHI, ASSETS, IUI and UIST, journals, and posters.

**Design choices to know about:**
- Involving target users in design decisions is treated as **always required** whenever a study designs something (a system, conditions, stimuli, measures or frameworks).
- Ethics, IRB and statistics checks are deliberately **minimal**: high-consequence items only.

**Less covered:** long field deployments and diary or longitudinal studies, heavy statistics or large-scale log analysis, purely technical benchmarks, research-through-design, theory papers, and literature reviews. Adapt or add checks for these.

## How it was built

The checks come from a systematic analysis of peer-review feedback on several HCI projects across multiple venues, combined with established HCI practice. The Skill contains only generalized lessons: no reviewer text and no details of specific papers. It was tested retrospectively on a held-out project and on a live study plan, then revised.

## Updating

When new reviews or feedback arrive, update the underlying analysis first. Change `SKILL.md` only when a problem recurs across more than one project, or when a run flags something unnecessary or misses something important.
