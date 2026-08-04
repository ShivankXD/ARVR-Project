# 🛍️ Aetheria Grand Mall — AR/VR Shopping Experience

[![Three.js](https://img.shields.io/badge/Three.js-r128-6366f1?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![WebXR](https://img.shields.io/badge/WebXR-VR_Ready-ec4899?style=for-the-badge)](https://immersiveweb.dev/)
[![Single File](https://img.shields.io/badge/Architecture-Single_HTML-06b6d4?style=for-the-badge)](index.html)
[![License](https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge)](LICENSE)

> A fully functional, zero-dependency, single-file **3D AR/VR Shopping Mall Application** built with Three.js (r128), ES6 classes, WebXR, HTML5 Canvas procedural textures, and Web Audio API.

---

## 🌟 Application Features

- 🏬 **Realistic 3D Shopping Mall Architecture**:
  - **6 Dedicated Boutiques**: *Urban Apparel*, *Luxe Leather*, *Kicks & Soles*, *Vanguard Bags*, *Chrono Timepieces*, and *Accessories Co*.
  - **Atmospheric Interiors**: Reflective marble floors, glass storefront windows, mezzanine level, procedural wood flooring, and ceiling spotlights.
  - **Animated Escalators**: Working escalator stairs with animated LED step lighting.
  - **Decorative Flora**: Potted indoor tropical plants and palms.

- 👕 **Interactive 3D Product Catalog**:
  - Shirts, T-Shirts, Hoodies, Leather Jackets, Trench Coats, Sneakers, Luxury Watches, Leather Backpacks, Sunglasses.
  - Procedural Canvas-generated product patterns, brand logos, and store entrance banners embedded dynamically inside JavaScript.

- 🎯 **Smart Gaze Detection & Product Cards**:
  - Continuous camera raycasting detects when player gaze points at a product.
  - **0.5s Gaze**: Highlights product with hover glow & displays floating glassmorphism product card.
  - **1.5s Gaze**: Smoothly reveals interactive action buttons (**Add to Cart**, **Buy Now**, **Wishlist**).

- 🚶 **Animated Shopper NPCs**:
  - Autonomous AI shopper NPCs walking around the mall with obstacle avoidance.

- 🗺️ **Live 2D Mini Map & Glassmorphism HUD**:
  - Real-time radar minimap tracking player position and shopper NPCs.
  - Interactive Shopping Cart count badge, Wishlist badge, and FPS performance counter.

- 🔊 **Embedded Web Audio Synthesizer**:
  - Real-time synthesized footstep audio, gaze hover chimes, and purchase confirmation sound sequences without external file dependencies.

---

## 🎮 Controls

| Action | Control Key |
| :--- | :--- |
| **Walk Mall** | <kbd>W</kbd> <kbd>A</kbd> <kbd>S</kbd> <kbd>D</kbd> |
| **Look Around** | **Mouse Drag** (Click screen to lock pointer) |
| **Inspect & Buy Product** | **Hold Gaze Reticle** on product for 0.5s – 1.5s |
| **VR Mode** | Click **ENTER VR MODE** button |

---

## 🌐 Launching on Web & Meta Quest VR

### Local Setup
```bash
git clone https://github.com/ShivankXD/ARVR-Project.git
cd ARVR-Project
npx http-server -p 8080 -o
```
Open `http://localhost:8080` in your web browser.

### Meta Quest 3 VR
Visit `https://shivankxd.github.io/ARVR-Project/` in Meta Quest Browser and click **ENTER VR MODE**.
