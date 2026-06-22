# Sunset House Landing Page

Single-page premium landing experience for three House music mixtapes.

## Interaction model

The landing page is a simplified portal:

- Full-screen looping background video
- One-hand mobile-first bottom control console
- No hamburger menu
- Lightweight playback with one shared audio instance
- Media Session integration for better lock-screen/background controls (browser permitting)

## Files to add

Place these files either in the project root (`/workspace`) or update paths in `index.html` to point to `/assets/...`.

- `sunset-dance-loop.mp4` (hero looping video, 8-15s, seamless)
- `hero-poster.jpg` (fallback poster image for hero video)
- `artwork-1.png` (or `.jpg`)
- `artwork-2.png` (or `.jpg`)
- `artwork-3.png` (or `.jpg`)
- `mixtape1.mp3`
- `mixtape2.mp3`
- `mixtape3.mp3`

## Quick customization

Open `index.html` and edit:

1. `PORTAL.site` for brand / credit / hero copy
2. `PORTAL.video` for background video + poster
3. `PORTAL.mixtapes` for each mixtape's `audio`, `download`, `artwork`, `mood`, and `tracklist`

The `PORTAL` object is the single source of truth for all editable content.