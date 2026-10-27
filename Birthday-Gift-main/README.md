# Cosmic Love — 3D Birthday Experience

A web-based 3D interactive application built with Three.js and GSAP. The application delivers a cinematic web experience featuring dynamic solar system rendering, customizable particle systems, and scroll-driven timeline animations.



>## Live Application
>URL: https://birthday-gift-sepia-mu.vercel.app/


---
## Technical Features

### 3D Graphics & Rendering Engine
* **WebGL Integration:** Interactive 3D scene built with Three.js using dynamic lighting and point light reflection.
* **NASA Texture Mapping:** High-resolution surface maps applied across 8 celestial bodies and dynamic ring geometries.
* **Atmospheric Shaders:** Custom glow shaders for solar visibility and animated planetary cloud layers.
* **Particle Mechanics:** Background star field utilizing 10,000+ individual points.

### Animation Pipeline
* **Sequenced Timeline:** 3-phase automated intro transition managed via GSAP timelines.
* **Scroll-Triggered Navigation:** Camera trajectories mapped to viewport scrolling for progressive reveal states.
* **UI Interactions:** Glassmorphic card interface, typewriter text reveals, and custom CSS loading indicators.

---

## Tech Stack

| Domain | Technology |
| :--- | :--- |
| **Rendering** | Three.js (WebGL) |
| **Animation Engine** | GSAP (GreenSock Animation Platform) |
| **Build Tool & Server** | Vite |
| **Core Logic** | JavaScript (ES6+) |
| **Styling** | HTML5 / CSS3 |
| **Auxiliary Libraries** | Howler.js, Lenis Scroll |

---

## Project Architecture

```text
birthday-gift/
├── public/
│   └── textures/
│       ├── planets/
│       │   ├── sun.jpg
│       │   ├── mercury.jpg
│       │   ├── venus.jpg
│       │   ├── earth.jpg
│       │   ├── earth-clouds.jpg
│       │   ├── mars.jpg
│       │   ├── jupiter.jpg
│       │   ├── saturn.jpg
│       │   ├── saturn-ring.png
│       │   ├── uranus.jpg
│       │   └── neptune.jpg
│       └── sky/
│           └── stars.jpg
├── src/
│   ├── main.js
│   └── main.css
├── index.html
├── package.json
├── vite.config.js
└── .gitignore
```
---
## 👤 Author

**Hithursan Navaretnarasa**

---
*Crafted with ❤️ for the modern connoisseu*#
