# Gate 2 — Pre-writing / pre-submission checklist

**Use when:** data are collected and analysed, and a manuscript, poster or outline is being written or is about to be submitted.
**Goal:** make sure what the paper claims is exactly what the study can support, presented so reviewers can verify it, at a venue that rewards it.
**Not the goal:** pre-empting every possible reviewer comment. Recommend a change only if it improves accuracy, clarity, or fit.

---

## Step 0 — Intake

1. The draft (or outline), and the target venue and track: full paper, journal article, short paper, poster or late-breaking work.
2. The study as actually run, if it differs from what the draft says: protocol, instruments, the system fidelity statement from Gate 1.
3. For a **resubmission**: previous reviews and what has changed since. No new data? Say so.
4. The deadline. This decides whether re-analysis items can still be done.

If an item is missing, ask; do not assume.

## Step 1 — Adapt to submission type

| Type | Weight more | Weight less | Specific checks |
|---|---|---|---|
| **Full conference paper** (CHI, ASSETS, IUI, UIST) | Contribution, claim–evidence alignment, methods transparency, discussion depth | — | All sections |
| **Journal article** (e.g. TiiS) | Scope fit (checked first, at desk review), completeness, related-work depth, replicability detail | Brevity | Venue scope statement in the first page; full methods; supplementary materials |
| **Short paper** | One clear contribution; tight claims | Breadth of related work and discussion | Cut secondary RQs instead of compressing them |
| **Poster / LBW** | A clear contribution at its current stage; honest status (preliminary, ongoing) | Completeness | Not a compressed full paper; analysis claims proportional to the data shown (e.g. do not claim reflexive thematic analysis on a few comments); essential method details stay in the main text, not the supplement |

---

## Step 2 — Run the checks

Each check has a **fix type**: **W** = writing · **R** = re-analysis · **N** = new data · **A** = acknowledge or scope.

### K. Contribution and framing

| # | Check | Red flag | Fix type |
|---|---|---|---|
| K1 | Do the abstract and introduction state the **stakes** (who benefits, what changes for HCI or practice), not only the gap? | Motivation is "little work has examined X" | W |
| K2 | Is the contribution type explicit and listed as specific contributions? | Contributions are vague ("insights", "implications") or mix types without saying so | W |
| K3 | What is the one new finding or capability? Is it in the abstract? | The abstract leads with findings that restate established principles | W (A if nothing new: reframe as a replication) |
| K4 | Is the novelty positioned against **adjacent fields** as well as the immediate topic (e.g. privacy, credibility, information design, clinical informatics)? | Only same-topic HCI work is cited; reviewers will know the adjacent literature | W |
| K5 | If the paper makes population-specific claims, does it say what the population focus reveals that a general sample would not? | "Specific needs" claimed with no comparison or mechanism | W / A |
| K6 | **Is a design limitation framed as a contribution?** Controlled, simulated or constrained setups may be presented as an advantage only for questions the setup actually varied. | A limitation recast as an "analytic opportunity" or as the central claim | W, and remove the claim |
| K7 | If a framework, rubric or measure is presented as a contribution, does its validation support that label? Otherwise call it initial or expert-derived. | "X-informed framework" without involvement or validation by X | W / A |

### L. RQ → method → result → claim alignment

| # | Check | Red flag | Fix type |
|---|---|---|---|
| L1 | **Claim-verb audit:** list every causal or comparative verb (shapes, drives, causes, determines, is a condition for, complementary, improves). Is each backed by a design that varied that factor? | Causal or comparative verbs on descriptive data | W |
| L2 | Is each result traceable to an RQ, and does each RQ get an answer? | Orphan results; unanswered RQs | W / R |
| L3 | Are effects attributed to a single factor when conditions differed in several ways? | The title or claims name one ingredient of a bundled manipulation | W (retitle to the bundle) |
| L4 | Are beliefs and perceptions kept apart from facts about the system or behaviour? | Participants' accounts reported as what the system did | W |
| L5 | Are population claims scoped to the sample as recruited (eligibility, education, experience)? | "Adults with X" where the sample is narrower | W / A |
| L6 | Are findings presented only where their evidence is presented? (No new findings in the discussion.) | Discussion introduces claims absent from Results | W / R |
| L7 | **Central-claim test:** remove the weakest component of the evidence. Does the main claim still stand? If not, can the claim be narrowed now? | The main claim depends on a non-equivalent comparison, an unreliable measure, or an unvaried property | R / A |

