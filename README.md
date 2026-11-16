# Buckwheat Sort

A small browser game: sort buckwheat grains. Good grains go into the bowl, bad grains and debris go into the bin.
The game gets faster level by level.

- Works on phone and desktop, and can be installed as an app (PWA, works offline).
- Ukrainian and English.
- A profile is only a nickname. Progress is saved in your own browser (localStorage). No email, no password, no server.
- Guest mode: play without saving anything.

Built with plain HTML, CSS and JavaScript. No framework, no build step.

## Run locally

Any static server works, for example:

```bash
npx serve .
```

Then open the address it prints. A service worker is used, so open it through a server, not as a file.

## Files

```
index.html      start screen: language, profile, menu
buckwheat.html  the game
sw.js           service worker (offline)
manifest.json   app manifest (install on phone)
icons/          app icons
```

## Deploy

It is a static site, so it can be deployed to Vercel as is.

## Licence

MIT, see `LICENSE`.
