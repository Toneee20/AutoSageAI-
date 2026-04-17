# AutoSageAI — Full Website Repository

> **Structured Intelligence. Delivered.**

---

## Live Routes

| URL | File | Description |
|---|---|---|
| `autosageai.co.za/` | `index.html` | Main website — full multi-page SPA |
| `autosageai.co.za/services` | `services.html` | **Services Hub** — 3-card directory linking to all catalogues |
| `autosageai.co.za/automation-agents` | `automation-agents.html` | AI Agents & Automation catalogue (purple spade logo) |
| `autosageai.co.za/marketing-package` | `marketing-package.html` | Marketing packages catalogue (orange brain logo) |
| `autosageai.co.za/find-my-package` | `find-my-package.html` | 3-step package finder wizard |

---

## File Structure

```
autosageai-website/
├── index.html                  ← Main website
├── services.html               ← Services Hub page (nav entry point)
├── automation-agents.html      ← Automation & AI Agents catalogue
├── marketing-package.html      ← Marketing packages catalogue
├── find-my-package.html        ← Package finder wizard
├── cta-banners.html            ← Snippets to inject into index.html (see below)
├── vercel.json                 ← All routes configured
├── .gitignore
└── README.md
```

---

## How Visitors Navigate to Catalogue Pages

Three mechanisms drive visitors from the main site to the extension pages:

### 1. Services Hub (`/services`)
A standalone hub page with 3 large cards — one per catalogue + the wizard.
Link it from the main site nav by adding this inside the `.nls` div (around line 404 of index.html):
```html
<div class="nlink" onclick="window.location='/services'" style="color:var(--cy);border:1px solid rgba(79,195,247,.2);background:rgba(79,195,247,.04);">Services</div>
```

### 2. Inline CTA Banners
The `cta-banners.html` file contains two ready-to-paste banner blocks:

**Banner 1 (Automation)** — paste after the closing `</section>` of the services section (line 472 of index.html)

**Banner 2 (Marketing)** — paste after the closing `</section>` of the cases section (around line 501)

Both banners are dark themed, branded, and match the main site aesthetic exactly.

### 3. Floating "Services" Nav Link
Visitors already on the main site can click the "Services" nav link to reach the hub at any time.

---

## Deployment

### Vercel (Recommended)
1. Push all files to GitHub
2. Import repo at [vercel.com](https://vercel.com)
3. Deploy — all 5 routes go live instantly, zero config needed

### Local Testing
Open any `.html` file directly in a browser, or use VS Code Live Server.
For routing to work as `/services` etc., use Vercel or Netlify — not file:// paths.

---

## Contact Details to Update

Search and replace across all files:

| Field | Value | Search for |
|---|---|---|
| Email | tonybuthel@gmail.com | `tonybuthel@gmail.com` |
| WhatsApp | 066 001 8931 | `27660018931` |
| Domain | autosageai.co.za | `autosageai.co.za` |

---

## Brand

| Token | Value | Used On |
|---|---|---|
| Cyan `#4FC3F7` | Primary | Main site, hub, nav |
| Purple `#9575CD` | Automation accent | automation-agents page |
| Orange `#F7931E` | Marketing accent | marketing-package page |
| Cyan/Green | Wizard accent | find-my-package page |
| Background `#000008` | All pages | |
| Display font | Orbitron | All pages |
| Body font | Space Grotesk | All pages |

---

*"Knowledge without execution is just entertainment."*
