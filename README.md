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

Phase 0 scaffold. Content is stubbed for all 9 types; Marlowe is authoring Type 1 content first. Screen 0 UI is a functional placeholder awaiting Sable's design. Not deployed to GitHub Pages yet — release gated on Scott's approval.

## Screens

- **Screen 0 — Type picker** (net-new, placeholder in scaffold)
- **Screen 1 — The Mirror** (Path C, type-direct content engine)
- **Screen 2 — The Play** (Path C, type-direct content engine)
- **Screen 3 — The Path Forward** (Path C, type-direct content engine)

## Deployment

Will deploy to GitHub Pages at `https://scottmcbean.github.io/enneagram-sliders/` when the full build lands and Scott approves the release. Same deploy pattern as `scottmcbean/mixing-board`.