### M. Methods transparency

| # | Check | Red flag | Fix type |
|---|---|---|---|
| M1 | **Fidelity statement:** is what was live vs scripted or simulated, the models or versions, what participants were told, and the debrief stated exactly as in the protocol? Is it identical to any earlier submission? | Vague "AI-generated"; descriptions that changed across versions | W |
| M2 | Are recruitment channels, flow (contacted → eligible → completed), how eligibility was determined, and the setting and geography reported? | "Recruited via mailing lists" only | W |
| M3 | Are the materials participants saw shown or supplied (example screens, scenarios, prompts, outputs)? | Reviewers cannot see the stimulus | W |
| M4 | Are instruments supplied (interview guide, questionnaire with anchors and category definitions)? | Ordinal categories reported but not defined | W |
| M5 | Is the analysis approach named precisely, with the process described (who coded, how codes became themes)? | "Thematic analysis" with no variant | W |
| M6 | Is the sample described early, with the characteristics relevant to the claims, and limits flagged in Methods rather than only in Limitations? | Sample limits first appear at the end | W |
| M7 | Are domain materials' review (expert, target-user realism) and any prompting instructions reported? | Domain content with no review statement; "participants were asked to inspect…" hidden | W / A |

### N. Analysis and strength of evidence

| # | Check | Red flag | Fix type |
|---|---|---|---|
| N1 | **Coding reliability:** were criteria frozen before independent coding? If they changed afterwards, has an independent recode been done? | Reconciled or adjudicated scores presented as validated; κ near 0 on any dimension | **R, before submission** |
| N2 | Are compared measures equivalent (same anchors and meaning)? If not, are they reported separately, with the comparison claim dropped? | Gap between non-equivalent scales interpreted as a substantive difference | R / W |
| N3 | Are the statistics appropriate (ordinal data, multiple comparisons, effect sizes), and do claims rest on the corrected results? | Claims rest on comparisons that do not survive correction | R / W |
| N4 | Are single-item or self-written measures described as such, with claims proportional to them? | Strong claims on unvalidated single items | W / A |
| N5 | For stochastic outputs: is sampling (number of generations, versions, dates) reported, and are stability claims limited accordingly? | Model or condition differences claimed from one generation | A / N |
| N6 | For qualitative work: are counts presented as spread within the sample, not prevalence? Is normative judgement of participants avoided ("the right reason")? Is positionality stated where relevant? | Evaluative language about participants' reasoning | W |
| N7 | **Consistency pass:** every number in text = tables = figures = appendix; totals add up; participant counts per finding match. | Any mismatch (reviewers find them) | W |

### O. Discussion and implications

| # | Check | Red flag | Fix type |
|---|---|---|---|
| O1 | For each key finding: which prior result does it confirm, contradict or extend? | The discussion restates the Results | W |
| O2 | If a theory or lens is used: what does it explain, where does the data not fit, and why? | The lens relabels findings into its vocabulary | W / R |
| O3 | Is each design implication tied to a specific finding and context, with its strength labelled (several participants vs one or two)? | Generic implications that would follow from prior work alone | W |
| O4 | Are implications that were never implemented or evaluated presented as proposals, not results? | "Customizable X improves Y" when X was not built | W |
| O5 | Is repetition across discussion subsections removed? Are cross-references only to earlier sections? | The same finding discussed in three subsections | W |

### P. Limitations

| # | Check | Red flag | Fix type |
|---|---|---|---|
| P1 | Does every known design limitation appear **and** change a claim somewhere (not only listed)? | Limitations listed but the abstract still claims more | W |
| P2 | Are the limitations actionable for readers (whom they affect, in which direction)? | "Future work should study more diverse populations" with no population context reported | W |
| P3 | Is anything a reviewer will see as a flaw framed as a deliberate, justified choice (with the trade-off stated) where that is honestly the case? | Defensible choices (scenario, single-turn, controlled content) left undefended | W |

