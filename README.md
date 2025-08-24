# Constellation Painter — README

A single-file HTML/CSS/JS demo that draws twinkling stars and connects each star
to its two nearest neighbors to form lightweight “constellations”. No libraries,
no build step — just open the file in a modern browser.

---

## ✨ Features
- Full-screen Canvas with DPR scaling (up to 2×) for crisp rendering.
- Organic per-star twinkle (phase + speed variance).
- Nearest-neighbors (k=2) lines with a distance cap to avoid long edges.
- Glassy on-screen controls:
  - **Toggle constellations**
  - **Add 50 stars**
  - **Clear stars**
- Click anywhere to add a star at the cursor.

---

## 🧪 Quick Start
1. Save the provided snippet as **`index.html`**.
2. Open `index.html` in Chrome/Firefox/Edge/Safari.
3. That’s it — no server, bundler, or dependencies required.

> Tip: The canvas auto-fits and scales to your device pixel ratio.

---

## 🎮 Usage
- **Click** on the canvas → adds a star at the click position.
- **Toggle constellations** → show/hide connecting lines.
- **Add 50 stars** → appends 50 random stars.
- **Clear stars** → removes all stars.

---
