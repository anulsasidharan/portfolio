# Anu L Sasidharan — Portfolio Website

Personal portfolio website for **Anu L Sasidharan**, AI Product Engineer & GenAI Architect based in Greater Toronto Area, Canada.

Live at: [anulsasidharan.github.io](https://anulsasidharan.github.io)

---

## About

This is a fully static, single-page portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. It highlights 14+ years of engineering experience spanning big data, cloud infrastructure, and modern generative AI.

---

## Sections

| Section | Description |
|---|---|
| Hero | Profile photo, animated role titles, availability badge, social links |
| Stats | Animated counters — years of experience, companies, GitHub projects, certifications |
| About | Professional summary, focus areas, open-to-hire highlights |
| Skills | 60+ tech tags across 6 categories (GenAI, Cloud, Big Data, DevOps, Databases, Languages) |
| Experience | Full career timeline — 7 companies from 2012 to present |
| Projects | 9 featured GitHub projects including VidShield AI and Unified RAG Studio |
| Certifications | 5 professional certifications |
| Contact | Email, phone, WhatsApp link, LinkedIn, GitHub, YouTube |

---

## Tech Stack

- **HTML5** — semantic markup, meta SEO tags
- **CSS3** — custom properties, glassmorphism cards, CSS Grid & Flexbox, scroll animations
- **Vanilla JavaScript** — typing animation, Intersection Observer scroll effects, animated counters, mobile nav
- **Google Fonts** — Space Grotesk (headings) + Inter (body)

---

## Project Structure

```
Portfolio_Website/
├── index.html          # Main HTML — all sections
├── styles.css          # All styles — dark theme, responsive
├── script.js           # Typing effect, scroll animations, counters
├── vercel.json         # Vercel deployment config & security headers
├── assets/
│   └── profile.png     # Profile photo
└── README.md
```

---

## Local Development

No build tools required. Just open the file in your browser:

```bash
# Option 1 — open directly
start index.html

# Option 2 — use VS Code Live Server extension
# Right-click index.html → Open with Live Server

# Option 3 — use Python's built-in server
python -m http.server 3000
# then visit http://localhost:3000
```

---

## Deploying to Vercel

### Option A — Vercel CLI

```bash
# Install CLI
npm install -g vercel

# Login
vercel login

# Deploy (from project root)
vercel

# Push to production
vercel --prod
```

### Option B — GitHub + Vercel Dashboard

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import the GitHub repository
4. No build command needed — Vercel detects it as a static site
5. Click **Deploy**

### Option C — Drag & Drop

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag and drop the project folder
3. Done — live in under a minute

> After deploying, connect a custom domain under **Settings → Domains** in the Vercel dashboard.

---

## Contact

| Channel | Details |
|---|---|
| Email | anulsasidharan@gmail.com |
| Phone | +1 (416) 453-3028 |
| WhatsApp | [wa.me/14164533028](https://wa.me/14164533028) |
| LinkedIn | [linkedin.com/in/anulsasidharan](https://www.linkedin.com/in/anulsasidharan/) |
| GitHub | [github.com/anulsasidharan](https://github.com/anulsasidharan) |
| YouTube | [youtube.com/channel/UCiOUEGXJ7fGxnBo2WWmJmOA](https://www.youtube.com/channel/UCiOUEGXJ7fGxnBo2WWmJmOA) |

---

© 2025 Anu L Sasidharan · Greater Toronto Area, Canada
