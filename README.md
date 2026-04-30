# Amruth Appachu K — Portfolio Resume

A single-page portfolio/resume website for **Amruth Appachu K**, Assistant Project Engineer at the Indian Institute of Science (IISc), Bengaluru.

**Live site:** [https://ajvizganapathy-pixel.github.io/amruth-appachu-resume/](https://ajvizganapathy-pixel.github.io/amruth-appachu-resume/)

---

## Overview

This is a responsive, mobile-first personal portfolio built with plain HTML, CSS (Tailwind via CDN), and vanilla JavaScript. It showcases professional experience, academic qualifications, honours, and contact details — no build step required.

## Features

- Hero section with profile photo and animated gold-medal badge
- VTU University Gold Medalist achievement banner
- Stats overview (12+ years XP, 50+ projects)
- Education and professional experience timeline
- Honours & Awards section (VTU Gold Medal, 5-Star GRIHA Rating, Kodava Samaja Gold Medal)
- Scroll-triggered reveal animations
- Fully responsive (mobile → desktop)
- Zero dependencies — no npm, no build tools

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 + [Tailwind CSS](https://tailwindcss.com/) (CDN) |
| Icons | [Font Awesome 6](https://fontawesome.com/) |
| Fonts | [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (Google Fonts) |
| Interactions | Vanilla JS (IntersectionObserver) |

## File Structure

```
amruth-appachu-resume/
├── index.html                  # Main portfolio page (single file)
├── profile.jpg                 # Profile photograph
├── Amruth_Appachu_Resume.pdf   # Downloadable résumé
└── README.md
```

## Running Locally

No installation needed. Just open `index.html` in any modern browser:

```bash
# Option 1 — direct open
open index.html          # macOS
start index.html         # Windows

# Option 2 — local server (avoids any CORS quirks)
npx serve .
# or
python -m http.server 8080
```

## Deploying to GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Set source to `main` branch, `/ (root)`.
4. The site will be live at `https://<username>.github.io/amruth-appachu-resume/`.

## Contact

**Amruth Appachu K**
Assistant Project Engineer, IISc Bengaluru
📧 amruthak@iisc.ac.in
📞 (+91) 87623 48577
