# Astavinayak Tour & Travels 🌍

A static travel agency website built with HTML and CSS, showcasing tour packages, destinations, and services across six dedicated pages with clean, page-wise styling.

🔗 **Live Site:** [astavinayak-tour-and-travels.vercel.app](https://astavinayak-tour-and-travels.vercel.app/)

---

## Overview

Astavinayak Tour & Travels is a multi-page static website that presents a travel agency's services in a structured and visually clean layout. Each page has its own dedicated CSS file, keeping styles modular and easy to maintain. The project demonstrates solid HTML fundamentals, organised folder structure, and static deployment — making it a strong base for expanding into a fully dynamic travel booking platform.

---

## Pages

| Page | File | Description |
|---|---|---|
| Home | `index.html` | Overview of travel services |
| About | `about.html` | Agency background and information |
| Packages | `packages.html` | Tour packages and offerings |
| Gallery | `gallery.html` | Travel images and destinations |
| Contact | `contact.html` | Contact details and inquiry section |
| Login | `login.html` | Basic login UI (frontend only) |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Scripting | Vanilla JavaScript (where applicable) |
| Deployment | Vercel |

---

## Project Structure

```
astavinayak-tour-and-travels/
│
├── css/
│   ├── style.css          # Global / base styles
│   ├── pages.css          # Shared page-level styles
│   ├── index.css          # Home page styles
│   ├── about.css          # About page styles
│   ├── packages.css       # Packages page styles
│   ├── gallery.css        # Gallery page styles
│   ├── contact.css        # Contact page styles
│   └── login.css          # Login page styles
│
├── index.html             # Home page
├── about.html             # About page
├── packages.html          # Packages page
├── gallery.html           # Gallery page
├── contact.html           # Contact page
├── login.html             # Login page
│
└── README.md
```

---

## Running Locally

No installation or build tools required.

**Option 1 — Open directly:**
```
Double-click index.html to open in your browser
```

**Option 2 — Live Server (recommended):**
```
Right-click index.html in VS Code → Open with Live Server
```
Live Server gives you instant hot-reload on every file save, making development much smoother.

---

## Deployment

Hosted on **Vercel** as a static site with zero configuration.

1. Push the project to a GitHub repository
2. Go to [vercel.com](https://vercel.com) → **New Project** → import the repo
3. No build settings needed — Vercel detects static HTML automatically
4. Every push to `main` triggers an automatic redeployment

---

## Concepts Demonstrated

- Multi-page static website architecture
- Page-wise CSS organisation for clean separation of concerns
- Semantic HTML5 structure
- Responsive layout fundamentals
- Modular folder organisation
- Static site deployment on Vercel

---

## Roadmap

- [ ] JavaScript form validation on contact and login pages
- [ ] Fully responsive layout for all screen sizes
- [ ] Backend integration for contact form and login (Node.js / Firebase)
- [ ] Tour booking and availability functionality
- [ ] UI enhancements with CSS animations and transitions

---

## Use Cases

- Live website for a travel agency
- College mini project submission
- HTML & CSS practice and portfolio project
- Static website deployment demonstration

---

## License

MIT — free to use and adapt with attribution.
