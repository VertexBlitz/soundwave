# Soundwave

A responsive music-discovery preview deployed as a static site on Netlify.

## Live preview

https://wondrous-buttercream-752929.netlify.app

## Deploy

Netlify builds the repository root:
- Build command: `echo 'Soundwave preview is ready'`
- Publish directory: `.`

The preview has no build-time secrets or database requirement.

## Features in the live preview

- Responsive dark layout
- Live Audius trending catalogue and track search (read-only public API)
- HTML5 streaming player for tracks returned by Audius
- Play/pause, next/previous, seek, volume, shuffle and repeat
- Curated mood cards
- Likes stored in the current browser with localStorage
- Separate Spotify search links for each track

## Spotify

Spotify links open Spotify search for the selected artist and track. Soundwave does not extract or proxy Spotify audio. Spotify playback stays on Spotify; its streams are not mixed into the Audius player.

## Full-stack source

The full-stack Next.js/Prisma implementation is being prepared separately. Production accounts, PostgreSQL persistence, Google OAuth, email delivery, and direct S3/R2 uploads are not enabled in this static preview. They require service credentials and a database/storage configuration in Netlify environment variables.

## Music rights

Audius tracks are played through Audius stream endpoints. Do not upload or distribute tracks unless you own them or have permission to do so.
