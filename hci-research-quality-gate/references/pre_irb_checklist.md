# Gate 1 — Pre-IRB / study-design checklist

**Use when:** research questions and a draft study design exist, but the IRB has not been submitted and no data are collected.
**Goal:** catch problems that become expensive or impossible to fix after IRB submission or data collection.
**Not the goal:** optimizing the study to avoid every possible reviewer comment. Recommend a change only if it improves validity, relevance or contribution.

---

## Step 0 — Intake: what the reviewer needs

Collect these before judging. **If an item is missing, ask a targeted question; do not assume a flaw.**

1. Research questions, written out.
2. Intended contribution type (empirical, artifact or system, method or instrument, theory, dataset) and target venue family.
3. Target population, and how membership will be established.
4. Design summary: method(s), conditions or tasks, materials or system, procedure, session length, remote or in person.
5. The system, if any: what is live, what is scripted or simulated, and what participants will be told.
6. Planned measures and data: instruments, logs, recordings, interview guide.
7. Planned analysis.
8. Planned people-involvement activities so far (formative, co-design, expert review, pilots).
9. The 2–3 claims the researcher hopes to make in the abstract.

Item 9 is the most useful input. Most checks below test whether the design can support those claims.

---

## Step 1 — Run the checks

Checks are ordered by priority. Each has a **latest decision point**: the last moment the fix is still cheap.

### A. Human involvement in design decisions ★ highest priority
*Rule:* involvement is **mandatory** whenever the study designs an artifact, condition, instrument, rubric or framework; the *form* scales with the claim.

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| A1 | Does the study design anything (system, features, conditions, stimuli, rubric, framework, interview guide)? | — (if nothing is designed, A2–A4 reduce to "pilot the protocol with target users") | — |
| A2 | For each designed element: did, or will, target users shape it? Name the activity and the decision it can change. | Elements chosen only by researchers or from the literature; users appear only as evaluators | Before IRB |
| A3 | Will there be a traceable chain from user-derived finding → design goal → feature or criterion? | Features or criteria with no link; "informed by [population]" claimed without saying what that population changed | Before IRB |
| A4 | Are evaluation participants real target users? For accessibility work, people with the relevant disability rather than simulations or proxies? | Convenience sample; able-bodied proxies; disability simulation | Before IRB |
| A5 | Are all involvement activities inside the same IRB protocol? | Formative or co-design sessions planned "later" | Before IRB |

**Fix menu (pick what the claim needs):**
- *Claim that a system meets a population's needs* → formative interviews or observation before freezing features, plus one iteration round.
- *Comparison of design variants* → target users help generate or prioritize the variants, or a pilot confirms they perceive the intended difference.
- *Rubric, framework or measure "for" a population* → co-development or a validation round with that population.
- *Realistic domain materials* → domain-expert review plus a target-user realism check.
- *Descriptive interview study* → participants are the target users; pilot the guide with one or two of them.
- *Literature-only grounding* → **exception**; requires a written justification and scoped claims.

**Severity rule for A:** missing involvement is **Critical** when the central claim is needs-based, "informed by" a population, or presents a framework or measure *for* that population. Otherwise it is **Major**.

**If not fixed:** claims are limited to "a researcher-designed prototype or framework evaluated by target users". No "informed by", "needs-based" or "co-designed" language.

### B. Problem and research questions

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| B1 | Is the problem motivated by stakes (who benefits, what changes), not only by a gap? | "Little work has examined X" as the sole motivation | Before IRB |
| B2 | Is each construct defined in one sentence and distinguished from its neighbours? | RQs that overlap (e.g. two constructs often treated as one) or undefined key terms | Before IRB |
| B3 | Is each RQ answerable by one identifiable part of the design? | An RQ with no matching data, or two RQs answered by the same data | Before IRB |
| B4 | Is each RQ typed (descriptive / comparative / causal-explanatory), and are its verbs consistent with that type? | "How does X shape Y" when X will not be varied | Before IRB |

