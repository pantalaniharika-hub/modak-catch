# 🥟 Modak Catch (मोदक कैच)
> A vibrant, browser-based festive arcade game celebrating **Ganesh Chaturthi**!

Built with **100% plain HTML5, CSS3, and JavaScript** in a single self-contained file — zero external libraries, zero build tools, zero external assets, and real-time procedural Web Audio API sound synthesis.

---

## 🎮 Play Online
👉 **[Play Modak Catch Live on GitHub Pages](https://pantalaniharika-hub.github.io/modak-catch/)**

---

## 🕹️ Controls

The basket directly and smoothly glides to follow your cursor's horizontal position in real time:

- **Desktop**: Simply move your mouse pointer left and right across the game area. **No clicks or drags needed** — the basket glides with subtle lerp smoothing toward your cursor.
- **Mobile & Tablet**: Touch anywhere on the screen — the basket follows your touch point with 1:1 responsive tracking.
- **Pause & Audio**: Tap the 🔔 / 🔕 button to toggle sound, and ⏸ / ▶ to pause.

---

## 🌟 Gameplay & Rules

- **Offerings (Good Items)**:
  - 🥟 **Modak**: Sacred pleated dumplings (+1 base score).
  - 🌺 **Hibiscus Flower**: Auspicious floral offerings (+1 base score).
  - 🪙 **Gold Coin**: Gleaming lucky coins stamped with sacred OM (+1 base score).
- **Combo Multiplier**:
  - Catch consecutive items to unlock combo tiers:
    - 3+ catches: **Combo x2!**
    - 6+ catches: **Combo x3!**
    - 10+ catches: **Combo x4!**
    - 15+ catches: **Combo x5!** (Maximum celestial bonus!)
  - High combos trigger glowing text flashes, golden particle sparkles, and ascending fanfare chords!
- **Playful Obstacle — Mushak the Mouse 🐭**:
  - Lord Ganesha's devoted mount occasionally dashes horizontally across the screen carrying his own stolen modak.
  - Intercepting Mushak costs **1 Life** and resets your combo (*"Oops! That was Mushak's modak! 🐭 -1 Life"*).
- **3 Lives System**:
  - 3 modak icons in the HUD.
  - Letting an offering drop or catching Mushak deducts 1 life and resets your combo.
  - When lives reach 0, the festival wrap summary displays your final score, best combo, high score, and rank blessings!

---

## 🎨 Visual & Audio Polish

- **Rich Festive Palette**: Deep maroon and crimson background gradient, warm saffron and gold accents.
- **Low-Contrast Backdrop**: Subtle pandal silhouettes, faint rangoli watermark, and drifting sacred diya motes that keep the focus on gameplay.
- **Item Aesthetics**: Soft glowing drop-shadows, sinusoidal bobbing, and gentle rotation as items descend.
- **Squash & Stretch**: The golden puja thali squashes and bounces dynamically when catching offerings.
- **Web Audio API**: Real-time synthesized temple chimes, plucks, metallic coin rings, and fanfare chords.

---

## 🛠️ Local Development

Simply open `index.html` in any browser:
```bash
# In your browser:
Double-click index.html
# Or serve with Python:
python -m http.server 8080
```

---

## 📜 License
Created with devotion for the Ganesh Chaturthi Game Design Contest. Ganpati Bappa Morya! 🙏
