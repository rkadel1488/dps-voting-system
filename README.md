# DPS Biratnagar — Student Council Voting System

A complete school election platform for DPS Biratnagar built as a single self-contained HTML file.

## Features

- **Student voting flow** — Identity → House selection → 7 sequential ballots → sealed receipt
- **Admin dashboard** — Password protected (`dps2026`), with candidate management, live results, house/class config, and CSV export
- **4 Houses** — Sargas (Green), Sirius (Red), Pollux (Blue), Deneb (Yellow)
- **7 Roles** — School Captain (Boy/Girl), Vice/Chief Captain (Boy/Girl), House Captain, Vice House Captain, Class Prefect
- **24 election symbols** — Indian ballot-style SVG icons
- **Honor-system deduplication** by name + class
- **LocalStorage persistence** — all data survives page reloads

## Usage

Just open `index.html` in a browser — no server or dependencies required.

**Admin password:** `dps2026`

## Tech

React 18 + Babel (CDN), plain CSS, no build step.
