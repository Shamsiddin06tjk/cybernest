# CyberNest

A 3D corridor you walk through room by room. Each room is one lesson with a real-life example:
networks, Linux, and Git, ending with your first `git push` to GitHub.

Languages: Uzbek, Russian, Tajik, English.

**Live demo:** https://shamsiddin06tjk.github.io/cybernest/

## Rooms

| Wing | Rooms |
|------|-------|
| Networks | 01 What is a network · 02 Router and DNS · 03 Ports and protocols · 04 Ping and traceroute |
| Linux | 05 Terminal · 06 Files and folders · 07 Permissions · 08 SSH and keys |
| Git & GitHub | 09 Git commits · 10 Push to GitHub |

## Controls

- Desktop: `W A S D` or arrow keys to walk, drag to look, click a door (or press `E`) to enter
- Phone: ▲▼ buttons to walk, swipe to look, tap a door or a room number

## Built with

- HTML, CSS, JavaScript
- [Three.js](https://threejs.org/) r128 for the 3D scene

## Run locally

```bash
python -m http.server 8000
```

Then open http://localhost:8000
