# 🎨 git-viz — 3D GitHub Skyline, Galaxy & Duel Visualizer

> Transform any GitHub profile into an interactive 3D city skyline, a floating repository constellation, or a side-by-side developer duel in real-time.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-blue)](https://threejs.org/)

---

## 🎮 3 Main Interactive Modes

1. 🏙️ **3D City Skyline Mode**:
   - Renders a 7x52 matrix grid (364/365 days) with procedural building window textures, rooftop antennas with red beacons for top activity, and raycaster hover tooltips.
   - **🎬 12-Month Timeline Scrubber & Playback:** Click ▶ to watch your city build chronologically week-by-week from Week 1 to Week 52!

2. 🌌 **3D Repo Galaxy Constellation Mode**:
   - Renders your repositories as glowing orbital stars around your central profile core.
   - Laser beam connection lines link repositories to the central user core, color-coded by programming language.
   - **Interactive Click:** Clicking any repository node opens its official GitHub repository page in a new tab!

3. ⚔️ **Side-by-Side 3D User Duel Mode**:
   - Compare two GitHub profiles side-by-side (e.g. `torvalds` VS `gaearon`).
   - Renders dual skylines in 3D space with a laser divider (Cyan vs Crimson palette) and a live VS star leaderboard.

---

## 🎨 Visual Themes & Atmospheric Weather

- 🐙 **GitHub Dark:** Classic green contribution skyline with ambient star dust.
- 🌌 **Cyberpunk Neon:** Glowing magenta & cyan matrix with floating ember particles.
- 🟢 **Matrix Emerald:** Digital rain falling particles with terminal green aesthetics.
- 🌅 **Sunset Gold:** Warm amber & dusk violet aesthetic with floating embers.
- ⚡ **Obsidian Silver:** Sleek monochrome glass & steel skyline.

---

## 🔊 Audio & Controls

- 🔊 **Web Audio Synthesizer:** Subtle procedural sine & triangle synth audio feedback on hover and skyline load (with mute toggle).
- 📸 **High-Res PNG Exporter:** 1-click screenshot button to export high-definition PNG images.
- 📐 **Camera Controls:** Isometric 3D View, Top-Down Heatmap View, and Orbit Auto-Rotation toggle.

---

## 🚀 Quick Start

1. Open [`index.html`](file:///C:/Git/Repo%202/git-viz/index.html) in your browser (or visit `http://localhost:8080`).
2. Select your desired mode (**Skyline**, **Galaxy**, or **Duel VS**).
3. Enter GitHub usernames or click quick preset chips (`octocat`, `torvalds`, `gaearon`).
4. Hit **"⚡ Visualize"** and explore!

---

## 📄 License

MIT — 100% free, client-side, zero backend required.