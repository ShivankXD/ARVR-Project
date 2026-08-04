# 🛸 Aetheria VR — Flying Spaceship Simulator

[![A-Frame](https://img.shields.io/badge/A--Frame-1.7.1-6366f1?style=for-the-badge&logo=aframe)](https://aframe.io/)
[![Meta Quest 3](https://img.shields.io/badge/Meta_Quest-3%2F3s_Ready-ec4899?style=for-the-badge&logo=meta)](https://www.meta.com/quest/)
[![WebXR](https://img.shields.io/badge/WebXR-Supported-06b6d4?style=for-the-badge)](https://immersiveweb.dev/)
[![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)

> Step inside the cockpit of an advanced 6DoF sci-fi starfighter! Fly through space, maneuver through energy ring checkpoints, and pilot your ship in immersive Virtual Reality built with **A-Frame 1.7.1** for **Meta Quest 3/3s** and Desktop browsers.

---

## 🚀 Key Simulator Features

- 🛸 **First-Person Pilot Cockpit**: Sit directly inside the ship's 3D cockpit featuring glass canopy frames, flight yoke joystick, holographic crosshairs, and live digital airspeed/altitude HUD gauges.
- ⚡ **6DoF Flight Physics**: Smooth 3D flight mechanics with pitch, yaw, and roll controls, acceleration throttle, and turbo engine boost.
- ⭕ **Aerial Energy Ring Course**: Fly through glowing orbital slalom rings in space. Ring collisions trigger speed boosts, score points, and play audio chimes!
- 🔊 **Dynamic Engine Audio Synthesizer**: Real-time Web Audio synth engine rumble that scales frequency and volume with your throttle speed.
- 🪐 **Deep Space Flight Sector**: Galactic Space Station landmark, floating asteroid hazards, and deep space skybox panorama.

---

## 🎮 Flight Controls

| Control Action | Desktop Key | Meta Quest 3 / 3s VR |
| :--- | :--- | :--- |
| **Throttle Up / Down** | <kbd>W</kbd> / <kbd>S</kbd> or <kbd>↑</kbd> / <kbd>↓</kbd> | Automatic / Controller Trigger |
| **Steer Left / Right (Yaw & Roll)** | <kbd>A</kbd> / <kbd>D</kbd> or <kbd>←</kbd> / <kbd>→</kbd> | Right Touch Thumbstick |
| **Pitch Nose Up / Down** | <kbd>I</kbd> / <kbd>K</kbd> | Right Touch Thumbstick |
| **Turbo Boost** | <kbd>Space</kbd> | Controller Grip |

---

## 🌐 Launch on Meta Quest 3 (GitHub Pages)

1. Open your headset's **Meta Quest Browser**.
2. Visit: `https://shivankxd.github.io/ARVR-Project/`
3. Click the glowing **"VR"** button in the bottom-right corner to step directly into the pilot seat!

---

## 💻 Local Development Setup

```bash
# Clone the repository
git clone https://github.com/ShivankXD/ARVR-Project.git

# Launch local server
npx http-server -p 8080 -o
```

Open `http://localhost:8080` in your web browser.
