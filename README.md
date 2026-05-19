# Ashley Wenwa — Portfolio Website

> Cloud Security Engineer & Analyst · Nairobi, Kenya

Live portfolio site built for GitHub Pages deployment.

---

## 🚀 Deploy to GitHub Pages (free hosting)

### Step 1 — Create the repository
1. Go to [github.com/new](https://github.com/new)
2. Name the repo exactly: `ashley-wenwa.github.io`
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload your files
**Option A — GitHub web UI (easiest):**
1. Open your new repo
2. Click **Add file → Upload files**
3. Drag in `index.html` (and `ashley-wenwa-cv.pdf` when ready)
4. Commit directly to `main`

**Option B — Git CLI:**
```bash
git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/WENWA444/ashley-wenwa.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch → main → / (root)**
3. Click **Save**
4. Your site goes live at: `https://ashley-wenwa.github.io` (takes ~1 minute)

---

## 📄 Adding your CV

Place your CV PDF in this folder named exactly:
```
ashley-wenwa-cv.pdf
```
The Download CV buttons are already wired to this filename.

---

## ✏️ Personalisation checklist

- [ ] Replace `ashley@example.com` in `index.html` (line ~430) with your real email
- [ ] Add `ashley-wenwa-cv.pdf` to the folder before deploying
- [ ] Update project GitHub links once repos are public
- [ ] Add your actual profile photo (optional — add an `<img>` to the hero section)

---

## 🗂 File structure
```
ashley-portfolio/
├── index.html           ← Main site (single file)
├── ashley-wenwa-cv.pdf  ← Your CV (add this yourself)
└── README.md            ← This file
```

---

Built with HTML, CSS & vanilla JS · No frameworks · No build step required
