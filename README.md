# Crypts of Eternity

A browser-based turn-based roguelike dungeon crawler — fully contained in a single HTML file. No installation, no dependencies, just open and play.

## Play

Open `index.html` in any modern browser, or play it live via GitHub Pages.

## Features

- **4 Playable Classes** — Mage, Brawler, Warlock, Tank, each with unique stats and skill sets
- **Infinite Dungeons** — Procedurally generated floors with no end. How deep can you go?
- **Boss Floors** — A boss encounter every 3 floors, scaling in difficulty as you descend
- **11 Enemy Types** — All scaling infinitely with dungeon depth
- **Loot & Equipment** — Find and equip weapons, armor, and accessories across rarity tiers
- **Persistent Save** — Progress is automatically saved to `localStorage` and survives browser closes
- **Permanent Upgrades** — Spend gold at the shop between runs to unlock lasting power

## How to Play

| Key | Action |
|-----|--------|
| Arrow Keys / WASD | Move / Attack |
| `1–4` | Use skill |
| `G` | Pick up item |
| `>` | Descend stairs |
| `I` | Open inventory |
| `H` | Help / controls |

## Tech

- Pure HTML5, CSS3, JavaScript — zero frameworks, zero build steps
- HTML5 Canvas for dungeon rendering
- DOM panels for UI (stats, inventory, combat log)
- Google Fonts: Press Start 2P

## Development

All game code lives in `index.html`. To make changes, edit that file and push:

```bash
git add -A
git commit -m "your change"
git push
```
