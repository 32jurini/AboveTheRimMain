# ABOVE THE RIM
Browser-based stylized 3D basketball game, offline playable build.

## Running
Upload all files (except README if desired) to the root of a GitHub repository. Enable GitHub Pages: Settings > Pages > Deploy from a branch > main > /(root). Visit your Pages URL. You can also use VS Code Live Server. Do not open index.html with file:// because ES modules need HTTP.

## Features
Quick Play 1v1 vs CPU, Streetball 1v1 first to 11, MyCareer XP progression, Championship first to 15, practice, MyPlayer customizations and saved local progress. 3D court, third-person camera, movement, timed shots, AI opponent, ball arcs, bounces, scoring, and steals.

## Limitations
This is an offline starter build, not NBA 2K fidelity. No real online multiplayer, user accounts, server, advanced skeleton animations, passing, teams, complete foul system or tournament brackets yet. MyCareer and Championship are simplified match-based modes. Profile data is stored in browser localStorage and is not synced across devices.

## Controls
WASD / arrows: move. Shift: sprint. Hold and release Space: shoot. E: steal. Q: crossover. R: reset in practice. Menu button: return to menu.

## Technology
Three.js 0.170 via jsDelivr; HTML/CSS/JS modules. Internet needed to load Three.js. No build tooling required.
