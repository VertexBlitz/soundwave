# Soundwave

Responsive static music-streaming preview for Netlify.

## Deploy to Netlify

1. Open the Deploy to Netlify link:
   https://app.netlify.com/start/deploy?repository=https://github.com/VertexBlitz/soundwave
2. Sign in to Netlify and authorize its GitHub App for the `VertexBlitz/soundwave` repository.
3. Confirm the suggested settings and publish.

The repository contains `index.html` and `netlify.toml`. Netlify publishes the repository root as a static site.

## Preview features

- Responsive dark interface
- Search across demo tracks
- Playlist cards
- HTML5 audio player with play/pause, next/previous, seek, volume, shuffle and repeat
- Likes stored in the current browser using localStorage

## Scope

This is a front-end preview. It does not yet include server-side accounts, Google OAuth, PostgreSQL/Prisma persistence, artist uploads, or a production music-provider integration. The demo player points to sample audio streams; replace them with properly licensed catalog streams before a public music launch.
