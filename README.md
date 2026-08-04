# ✨ Aetheria VR — Cyberpunk Sanctuary

[![A-Frame](https://img.shields.io/badge/A--Frame-1.7.1-6366f1?style=for-the-badge&logo=aframe)](https://aframe.io/)
[![Meta Quest 3](https://img.shields.io/badge/Meta_Quest-3%2F3s_Ready-ec4899?style=for-the-badge&logo=meta)](https://www.meta.com/quest/)
[![WebXR](https://img.shields.io/badge/WebXR-Supported-06b6d4?style=for-the-badge)](https://immersiveweb.dev/)
[![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)

> A high-fidelity, single-file 3D & Virtual Reality exploration sanctuary built with **A-Frame 1.7.1** for **Meta Quest 3/3s** headsets and Desktop WebVR browsers.

---

## 🌟 Feature Highlights

- 💎 **Interactive Crystal Obelisk**: Levitating octahedron crystal core with dynamic color cycling (*Indigo Core*, *Neon Magenta*, *Cyan Plasma*, *Emerald Flux*, *Solar Amber*, *Cosmic Violet*) and Web Audio synthesizer chimes.
- 🌀 **Realm Gateway Portal**: Interactive portal ring that transitions the entire environment between 5 procedural realms (*Starry Sky*, *Cyberpunk Neon*, *Ether Dream*, *Ashen Volcano*, *Mystic Forest*).
- 🤖 **Animated Companion Bot**: Rigged 3D companion robot with interactive animation clips (*Dance*, *Jump*, *Walk*, *Idle*).
- 🪖 **Sci-Fi Relic Display**: Ancient damaged helmet displayed on a floating holographic pedestal.
- 👨‍🚀 **Explorer Vanguard**: Full-scale astronaut entity in zero-gravity stance.
- 🌌 **Majestic Horizon Rings**: Orbiting cosmic rings casting ambient luminescence across the sky.
- 🔊 **Zero-Dependency Web Audio Synth**: Synthesizes real-time sound effects and chimes without external audio asset download risks.

---

## 🎮 Controls & Exploration

| Mode | Input Device | Controls & Action |
| :--- | :--- | :--- |
| **Meta Quest 3 / 3s VR** | Touch Controllers | Point laser pointer & pull trigger button to interact with `.clickable` targets. Room-scale physical movement. |
| **Desktop WebVR** | Keyboard & Mouse | <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> to walk, **Mouse Click & Drag** to look around, **Left Click** on glowing objects to activate. |
| **Mobile / Cardboard** | Touch & Gyro | Touch screen reticle gaze control. |

---

## 🚀 How to Deploy on Meta Quest 3 (GitHub Pages)

Follow these simple steps to launch your VR world on your Meta Quest headset:

1. **Push Code to GitHub**:
   Ensure `index.html` and `README.md` are pushed to your repository `ShivankXD/ARVR-Project`.

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub: `https://github.com/ShivankXD/ARVR-Project`
   - Click **Settings** ➔ **Pages** (left sidebar).
   - Under **Build and deployment** ➔ **Source**, select **Deploy from a branch**.
   - Select Branch: `main` and Folder: `/ (root)`.
   - Click **Save**.

3. **Open in Meta Quest 3**:
   - Put on your Meta Quest 3 / 3s headset.
   - Open the **Meta Quest Browser**.
   - Type your live site URL: `https://shivankxd.github.io/ARVR-Project/`
   - Click the glowing **"VR"** button in the bottom-right corner to enter full immersive 6DoF Virtual Reality!

---

## 💻 Local Development Setup

To test the application locally on your PC:

```bash
# Clone the repository
git clone https://github.com/ShivankXD/ARVR-Project.git

# Navigate into the project folder
cd ARVR-Project

# Launch a local server (using npx or Python)
npx http-server -p 8080 -o
# OR
python -m http.server 8080
```

Open `http://localhost:8080` in your web browser.

---

## 🛠️ Technology Stack

- **Framework**: [A-Frame 1.7.1](https://aframe.io/)
- **Environment**: `aframe-environment-component` (1.3.4)
- **Animations & Rigging**: `aframe-extras` (7.5.0)
- **3D Model Formats**: `GLTF / GLB` (PBR Metallic Roughness workflow)
- **Audio Engine**: Native Web Audio API (Web Audio Synth)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

Made with ❤️ for AR/VR Enthusiasts & Meta Quest Developers.
