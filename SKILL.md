---
name: jesse-schell-game-design-master
description: "Master game-design diagnosis and decision system combining Jesse Schell's 112 lenses and 35-chapter knowledge base with risk-first prototyping, behavioral playtest evidence, production constraints, business viability, community health, and design responsibility. Use for designing or reviewing a game, mechanic, level, puzzle, interface, progression, narrative, multiplayer system, VR/AR experience, prototype, pitch, economy, live operation, or playtest plan; especially when teams face conflicting ideas, unclear fun, balance problems, weak retention, scope risk, or uncertain next steps."
---

# Jesse Schell Game Design Master

Use the book as a queryable instrument, not a checklist. Diagnose the decision that matters now, select only lenses capable of changing it, and finish with a falsifiable next move.

## Governing chain

**Deep listening → essential experience → real context → system coherence → player behavior → single largest risk → disposable prototype → behavioral evidence → production/business/community/responsibility closure.**

Preserve five principles:

1. Design the player's experience, not a feature inventory.
2. Use lenses to expose blind spots; use risk to set priority.
3. Treat player models and designer intuition as hypotheses.
4. Require behavior evidence before raising confidence.
5. Track foreseeable consequences beyond author intent.

## Choose the operating mode

- **Quick diagnosis**: A concrete problem and limited evidence. Use 3 lenses and one next experiment.
- **Deep design review**: A build, design document, rules, video, telemetry, or playtest notes are available. Use 3–5 lenses, system tracing, and a decision log.
- **Concept creation**: No build exists. Define essential experience, context, theme, four elements, largest risk, and a throwaway prototype.
- **Reference lookup**: The user asks for a lens, chapter, or concept. Read the relevant reference and answer without forcing the full protocol.

Do not run a full audit unless the user explicitly requests one. Breadth without priority is analysis theater.

## Step 1 — Establish the decision

Write these before choosing lenses:

- **Player micro-scene**: “A player in [place/time/posture/social context/interruption conditions] tries to [action] and should feel/understand/expect [experience].”
- **Decision at stake**: The reversible or irreversible choice the team must make.
- **Provisional experience problem**: “Players fail to feel/understand/do X, possibly because Y.”
- **Single largest risk**: “If assumption X is false, the game still fails even if everything else ships.”

If evidence is missing, label the problem and risk as provisional. Never invent build behavior, metrics, rules, or player reactions.

## Step 2 — Classify project stage and evidence

Select one stage: concept, core-loop prototype, vertical slice, production, soft launch, live operations, or redesign. Read [routing.md](references/routing.md) for stage-specific lens clusters and deliverables.

Grade evidence:

| Grade | Evidence | Use |
|---|---|---|
| E4 | Reproducible build behavior, rules, telemetry | Can support a decision |
| E3 | Recorded target-player behavior across sessions | Strong but context-bound |
| E2 | Player interview or survey linked to observed behavior | Explanatory, not decisive alone |
| E1 | Stakeholder claim, market anecdote, community opinion | Generates hypotheses |
| E0 | Designer intuition or model inference | Direction only |

State confidence as **high / medium / low** and name what evidence would change it.

## Step 3 — Select 3–5 lenses algorithmically

Read [routing.md](references/routing.md), then use [lenses.md](references/lenses.md) or the relevant chapter only when needed.

Score each candidate:

`score = relevance(0–3) + decision leverage(0–3) + falsifiability(0–2) + evidence gap(0–2) − redundancy(0–2)`

Select at least:

- one **experience/player lens**;
- one **system/expression lens**;
- one **risk/evidence lens**.

Add a fourth or fifth only if it may change the prototype, metric, safety threshold, or continue/stop decision. For every selected lens, write: **“This lens could disprove…”**

Resolve conflicts in this order:

1. Safety, informed consent, accessibility, and legal constraints;
2. essential experience in the real play context;
3. stronger player-behavior evidence;
4. system and theme coherence;
5. production and commercial viability;
6. designer preference.

