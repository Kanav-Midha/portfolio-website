[README.md](https://github.com/user-attachments/files/29330222/README.md)
# Kanav Midha — Portfolio Website

> Personal engineering portfolio. Built to give recruiters, collaborators, and curious strangers a fast, honest look at who I am and what I'm building.

**Live site:** [kanavmidha.vercel.app](https://kanavmidha.vercel.app)

---

## About

This is my personal portfolio site: a single-page, self-contained showcase of my background, technical stack, ongoing projects, and academic journey across the BITS Pilani–RMIT Melbourne dual-degree programme.

I built it to be lightweight, fast, and entirely dependency-free on the frontend — no frameworks, no build step, just hand-written HTML and CSS that I designed and iterated on myself.

## Tech Stack

- **HTML5** — semantic, single-file structure
- **CSS3** — custom properties (CSS variables), grid layouts, scroll-triggered animations via `IntersectionObserver`
- **Vanilla JavaScript** — no frameworks, no libraries
- **Fonts:** [Fraunces](https://fonts.google.com/specimen/Fraunces) (serif), [Manrope](https://fonts.google.com/specimen/Manrope) (sans), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (monospace)
- **Hosting:** [Vercel](https://vercel.com), continuously deployed from this repository

## Features

- Fully responsive, single-page layout with smooth-scroll navigation
- Scroll-based reveal animations (no animation library, pure `IntersectionObserver`)
- Sections covering About, Technical Stack, Current Focus, Achievements, Projects, Education, and Contact
- Zero build tooling — clone it, open `index.html`, and it just works

## Running Locally

No installation, no dependencies, no build step.

```bash
git clone https://github.com/Kanav-Midha/portfolio-website.git
cd portfolio-website
open index.html
```

That's it. Any modern browser will render it correctly.

## Project Structure

```
portfolio-website/
├── index.html          # Entire site: markup, styles, and script
├── kanav-photo.jpg      # Hero section portrait
├── kanav-suit.jpg       # About section portrait
├── BITS Pilani Photo.jpeg
├── RMIT Photo.jpg
├── BBPS Photo.jpeg
├── *.jpg / *.jpeg       # Institutional logos used in the Education section
└── README.md
```

## Deployment

This site auto-deploys to Vercel on every push to `main`. No manual build step is required since it's static HTML — Vercel simply serves the files as-is.

## About Me

I'm a Computer Science undergraduate pursuing a dual degree between **BITS Pilani** and **RMIT University, Melbourne**. I'm currently deepening my foundations in Data Structures & Algorithms and exploring the Machine Learning ecosystem. You can read the full story on the [live site](https://kanavmidha.vercel.app).

## Connect

- **Email:** [kanavmidha9@gmail.com](mailto:kanavmidha9@gmail.com)
- **LinkedIn:** [linkedin.com/in/kanav-midha-696779296](https://www.linkedin.com/in/kanav-midha-696779296)
- **GitHub:** [@Kanav-Midha](https://github.com/Kanav-Midha)

---

<sub>Built and designed by Kanav Midha.</sub>
