# 🚀 404 - Lost in Cyberspace | SADEEPA TECH

A modern, cyberpunk-inspired, interactive **HTTP 404 Error Page** built entirely in a single, lightweight HTML/CSS/JavaScript file with zero heavy build steps.

Featuring **"Byte the Tech Bot"**—an interactive SVG mascot with real-time eye tracking—and **"Byte's Cosmic Glitch Runner (Turbo v2.0)"**, a full-featured HTML5 Canvas arcade mini-game powered by the procedural Web Audio API.

---

## ✨ Features

- **🎮 Built-In Arcade Mini-Game ("Byte's Cosmic Glitch Runner Turbo v2.0")**:
  - HTML5 `<canvas>` runner engine with delta-timed physics (locked 60 FPS pacing).
  - Double jump mechanics, collision handling (AABB), and scaling difficulty levels.
  - Collectibles: Tech Stars (`+50 pts`) and Cyber Shields (`🛡️` absorbs one obstacle collision).
  - High score persistence via `localStorage`.
  - Pause/Resume controls (`P` key or UI button) and audio toggle.
  - Dedicated on-screen jump bar for responsive mobile gameplay.
- **🔊 Zero-Asset Sound Synthesizer**:
  - Uses the native Web Audio API (`AudioContext`) to generate retro jump, pickup, shield break, and crash sound effects on the fly—no external `.mp3` or `.wav` files required.
- **🤖 Interactive SVG Mascot ("Byte")**:
  - Pure SVG vector bot with glowing neon visuals and animations.
  - Interactive pupils that track mouse movement in real time.
- **🌌 Ambient Cyberspace Visuals**:
  - Background starfield animated on a canvas layer.
  - Subtle animated cyber-grid overlay.
  - Glassmorphic translucent cards with glowing neon borders.
- **🔍 Quick Search & Navigation**:
  - Blog search box directly integrated with Blogger query endpoints.
  - Hub cards linking directly to Blog, Portfolio, YouTube, GitHub, and LinkedIn.
  - Trending topic tags/chips for instant topic discovery.
- **📱 Fully Responsive**:
  - Fluid mobile-first grid, scalable SVG vectors, and touch-ready controls.

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| **Structure** | Semantic HTML5 |
| **Styling** | Modern CSS3 (Variables, CSS Grid, Flexbox, Keyframes, Glassmorphism) |
| **Fonts** | Google Fonts (*Plus Jakarta Sans*, *Space Grotesk*, *Fira Code*) |
| **Icons** | Font Awesome 6.5.1 CDN |
| **Game Engine** | Vanilla JavaScript + HTML5 Canvas API |
| **Audio** | Procedural Web Audio API (`OscillatorNode`, `GainNode`) |

---

## 🚀 Getting Started

Because the entire implementation is self-contained in a single file, setup is instantaneous.

### 1. Clone the Repository
```bash
git clone https://github.com/sadeepas/404-lost-in-cyberspace.git
cd 404-lost-in-cyberspace
```

### 2. Run Locally
Open `index.html` (or your 404 template file) directly in any modern browser:
- Double-click the HTML file, or
- Use a local dev server such as VS Code's **Live Server**, or run:
  ```bash
  # Python 3
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000`.

---

## 🕹️ Game Controls

| Action | Desktop Controls | Mobile / Touch |
|---|---|---|
| **Jump** | `Space` or `↑ Arrow` or Left-Click Canvas | Tap on Canvas / Tap Jump Button |
| **Double Jump** | Press `Space` / `↑ Arrow` again in mid-air | Double-tap Jump Button |
| **Pause / Resume** | `P` key or "Pause" button | Tap "Pause" button |
| **Sound Toggle** | Click "Sound: ON/OFF" | Tap "Sound: ON/OFF" |

---

## ⚙️ Customization & Deployment

### 1. Deploying on Blogger / Blogspot
1. Go to your **Blogger Dashboard** > **Settings** > **Errors and redirects**.
2. Under **Custom 404**, paste this HTML code directly (or host the file on GitHub Pages and use an `iframe`/redirect script).
3. Update the navigation links, brand name, and labels to match your blog.

### 2. Deploying on GitHub Pages, Netlify, or Vercel
- Rename the file to `404.html` (or `index.html` if used as a standalone demo).
- Place it in your project's root or `public/` directory. Static hosts automatically serve `404.html` upon missing routes.

### 3. Personalization
Search and replace the following values in the code:
- **Brand & Domain**:
  - `https://sadeepatech.blogspot.com/` → Your website/blog URL
  - `https://hsadeepalakshan.github.io/portfolio/` → Your portfolio link
  - `https://www.youtube.com/@sadeepatech` → Your social link
  - `contact.sadeepatech@gmail.com` → Your support email
- **Theme Colors** (Inside `:root` in `<style>`):
  ```css
  --primary: #6366f1;
  --secondary: #06b6d4;
  --cute-pink: #ec4899;
  --bg-dark: #090d16;
  ```

---

## 📂 Project Structure

```text
├── 404.html          # Standalone 404 page (HTML + CSS + Canvas Game + Synth JS)
└── README.md         # Documentation
```

---

## 👤 Author

**Sadeepa Lakshan**
- **Blog**: [Sadeepa Tech](https://sadeepatech.blogspot.com/)
- **Portfolio**: [hsadeepalakshan.github.io/portfolio](https://hsadeepalakshan.github.io/portfolio/)
- **GitHub**: [@sadeepas](https://github.com/sadeepas)
- **LinkedIn**: [sadeepa-lakshan](https://www.linkedin.com/in/sadeepa-lakshan)
- **YouTube**: [@sadeepatech](https://www.youtube.com/@sadeepatech)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to customize and use it for your personal or commercial sites!
```
