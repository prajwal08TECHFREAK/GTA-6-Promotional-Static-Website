# GTA VI — Welcome to Leonida

An unofficial, fan-made tribute site for **Grand Theft Auto VI**, built as an immersive PS5 loading-screen experience for the road to launch.

**Grand Theft Auto VI launches November 19, 2026** — PS5, PS5 Pro and Xbox Series X|S.

> This is a fan project. It is not affiliated with, endorsed by, or connected to Rockstar Games, Rockstar North, Rockstar Toronto or Take-Two Interactive in any way.

## Highlights

- Cinematic cover-art hero, Vice City neon palette, film-grain loading-screen aesthetic
- Live countdown to launch day (November 19, 2026)
- Editions & pricing with USD / GBP / EUR toggle (Standard and Ultimate)
- Road to launch: sourced timeline of official GTA VI news and milestones
- FAQ accordion covering release, platforms, price and PC status
- Interactive **Leonida** map of the state
- **Leonida Radio** — the site streams *"GTA 6 — Official Main Theme Music"* (Dan Allen Gaming, YouTube) as background music. Audio starts muted at page load and comes in with sound on your first tap or scroll (browser autoplay rules), and the power button toggles it on/off.
- GTA V-style cursor site-wide, original loading screen, back-to-top and toast feedback
- Fully self-contained: one `index.html` with inline CSS/JS and local assets — no build step, no dependencies

## Project structure

```
.
├── index.html          # The entire site (inline CSS + JS)
├── assets/             # Artwork, screenshots, map and YouTube thumbnails (local)
├── README.md
└── .gitignore
```

## Run locally

Any static file server works. From the project folder:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy on GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repo: **Settings → Pages**.
3. Source: **Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
4. Your site goes live at `https://<username>.github.io/<repo>/`.

## Credits

- **Grand Theft Auto VI** and all official key art, screenshots and logos © Rockstar Games / Rockstar North / Rockstar Toronto / Take-Two Interactive. Used here under fan-tribute practice, non-commercially, for informational and entertainment purposes. No commercial rights are claimed.
- **Videos** are not embedded or re-hosted; every card links out to the official Rockstar Games YouTube channel.
- **Background music**: "GTA 6 — Official Main Theme Music" by [Dan Allen Gaming](https://www.youtube.com/@DanAllenGaming) — a fan-made interpretation of the theme, streamed from YouTube. Not Rockstar's music. No affiliation.
- **Map of Leonida**: full-color interactive map sourced from the GTA VI community wiki (wikigta6). Not official Rockstar material.
- **Cursor artwork**: based on the GTA V in-game cursor (fan-supplied artwork).
- Trailer songs belong to their respective rights holders (The Pointer Sisters, Tom Petty, Justice, etc.).

## Legal

This project is unofficial fan work provided without warranty of any kind. All trademarks, characters and assets belong to their respective owners. If you are a rights holder and have any concern, please open an issue and it will be addressed promptly. The site contains no pre-orders, no payments, no data collection and no affiliate links.
