# 🔨 Interactive Glass Shattering Simulation

An immersive, highly interactive web graphic application that simulates realistic glass-shattering visual and audio effects built entirely using JavaScript, SVG, and CSS. 

## 🚀 Live Demo
Check out the live project here: **[Live Demo](https://yourtarikur.netlify.app/)**

---

## ✨ Features

- **Dynamic Shattering Engine:** Generates randomized, realistic glass cracks, impact rings, and dust branches based on exactly where you click.
- **Physics-Based Debris:** Glass shards and tiny dust particles burst outward with velocity, gravity, and rotation upon impact.
- **Audio & Sensory Feedback:** Integrated glass smashing sound effect paired with a dynamic screen shake animation to deliver a high-impact feel.
- **Real-Time Customization (Tweakpane):** Control crack radius, ray count, particle force, gravity, and shake intensity instantly via an interactive GUI panel.
- **Modern UI:** Clean, glassmorphic layout styled beautifully for desktop and mobile browsers.

---

## 🛠️ Tech Stack

- **HTML5** & **CSS3** (Custom Properties, OKLCH Color Space, CSS Keyframes)
- **Scalable Vector Graphics (SVG)** (Dynamic path generation, complex SVG filter effects like `feTurbulence` and `feDisplacementMap`)
- **Vanilla JavaScript (ES6+)** (Object-Oriented Architecture using private class methods, Custom Web Audio API)
- **Tweakpane** (For real-time parameter configuration)

---

## 🎨 SVG Filters & Effects Used

This project heavily utilizes advanced SVG filters to achieve the realistic look of frosted glass:
- `feTurbulence` & `feDisplacementMap` – For creating realistic structural stress patterns on individual glass shards.
- `feGaussianBlur` – To achieve the depth of field and soft bloom on lighting impacts.
- `feColorMatrix` – To fine-tune alpha levels, shadows, and frosted white edges.

---

## ⚙️ Customization Settings

Through the embedded **Settings Panel**, you can tweak the following engine parameters:
- **Crack:** Min/Max Rays, Min/Max Radius, Branching Odds.
- **Rings & Debris:** Max Rings, Dust particle count, Force, and Gravity.
- **Impact FX:** Screen Shake intensity and Flash duration.

---

## 🧑‍💻 Designed & Developed By

**Tarikur Rahman**
- 🌐 Portfolio: [yourtarikur.netlify.app](https://yourtarikur.netlify.app/)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
