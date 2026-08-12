<div align="center">

# 🎨 git-viz
### 3D GitHub Skyline, Repo Galaxy, Tech Archipelago & Developer Duel

*Turn any GitHub profile into an interactive 3D city skyline, a floating orbital galaxy, tech archipelago islands, or an epic developer duel with WASD flight, shaders & synth audio.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Three.js](https://img.shields.io/badge/Made%20with-Three.js-000000?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/Language-Vanilla%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-FF6C37?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Backend](https://img.shields.io/badge/Backend-100%25%20Client--Side-238636?style=for-the-badge)](https://github.com)

</div>

---

## 🌟 Overview

**git-viz** is a lightweight, zero-dependency 3D web app built with **Three.js** and **Vanilla JS** that fetches public data from the GitHub REST API to render beautiful, animated 3D environments.

Whether you want to show off your annual contribution history as a futuristic 3D city skyline, inspect your top repositories as an orbiting star galaxy, explore language islands in a tech archipelago, or duel a fellow developer side-by-side, **git-viz** turns profile metrics into a state-of-the-art visual experience.

---

## 🎮 4 Main Interactive Modes

| Mode | Visual Description | Key Features |
| :--- | :--- | :--- |
| 🏙️ **3D City Skyline** | A 7×52 matrix grid representing 365 days of activity as 3D skyscrapers. | • Procedural window lights & spires<br>• Holographic username billboards<br>• **🏆 3D Monuments & Trophies** (Circadian Clock Tower, Star Magnet)<br>• **🎬 12-Month Timeline Scrubber & Melodic Playback** |
| 🌌 **Repo Galaxy** | An orbital node network surrounding a central profile star. | • Primary language color-coded laser beams<br>• **🏷️ Floating 3D Text Sprites** for repo names & stars<br>• **🖱️ One-Click Jump**: Click any star to open its GitHub repo |
| 🏝️ **Tech Archipelago** | 3D floating landmass islands grouped by programming language. | • Low-poly floating island bases with glowing rims<br>• Repository crystal spires scaled by star count<br>• Language distribution visualization |
| ⚔️ **Developer Duel** | Side-by-side 3D skylines comparing two GitHub profiles in real time. | • Cyan vs Crimson split 3D grid layout<br>• Central laser boundary divider<br>• **🏆 Live Star Leaderboard Banner** comparing scores |

---

## ⚡ Feature Highlights

- 🚶 **WASD Drone Street View:** Press **`🚶 Drone`** to enter ground-level flight controls (**WASD** to move, **Q/E** to adjust altitude, mouse drag to look around).
- ✨ **Three.js Post-Processing Bloom:** Built-in `UnrealBloomPass` shader for neon glows on rooftop antennas, lasers, and spires.
- 🎶 **Melodic Code Synthesizer:** Procedural Web Audio API synth playing harmonic scale arpeggios as the 12-month timeline builds.
- 🎆 **3D Particle Fireworks:** Launch interactive multi-colored particle fireworks over the city skyline with sound effects.
- 🎥 **WebM Video Exporter:** One-click **"🎥 Record Video"** button captures a 5-second 360° auto-rotating webm animation directly in-browser.
- 📸 **High-Res PNG Screenshots:** Export crisp high-definition PNG renders for portfolio READMEs or social sharing.
- 🛡️ **API Rate Limit Protection & Demo Mode:** Built-in PAT token setting + automatic mock profile fallback if GitHub API limits are met.

---

## 🎨 5 Vibrant Color Themes

| Theme | Aesthetic | Atmosphere & Weather |
| :--- | :--- | :--- |
| 🐙 **GitHub Dark** | Classic GitHub contribution greens (`#0e4429` → `#39d353`) | Floating ambient star dust |
| 🌌 **Cyberpunk Neon** | Futuristic magenta, purple, and neon cyan glow | Floating neon ash & embers |
| 🟢 **Matrix Emerald** | Deep dark green matrix terminal styling | Falling digital rain particles |
| 🌅 **Sunset Gold** | Warm dusk violet & golden amber illumination | Glowing ember particles |
| ⚡ **Obsidian Silver** | Sleek monochrome glass, steel, and brilliant white glow | Subtle monochrome dust |

---

## 🚀 Quick Start

### Option 1: Open Locally (No Installation Needed)
1. Download or clone this repository:
   ```bash
   git clone https://github.com/Pradeep-B28/GIT---viz.git
   ```
2. Double-click [`index.html`](file:///C:/Git/Repo%202/git-viz/index.html) to open directly in any modern web browser.

### Option 2: Run via Local Dev Server
```bash
npx serve .
# or
python -m http.server 8080
```
Then open `http://localhost:8080` in your browser.

---

## 🕹️ Controls Guide

- **Rotate / Pan / Zoom:** Left-click drag / Right-click drag / Scroll wheel.
- **Drone Street View:** Click **`🚶`**, use **WASD** to fly, **Q/E** for height, mouse to look around.
- **Timeline Playback:** Drag the slider or press **Play (▶)** to listen to your code melody.
- **Launch Fireworks:** Click **`🎆`** to detonate fireworks over the spires.
- **Save Renders:** Click **`📸 Save PNG`** for screenshots or **`🎥 Record Video`** for animated videos.

---

## 📦 Dependencies & Tech Stack

All libraries are loaded via ES Modules from CDN:
- **[Three.js (v0.163.0)](https://threejs.org/)** — 3D scene rendering, lighting, shadows, and particle systems.
- **[EffectComposer & UnrealBloomPass](https://threejs.org/docs/#examples/en/postprocessing/EffectComposer)** — Post-processing bloom shaders.
- **[OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls)** — Camera navigation.
- **[GitHub REST API v3](https://docs.github.com/en/rest)** — Public profile, repository, and event data.
- **[Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)** — Procedural melodic synthesizer audio.

---

## 📄 License

This project is open-source under the [MIT License](LICENSE). Feel free to modify, host on GitHub Pages, or use it in your personal developer portfolio!