### C. Can the design answer the RQs?

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| C1 | Write each hoped-for claim (Step 0, item 9). What result would show it is false? Can this design produce that result? | No disconfirming outcome is possible | Before IRB |
| C2 | List **every** difference between conditions or features being compared. | More than one difference, yet results will be attributed to one factor | Before data collection |
| C3 | Does the design vary each property the claims depend on? | Claims about calibration, reliance or error handling with only accurate outputs; claims about an effect with no condition lacking it | Before data collection |
| C4 | Is the comparison or baseline present **only where a planned claim needs it**? | Comparative or population-specific claim with no comparison, **or** a control added "just in case" | Before data collection |
| C5 | Is the central claim protected? Would any plausible confound or gap undermine the *main* claim rather than only its scope? | The main claim depends on the weakest part of the design | Before IRB |

**If not fixed:** change RQ verbs to descriptive ones (participants described, attributed, preferred), retitle the comparison to the bundle actually tested, and move mechanisms to future work.

### D. Contribution and venue

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| D1 | Is the contribution type named, and does the design produce what that type is judged on? | A methodological contribution without a validation plan; an artifact contribution without a real capability | Before IRB |
| D2 | What is the **one** finding or capability that would be new even if everything else confirms prior work? Can this design produce it? | Expected findings restate established principles in a new setting, with no population- or context-specific mechanism | Before IRB |
| D3 | If claims are population-specific, what evidence will show the population matters? | "Specific needs" claimed without comparison, mechanism, or prior evidence | Before IRB |
| D4 | Does the target venue reward this contribution type? | AI or systems venue with no live intelligent component; accessibility venue without disabled people in the framework | Before IRB (contribution); before submission (venue) |

### E. Population, sampling, recruitment

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| E1 | Does the screener keep apart the categories you may need to report (e.g. diagnosed vs self-identified; current vs former users)? | One item merges categories | Before IRB |
| E2 | Will you collect the participant characteristics the claims depend on (support context, expertise, demographics relevant to the construct)? | Variables needed for interpretation are missing from the questionnaire | Before IRB |
| E3 | Does recruitment reach beyond personal networks and the university when population claims matter? Are scarce subgroups planned for? | Only convenience channels; a homogeneous, highly educated or technology-experienced sample with broad claims | Before data collection |
| E4 | Will the recruitment channels and flow be logged as you go? | No record of channels or counts | Before data collection |
| E5 | Sample size: if claims are inferential, is there a justification (power or precedent)? If qualitative, is the depth or saturation strategy stated? | Numbers chosen with no rationale. **Do not invent targets.** | Before IRB |

### F. Tasks, conditions, materials, system fidelity

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| F1 | **Fidelity statement:** one paragraph covering what is live, what is scripted or simulated, which models or versions, what participants are told, and the debrief. It will be reused verbatim in the protocol and paper. | Team members describe the system differently; "AI-generated" content that is actually pre-written | Before IRB |
| F2 | Do instructions or procedures prompt the behaviour you will report? | Asking participants to inspect, verify or compare, then reporting that they did | Before data collection |
| F3 | Are the order of conditions **and** of scenarios counterbalanced or justified? | Fixed order across tasks whose earlier experience can prime the later ones | Before data collection |
| F4 | Are realistic domain materials reviewed by a domain expert and checked by a target user? | Clinical, legal or other domain content authored only by researchers or AI tools | Before data collection |
| F5 | For stochastic systems: are several outputs per prompt sampled, with version, settings and date fixed? | One generation per condition | Before data collection |
| F6 | Are the realism trade-offs (scenario, simulated, single-turn) named, with the ecological claims you give up? | Realism limits discovered only in the limitations section | Before IRB |
| F7 | Are stimuli visible while participants rate them, unless recall is the point? | Rating after the stimulus is closed | Before data collection |

### G. Measures and collected data vs intended claims

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| G1 | **Claim → evidence table:** for each claim, what data supports it and what data could contradict it? | A claim with no supporting data or no possible contradicting data | Before IRB |
| G2 | Do instruments measure the defined constructs? Established measures where they exist; self-written items justified and piloted? | Ad hoc scales with undefined categories; single items for multidimensional constructs | Before IRB |
| G3 | If two raters or instruments will be compared, do the scale points mean the same thing? | Different anchors or midpoint meanings across the compared scales | Before IRB |
| G4 | Claims about behaviour or system state: is observed data planned (logs, screen recordings, settings or history review), with consent? | Self-report or recall only, while claims concern what people or systems actually did | Before IRB |
| G5 | Does the interview guide cover every known dimension of the construct (including motivation for use and change over time where relevant)? | Guide covers the obvious dimension only | Before data collection |
| G6 | Has the full instrument been piloted with 1–2 target users? | No pilot | Before data collection |

