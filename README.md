# game-menu-style-portfolio
# 🎮 M. ZURAIN — SYSTEM INITIALIZED

A retro-cyberpunk, gaming-inspired main menu concept built for an interactive developer portfolio. This project utilizes CSS `:target` pseudo-classes to handle navigation and panel rendering dynamically without relying on heavy JavaScript frameworks, mimicking a classic CRT arcade or RPG main menu interface.

## ⚡ Features

* **Retro CRT Scanlines & Vignette:** A pure CSS overlay simulation that provides an authentic arcade monitor feel.
* **Zero-JS Navigation:** Uses HTML anchors and CSS `:target` selectors to transition between panels flawlessly.
* **Responsive UI:** Stacks layout dynamically on mobile screens while scaling text and dropping sub-labels cleanly.
* **Media Locking:** Background elements are fully isolated via `pointer-events: none` to prevent unintended user drag/save highlights.

---

## 🛠️ Tech Stack & Skill Tree

```
  [Front-End] ── HTML5 ── CSS3 (Custom Grid/Flexbox)
  [Typography] ─ Monospace System Fonts
  [Styling] ─── Radial/Linear Gradients & Post-Processing FX
```

---

## 💾 Menu Architecture

* **NEW GAME (`#about`)** — Player bio and entry-level brief.
* **LOAD DATA (`#projects`)** — Directory of deployed operations/projects.
* **SKILL TREE (`#skills`)** — Core language proficiencies and technical frameworks.
* **MULTIPLAYER (`#contact`)** — Server connection endpoints (Socials & Communication).

---

## 🚀 Quick Start & Deployment

### 1. Clone the Terminal
```bash
git clone https://github.com/zurainrehmani95/your-repo-name.git
```

### 2. Launch the System
Simply open `index.html` in any modern web browser, or launch it using an extension like **Live Server** in VS Code.

### 3. File Directory
```text
├── index.html   # Main system structure & content markup
├── style.css    # Core styling, CRT effects, and layout configuration
└── download.gif # Animated background environment
```

---

## ⚙️ Customization Guide

### Changing the Background Environment
Swap out `download.gif` with any pixel-art loop or video backdrop. The layout engine will auto-scale and apply the vignette overlay natively:
```css
#bg-gif {
    /* Locks the image canvas */
    object-fit: cover;
    image-rendering: pixelated; 
}
```

### Expanding the Menu Options
To add a new menu option, create an anchor tag inside `<nav class="main-menu">`:
```html
<a href="#inventory" class="menu-item">INVENTORY <span class="subtitle">(Tools)</span></a>
```
Then build the matching block lower down in the document wrapper:
```html
<div id="inventory" class="content-panel">
    <h2>Inventory Matrix</h2>
    <p>Items equipped go here...</p>
    <a href="#" class="back-btn">RETURN TO MENU</a>
</div>
```

---

## 📡 Multiplayer Logs

* **GitHub:** [@zurainrehmani95](https://github.com/zurainrehmani95)
* **Email:** [zurainrehmani95@gmail.com](mailto:zurainrehmani95@gmail.com)

---
*Developed by a Software Engineering student trying to push the boundaries of clean, thematic frontend layouts.*
