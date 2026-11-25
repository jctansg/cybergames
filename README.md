# CyberGames

A collection of free, browser-based arcade games with a retro cyber/terminal aesthetic. No installs, no sign-ups — just open the game in your browser and play.

## Live site

No install needed — play the games directly on GitHub Pages:

- [Password Asteroids](https://jctansg.github.io/cybergames/password-asteroids.html)
- [DOS Defender](https://jctansg.github.io/cybergames/dos-defender.html)

## Games

| Game | File | Description |
|------|------|-------------|
| Password Asteroids | [password-asteroids.html](password-asteroids.html) | A neon typing shooter. Asteroids encrypted with real-world passwords hurtle toward Earth — type each password exactly to crack and destroy it before it breaches. Longer, more complex passwords score more. Reach 500+ points to secure the planet. |
| DOS Defender | [dos-defender.html](dos-defender.html) | A network-security simulation with a DOS-era terminal look. Malicious requests flood your server — tap red attackers to filter them and let green users through, or the server collapses under load. |

## Features

- Fully client-side — everything runs in the browser
- Mobile-friendly touch controls and on-screen keyboards
- Sound effects with toggles
- Installable as a PWA on supported devices
- Heavily commented JavaScript for easy reading and learning

## Run locally

These are plain static HTML files. Serve the folder with any static server:

```bash
cd cybergames
python3 -m http.server 8000
```

Then open http://localhost:8000/password-asteroids.html or http://localhost:8000/dos-defender.html.

## Self-host (optional)

These are plain static HTML files — clone the repo and serve the folder with any static server, or deploy it to any static host (Netlify, Vercel, Cloudflare Pages). No build step required.


## Structure

```
cybergames/
├── README.md               # This file
├── password-asteroids.html # Password Asteroids (single-file game)
└── dos-defender.html       # DOS Defender (single-file game)
```

## License

MIT
