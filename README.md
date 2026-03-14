# Sagar Malla - Portfolio

Sagar Malla Portfolio
https://sagarmalla.info.np/

A premium, highly interactive portfolio website designed with a Midnight Aurora aesthetic. This project showcases my journey as a DevOps Engineer and System Administrator, featuring dynamic animations, a custom design system, and a dedicated tutorial lab.

## Features

- Midnight Aurora Theme: A custom-designed dark aesthetic using mesh gradients, noise textures, and vibrant accent colors (Indigo, Purple, Teal).
- Fully Responsive: Optimized for all screen sizes, featuring a fixed sidebar on desktop and a responsive navigation bar on mobile.
- Interactive UI:
  - Custom Cursor: A dynamic dot-and-outline cursor that reacts to interactive elements.
  - AOS Animations: Smooth scroll-triggered animations for a professional feel.
  - Glassmorphism & Material Design: A blend of modern glass effects and solid material surfaces for depth and clarity.
- Dedicated Tutorials Hub: A separate section (`tuto.html`) for showcasing laboratory practices and technical documentation.
- Certifications Gallery: An interactive carousel gallery (`gallery.html`) that highlights professional certifications and awards.
- Smart Fallback System: Built-in compatibility for static hosting (GitHub/Cloudflare) ensuring dynamic listings work everywhere.
- Cross-Platform Optimized: Tailored experiences for Desktop (Custom Cursor) and Mobile (Default Navigation, single-row social icons).
- Skeleton Loading: Modern shimmer placeholders in the Gallery and Tutorials for a smooth loading experience.

## Technologies Used

- Core: HTML5, Vanilla CSS3, Javascript (ES6+)
- Frameworks: Bootstrap 5
- Animations: AOS (Animate On Scroll)
- Icons: Font Awesome 6, Google Material Symbols
- Typography: Saira Extra Condensed, Muli

## Project Structure

```text
.
├── index.html          # Main portfolio entry point
├── tuto.html           # Tutorials & Lab index page
├── gallery.html        # Certifications Gallery page
├── assets/
│   ├── img/            # Brand assets & GIFs
│   └── certifications/ # Certification images
├── css/
│   └── styles.css      # Core theme and Bootstrap overrides
└── tuto/
    └── *.html          # Individual tutorial lab files
```

## Getting Started

To run this project locally, you can use any static file server.

### Using Python
python3 -m http.server 3000

Then visit http://localhost:3000 in your browser.

### Using VS Code Live Server
1. Open the project in VS Code.
2. Click "Go Live" in the bottom right corner.

## About Me

I am a DevOps Engineer and System Administrator with over 4 years of experience in managing high-availability infrastructure, CI/CD pipelines, and network security.

- Location: Lalitpur, Nepal
- Specialization: CI/CD (Jenkins, GitLab), Containerization (Docker, K8s), Monitoring (ELK, Prometheus, Grafana).

## License

This project is personal portfolio work. Feel free to use the design patterns and inspiration for your own projects.

---
Developed by Sagar Malla (sagarmalla08@gmail.com)
