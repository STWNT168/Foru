# Happy Girlfriend Day 💌

A cinematic, single-page love letter — moonlit sky, opening envelope, typewriter letter, photo gallery, and a final surprise.

## 🚀 Host it on GitHub Pages (free, takes ~3 minutes)

1. **Create a new repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it anything, e.g. `for-shetu` (avoid obvious names if you want it to stay private/discreet)
   - Set it to **Public** (required for free GitHub Pages) or use a **Private** repo if you have GitHub Pro
   - Click **Create repository**

2. **Upload the files**
   - Click **Add file → Upload files**
   - Drag in `index.html` (and `photo1.jpg`…`photo6.jpg` / `piano-romance.mp3` if you're adding them — see below)
   - Click **Commit changes**

3. **Turn on GitHub Pages**
   - Go to **Settings → Pages** (left sidebar)
   - Under **Build and deployment → Source**, select **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → **Save**
   - Wait 1–2 minutes, then refresh the page — you'll see a green box with your live link:
     `https://your-username.github.io/your-repo-name/`

4. **Share the link** — that's it, it's live.

## 🖼️ Adding your own photos

Drop image files into the repo root named exactly:

```
photo1.jpg
photo2.jpg
photo3.jpg
photo4.jpg
photo5.jpg
photo6.jpg
```

They'll automatically slot into the gallery frames — no code changes needed. If a file is missing, that frame just shows the placeholder.

## 🎵 Adding background music

Add an MP3 file named exactly `piano-romance.mp3` to the repo root. The music note button (top right) will then play it on tap. Use a track you have rights to use — a royalty-free piano piece works well. If the file isn't there, the button just does nothing when tapped (no errors shown).

## 📁 Final repo structure

```
your-repo/
├── index.html
├── photo1.jpg      (optional)
├── photo2.jpg      (optional)
├── photo3.jpg      (optional)
├── photo4.jpg      (optional)
├── photo5.jpg      (optional)
├── photo6.jpg      (optional)
└── piano-romance.mp3   (optional)
```

## 📱 Notes

- Works fully offline once loaded, except for the Google Fonts and the optional music/photo files.
- Fully responsive — tested down to mobile widths.
- Respects reduced-motion accessibility settings automatically.
