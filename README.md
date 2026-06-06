# 🏃 Endless Runner

A fast-paced endless runner browser game built with **Unity** and exported to **WebGL**. Run as far as you can, dodge obstacles, and beat your high score!

---

## 🎮 Gameplay

- Your character runs automatically — keep moving forward!
- Jump or dodge to avoid obstacles in your path
- The longer you survive, the higher your score
- The game speeds up over time — how far can you go?

---

## 🚀 Play in Browser

Since this is a Unity WebGL build, you need a local HTTP server to run it (browsers block direct file access due to CORS).

### Option 1 — Python (recommended)

```bash
git clone https://github.com/kalyan405111/Endless-Runner.git
cd Endless-Runner/hunter/hunter
python3 -m http.server 8080
```

Then open your browser and go to: [http://localhost:8080](http://localhost:8080)

### Option 2 — Node.js

```bash
npx serve .
```

---

## 🌐 Host on GitHub Pages (Free)

Share the game publicly using GitHub Pages:

1. Go to your repo → **Settings** → **Pages**
2. Set the source branch to `main`
3. Set the folder to `/hunter/hunter`
4. Click **Save**

Your game will be live at:
`https://kalyan405111.github.io/Endless-Runner/`

---

## 🛠️ Tech Stack

| Property | Details |
|---|---|
| Engine | Unity (WebGL Export) |
| Product Name | Runner |
| Company | SoloDev |
| Runtime | WebAssembly (WASM) |
| Graphics API | WebGL 2.0 / WebGL 1.0 |
| Canvas Size | 960 × 600 px |
| Memory | 256 MB |

---

## 📁 Project Structure

```
Endless-Runner/
└── hunter/hunter/
    ├── index.html                        # Game entry point
    ├── Build/
    │   ├── UnityLoader.js                # Unity WebGL loader
    │   ├── hunter.json                   # Game configuration
    │   ├── hunter.data.unityweb          # Compressed game assets
    │   ├── hunter.wasm.code.unityweb     # Game logic (WebAssembly)
    │   └── hunter.wasm.framework.unityweb  # Unity runtime
    └── TemplateData/
        ├── style.css                     # Loading screen styles
        ├── UnityProgress.js              # Loading bar script
        └── *.png / favicon.ico           # UI assets
```

---

## 📋 Requirements

- A modern browser with **WebGL support** (Chrome, Firefox, Edge, Safari)
- No installation needed — runs entirely in the browser

---

## 👤 Author

**Kalyan** — [GitHub Profile](https://github.com/kalyan405111)

---

## 📄 License

This project is open source. Feel free to fork and build upon it!
