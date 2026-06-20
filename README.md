# Sopwith Camel — Enhanced ✦

A modern HTML5 Canvas tribute to the 1984 classic **Sopwith** — biplane dogfighting, bombing runs, procedural terrain, and synthesized audio. Zero dependencies, single file.

## 🎮 Play It

👉 **[Play now](https://nwfella.github.io/slopwith-camel/)** (GitHub Pages)

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ↑ ↓ | Pitch up / down |
| **X** | Accelerate |
| **Z** | Brake / decelerate |
| **SPACE** | Fire machine gun |
| **B** | Drop bomb |

Land on the **HOME BASE** runway to refuel and reload.

## ✨ Features

- **Physics-based flight** — gravity, momentum, lift, stalls, loops
- **Procedural terrain** — sine-wave generated, looping world (16K px wide)
- **Enemy biplanes** — AI that patrols, chases, dives, climbs, and shoots back
- **Ground targets** — Oil tanks (shootable), Factories (bomb-only), AA guns (flak bursts)
- **Particle system** — Object-pooled explosions, smoke trails, debris, fire
- **Smooth camera** — Parallax scrolling with background mountains, stars, and moon
- **Web Audio API** — Synthesized SFX: engine hum, machine gun, bomb whistles, explosions
- **Retro HUD** — Score, lives, fuel gauge, HP bar, ammo counters, stall warning
- **Full screen** — Responsive canvas, dark neon aesthetic

## 🛠️ Tech

- **HTML5 Canvas 2D** — All vector graphics drawn via canvas primitives
- **Web Audio API** — Procedurally generated sound effects (no audio files)
- **ES6+ JavaScript** — Classes, object pools, fixed-timestep game loop
- **Zero dependencies** — Single `index.html` file, nothing to install

## 📦 Local Dev

Just open `index.html` in any modern browser:

```bash
git clone https://github.com/nwfella/slopwith-camel.git
cd slopwith-camel
# Open index.html in your browser
```

No build step, no server, no npm.

## 🏆 Credits

Inspired by the original **Sopwith** (1984) by David L. Clark for the IBM PC/XT. Built as a tribute and learning project.
