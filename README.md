# 🎬 LOLhub — Your Daily Dose of Funny

A one-stop shop for funny videos that auto-updates with fresh content from across the web.

![LOLhub Preview](https://img.shields.io/badge/Status-Live-brightgreen)

## 🎯 What It Does

- **Live Reddit integration** — fetches from 16 subreddits (fails, animals, cats, pranks, kids, wholesome, wtf, classic)
- **Giphy trending** — auto-playing MP4 GIFs that work without embed restrictions
- **YouTube curated** — hand-picked classic funny videos
- **Category filters** — All, Fails 💥, Animals 🐕, Cats 🐱, Pranks 😏, Kids 👶, Wholesome 💛, WTF 🤯, Classic 📼
- **3 sort modes** — 🔥 Hot (Reddit-style decay), ✨ Fresh (newest), 👑 Top (highest score)
- **Live search** — debounced search across titles, categories, and sources
- **Video modal** — Giphy/Reddit play inline as HTML5 video, YouTube opens in embed
- **Auto-refresh** every 5 minutes with toast notifications
- **Dark mode** with animated gradient blobs and smooth card animations
- **Responsive** — works on mobile (3→2→1 column grid)

## 🚀 Run It

### Option 1: Direct
Just open `index.html` in a browser. Some features (YouTube embeds) work better from HTTP.

### Option 2: Local Server (recommended)
```bash
cd funny-videos
python3 -m http.server 8888
```
Then open **http://localhost:8888**

### Option 3: GitHub Pages
It's live! Just enable GitHub Pages in repo Settings → Pages → Source: `main` / `/ (root)`.

## 🛠 Tech

- Vanilla HTML/CSS/JS — no frameworks, no build step
- Reddit Public JSON API
- Giphy Public API (beta key)
- YouTube embeds (nocookie domain)

## 📦 Sources

| Source | Content | Plays Inline? |
|--------|---------|--------------|
| Reddit | Hot video posts from 16 subreddits | ✅ (HTML5 video) |
| Giphy | Trending GIFs/MP4s | ✅ (MP4 video) |
| YouTube | Curated funny videos | ✅ (iframe embed) |

## 📝 License

MIT — do whatever you want with it. Go laugh.