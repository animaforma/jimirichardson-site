# Jimi Richardson Portfolio Site

Personal portfolio for Jimi Richardson — independent 3D motion designer specialising in Houdini simulation and product animation. Single-page HTML/CSS/JS, deployed on Vercel.

## Stack

- Each page is its own file (HTML, CSS, JS all inline, no build step): `index.html` plus one file per case study
- Clean URLs via `vercel.json` (`cleanUrls: true`) — e.g. `jurlique.html` is served at `/jurlique`
- Assets: Bunny CDN at `jimi-richardson.b-cdn.net/SITE FILES/`
- Deployment: Vercel (auto-deploys on push to `main`)
- Live URL: `https://jimirichardson.com`

## Key Assets

- Showreel (desktop): `https://jimi-richardson.b-cdn.net/SITE%20FILES/SHOWREEL/SHOWREEL%202026.mp4`
- Showreel (mobile): `https://jimi-richardson.b-cdn.net/SITE%20FILES/SHOWREEL/SHOWREEL_2026_mobile.mp4`

## Content Reference

- Contact email: `jimi@jimirichardson.com`
- Work grid projects (in order): Jurlique (`/jurlique`), MCO Beauty (`/mco-beauty`), Phyco Health Seascrub (`/seascrub`), Phyco Health Kombucha (`/phycobucha`), Shaw + Smith (`/shaw-smith`), Minirig (`/minirig`), Royal Salute (`/royal-salute`), BioLumi (`/biolumi`)
- Case studies: one HTML page per project, matching the routes above

## Roadmap

- [x] Build individual case study pages per project
