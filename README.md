# 🏏 Pixel Cricket v1 — Ultimate Arcade Edition

![Version](https://img.shields.io/badge/version-1.0.0-00ffcc?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-ff0055?style=flat-square)
![Stack](https://img.shields.io/badge/tech-HTML5%20%7C%20Canvas%20%7C%20JS-ffcc00?style=flat-square)

An arcade-inspired single-file retro cricket game built using HTML5 Canvas, CSS Flexbox, and vanilla JavaScript. Features custom Web Audio API chiptunes, dynamic pitch conditions, and a real-time match dashboard.

---

## 📸 Visuals & Screenshots

|             Title Screen / Main Menu             |                Gameplay & Match Dashboard                |
| :----------------------------------------------: | :------------------------------------------------------: |
| ![Pixel Cricket Menu](docs/screenshots/menu.png) | ![Pixel Cricket Gameplay](docs/screenshots/gameplay.png) |

---

## ✨ Features & Game Mechanics

- **🌱 Dynamic Pitch Conditions:** Experience varying ball bounce speeds and drift with **Green Seam**, **Dusty Spin**, and **Standard** pitch types.
- **🎯 Directional Shot Control:** Combine key inputs to execute lofted power hits or controlled grounded drives.
- **🏆 Multiple Game Modes:**
  - **SOLO:** Chase procedurally generated target runs in a 6-ball over.
  - **2P VS:** Local two-player head-to-head match setup.
  - **WORLD CUP:** Multi-stage tournament mode (Quarter-Final, Semi-Final, Final) with escalating difficulty.
- **⚡ Power Meter System:** Fill your power gauge through precise timing to unlock high-velocity Super Power Shots.
- **🎵 Chiptune Audio & Particle FX:** Synthesized retro audio created via Web Audio API, accompanied by boundary trail particles and screen shake effects.

---

## 🎮 Controls

| Key / Input               | Action                                               |
| :------------------------ | :--------------------------------------------------- |
| <kbd>◀</kbd> <kbd>▶</kbd> | Move batsman along the crease                        |
| <kbd>▲</kbd>              | Position for a **Lofted Power Shot**                 |
| <kbd>▼</kbd>              | Position for a **Grounded Defensive Drive**          |
| <kbd>Spacebar</kbd>       | Swing bat                                            |
| <kbd>P</kbd>              | Trigger **Super Power Shot** _(Requires Full Meter)_ |

---

## 🛠️ Project Structure

```text
pixel-cricket/
├── index.html            # Core game engine, UI layout, and audio logic
├── README.md             # Project documentation
├── LICENSE               # MIT License
└── docs/
    └── screenshots/      # Screenshots for repo display
        ├── menu.png
        └── gameplay.png
```
