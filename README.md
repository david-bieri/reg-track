# Financial Regulation Tracker · reg-track

Browser-based tracker for Congressional financial regulation bills
and federal regulatory actions.

**Live:** david-bieri.github.io/reg-track

## Features
- Multi-domain bill tracking: prediction markets, crypto, monetary policy,
  fintech, financial stability
- 8 seed bills with full text, sponsors, category, status pipeline
- 10 seed regulatory timeline entries (CFTC, Fed, DOJ, SEC, States)
- Live refresh via Anthropic API + web search (tab-aware)
- Add Bill modal with AI pre-fill from bill name, URL, or description
- Filter by domain, category, party (bills); agency, action type (timeline)
- Edit mode: update status, P(pass) probability, notes
- Persistent storage via localStorage
- Print-optimized layout

## Usage
Open bill_tracker.html directly in any browser.
No build step, no server.

## Data sources
Congressional press releases · CFTC Federal Register ·
Federal Reserve FEDS · DOJ · CNN · CNBC · Axios

## License
MIT · David Bieri · SPIA · Virginia Tech
