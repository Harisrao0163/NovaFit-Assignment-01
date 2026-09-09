# NovaFit — Fitness & Wellness Studio Landing Page

A fully responsive marketing landing page for **NovaFit**, a fictional boutique fitness and wellness studio, built as Assignment 1 for the DigiHust Frontend Web Development Internship.

**Live Demo:** [https://novafit-hazel.vercel.app/](https://novafit-hazel.vercel.app/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

## Overview

NovaFit was built to answer one question: could I independently design and ship a clean, production-style marketing site from a fictional client brief — no frameworks, no copied templates — using just HTML5, CSS3, and vanilla JavaScript?

The result is an eight-section, mobile-first landing page with a distinct visual identity (warm cream background, deep green panels, a single orange accent colour) that holds up cleanly across desktop, tablet, and mobile.

## Features

- 🧭 **Header & Navigation** — sticky nav with logo, primary links, and a JS-driven hamburger menu on smaller screens
- 🏋️ **Hero Section** — clear value proposition, dual call-to-action buttons, and a live-style class schedule card
- 💪 **Services Section** — "Four ways to train, one coaching philosophy" breakdown of coaching tracks
- 📖 **About Section** — studio story with animated stat counters (years coaching, certified coaches, locations)
- ⭐ **Testimonials** — horizontally scrollable member story cards
- 💳 **Pricing Section** — three membership tiers with a highlighted "most popular" plan
- 📬 **Contact Section** — working lead-capture form with client-side validation
- 🔗 **Footer** — sitemap, contact details, social links, and studio hours
- 📱 **Fully Responsive** — tested and tuned across desktop, tablet, and mobile breakpoints
- ✨ **Hover & Interaction States** — on buttons, nav links, and cards throughout

## Tech Stack

| Category | Tools |
|---|---|
| Markup | HTML5 (semantic structure) |
| Styling | CSS3 — Flexbox & Grid, custom properties, `clamp()` for fluid type/spacing |
| Interactivity | Vanilla JavaScript (mobile nav toggle, minor UI interactions) |
| Editor | VS Code |
| Version Control | Git & GitHub |
| Deployment | Vercel |
| Testing | Browser DevTools (responsive breakpoint testing) |

## Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `> 1024px` | Desktop |
| `900px – 1024px` | Small laptop / tablet landscape |
| `640px – 900px` | Tablet portrait (nav collapses to hamburger) |
| `400px – 640px` | Mobile |
| `< 400px` | Small phones |

## Project Structure

```
NovaFit-Assignment-01/
├── index.html          # Main landing page markup
├── style.css           # Styles (or embedded <style> in index.html)
├── script.js           # Mobile nav toggle + interactions (or embedded <script>)
├── assets/             # Images, icons, fonts (if applicable)
└── README.md
```

> Adjust this section to match your actual repo layout if your CSS/JS live in separate files rather than inline in `index.html`.

## Getting Started

Clone the repository and open the file directly in your browser — no build step or dependencies required.

```bash
git clone https://github.com/Harisrao0163/NovaFit-Assignment-01.git
cd NovaFit-Assignment-01
```

Then simply open `index.html` in your browser, or serve it locally:

```bash
# Using VS Code Live Server, or:
npx serve .
```

## Deployment

The project is deployed on **Vercel** and updates automatically with every push to the `main` branch.

🔗 **Live site:** [https://novafit-hazel.vercel.app/](https://novafit-hazel.vercel.app/)

## Challenges & Solutions

- **Pricing grid balance** — Kept the three-tier pricing grid visually balanced as it collapsed from three columns to one on mobile, using CSS Grid with defined breakpoints while preserving the highlighted "Coached" tier's emphasis.
- **Hero schedule card & stats reflow** — Moved from an absolutely-positioned layout to a flow-based Flexbox layout with breakpoint-specific stacking so nothing overlaps as the viewport narrows.
- **Contact form field layout** — Built the two-column form fields (name, email/phone) with CSS Grid so they collapse to a single column below the tablet breakpoint automatically, without separate mobile-only markup.

## Author

**Muhammad Haris**
DigiHust Frontend Web Development Internship — Assignment 1

## License

This project was built for educational purposes as part of the DigiHust internship program.
