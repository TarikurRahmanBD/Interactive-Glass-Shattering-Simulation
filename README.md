# 🔨 Interactive Glass Shattering Simulation

An immersive, highly interactive web graphic application that simulates realistic glass-shattering visual and audio effects. This project features a stunning glassmorphic layout and particle physics, bringing a highly tactile visual experience right to your browser.

---

## ✨ Features

- **Dynamic Shattering Engine:** Generates randomized, realistic glass cracks, impact rings, and dust branches based on exactly where you click.
- **Physics-Based Debris:** Glass shards and tiny dust particles burst outward with velocity, gravity, and rotation upon impact.
- **Audio & Sensory Feedback:** Integrated glass smashing sound effect paired with a dynamic screen shake animation to deliver a high-impact feel.
- **Real-Time Customization:** Control crack radius, ray count, particle force, gravity, and shake intensity instantly via an embedded Tweakpane GUI panel.
- **Modern UI:** Clean, glassmorphic design optimized beautifully for both desktop and mobile web environments.

---

## 🛠️ Tech Stack

- **HTML5** & **CSS3** (Custom properties, CSS keyframes, and OKLCH color space alignment)
- **Vanilla JavaScript** (ES6+ Object-Oriented Architecture using private class structures)
- **Scalable Vector Graphics (SVG)** (Dynamic path generation and mathematical point plotting)
- **Tweakpane** (For real-time parameter configuration and UI controls)

---

## 🎨 SVG Filters & Effects Used

This project heavily utilizes advanced SVG filters to achieve the realistic look of frosted glass shards:
- `feTurbulence` & `feDisplacementMap` – For creating realistic structural stress patterns on individual glass surfaces.
- `feGaussianBlur` – To achieve the depth of field and soft bloom on lighting impacts.
- `feColorMatrix` – To fine-tune alpha levels, drop shadows, and frosted white edges.

---

## 🚀 How to Run the Project

Since this is a client-side frontend project, you don't need any complex installation.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/glass-shattering-simulation.git](https://github.com/your-username/glass-shattering-simulation.git)
