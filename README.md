# LINEBREAK

The daily rugby union quiz. Six questions, 20 seconds each, type any correct answer. The rarer the answer, the further back your break starts: 5m, 22, 50 or 100 metres. Score is total metres (max 600).

Single self-contained `index.html`, no build step. Open it in a browser or host it on GitHub Pages.

- Reworked from SIXER (the cricket version); same engine: answer matching, saved progress, archive, share card.
- Match #1 is 17 Nov 2026. Three days of questions rotate; add more in the `MATCHES` array.
- Question format: `[name, tier, aliases[], note]`, tiers 1/2/4/6 map to 5m / 22m / 50m / 100m.
- Crowd percentages are seeded dummy data until a backend exists (see the `Crowd` object).
