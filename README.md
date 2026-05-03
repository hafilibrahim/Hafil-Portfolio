# Hafil Ibrahim M A — Portfolio

Personal portfolio website for Hafil Ibrahim M A — Electrical Engineer, Firmware Developer & Public Speaker.

**Live site:** [hafil-portfolio.vercel.app](https://hafil-portfolio.vercel.app)

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Step 1 — Push to GitHub

1. Go to [github.com](https://github.com) and create a **New Repository**
2. Name it `portfolio` (or anything you like)
3. Keep it **Public**, don't add any files yet — click **Create repository**
4. On your computer, open a terminal in the folder where `index.html` lives and run:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/hafilibrahim/Hafil-Portfolio.git
git push -u origin main
```

---

### Step 2 — Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign up / log in with your GitHub account
2. Click **"Add New Project"**
3. Select your `portfolio` repository from the list
4. Vercel will auto-detect it as a static site — **no configuration needed**
5. Click **Deploy**
6. Done! Your site is live at `https://your-repo-name.vercel.app`

---

### Step 3 — Custom Domain (Optional)

1. In Vercel dashboard → your project → **Settings → Domains**
2. Add your domain (e.g. `hafilibrahim.dev`)
3. Follow Vercel's DNS instructions to point your domain

---

## 📁 File Structure

```
hafil-portfolio/
└── index.html      ← The entire portfolio (single file, zero dependencies)
└── README.md       ← This file
```

No build step. No npm install. No frameworks. Just push and it works.

---

## ✏️ How to Update

| What to change | Where in index.html |
|---|---|
| Your LinkedIn URL | Search `https://linkedin.com` and replace |
| Contact email / phone | Search `hafil.ibrahim.ma@gmail.com` |
| Add a new project | Find `<!-- PROJECTS -->` section |
| Add a certification | Find `<!-- CERTIFICATIONS -->` section |
| Change colors | Edit CSS variables at the top inside `:root {}` |

After editing, just run:
```bash
git add .
git commit -m "Update portfolio"
git push
```
Vercel auto-deploys on every push — your live site updates in ~30 seconds.

---

## 🛠 Tech Stack

- Pure HTML + CSS + Vanilla JS
- Fonts: Barlow Condensed + DM Sans (Google Fonts)
- Animated wave canvas (no library)
- Zero dependencies — loads instantly
