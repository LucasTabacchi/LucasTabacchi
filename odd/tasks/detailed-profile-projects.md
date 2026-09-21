# Detailed profile projects

## Objective
Replace the brief project descriptions in the GitHub-profile README with detailed, evidence-based project cards.

## Problem
The existing project section names relevant work but does not show concrete scope, capabilities, or technology choices.

## Scope
- Update `README.md` only for the public-facing project showcase.
- Preserve the five existing projects and their repository links.
- Add three user-specified project paths with evidence-based descriptions.
- Base all claims on each project's public README.

## Constraints
- Spanish content, with concise, readable cards inspired by the provided two-column example.
- Do not add unverified claims.
- TDD: disabled/not applicable — documentation-only change; check with Markdown review and `git diff --check`.
- Delivery strategy: ask-on-risk; forecast: ~80 authored changed lines.

## Tasks
- [x] P1 — Replace the short project entries with five detailed, evidence-backed cards in `README.md`.
  - Route: delegated direct.
  - Trigger evidence: preparation required review of five repository READMEs; content change is non-trivial.
  - Acceptance: each card has value proposition, 2–3 verified highlights, and technology tags; links remain correct.
  - Checks: Markdown structure inspection; `git diff --check`.

- [x] P2 — Add detailed cards for Airports API, iBank and Network QoS Monitor in `README.md`.
  - Route: delegated direct.
  - Trigger evidence: preparation required research across three external project READMEs and updates to the feature task document plus README.
  - Acceptance: each card has a direct requested link, verified value proposition, 2–3 highlights and technology tags.
  - Checks: Markdown structure inspection; `git diff --check`.

## Progress
- Research complete: verified descriptions gathered from public READMEs for AutoDocker, ProjectFlow, Amargo y Dulce, Kafka banking events, and IS2_TPFI.
- P1 complete: expanded the five linked project entries with verified value propositions, highlights and technology tags. Markdown inspection and `git diff --check` passed. Evidence: current work-unit commit `feat(readme): expand project showcase`.
- New scope authorized: add Airports API, iBank and Network QoS Monitor after research verification.
- P2 complete: added evidence-based cards for Airports API, iBank and Network QoS Monitor with direct requested links, verified highlights and technology tags. Markdown inspection and `git diff --check` passed. Evidence: current work-unit commit `feat(readme): add architecture project cards`.
- Next: none.
