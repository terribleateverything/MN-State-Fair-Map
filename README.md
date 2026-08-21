# MN State Fair 2026 — Interactive Map

Interactive map of the **Minnesota State Fairgrounds** (Aug 27 – Sep 7, 2026): 980+ vendors, food, free giveaways, prize drawings, animals, stages, rides & shops.

## Usage
Open **`index.html`** in any browser — it's a single self-contained file (map + data inlined, no external dependencies).

## Features
- 📍 980+ mapped places across 8 toggleable categories
- 🎁 Free Stuff sorted by High / Medium / Low value (individually toggleable)
- 🎟️ Prize drawings (sign-up-and-win sweepstakes)
- 👁️ Hide/show individual pins — persists per device via browser localStorage
- 🌙 Dark / light mode
- 🔍 Instant search across names, foods, drinks & directions
- 🏛️ Building & area filter
- 🔎 Smooth pan/zoom with adaptive pin sizing

## Tech
Single self-contained HTML file. Data pulled from the official MN State Fair Fair-Finder catalog and 2026 Deals & Giveaways brochure.

## Regenerate / Update
Rebuild from source with `python3 build.py` in the `statefair/` workspace directory, then commit the new `index.html` here.