# About

## Synthesis

This repository combines two complementary designs:

- a complete, source-located knowledge base covering 35 chapters and 112 numbered lenses from the Chinese third edition of *The Art of Game Design*;
- a risk-first execution protocol that selects only lenses capable of changing a prototype, observation threshold, safety guardrail, or continue/stop decision.

## What the master version adds

1. Project-stage routing from concept through live operations and redesign.
2. E0–E4 evidence grades and explicit confidence.
3. A scored lens-selection portfolio across experience, system, and evidence layers.
4. Conflict resolution across safety, experience, evidence, coherence, viability, and preference.
5. Separate validation horizons for first, third, and thirtieth sessions.
6. Reusable artifacts for prototypes, playtests, economy, governance, responsibility, and decision logging.
7. Progressive disclosure: the core protocol stays in `SKILL.md`; detailed chapters and lenses load only when relevant.

## Validation record

- Skill frontmatter and naming validated with Codex `quick_validate.py`.
- 35 chapter reference files present.
- 112 lens numbers indexed, with the third edition's two distinct lens-93 entries preserved.
- All links from `SKILL.md` resolve.
- No empty bundled files.

## Maintenance rules

- Add a method only when it can alter a decision, artifact, observation, threshold, or stop condition.
- Keep facts, interpretations, counterevidence, decisions, and unknowns separate.
- Prefer behavioral thresholds to attitudinal claims.
- Update tests after any change to routing, evidence grades, output contract, or boundaries.
