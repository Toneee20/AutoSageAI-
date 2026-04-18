# AutoSageAI — Structured Intelligence. Delivered.

> AI Workflow Intelligence for South African businesses. 48-hour deployment. Real results.

![AutoSageAI](https://img.shields.io/badge/AutoSageAI-Structured%20Intelligence-4FC3F7?style=flat-square&labelColor=000008)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000?style=flat-square&logo=vercel)
![Status](https://img.shields.io/badge/Status-Live-4CAF50?style=flat-square)
![South Africa](https://img.shields.io/badge/Location-South%20Africa-FFB300?style=flat-square)

---

## 📁 File Structure

```
autosageai/
├── index.html      # Main HTML — all pages, sections, and navigation
├── style.css       # All styles, animations, and responsive rules
├── script.js       # Stars canvas, page routing, WhatsApp logic, interactions
└── README.md       # This file
```

---

## 🚀 Deploy to Vercel (Step-by-Step)

### Option A — Deploy from GitHub (Recommended)

1. **Push this repo to GitHub** (see commit message below)

2. Go to [vercel.com](https://vercel.com) → **Add New Project**

3. **Import** your GitHub repository

4. Vercel will auto-detect it as a **static site** — no framework needed

5. Leave all settings as default:
   - **Framework Preset**: Other
   - **Build Command**: *(leave empty)*
   - **Output Directory**: *(leave empty / root)*
   - **Root Directory**: `/`

6. Click **Deploy** → Your site goes live in under 60 seconds

### Option B — Vercel CLI

```bash
npm install -g vercel
cd your-project-folder
vercel
```
Follow the prompts. Done.

---

## ⚙️ Configuration

No build step. No dependencies. No package.json required.

This is a **pure static site** — Vercel serves it directly from the root.

| Setting | Value |
|---|---|
| Framework | None (Static HTML) |
| Build Command | *(empty)* |
| Output Directory | `.` (root) |
| Node.js Version | Not required |
| Environment Variables | None |

---

## 📄 Pages Included

| Page | Description |
|---|---|
| Home | Hero, stats, value proposition |
| Services | Four core service offerings |
| Process | Five-stage methodology |
| Cases | Industry case studies |
| Blog | Research articles (AI adoption SA) |
| Careers | Team application modal |
| Contact | Engagement request form |

---

## 📞 Contact & WhatsApp

WhatsApp integration is built in. To update the number:

In `script.js`, search for `066 001 8931` and replace with your number in international format:

```js
// Example — update this line:
window.open('https://wa.me/27660018931?text=...')
```

To update email: search `tonybuthel@gmail.com` in `index.html`.

---

## 🎨 Brand

| Element | Value |
|---|---|
| Primary Colour | `#4FC3F7` (Cyan) |
| Accent Colour | `#7C4DFF` (Purple) |
| Background | `#000008` (Deep Black) |
| Font — Display | Orbitron |
| Font — Body | Space Grotesk |
| Tagline | *Structured Intelligence. Delivered.* |

---

## 🔄 Custom Domain (Optional)

After deploying on Vercel:

1. Go to your project → **Settings** → **Domains**
2. Add your domain (e.g. `autosageai.co.za`)
3. Update your DNS records at your registrar as Vercel instructs
4. SSL is automatic and free

---

## 📝 Updating Content

| What to update | Where |
|---|---|
| Hero headline / tagline | `index.html` — search `hero-h1` |
| Service descriptions | `index.html` — search `srv-cards` |
| Pricing / stats | `index.html` — search `stat` |
| Blog articles | `index.html` — search `blog-cards` |
| WhatsApp number | `script.js` — search `wa.me` |
| Contact email | `index.html` — search `tonybuthel` |

---

## 🛡️ License

© 2026 AutoSageAI · Thulane Anthony Buthelezi · All rights reserved.

Built by **AutoSageAI** — *Structured Intelligence. Delivered.*

---

*autosageai.co.za · WhatsApp: +27 66 001 8931 · @tony_ke_star*
