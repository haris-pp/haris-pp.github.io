# Haris P P — Portfolio

A simple, fast two-page portfolio for `haris-pp.github.io`:

- **Home** (`index.html`) — intro, skills, experience, education, contact, resume download
- **Projects** (`projects.html`) — 6-project showcase on a single page

## 🚀 Deploy to GitHub Pages

1. Create (or open) the repo named **`haris-pp.github.io`** on your GitHub account.
2. Copy **all** files from this folder into the repo root:
   ```
   index.html
   projects.html
   styles.css
   Haris-Resume.pdf
   assets/   (the 6 project images)
   ```
3. Commit & push:
   ```bash
   git add .
   git commit -m "Add portfolio"
   git push origin main
   ```
4. In the repo: **Settings → Pages → Build and deployment**
   - Source: *Deploy from a branch*
   - Branch: `main` / `root`
5. Wait ~1 minute. Your site is live at **https://haris-pp.github.io/**
   Projects page: **https://haris-pp.github.io/projects.html**

## 🖼 Add real screenshots (recommended)

The project cards currently use placeholder graphics in `assets/`.
Replace them with real screenshots for a stronger impression:

1. Drop your screenshot (PNG/JPG) into `assets/`, e.g. `assets/streaming.png`
2. In `projects.html`, find the matching `<img src="assets/project-streaming.svg" ...>`
3. Change the `src` to your file: `<img src="assets/streaming.png" ...>`

Recommended image size: **~640×440px** (landscape).

## ✏️ Editing content

- All text is plain HTML — edit `index.html` / `projects.html` directly.
- Colors and layout live in `styles.css` (top `:root` block holds the theme colors).
- The resume link points to `Haris-Resume.pdf` — replace that file anytime to update it.

## Tech

Pure HTML + CSS. No build step, no dependencies. Loads instantly.
