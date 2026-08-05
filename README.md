<div align="center">

# Kerolos A. — Logo & Brand Identity Designer

**Portfolio site with an interactive lead-generation chatbot**

[![Live Site](https://img.shields.io/badge/live-kerolos--design-2f4538?style=for-the-badge)]([ht](https://kerolosadly-co.github.io/Portfolio/) 
[![GitHub Pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-a9814f?style=for-the-badge&logo=github)](https://pages.github.com/)
[![No Backend](https://img.shields.io/badge/backend-none-6c6a5f?style=for-the-badge)]()

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![FormSubmit](https://img.shields.io/badge/FormSubmit-email%20delivery-lightgrey?style=flat-square)

</div>

---

## Overview

A single-page portfolio for a freelance logo & brand identity designer — built with plain HTML, CSS, and vanilla JavaScript, no frameworks, no build step. Hosted as a static site on GitHub Pages.

## Features

- 🖼️ Responsive one-page layout — hero, work gallery, approach, about, testimonials, contact
- 🎠 Auto-fading testimonial carousel with navigation dots
- 🎬 Scroll-reveal animations for portfolio cards (`IntersectionObserver`)
- 🔔 Chatbot widget with a synthesized bell sound (Web Audio API, no audio file)
- 💬 Branching conversation: services, wedding invitations, quote qualifier, lead registration
- 📩 Sends leads (name + WhatsApp) straight to email via FormSubmit — no server needed
- ♻️ Chat rewrites itself from scratch every time it's reopened

## How a lead flows through the site

```mermaid

flowchart LR

    A[Visitor] -->|opens chat| B[Chatbot widget]

    B -->|name + WhatsApp| C[FormSubmit.co]

    C -->|email| D[(Inbox)]
```

## Tech stack

| Layer    | Technology                                          |
|----------|------------------------------------------------------|
| Markup   | HTML5                                                 |
| Styling  | CSS3 — custom properties, Grid, Flexbox               |
| Fonts    | Fraunces, Inter, IBM Plex Mono (Google Fonts)         |
| Behavior | Vanilla JavaScript (ES6+)                             |
| Forms    | FormSubmit.co (serverless email delivery)             |
| Hosting  | GitHub Pages                                          |

## Project structure

```
kerolos-design/
├── index.html      # entire site: markup, CSS, and JS in one file
├── rose.jpg
├── greenhill.jpg
├── elegant.jpg
├── mindville.jpg
├── sutari.jpg
├── diamond.jpg
├── alterna.jpg
├── carcare.jpg
├── aulia.jpg
├── coffeesuntuy.jpg
├── happyshop.jpg
├── weddinginvitations.jpg
└── README.md
```

## Local development

```bash
git clone https://github.com/kerolosadly584-cyber/kerolos-design.git
cd kerolos-design
python3 -m http.server 8000
# open http://localhost:8000
```

## Deployment

Deployed automatically via **GitHub Pages** from the `main` branch — any push updates the live site.

---

<div align="center">

**Contact**

[📧 kerolosadly584@gmail.com](mailto:kerolosadly584@gmail.com) · [🔗 Upwork profile](https://www.upwork.com/freelancers/~0155c31d90e911681f)

© 2026 Kerolos A. All rights reserved.

</div>
