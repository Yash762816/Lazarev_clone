# Lazarev Agency — Frontend Clone 🎨

A pixel-perfect frontend clone of the award-winning **Lazarev design agency** website, built with vanilla HTML, CSS, and JavaScript. This project focuses on replicating advanced UI/UX patterns including smooth scroll animations, GSAP-powered transitions, and interactive hover effects.

🔗 **Live Demo:** https://yash762816.github.io/Lazarev_clone/

---


## ✨ Features

- **Smooth Locomotive Scroll** — Inertia-based scrolling for a premium feel
- **GSAP Animations** — Scroll-triggered entrance animations on every section
- **Interactive Navigation** — Hover dropdowns with animated sub-menu items
- **Auto-scrolling Marquee** — Infinite logo ticker (Forbes, Adweek, PMI, Webby Awards, etc.)
- **Video Showreel Section** — Play-on-click video with overlay controls
- **Case Studies Showcase** — Image + video hover effects for Accern Rhea & AfroTech projects
- **Accordion Services Section** — Expandable UI/UX & Product Design service cards
- **Digital Design Process** — Structured multi-column process breakdown
- **Custom Cursor** — Branded cursor animation
- **Fully Responsive Layout** — Adapts across screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Styling, transitions, layout (Flexbox) |
| JavaScript (Vanilla) | DOM manipulation, interactions |
| GSAP 3.12.5 | Scroll-triggered animations |
| ScrollTrigger (GSAP Plugin) | Animation triggers on scroll |
| Locomotive Scroll 3.5.4 | Smooth inertia scrolling |
| Remix Icons | Icon library |
| Google Fonts (Poppins) | Typography |

---

## 📁 Project Structure

```
Lazarev_clone/
├── index.html              # Main HTML — all sections and structure
├── style.css               # All styles — layout, animations, responsiveness
├── script.js               # JS logic — GSAP, Locomotive Scroll, interactions
└── accern-rhea-cover-big.mp4  # Local video asset for case study section
```

---

## 🗂️ Sections Breakdown

| Section | Description |
|---|---|
| **Navbar** | Animated dropdown nav with "Let's Talk" CTA button |
| **Page 1 — Hero** | Large heading with SVG morph animation + marquee strip |
| **Page 2 — Insights** | Left text + right scrollable article cards |
| **Page 3 — Showreel** | Full-width video with play button overlay |
| **Page 4 — Case Studies** | Project cards with image/video hover switch |
| **Page 5 — Services** | Accordion for UI/UX Design & Product Design |
| **Page 6 — Design Process** | Process steps: Strategy → UX → UI → Delivery |

---

## 🚀 Getting Started

No build tools or dependencies needed — just open in browser.

```bash
# Clone the repository
git clone https://github.com/Yash762816/Lazarev_clone.git

# Navigate into the folder
cd Lazarev_clone

# Open in browser
open index.html
```

Or simply drag and drop `index.html` into your browser.

---

## 🧠 Key Learnings

- Integrating **Locomotive Scroll** with **GSAP ScrollTrigger** for synchronized smooth animations
- Creating complex **CSS hover effects** with layered pseudo-elements
- Building **infinite marquee animations** using CSS `@keyframes` and duplicated DOM elements
- Using `<details>` and `<summary>` HTML tags to build **accessible accordions** without JavaScript
- Managing **video autoplay on hover** using JavaScript event listeners
- Working with **SVG path morphing** animations using GSAP

---

## 🔗 Original Reference

This is a clone of [lazarev.agency](https://lazarev.agency) — a real-world award-winning design studio website. Built for learning and portfolio purposes only.
