# China Reels Map

Paste a reel or TikTok of somewhere in China, and it becomes a pin on a map —
with the link, a note, and enough info to actually find the place when you're
standing in the city. Works on your phone and your laptop.

> **Status:** early build. The plan and scaffolding are in place; nothing is
> deployed yet. See [`PROGRESS.md`](PROGRESS.md) for the running status.

## Why this exists

Every good place in China is buried in a reel I'll never find again. Saved
folders on TikTok and Instagram are where travel plans go to die — no map, no
idea which city, no way to see them all at once. So this is the thing I wanted:
drop the link, get a pin, see the whole trip on one map.

## What it does (the plan)

**Add a place in a few taps**
- Paste a reel/TikTok link (or just a name). It works out the spot, drops a pin
  you can nudge, and saves the link alongside it.
- Coordinates come from the place name, not the video — reliable and free.

**See everything on one map**
- Pins by category — food, shopping, sights — across every city on the trip.
- Tap a pin for the note, the Chinese name (the one that actually works
  in-country), and the original reel.
- Filter by city, category, or status: want / booked / visited.

**Built for the ground, not just the couch**
- Mobile-first: one map, one thumb.
- Coordinates in true GPS (WGS-84). Inside China a pin can sit a little off —
  that's fine: the saved address is right there to copy into a local map app.

**Yours, and portable**
- Runs as a static site: no account, no build step.
- Your pins save in the browser; export/import the whole map as `.json` to move
  it between devices.

## The look

Editorial and minimal — real typography, no gradient soup, no emoji standing in
for icons. Meant to look like something a person made on purpose.

## Status & roadmap

Phase 1 (in progress): solo, localStorage, paste-to-pin, browse + filter on a
map, export/import.

On the bench:
- A shared map for the trip group
- Install-to-home-screen (PWA) and share-straight-from-TikTok on Android
- An iOS Shortcut to send links from the share sheet

## Fine print

Personal project, unofficial. Place data is best-effort — check it before you
rely on it to get somewhere.

*Built by a Monash student who was sick of losing good places in his saved
folder.*
