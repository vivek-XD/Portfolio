# VIKUU<p align="center">
  <img src="https://img.shields.io/badge/status-live-brightgreen?style=flat-square" alt="status"/>
  <img src="https://img.shields.io/badge/made%20with-HTML%20%7C%20CSS%20%7C%20JS-blue?style=flat-square" alt="tech"/>
  <img src="https://img.shields.io/badge/deployed%20on-Vercel-black?style=flat-square&logo=vercel" alt="vercel"/>
</p> — Vivek Chauhan | Portfolio

A personal portfolio website for **Vivek Chauhan (Vikuu)**, a data analyst and final-year B.Tech (AI & ML) student. Built as a single, self-contained HTML file with a bento-grid layout, animated sections, and detail views for projects, experience, certifications, and education.

🔗 **Live site:** https://portfolio-c1kv.vercel.app

---

## ✨ Features
- Animated hero with a scrolling name marquee and portrait
- "Float on scroll" About section
- Bento-tile navigation (Projects, Experience, Certifications, Education, Tools)
- Filterable project categories (Data Analysis, Machine Learning, Gen AI, Vibe Coded)
- Certifications gallery with live thumbnails and verify links
- Experience timeline with certificate links
- Fully responsive, no build step, no dependencies

## 🛠️ Tech Stack
- **HTML5** — single-file structure
- **CSS3** — custom properties, grid, OKLCH colors, keyframe animations
- **Vanilla JavaScript** — IntersectionObserver reveals, detail overlays, dynamic cards
- **Google Fonts** — Space Grotesk, Inter, Comic Neue, Playfair Display

## 🚀 Deploy
This is a static site. To host it:
1. Make sure the main file is named `index.html`.
2. Push this repo to GitHub.
3. Import the repo into [Vercel](https://vercel.com) and hit **Deploy** (framework: Other).

Any static host works too (Netlify, GitHub Pages, Cloudflare Pages).

## ✏️ Editing
Everything lives in `index.html`.
- **Projects:** edit the `categories` object in the `<script>` block.
- **Certifications:** edit the `certs` array (each item takes a Google Drive file `id`).
- **Experience:** edit the `expHTML` template.
- **Text / colors:** update the markup or the CSS variables in `:root`.

After editing, re-upload `index.html` to GitHub and Vercel auto-redeploys.

## 📬 Contact
- **Email:** vickychauhan8814@gmail.com
- **LinkedIn:** [vivek-chauhan](https://www.linkedin.com/in/vivek-chauhan-31b524369/)
- **GitHub:** [vivek-XD](https://github.com/vivek-XD)

---
© 2026 Vivek Chauhan (Vikuu).
