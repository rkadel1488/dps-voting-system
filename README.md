# DPS Biratnagar — Student Council Voting System

A complete school election platform for DPS Biratnagar. All data is stored in **Supabase** — votes, candidates, houses, classes and poll status are synced in real-time across every device.

## Features

- **Cloud storage** — Supabase backend; data is identical everywhere the app is opened
- **Real-time sync** — votes and poll status update live via Supabase Realtime
- **Student voting flow** — Identity → House selection → 7 sequential ballots → sealed receipt
- **Admin dashboard** — Password protected (`dps2026`), with candidate management, live results, house/class config, and CSV export
- **4 Houses** — Sargas (Green), Sirius (Red), Pollux (Blue), Deneb (Yellow)
- **7 Roles** — School Captain (Boy/Girl), Vice/Chief Captain (Boy/Girl), House Captain, Vice House Captain, Class Prefect
- **24 election symbols** — Indian ballot-style SVG icons
- **Duplicate prevention** — Checks Supabase before allowing a ballot

## Usage

Open `index.html` in any browser — no server required (Supabase handles the backend).

**Admin password:** `dps2026`

## Stack

- React 18 + Babel (CDN)
- Supabase JS v2 (CDN)
- Plain CSS — no build step

## Supabase Project

- **URL:** https://kmgipsafwcsymffoqvvc.supabase.co
- **Tables:** `houses`, `classes`, `candidates`, `votes`, `settings`