### Q. Structure and presentation

| # | Check | Red flag | Fix type |
|---|---|---|---|
| Q1 | Are subsection titles informative (state the finding), and do headings deliver what they promise? | Generic theme titles; a heading whose topic never appears | W |
| Q2 | Are figures accessible (colour-vision safe, alt text) and suited to the data (e.g. diverging stacked bars for Likert data)? | Box plots of Likert data; red/green encodings | W |
| Q3 | Is the length within limits, with each section earning its space? Is related work kept to what is used later? | Background topics never revisited | W |

### R. Venue fit

| # | Check | Red flag | Fix type |
|---|---|---|---|
| R1 | Does the venue reward this contribution type? | AI or systems venue without a real intelligent or technical contribution; journal scope not met | Retarget venue |
| R2 | Is the paper written for this community's reviewers (their literature, their evaluation norms)? | Accessibility paper without disability-studies framing; systems paper without implementation detail | W |
| R3 | Do the format and track match the stage of the work? | Full-paper-scale claims in a poster; a poster submission that reads as a compressed full paper | W / retarget track |

### S. Resubmission mode (only if resubmitting)

| # | Check | Red flag | Fix type |
|---|---|---|---|
| S1 | Map every previous criticism to a change, a justified non-change, or an acknowledgment. | Criticisms silently ignored | W |
| S2 | Which previous criticisms recur across venues? Treat recurring ones as real, even if they look like misreadings. A misreading still signals unclear writing. | Arguing with persistent criticism instead of fixing the explanation or narrowing the claim | W / A |
| S3 | Did any reframing **create** a new central claim that the data cannot carry? | New "analytic angle" on old data | W |
| S4 | With no new data, design-level criticisms can only be scoped and acknowledged. Does the new version do that rather than reframe around them? | Repositioning that keeps the original claim | A |

---

## Step 3 — Fixability triage (always do this)

Sort every issue by fix type, then act in this order:
1. **R (re-analysis):** do it **before submission**. Rebuttals and short revision windows do not absorb re-analysis; reviewers judge it as needing a new round.
2. **N (new data):** decide now whether to collect (and delay) or to narrow the claims (A).
3. **W (writing):** fix everything.
4. **A (acknowledge):** state the limitation and change the affected claims.

If an R or N item touches the central claim and cannot be done before the deadline: **narrow the central claim, or move the submission** (later deadline, poster or LBW, different venue).

## Step 4 — Severity, labels, and don't-over-correct

- **Critical:** the central claim is unsupported, or a decisive venue-fit problem.
- **Major:** a secondary claim is unsupported; transparency gaps reviewers will need to judge correctness.
- **Minor:** clarity and presentation.

Label each issue as an **actual problem**, a **risk** (needs information: ask), or **optional**.

Don't over-correct:
- Do not add literature, analyses or limitations that change no claim.
- Do not demand inter-rater statistics for reflexive analysis.
- Do not ask for new data when narrowing a claim fully resolves the issue.
- If a known reviewer concern does not apply to this paper, say so in one line.

## Step 5 — Report format (for each issue that fails or is at risk)

- **Issue:** a specific title
- **Severity:** Critical / Major / Minor, labelled actual problem / risk / optional
- **Fix type:** writing / re-analysis / new data / acknowledge
- **What's wrong**
- **Why it matters**
- **How to fix it:** concrete; give example rewording for claim fixes
- **When:** before submission / can wait for revision
- **If not fixed:** which claims must be limited

Report only checks that fail or are at risk. Routine reports contain **no citations, reviewer IDs, pattern IDs or project provenance**.

## Step 6 — Close with

1. **Prioritized action list:** grouped as re-analysis (do first) → new-data decisions → writing → acknowledgments.
2. **Claim table:** each abstract claim → its supporting evidence → status (supported / narrow it / remove it).
3. **Open questions** for every risk item.
4. **Already solid:** one line per area that passed.
