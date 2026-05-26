# VOID ☄️

> **A minimalist neon space survival game. Navigate the asteroid field. Survive. Upgrade.**

![Game Preview](https://img.shields.io/badge/game-browser--based-0cf?style=flat-square&logo=html5&logoColor=white)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## ▶ Play

**[williamandersson2-art.github.io/void-game](https://williamandersson2-art.github.io/void-game/)**

Or clone and open `index.html` — no install, no build step, no dependencies.

---

## Controls

| Input | Action |
|---|---|
| **Mouse** | Steer the ship |
| **W A S D** | Move (standard keyboard) |
| **Arrow Keys** | Move (alternative) |
| **Space / Click** | Shoot *(requires Turret upgrade)* |

---

## Upgrades

Every **5 orbs** collected, pick one of 3 random upgrades:

| Upgrade | Effect |
|---|---|
| ◎ **MAGNET** | Orbs fly toward you |
| ⬡ **SHIELD** | Absorbs 1 extra hit (up to 3x) |
| ▶ **VELOCITY** | Ship speed +25% (stackable) |
| ◆ **BOUNTY** | Orbs worth double points |
| ✦ **FROST** | Asteroids move 18% slower (stackable) |
| ▲ **TURRET** | Space/click to shoot and destroy asteroids |
| ♥ **REPAIR** | Instantly restore 1 life |
| ◌ **GHOST** | Longer invincibility window after hits |

---

## Features

- 60fps canvas rendering with particle effects
- WASD + Arrow Keys + Mouse controls
- 8-upgrade progression system — choose every 5 orbs
- Best score saved to `localStorage` (persists between sessions)
- Shield ring visual when shield upgrade is active
- Turret aim line when turret upgrade is active
- Magnet pulls orbs toward you
- Wave difficulty scaling every 18 seconds
- Procedurally generated asteroid shapes
- Ship trail, engine flame, explosion particles
- Mobile touch support

---

## Built With

Pure HTML5 Canvas · Vanilla JS · [Orbitron](https://fonts.google.com/specimen/Orbitron) font

---

MIT License
