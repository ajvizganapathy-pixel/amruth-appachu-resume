# Amruth Appachu K — Portfolio Resume

A single-page portfolio/resume website for **Amruth Appachu K**, Assistant Project Engineer at the Indian Institute of Science (IISc), Bengaluru.

🔗 **Live site:** https://ajvizganapathy-pixel.github.io/amruth-appachu-resume/

---

## Overview

A responsive, mobile-first personal portfolio built with plain HTML, CSS (Tailwind via CDN), and vanilla JavaScript. Showcases professional experience, academic qualifications, honours, and awards — no build step required.

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Full name, professional summary, profile photo |
| **Achievement Banner** | VTU Gold Medal highlight strip with animated shimmer |
| **Stats / Info** | Purple info card with contact details + 2×2 stats grid + skill pills |
| **Experiences** | Education timeline (M.Tech, B.E, PUC) + Professional (IISc, KPWD) |
| **Honours & Awards** | VTU Gold Medal · 5-Star GRIHA Rating · Kodava Samaja Gold Medal · NPTEL Course Topper |
| **Footer** | Copyright |

---

## Honours & Awards

1. 🏅 **VTU University Gold Medal** — M.Tech Civil Engineering, 86.83%, 1st University Rank (2014)
2. 🌿 **5-Star GRIHA Rating Award** — 500-room Ladies Hostel, IISc Bengaluru
3. 🎖️ **Kodava Samaja Gold Medal** — Highest academic achievement, 10th std through M.Tech
4. 🌍 **NPTEL Course Topper** — Climate Change Science, Jan–Apr 2026, 85/100, 4 Credits (IIT Madras)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 + [Tailwind CSS](https://tailwindcss.com) (CDN) |
| Icons | [Font Awesome 6](https://fontawesome.com) |
| Fonts | [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Google Fonts) |
| Interactions | Vanilla JS (IntersectionObserver) |

---

## File Structure

```
amruth-appachu-resume/
├── index.html          # Main portfolio page (single file)
├── profile.jpg         # Profile photograph
└── README.md
```

---

## Running Locally

No installation needed. Just open `index.html` in any modern browser:

```bash
# Option 1 — double-click index.html
# Option 2 — serve with Python
python3 -m http.server 8080
# then open http://localhost:8080
```

---

## Deploying to GitHub Pages

1. Push all files to the `main` branch of your repository
2. Go to **Settings → Pages**
3. Source → **Deploy from a branch** → `main` → `/ (root)`
4. Save — live at `https://ajvizganapathy-pixel.github.io/amruth-appachu-resume/` within ~60 seconds

---

## Updating Content

All content is in `index.html`. Key areas:

| What to update | Where in the file |
|---|---|
| Name / summary | Hero section `<h1>` and `<p>` |
| Contact details | Purple info card in Stats/Info section |
| Education entries | `.exp-group` Education block |
| Professional entries | `.exp-group` Professional block |
| Awards | `#awards-grid` in Honours & Awards section |
| Profile photo | Replace `profile.jpg` (keep the same filename) |

---

## License

Personal portfolio — content belongs to Amruth Appachu K.  
Code structure is open for reference and adaptation.
