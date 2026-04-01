# Changelog

## [1.0] — 2026-03-31

### Added
- 8-bill Congressional tracker (Mar 5 – Mar 26 2026) with three-row layout:
  metadata strip | full-width summary + teeth panel | expandable detail
- 10-entry Regulatory Timeline (Feb–Mar 2026): CFTC, Fed, DOJ, SEC, States
- Domain taxonomy (5 domains): prediction-markets, crypto, monetary-policy,
  fintech, financial-stability — left border encodes domain identity
- Filter bars: domain, category, party (bills); agency, action type (timeline)
- Reactive stats bar (5 cells): domain breakdown for bills, agency/enforcement
  breakdown for timeline
- Refresh button: Anthropic API + web search, tab-aware prompts
- Add Bill modal: three-step flow with AI pre-fill from name, URL, or description
- Edit mode: status pipeline, P(pass) %, notes, domain per bill or entry
- localStorage persistence with timestamp (key: reg-track-v1)
- Print-optimized CSS
- index.html redirect, README.md