Do not hide a value conflict behind a numerical score; state the trade-off.

## Step 4 — Trace the system

Run only the relevant checks:

1. **Experience–context**: Does the intended experience fit attention, body, device, companions, session length, and interruption?
2. **Experience–four elements**: Do mechanics, story, aesthetics, and technology reinforce the same theme?
3. **State–action–feedback**: Can players know what they can do, what happened, and why?
4. **Choice–consequence**: Are choices legible, consequential, and free of universal dominant strategies?
5. **Challenge–skill–economy**: Do probability, rewards, timing, and feedback create learning or runaway advantage?
6. **Moment–session–lifecycle**: Separate first-session magic, third-session learning, and thirtieth-session replay/social value.
7. **Individual–social–commercial**: What behaviors do identity, ranking, rewards, payment, and governance encourage?
8. **Impact–responsibility**: Who benefits, who may be harmed, what threshold triggers intervention, and who owns remediation?

## Step 5 — Build a falsifiable artifact

Choose the cheapest artifact that answers the largest-risk question: paper rules, role-play, one-room graybox, fake door, video, economy simulation, technical spike, moderation drill, or live-data query.

Use the templates in [deliverables.md](references/deliverables.md). Every prototype card must contain:

- hypothesis and credible alternative explanation;
- what the prototype deliberately excludes;
- target players, context, and sample limitations;
- success behavior, failure behavior, guardrail, and stop line;
- the decision triggered by pass, mixed, or fail results.

Do not use prototype polish as evidence of product progress.

## Step 6 — Interpret without laundering uncertainty

Separate:

- **observation**: what happened;
- **interpretation**: why it may have happened;
- **counterevidence**: what conflicts with the interpretation;
- **decision**: continue, modify, replace, or stop;
- **next unknown**: the new largest risk.

Do not generalize a short test to long-term retention, economy health, community safety, cultural impact, or low-probability/high-harm events.

## Step 7 — Return a decision-ready answer

Unless the user requests reference-only mode, output:

1. **Strong diagnosis** — one sentence, confidence, and evidence grade.
2. **Player micro-scene** — one observable moment.
3. **Decision and single largest risk** — why it outranks other issues.
4. **Selected lenses** — 3–5, each with “could disprove.”
5. **System finding** — causal chain, not a feature list.
6. **Falsifiable artifact** — smallest useful prototype or analysis.
7. **Success / failure / guardrail / stop line** — behavioral thresholds.
8. **Next decision** — pass, mixed, and fail branches.
9. **Unknowns and responsibility** — missing evidence and foreseeable harm.

Prefer a compact decision brief. Add chapter detail only when it changes the decision.

## Reference routing

- Read [routing.md](references/routing.md) to choose lenses by problem and project stage.
- Read [deliverables.md](references/deliverables.md) for reusable design artifacts and evidence thresholds.
- Read [lenses.md](references/lenses.md) for the complete numbered lens index.
- Read [glossary.md](references/glossary.md) for concise terminology.
- Read [patterns.md](references/patterns.md) for recurring methods.
- Read [cheatsheet.md](references/cheatsheet.md) for fast decision rules.
- Read exactly the relevant file in `references/chapters/` for chapter-level depth or source-page location. Search filenames by chapter number or title; do not load all 35 chapters.

## Boundaries

- Do not impersonate Jesse Schell or present this synthesis as his personal judgment.
- Do not apply it to unrelated management, investing, or life advice.
- Do not equate feature count, branches, graphics, novelty, conversion, or engagement with player value.
- Do not use indirect control to hide payment, privacy, risk, or irreversible consequences.
- Do not let an elegant framework overrule contradictory player evidence.
- For current laws, platform rules, markets, safety, health, minors, privacy, or AI rights, verify contemporary primary sources and involve qualified reviewers.
