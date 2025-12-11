# Chaos Site (fork of theannoyingwebsite.com)

An aggressively annoying single-page site. As soon as a user interacts, it spawns a relentless swarm of pop-up windows that bounce around, respawn instantly when closed, and refuse to stay gone. Expect vibrating devices, clipboard pranks, fullscreen grabs, loud speech, and various other anti-user tricks.

## Run locally
- `npm install`
- `npm start`
- Open `http://localhost:4000` and click/press anything to unleash the chaos.

## What’s different in this fork
- Faster-moving popups with a minimum swarm that continuously replenishes (closing one immediately opens another).
- Still includes the original annoyances: bouncing windows, random searches, file downloads, clipboard spam, speech, and history hijinks.

## Notes
- Static assets live in `static/`. The main behavior is in `static/index.js`.
- This is intentionally hostile UX; only run in a disposable browser session.***

