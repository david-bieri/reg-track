# Changelog

All notable changes to the Financial Regulation Tracker are documented in this file.

## [1.3] — 2026-04-01

### Added
- Contextual about strip between nav and stats bar
  - Slim always-visible bar: descriptor text + 5 domain coverage pills
  - Expandable panel (toggle via nav "About ▾/▴" button): scope description,
    per-tab data sources, methodology note, author attribution and disclaimer
- `showAbout` state; About toggle button in nav right cluster (ghost style, blue active state)
- Light/dark/auto theme toggle in nav bar (persists to localStorage)
- `domain` and `url` fields on all SEED_TIMELINE entries
- New timeline entry tl-11: Treasury NPRM on GENIUS Act stablecoin regulatory regime
- Domain filter dropdown on timeline tab
- Domain pill and "Source ↗" link in TimelineRow expanded info panel
- Domain select and URL input in TimelineRow edit mode
- Timeline stats bar now uses domain-based counts (mirrors bills tab)
- `AddEntryModal` component: 3-step flow (paste URL → AI fetch → review/confirm)
  with domain select, source URL field, and all timeline entry fields
- "+ Add entry" teal button in timeline filter bar
- `doFetchEntry`, `doConfirmEntry`, `closeAddEntryModal` handlers
- Column sorting: Date (bills tab); Date, Agency, Action type (timeline tab)
  with clickable headers and ▲/▼ indicators

### Changed
- Refresh prompt broadened from prediction-market-only agencies to full regulatory
  scope (CFTC, Fed, DOJ, SEC, Treasury, OCC, FDIC, FinCEN)
- Refresh JSON schema now requires `domain` and `url` fields for new entries
