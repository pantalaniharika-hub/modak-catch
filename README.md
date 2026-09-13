# 🥟 Modak Catch (मोदक कैच)
> A vibrant, browser-based festive arcade game celebrating **Ganesh Chaturthi**!

Play as **Mushak the Mouse**, Lord Ganesha's loyal devotee and mount, as you catch sacred festive offerings in a golden puja thali under the watchful blessings of **Lord Ganesha**!

Built with **100% plain HTML5, CSS3, and JavaScript** in a single self-contained file — zero external libraries, zero build tools, zero external assets, and real-time procedural Web Audio API sound synthesis.

---

## 🎮 Play Online
👉 **[Play Modak Catch Live on GitHub Pages](https://pantalaniharika-hub.github.io/modak-catch/)**

---

## 🕹️ Controls

Mushak glides smoothly to follow your cursor's horizontal position in real time:

- **Desktop**: Simply move your mouse pointer left and right across the game area. **No clicks or drags required** — Mushak glides with subtle lerp smoothing directly toward your cursor.
- **Mobile & Tablet**: Touch anywhere on the screen — Mushak follows your touch point with 1:1 responsive tracking.
- **Pause & Audio**: Tap the 🔔 / 🔕 button to toggle sound, and ⏸ / ▶ to pause.

---

## 🌟 Festive Items & Rules

- **Sacred Offerings for Lord Ganesha**:
  - 🥟 **Modak**: Sacred sweet dumplings (+1 base score).
  - 🟡 **Motichoor Laddoo**: Golden-saffron boondi sweet sphere (+1 base score).
  - 🥥 **Sacred Coconut (Shriphal)**: Auspicious coconut crowned with green mango leaves (+1 base score).
  - 🌺 **Red Hibiscus Flower**: Sacred floral blossom beloved by Ganesha (+1 base score).
- **Hazard to Dodge**:
  - 🌶️ **Fiery Red Chilli**: Hot spicy chilli falling from above! Catching it burns Mushak's tongue, costs **1 Life**, and resets your combo streak (*"Oops! Modaks only, no spicy chillies! 🌶️ -1 Life"*).
- **Combo Multipliers**:
  - Catch consecutive sweet offerings to build your combo:
    - 3+ catches: **Combo x2!**
    - 6+ catches: **Combo x3!**
    - 10+ catches: **Combo x4!**
    - 15+ catches: **Combo x5!** (Maximum celestial bonus!)
  - High combos trigger glowing text banners, golden particle sparkles, and ascending fanfare chords!
- **3 Lives System**:
  - Represented by 3 golden modak icons in the HUD.
  - Letting a good offering drop or catching a fiery chilli deducts 1 life.
  - At 0 lives, the festival wrap summary displays your score, best combo, and rank blessings!

---

## 🎨 Visual Design

- **Lord Ganesha Shrines**: In place of wall diyas, illuminated shrines featuring Lord Ganesha on lotus pedestals adorn the temple pillars, radiating divine light.
- **Mushak the Mouse Player**: An adorable, devoted mouse wearing a tiny festive saffron pagri holding the golden puja thali with squash-and-stretch bounce.
- **Low-Contrast Pandal Backdrop**: Deep maroon gradient, faint arch silhouette, and floor rangoli watermark that keeps gameplay readable and elegant.

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
