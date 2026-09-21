# Detailed profile projects and stack

## Objective
Showcase evidence-based projects and a categorized technology stack in the GitHub-profile README.

## Scope
- Preserve the project cards currently present in the README.
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

- [x] P4 — Render existing project cards in a two-column GitHub-native table layout. Evidence: pending commit.
  - Route: delegated direct.
  - Trigger evidence: layout conversion touches the README and feature task document; raw HTML compatibility was researched.
  - Acceptance: project content and links are preserved in bordered two-column cards, with a full-width final card when needed.
  - Checks: Markdown/HTML structure inspection; `git diff --check`.
## Progress
- P1/P2 complete.
- P3 complete: categorized direct-use technologies across languages/web, backend/APIs, mobile, data/cloud, infrastructure/events, quality/UI/DX and data/IA. Markdown inspection and `git diff --check` passed. Evidence: `feat(readme): categorize technology stack`.
- P4 complete: converted the seven current project cards into a GitHub-native raw HTML table with three two-column rows and one full-width final row. Markdown/HTML structure inspection and `git diff --check` passed. Evidence: pending commit.
- Next: none.
