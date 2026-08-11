# Hasnain Ali — Developer Portfolio

A personal developer portfolio website for Hasnain Ali, a Full-Stack Web Developer, built to present his skills, background, and selected project work in a modern, single-page format.

## Live Demo

[hasnainalishaikh.github.io/hasnain-portfolio](https://hasnainalishaikh.github.io/hasnain-portfolio/)

## Overview

This repository holds a single static HTML page used as a personal portfolio site. It introduces Hasnain Ali as a Full-Stack Web Developer, presents his core technical skills, and showcases four of his web development projects with links to their live demos and/or source repositories, where those links actually exist.

## Key Features

Verified directly from the code:

- Fixed, blurred-glass navigation bar with smooth in-page scrolling to each section
- Animated gradient hero heading with a typed-text placeholder effect
- Animated skill proficiency bars for HTML, CSS, JavaScript, PHP, and MySQL
- About section with a profile photo and highlight stat cards
- Skills section organized into four categories: Full Stack Development, Frontend Development, Backend Development, and UI/UX & Performance
- A projects carousel with previous/next navigation controls, displaying four project cards with images, descriptions, tech tags, and links
- A "Professional Experience" entry describing freelance work
- Contact section with clickable email and phone links, and a contact form (`id="contactForm"`) tied to a `handleContactForm(event)` JavaScript function
- Custom animated cursor and glowing background orbs, automatically disabled on touch devices (`pointer: coarse` media query)
- Scroll-triggered reveal animations on section content
- Responsive layout with a dedicated slide-in mobile navigation menu and hamburger toggle

## Tech Stack

| Technology | Role |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | All styling, layout, responsiveness, and animations (embedded directly in `index.html`) |
| JavaScript | Scroll reveal, custom cursor, typed-text effect, projects carousel, mobile menu toggle, contact form handling |
| Font Awesome | Icon set (loaded via CDN) |
| Google Fonts | Typography — Inter, Poppins, Space Grotesk, Sora, Outfit (loaded via CDN) |

This repository is **frontend-only and fully static** — no PHP, MySQL, or any server-side code is present here. It is directly compatible with GitHub Pages.

## Portfolio Sections

Confirmed sections in `index.html`, in order:

- **Home / Hero** — introduction, tagline, call-to-action buttons, social links (GitHub, LinkedIn, Upwork)
- **About** — background summary, profile photo, and highlight stat cards
- **Skills** — categorized technical skill listing
- **Projects** — the featured project carousel and a professional experience entry
- **Contact** — contact details and a contact form

## Featured Projects

| Project | Description (as shown on the page) | Technologies Shown | Live Demo | GitHub |
|---|---|---|---|---|
| **M.A Detailing Studio** | Luxury car detailing website with premium UI, service showcase, booking section, responsive layouts, and a PPF visualizer concept | HTML, CSS, JavaScript, PHP, MySQL | [Live](https://hasnainalishaikh.github.io/car-detailing-website2/) | [Repo](https://github.com/hasnainalishaikh/car-detailing-website2.git) |
| **Vital Mobiles** | Modern e-commerce website with product listings, product pages, shopping cart, checkout, and reviews | HTML, CSS, JavaScript, PHP, MySQL | Unavailable (placeholder link) | Unavailable (placeholder link) |
| **Hospital Management System** | Hospital management platform with patient records, appointment scheduling, doctor management, billing and reporting | HTML, CSS, JavaScript, PHP, MySQL | [Live](https://medicareplus.42web.io/hospital/) | [Repo](https://github.com/hasnainalishaikh/Medicare.git) |
| **Islamic Website** | Islamic website with prayer times, Quran reading, and guidance content | HTML, CSS, JavaScript, PHP, MySQL | Unavailable (placeholder link) | [Repo](https://github.com/hasnainalishaikh/islam.git) |

> The M.A Detailing Studio card's GitHub link currently points to a repository named `car-detailing-website2`. If your actual project repository is named `car-detailing-website`, this link should be corrected in `index.html` before publishing.

## UI / Design

Confirmed from the CSS and markup:

- Dark, glassmorphism-based visual theme with cyan/blue/violet gradient accents
- Fully responsive layout with defined breakpoints at 900px and 480px, including a slide-in mobile navigation drawer
- Scroll-triggered reveal animations (`.reveal` / `.reveal.active` classes) on cards and sections
- A custom animated cursor and cursor-follower on pointer devices, disabled automatically on touch devices
- A dedicated projects carousel with previous/next buttons and smooth transform-based transitions
- Smooth scrolling between in-page sections

## Project Structure

```text
hasnain-portfolio/
├── index.html
├── hasnain-profile.png
├── car-detailing.png
├── vital-mobile.png
├── hospital-management.png
└── islamic-website.png
```

## Getting Started

This is a static HTML/CSS/JavaScript project with no build step or dependencies.

1. Clone the repository:
```bash
   git clone https://github.com/hasnainalishaikh/hasnain-portfolio.git
```
2. Open `index.html` directly in a browser, or serve it locally:
```bash
   npx serve .
```
3. No installation, build tools, or backend setup is required.

## Deployment

The site is deployed via **GitHub Pages** at [hasnainalishaikh.github.io/hasnain-portfolio](https://hasnainalishaikh.github.io/hasnain-portfolio/). Being fully static, it redeploys automatically whenever changes are pushed to the default branch with GitHub Pages enabled, and it can equally be hosted on any static file host (Netlify, Vercel, etc.) with no additional configuration.

## Screenshots

The repository's images (`car-detailing.png`, `vital-mobile.png`, `hospital-management.png`, `islamic-website.png`) are project thumbnails used inside the portfolio's project cards — they are not screenshots of the portfolio site itself, so they are not included here as such. `hasnain-profile.png` is the profile photo used in the About section. If you'd like actual screenshots of the portfolio page for this README, those would need to be captured separately.

## Future Improvements

- Add a real Live Demo and GitHub link for the "Vital Mobiles" project card (currently a placeholder anchor)
- Add a real Live Demo link for the "Islamic Website" project card (currently a placeholder anchor)
- Confirm and correct the GitHub link on the M.A Detailing Studio card if `car-detailing-website2` isn't the intended repository
- Verify and, if needed, implement actual message delivery for the contact form, since its current backend behavior couldn't be fully confirmed from the visible code
- Split the single large `index.html` file into separate HTML/CSS/JS files for easier maintenance
- Add real portfolio screenshots for documentation purposes

## Learning Outcomes

This project demonstrates practical experience with:

- Building a fully responsive, single-page layout using vanilla HTML/CSS/JavaScript with no framework
- Implementing scroll-based reveal animations and interactive UI elements (carousel, custom cursor, mobile navigation) from scratch
- Structuring a personal portfolio to present skills and project work clearly to recruiters and clients
- Deploying a static website via GitHub Pages

## Developer

**Hasnain Ali**
Full-Stack Web Developer

- GitHub: [github.com/hasnainalishaikh](https://github.com/hasnainalishaikh)
- Portfolio: [hasnainalishaikh.github.io/hasnain-portfolio](https://hasnainalishaikh.github.io/hasnain-portfolio/)
- LinkedIn: [linkedin.com/in/hasnain-ali-shaikh](https://www.linkedin.com/in/hasnain-ali-shaikh)
