# Soundwave

A responsive music-discovery preview deployed on Netlify.

## Live site

https://wondrous-buttercream-752929.netlify.app

## Music in the live preview

- Official Spotify Embed: Clean Pop Hits playlist featuring recognizable pop tracks such as Blinding Lights, Die With A Smile, End of Beginning and Cruel Summer.
- Audius discovery catalog: independent artist tracks and search, played in a separate Soundwave HTML5 player.
- No more SoundHelix sample/test MP3s.

## Spotify playback

The Spotify playlist is embedded through Spotify's official website embed. Playback and account/region availability are controlled by Spotify. Spotify audio stays inside the Spotify player and is not mixed with Audius streams.

## Deploy

Netlify builds the repository root:
- Build command: `echo 'Soundwave preview is ready'`
- Publish directory: `.`

The site is static and does not require build-time secrets.

## Current scope

The public preview does not yet include production accounts, PostgreSQL persistence, Google OAuth, or user uploads. These require a separately deployed backend, database, and object storage configuration.

## Music rights

Audio is played through the respective provider's official player/stream. Do not upload or distribute music unless you own it or have permission.
