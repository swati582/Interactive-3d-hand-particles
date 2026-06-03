# Interactive-3d-hand-particles
An interactive 3D particle system built with Three.js and tracked in real-time using MediaPipe computer vision.

## 🚀 Live Interactive Demo
**[👉 CLICK HERE TO RUN DISCOVERY LAYER](https://swati582.github.io/Interactive-3d-hand-particles/)**

---

## 🎨 Key Features
* **Real-time Computer Vision:** Tracks dual-hand spatial movements via user webcams seamlessly in-browser without requiring external hardware dependencies.
* **Dynamic Scale Modulation:** Spreading hands apart or bringing them together translates to coordinate metrics that scale 35,000 active particles smoothly.
* **Math-Driven Templates:** Toggle between procedural geometric shapes including Saturn's planetary rings, algorithmic flowers, and quantum fireworks.
* **Immersive Fullscreen Environment:** Clicking anywhere on the particle canvas triggers native fullscreen mode, optimizing viewport pixel arrays automatically.

---

## 🛠️ Tech Stack & Architecture
* **Core Engine:** Vanilla JavaScript / HTML5 / CSS3
* **3D Graphics Layer:** Three.js (WebGL rendering pipeline with Additive Blending and custom canvas gradient textures)
* **AI/Machine Learning Tracking:** Google MediaPipe Hands Framework (using spatial landmark array monitoring)

---

## ⚙️ Local Setup / How to Run
1. Clone or download this repository to your local device.
2. Open the directory and boot up a local development server (e.g., using VS Code's *Live Server* extension or Python's `http.server`).
3. Open `http://localhost:3000` (or your corresponding local port address) in your browser.
4. Allow webcam permissions, step back, and raise both hands into view!
