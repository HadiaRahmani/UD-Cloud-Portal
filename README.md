# UD Cloud - Self-Service Portal

A single-page, self-service cloud portal concept built to demonstrate how end users can browse a service catalog, provision cloud resources on demand, manage running instances, and track metered billing — all from one interface.

🔗 Live demo: https://hadiarahmani.github.io/UD-Cloud-Portal/

---

## What this is

UD Cloud simulates a real cloud provider's customer-facing portal — similar in spirit to the AWS, Azure, or GCP consoles, but scoped down to the core self-service workflow:

- Service catalog — browse IaaS, PaaS, and SaaS offerings, filterable by category
- Service detail page — compare resource grades (Bronze / Silver / Gold), configure deployment options, and manage running instances
- Guided ordering wizard — a 3-step flow (Configure → Contract → Provision) that mirrors how real cloud providers handle checkout and orchestration
- Packages — pre-bundled service tiers (Starter / Pro / Enterprise) for quick provisioning
- Billing — metered usage, chargeback model selection, and invoice history
- Light & dark themes — fully consistent across every screen

This project was built for a cloud computing course assignment to demonstrate understanding of self-service portal design, service models (IaaS/PaaS/SaaS), resource grading, and metered billing concepts.

---

## Running it locally

This is a single static HTML file — no build step, no install required.

1. Clone or download this repository
2. Open `index.html` directly in any modern browser

> Note: The app loads React, ReactDOM, and Babel from `unpkg.com` at runtime, so you'll need an active internet connection even when running it locally.

---

## Tech stack

| Layer        |            Technology |
| UI framework |            React 18 (UMD build, loaded via CDN) |
| Compiler     |            Babel Standalone (in-browser JSX transform) |
| Styling      |            Custom CSS-in-JS / inline styles, no external CSS framework |
| Hosting      |            Static HTML — works on GitHub Pages, Netlify, Vercel, or any static file host |

No backend, database, or build tooling is required — everything runs client-side in the browser.

---

## Browser & platform compatibility

UD Cloud is a modern, client-side web app and runs anywhere a current browser is available:

- Desktop browsers: Chrome, Edge, Firefox, Safari (latest two major versions recommended)
- Operating systems: Windows, macOS, Linux, ChromeOS — the portal runs entirely in the browser, so it is OS-independent
- Mobile browsers: Chrome and Safari on iOS/Android (responsive layout)
- Hosting platforms: GitHub Pages, Netlify, Vercel, or any static web server — no server-side runtime needed

Requirements: JavaScript enabled and an internet connection (for the CDN-loaded React/Babel scripts on first load).

---

## Project structure
.
├── index.html      # The entire application (markup, styles, and React app)
└── README.md       # This file

---

## Author
Hadia Rahmani — Cloud Computing coursework project
