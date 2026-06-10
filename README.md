# World Cup 2026 — Bracket Predictor ⚽🏆

A single-file, zero-dependency web app for predicting the entire FIFA World Cup 2026 (48 teams, June 11 – July 19). Rank every group, pick the 8 best third-place teams, score every knockout game, and export a shareable poster + full wall chart.

**[▶️ Play it live](https://world-cup-2026-bracket-two.vercel.app)** · [GitHub Pages mirror](https://enrique-perlan.github.io/world-cup-2026-bracket/)

## Features

- **Group stage** — tap teams in finishing order (1st / 2nd / 3rd), or press-and-hold to drag onto the podium.
- **Best 3rds** — pick the 8 third-place qualifiers; they're auto-slotted into the official FIFA bracket via backtracking.
- **Knockout bracket** — Round of 32 → Final, with score entry, automatic advancement, and penalty shoot-out picker for ties.
- **Bonus picks** — Golden Boot, Golden Ball, total goals.
- **Snapshots** — generates a tall poster and a landscape wall chart (canvas-rendered PNGs) you can download and share.
- **Light / dark theme**, confetti, mobile-first, fully responsive, no build step.

## Run locally

Just open `index.html` in a browser — there's no build, no dependencies, no server required.

## Tech

Plain HTML/CSS/JS in one file. Snapshots are rendered with the Canvas 2D API.
