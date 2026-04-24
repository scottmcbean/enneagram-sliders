# Enneagram Sliders

A type-specific variant of the Veris **Energy Mixing Board**, built for confirmed-client use only. Where the public Mixing Board (`scottmcbean/mixing-board`) detects behavioral patterns from the shape of the board, the Sliders tool keys directly off the user's known Enneagram type (and optional dominant instinct), producing recommendations calibrated to their type-specific motivations, defenses, and growth edges.

## How it differs from the public Mixing Board

| | Mixing Board (public) | Enneagram Sliders (this repo) |
|---|---|---|
| **Audience** | Anyone, anonymous | Confirmed Veris clients only |
| **Entry** | Jump straight into Screen 1 | Screen 0: pick type + optional instinct |
| **Content engine** | Pattern detection from slider shape | Direct `(type, subtype, category, direction)` lookup |
| **Voice** | General, archetypal | Type-specific, coaching-aware |
| **Purpose** | Self-exploration and lead-in tool | Coaching companion after typing is known |

## Status

**Path 3 build landed (2026-04-23).** The Linden-recommended, Scott-greenlit, Sutton-endorsed surgical hybrid after the round-2 content-structure audit. Full Marlowe 9-type library wired. Live at `https://scottmcbean.github.io/enneagram-sliders/`.

### What's in this build

- **Screen 0** — Sable spec verbatim: 3x3 Freight-numeral grid, inline "No preference"-default instinct picker, Path C transitions.
- **Screen 1** — V5 sliders, unchanged from Mixing Board.
- **Screen 2** — Single-pick card grid. Tag-pick sub-step dropped (Path 3 decision: Marlowe's type-specific content already is the commitment surface).
- **Screen 3** — Dial-up and dial-down render as unified mini-blocks (title + framing + 3 notice bullets + move). Subtype-gated content with graceful fallback to generic Type-N when "No preference" is selected.
- **Hero coaching questions** — Subtype-gated triplets per type. Pattern detection engine retired.
- **Two-layer exclusion filter** — Construct map (Sutton 2026-04-21) plus type-signature under-invest filter (Sutton 2026-04-23, Section 4). Graceful degradation if filter strips the pool below 2.
- **Rest dial-down retired** — Per cross-type decision 2026-04-22. Rest still renders dial-up; never dial-down.

## Deployment

Deployed to GitHub Pages at `https://scottmcbean.github.io/enneagram-sliders/`. Same static-hosting pattern as `scottmcbean/mixing-board`.
