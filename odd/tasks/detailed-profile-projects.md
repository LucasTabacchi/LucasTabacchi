# Detailed profile projects and stack

## Objective
Showcase evidence-based projects and a categorized technology stack in the GitHub-profile README.

## Scope
- Preserve the eight detailed project cards.
- Replace the flat technology icon list with a categorized stack based on the user's public repositories.

## Constraints
- Spanish category headings while preserving the README's current visual style.
- Show direct-use technologies, not every transitive dependency.
- Exclude forks, fixtures and unsupported claims.
- TDD: disabled/not applicable; Markdown inspection and `git diff --check`.
- Delivery strategy: ask-on-risk; forecast: ~150 authored changed lines.

## Tasks
- [x] P1 — Expand the original five project entries. Evidence: `3ad8f98`.
- [x] P2 — Add Airports API, iBank and Network QoS Monitor cards. Evidence: `db50d60`.
- [x] P3 — Replace the flat technology list with categorized, evidence-based stack groups. Evidence: `feat(readme): categorize technology stack`.
  - Route: delegated direct.
  - Trigger evidence: 24-repository inventory plus updates to README and feature task document.
  - Acceptance: visible categories separate languages/web, backend/APIs, mobile, data/cloud, infrastructure/events and quality/UI; all claims are supported by public repositories.
  - Checks: Markdown structure inspection; `git diff --check`.

## Progress
- P1/P2 complete.
- P3 complete: categorized direct-use technologies across languages/web, backend/APIs, mobile, data/cloud, infrastructure/events, quality/UI/DX and data/IA. Markdown inspection and `git diff --check` passed. Evidence: `feat(readme): categorize technology stack`.
- Next: none.
