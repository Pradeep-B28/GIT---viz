<div align="center">

# 🎨 git-viz
### 3D GitHub City Skyline, Repo Galaxy & Developer Duel Visualizer

*Turn any GitHub profile into an interactive 3D art piece, a floating orbital constellation, or an epic developer duel in real-time.*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Three.js](https://img.shields.io/badge/Made%20with-Three.js-000000?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/Language-Vanilla%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Audio-Web%20Audio%20API-FF6C37?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Zero Backend](https://img.shields.io/badge/Backend-100%25%20Client--Side-238636?style=for-the-badge)](https://github.com)

</div>

---

## 🌟 Overview

**git-viz** is a lightweight, zero-dependency 3D web app built with **Three.js** and **Vanilla JS** that fetches public data from the GitHub REST API to render beautiful, animated 3D environments.

Whether you want to show off your annual contribution history as a futuristic 3D city skyline, inspect your top repositories as an orbiting star galaxy, or duel a fellow developer side-by-side, **git-viz** turns boring profile metrics into a state-of-the-art visual experience.

---

## 🎮 3 Main Interactive Modes

| Mode | Visual Description | Key Features |
| :--- | :--- | :--- |
| 🏙️ **3D City Skyline** | A 7×52 matrix grid representing 365 days of activity as 3D skyscrapers. | • Procedural building window lights<br>• Rooftop beacon antennas for high activity<br>• **🎬 12-Month Timeline Scrubber & Auto-Playback (▶ / ⏸)**<br>• Precise Raycaster Hover Tooltips |
| 🌌 **Repo Galaxy** | An orbital node network of repositories surrounding a central profile star. | • Primary language color-coded laser beams<br>• **🏷️ Floating 3D Text Sprites** for repo names & stars<br>• **🖱️ One-Click Jump**: Click any star to open its GitHub repo |
| ⚔️ **Developer Duel** | Side-by-side 3D skylines comparing two GitHub profiles in real time. | • Cyan vs Crimson split 3D grid layout<br>• Central laser boundary divider<br>• **🏆 Live Star Leaderboard Banner** comparing scores |

---

## 🎨 5 Vibrant Color Themes & Weather FX

| Theme | Aesthetic | Atmosphere & Particles |
| :--- | :--- | :--- |
| 🐙 **GitHub Dark** | Classic GitHub contribution greens (`#0e4429` → `#39d353`) | Floating ambient star dust |
| 🌌 **Cyberpunk Neon** | Futuristic magenta, purple, and neon cyan glow | Floating neon ash & embers |
| 🟢 **Matrix Emerald** | Deep dark green matrix terminal styling | Falling digital rain particles |
| 🌅 **Sunset Gold** | Warm dusk violet & golden amber illumination | Glowing ember particles |
| ⚡ **Obsidian Silver** | Sleek monochrome glass, steel, and brilliant white glow | Subtle monochrome dust |

---

## 🛠️ Feature Highlights

- 🎬 **12-Month Timeline Playback:** Scrub through weeks 0 to 51 using the bottom timeline slider, or hit **Play (▶)** to watch your city build chronologically over the year.
- 🎯 **Raycaster Tooltips:** Hovering over skyscrapers or galaxy stars displays date, day of week, contribution count, and repository details.
- 🔊 **Web Audio Synthesizer:** Procedural sine & triangle synth sound feedback on hover and skyline generation (includes instant mute/unmute toggle).
- 🛡️ **API Rate Limit Protection & Demo Mode:** Built-in PAT token input (`⚙️ Settings`) + automatic **Demo Mode fallback** if GitHub API rate limits (60 req/hr) are reached.
- 📷 **High-Res PNG Export:** One-click screenshot button to download high-definition PNGs for social media or portfolio READMEs.
- 📐 **Camera Controls:** Quick toggles for **Isometric 3D View**, **Top-Down 2D Heatmap View**, and **Orbit Auto-Rotation**.
- 🧹 **WebGL Memory Optimization:** Automated disposal of geometries, materials, and textures when switching modes or profiles.

---

## 🚀 Quick Start

### Option 1: Open Locally (No Installation Needed)
1. Download or clone this repository:
   ```bash
   git clone https://github.com/Pradeep-B28/git-viz.git
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

## 🕹️ How to Use

1. **Select Mode:** Choose between **🏙️ Skyline**, **🌌 Galaxy**, or **⚔️ Duel VS** at the top bar.
2. **Enter Username(s):** Type any public GitHub username (or two usernames in Duel mode), or click one of the quick preset chips (`octocat`, `torvalds`, `gaearon`, `yyx990803`, `sindresorhus`).
3. **Visualize:** Click **"⚡ Visualize"** to generate the 3D scene.
4. **Interact:** Rotate, zoom, and pan using mouse drag / touch controls. Hover over buildings or click repository stars!

---

## 📦 Dependencies & Tech Stack

All libraries are loaded via ES Modules from CDN:
- **[Three.js (v0.163.0)](https://threejs.org/)** — 3D scene rendering, lighting, shadows, and particle systems.
- **[OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls)** — Smooth camera navigation.
- **[GitHub REST API v3](https://docs.github.com/en/rest)** — Public profile, repo, and event data.
- **[Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)** — Procedural audio synthesis.

---

## 📄 License

This project is open-source under the [MIT License](LICENSE). Feel free to modify, host on GitHub Pages, or use it in your personal developer portfolio!

