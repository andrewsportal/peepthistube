# Sunset House Landing Page

Single-page premium landing experience for three House music mixtapes.

## Interaction model

The landing page is a simplified scene portal:

- Full-screen looping background video per mixtape scene
- Left/right edge arrows to move between the 3 scenes
- One-hand mobile-first bottom control console
- Controls auto-fade during playback and return on tap
- No top hamburger or multi-menu layout
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

1. `PORTAL.fallbackVideo` and `PORTAL.fallbackPoster`
2. `PORTAL.mixtapes` for each scene's:
   - `title`
   - `description`
   - `audio` / `download`
   - `video`
   - `tracklist`

The `PORTAL` object is the single source of truth for all editable content.