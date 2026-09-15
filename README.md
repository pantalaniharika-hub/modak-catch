# 🥟 Modak Catch: Mushak's Festive Basket

> A vibrant, browser-based arcade game celebrating **Ganesh Chaturthi** where you steer a festive puja basket to catch falling sacred offerings for Lord Ganesha!

---

## 🚀 How to Run

- **Option 1 (Local)**: Open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari) — no installation, build step, or web server required!
  - You can also serve it locally using Python:
    ```bash
    python -m http.server 8080
    ```
    Then visit `http://localhost:8080` in your browser.
- **Option 2 (Live Online)**: Play instantly on GitHub Pages:
  👉 **[https://pantalaniharika-hub.github.io/modak-catch/](https://pantalaniharika-hub.github.io/modak-catch/)**

---

## 🕹️ Controls

- **Desktop (Mouse / Trackpad)**: Move your mouse or cursor horizontally across the game screen. The festive basket glides smoothly with responsive lerp tracking toward your cursor position (no clicking needed).
- **Keyboard**: Use **◄ Left Arrow** / **A** and **► Right Arrow** / **D** keys to steer horizontally.
- **Mobile & Tablet (Touch)**: Slide or drag your finger anywhere across the screen to glide the basket.
- **Game Controls**:
  - 🔔 / 🔕 **Sound Button**: Toggle temple ambient audio and sound effects on/off (available on Start Screen and HUD).
  - ⏸ / ▶ **Pause Button**: Pause and resume active gameplay.

---

## ✨ Main Features

1. **Sacred Offerings & Scoring**:
   - 🥟 **Modak**: Sacred sweet dumplings (+1 point).
   - 🟡 **Motichoor Laddu**: Traditional saffron boondi sweet (+1 point).
   - 🥥 **Sacred Coconut (Shriphal)**: Fresh cracked coconut with mango leaves (+1 point).
   - 🍈 **Custard Apple (Sitaphal)**: Auspicious whole green fruit (+1 point).
   - 🌺 **Red Hibiscus Flower**: Beloved sacred floral offering (+1 point).
2. **Dynamic Combo Streak (up to 5x)**:
   - Catch consecutive offerings to build combo multipliers (2x at 3 catches, 3x at 6 catches, 4x at 10 catches, and max 5x at 15 catches) with festive sound fanfares and particle bursts.
3. **Power-Ups**:
   - ⭐ **Star Power-Up (Golden Boost)**: Rare falling smiling star offering that awards **+10 bonus points** immediately and activates a **2x score multiplier for 5 seconds** with a glowing HUD countdown badge.
   - 🛡️ **Shield Power-Up (3D Silver Shield)**: Rare falling protective shield that grants a protective forcefield around the basket. Absorbs falling bomb blasts without losing lives or combo streaks.
4. **Hazards & 3 Lives System**:
   - 💣 **Explosive Bomb**: Dangerous falling hazard. Catching a bomb without a shield or letting a good offering fall deducts 1 life (represented by 3 golden modak icons in the HUD).
5. **Saved High Score & Celebrations**:
   - High scores are saved in `localStorage` across sessions.
   - Best score displayed on Start and Game Over screens.
   - Live in-game celebration with confetti particle explosion, golden screen flash, and fanfare when beating your personal best.
6. **Milestone Toasts**:
   - Non-blocking celebratory toast banners appear at score milestones (every 25 points) with harmonic chime bells.
7. **Procedural Indian Temple Audio**:
   - Zero-dependency meditative ambient drone (Sa-Pa, C3 & G3) procedurally generated using the pure Web Audio API, accompanied by custom sound effects.
8. **Devotee Profiles & Avatars**:
   - Switch between **Bal Ganesha** and **Mushak the Mouse** avatars with custom name personalization.

---

## 🛠️ Tools & Frameworks Used

- **HTML5**: Semantic canvas layout and responsive viewport overlay structure.
- **CSS3**: Modern Flexbox/Grid styling, CSS custom properties (variables), keyframe animations, and glowing gradients with no external CSS dependencies.
- **JavaScript (ES6+)**: Pure vanilla JavaScript game engine with 60 FPS requestAnimationFrame loop, lerp movement physics, bounding-box collision detection, and particle systems.
- **HTML5 Canvas 2D API**: High-performance procedural and sprite-based rendering with custom lighting and drop shadows.
- **Web Audio API**: Real-time procedural audio synthesis (oscillators, biquad filters, gain nodes, and LFO modulation) with zero external sound files.
- **Local Storage API**: Instant offline persistence for devotee profiles, sound preferences, and high scores.
