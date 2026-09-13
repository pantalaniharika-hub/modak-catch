# 🥟 Modak Catch (मोदक कैच)
> A vibrant, browser-based festive arcade game celebrating **Ganesh Chaturthi**!

Built with **100% plain HTML5, CSS3, and JavaScript** in a single file — zero external libraries, zero build tools, zero external assets, and pure procedural Web Audio API sound synthesis.

---

## 🎮 Play Online
👉 **[Play Modak Catch Live on GitHub Pages](https://pantalaniharika-hub.github.io/modak-catch/)**

---

## 🌟 Gameplay & Features

- **Lord Ganesha's Puja Thali**: The player guides an ornate golden offering thali held by a joyful, adorable Ganesha avatar at the bottom of the screen.
- **Festive Offerings**:
  - 🥟 **Modak**: Sacred sweet dumplings (+1 base score).
  - 🌺 **Hibiscus Flower**: Auspicious red floral offerings (+1 base score).
  - 🪙 **Gold Coin**: Gleaming coins stamped with sacred motifs (+1 base score).
- **Combo Multiplier System**:
  - Catch consecutive items without missing to build up multipliers:
    - 3+ in a row: **2x**
    - 6+ in a row: **3x**
    - 10+ in a row: **4x**
    - 15+ in a row: **5x**
  - High combos trigger celestial chime fanfares and golden particle explosions!
- **Playful Obstacle — Mushak the Mouse 🐭**:
  - Lord Ganesha's friendly mount occasionally dashes horizontally across the screen carrying his own modak.
  - If the player accidentally intercepts Mushak, a life is lost (*"Oops! That was Mushak's modak! 🐭 -1 Life"*), played respectfully and lightly.
- **3 Lives System**:
  - Represented by 3 golden modak icons in the HUD.
  - Dropping an offering or bumping into Mushak loses 1 life and resets the combo streak.
  - Game ends when lives reach 0, leading to a celebratory festival wrap screen with rank titles and high score tracking!
- **Dynamic Difficulty**:
  - Fall speed and spawn frequency smoothly increase as your score rises.

---

## 🕹️ Controls

| Platform | Controls |
| :--- | :--- |
| **Desktop Keyboard** | `Left / Right Arrow` or `A / D` to move • `Esc / P` to Pause |
| **Desktop Mouse** | Move or drag mouse across the game area |
| **Mobile & Tablet** | 1:1 Smooth Touch Drag anywhere on the screen |
| **Audio Controls** | Tap the 🔔 / 🔕 button on the top right to toggle sound |

---

## 🎨 Visual & Audio Polish

- **Devotional Color Palette**: Saffron orange, marigold yellow, royal crimson, and temple gold accents.
- **Pandal Backdrop**: Hanging marigold floral torans, temple pillars, floor rangoli, and flickering oil diyas with animated warm flame glows.
- **Web Audio API Sound Engine**: Real-time synthesized temple bells, gentle harp plucks, sparkling coin chimes, boings, and celebratory fanfares without needing any external audio files.
- **Retina / High-DPI Support**: Automatically handles `window.devicePixelRatio` for sharp rendering on 4K monitors and high-resolution mobile devices.

---

## 🛠️ Local Development & Running

Simply open `index.html` in any modern web browser:
```bash
# In your browser:
Double-click index.html
# Or serve locally:
npx serve .
# or
python -m http.server 8080
```

---

## 📜 License
Created with devotion for the Ganesh Chaturthi Game Design Contest. Free to play and share! Ganpati Bappa Morya! 🙏
