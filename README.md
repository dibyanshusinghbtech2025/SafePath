# SafePath

**Safer night routes for women.** SafePath compares walking routes after dark using street lighting, open shops and places with people nearby, and user reports. Each route gets a Green / Amber / Red safety score with plain reasons, so a woman can choose before she leaves.

Built for the **Seva Innovation Challenge 2026** (Maharashtra Zone), Problem Statement 258. Team DIBZ (solo): Dibyanshu Singh.

**Live demo:** https://peaceful-kleicha-fb8039.netlify.app

> **Prototype status:** proof of concept. The demo runs on sample data for an imaginary area, not real streets. It has not yet been tested with real users.

## What it does

- Compare Shortest, Balanced and Safest walking routes between two places
- See why a route scores the way it does (lit street %, open places nearby, longest unlit stretch)
- Tap a street to report a broken light or an isolated stretch, and watch the scores update
- Use it in English, Hindi or Marathi, in any phone browser with no install

## How the score works

The score is rule-based, not AI. For each street segment: lit street adds points, open shops or places with people add points, and user reports subtract points. A route's score is the length-weighted average of its segments.

## Run it

Open `index.html` in a browser. It is a single file with no build step.

## Roadmap

1. Replace sample data with a real survey of one pilot area
2. Add real map data (OpenStreetMap) and live walking routes
3. Pilot with a college, then share unsafe-spot reports with the local council
4. Extend to other Maharashtra towns

## Privacy

No account is needed, location is not stored, and reports are anonymous.