### H. Analysis plan

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| H1 | Is the analysis approach named and matched to the RQ (e.g. reflexive thematic analysis, codebook thematic analysis, content coding, ordinal models)? | "Thematic analysis" with no variant; analysis chosen after data | Before data collection |
| H2 | For rubric, content or codebook coding: calibration on items that are not study data → freeze criteria → independent coding → agreement → reconcile. Is this order in the plan? | No calibration round; criteria expected to evolve during coding | Before analysis |
| H3 | For reflexive approaches: are positionality and the reflexivity process planned rather than inter-rater statistics? | Inter-rater statistics added to reflexive analysis (over-correction) | Before analysis |
| H4 | For mixed methods: where do the strands meet, and are only like-for-like measures compared? | Cross-strand comparisons on non-equivalent measures | Before IRB |
| H5 | For ordinal ratings: are the analysis and visualization suitable for ordinal data? | Means only; inappropriate plots | Before analysis |

### I. Ethics and IRB, minimal
*Scope:* IRB is assumed to be routine; check only the high-consequence items.

| # | Check | Red flag | Latest decision point |
|---|---|---|---|
| I1 | Does the protocol include **every** planned activity (formative, co-design, pilots, expert reviews, follow-ups, artifact or log review)? | Activities planned "later", requiring amendments | Before IRB |
| I2 | Does consent cover data needed after the fact: logs, chat histories, recordings, quotes, images? | Claims need data the consent does not cover | Before IRB |
| I3 | If anything is simulated, does the protocol state what participants are told and when they are debriefed? | Simulated intelligence presented as real, with no debrief plan | Before IRB |

### J. Evidence that cannot be collected after the fact
Final sweep. Anything listed here and not planned is **Critical** if the central claim depends on it, **Major** otherwise.
- Evidence that target users shaped design decisions (A2–A3)
- Observed behaviour, logs, history or settings (G4)
- Consent for quotes, video or images (I2)
- Participant characteristics the claims depend on (E2) and separable eligibility categories (E1)
- Varied conditions or properties the claims depend on (C2–C3)
- Expert and realism review of materials before participants see them (F4)

---

## Step 2 — Severity and labels

| Severity | Meaning |
|---|---|
| **Critical** | Threatens the central claim **and** cannot be fixed after data collection |
| **Major** | Threatens a secondary claim, or the central claim but fixable with substantial work |
| **Minor** | Improves clarity or rigour; low risk |

Each issue also gets one label:
- **Actual problem:** present in the design as described.
- **Risk:** depends on information not yet given. Ask the question.
- **Optional:** an improvement, not required.

**Don't-over-correct rules:**
- If a past concern does not apply to this study, say so in one line and do not recommend the activity.
- Do not add controls, scales, sample size or co-design sessions that no planned claim needs.
- Prefer scoping a claim to adding an activity when the activity would not change a decision.
- Do not invent sample-size targets without a methodological rationale.

## Step 3 — Report format (for each issue)

**Report only checks that fail or are at risk.** Do not walk through passing checks; summarize them in Step 4, item 3.


- **Issue:** a specific title
- **Severity:** Critical / Major / Minor, labelled actual problem / risk / optional
- **What's wrong**
- **Why it matters**
- **How to fix it:** concrete and feasible for this study
- **When to fix it:** the latest practical decision point
- **If not fixed:** which claims must be limited, and how

Routine reports contain **no citations, reviewer IDs, pattern IDs or project provenance**.

## Step 4 — Close with

1. **Prioritized action checklist:** items ordered by severity, then by how soon the decision point arrives. Group them into before IRB submission / before data collection / before analysis.
2. **Open questions:** targeted questions for every "risk" item.
3. **What is already solid:** one line per area that passed. No compliments; only what does not need changing.
