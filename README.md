# Solviq Lead Tracker

Internal tool for researching and categorising hotel leads in Phuket.

## Features
- Batch AI research — paste hotel names, auto-fetches ratings, reviews, phone numbers
- Auto-scores A/B/C tier based on your criteria
- Status tracking (New → Contacted → Replied → Meeting Set → Closed Won)
- CSV export for Google Sheets import
- Data persists in localStorage (stays in your browser)

## Tier criteria
- **A** — rating ≥ 4.0 AND reviews ≥ 50
- **B** — rating ≥ 3.8 OR reviews ≥ 20
- **C** — everything else

## Setup
Just open `index.html` in a browser, or visit the GitHub Pages URL.

Requires an Anthropic API key for the batch research feature.
