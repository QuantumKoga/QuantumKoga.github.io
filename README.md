# Norbert Janik — Personal Portfolio

<p align="center">
  <strong>Software Developer · Cybersecurity Enthusiast · Infrastructure Engineer</strong>
</p>

<p align="center">
  <a href="https://quantumkoga.github.io">Live Website</a> ·
  <a href="https://github.com/QuantumKoga">GitHub</a> ·
  <a href="https://www.linkedin.com/in/norbert-janik-4698a321b/">LinkedIn</a>
</p>

<p align="center">
  <img
    src="public/images/portfolio-preview.png"
    alt="Preview of my personal portfolio website"
    width="900"
  />
</p>

## About

This repository contains the source code for my personal portfolio website.

The site brings together my professional experience in software development, independent engineering projects, and ongoing exploration of cybersecurity.

My background combines low-level C++ development for real-time 5G systems with hands-on work involving Linux, infrastructure, automation, and security.

The portfolio is intended to document what I build, what I learn, and how I approach engineering problems.

## Tech Stack

- **Framework:** [Astro](https://astro.build/)
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **Language:** TypeScript / JavaScript
- **Package manager:** npm
- **Development environment:** Nix Flakes
- **Deployment:** GitHub Pages
- **CI/CD:** GitHub Actions

## Getting Started

### Prerequisites

The project uses Nix Flakes to provide a reproducible development environment.

You will need:

- [Nix](https://nixos.org/) with Flakes enabled
- Git

### Development

Clone the repository:

```bash
git clone https://github.com/QuantumKoga/QuantumKoga.github.io.git
cd QuantumKoga.github.io
```

Enter the development environment:

```bash
nix develop
```

Install dependencies:

```bash
npm ci
```

Start the local development server:

```bash
npm run dev
```

Astro will make the website available at `http://localhost:4321`.

### Production Build

Build the website:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

The generated static website is placed in the `dist/` directory.

## Deployment

The website is hosted on **GitHub Pages**.

A GitHub Actions workflow automatically builds and deploys the site when changes are pushed to the `master` branch. The workflow can also be triggered manually.

Live version: **[quantumkoga.github.io](https://quantumkoga.github.io/)**

## Project Structure

```text
.
├── public/
│   ├── documents/       # CV and educational documents
│   └── images/          # Project images and other assets
├── src/
│   ├── components/      # Reusable UI components
│   ├── layouts/         # Page layouts
│   ├── pages/           # Website pages
│   └── styles/          # Global styles
├── .github/
│   └── workflows/       # CI/CD workflows
├── flake.nix            # Nix development environment
├── package.json
└── astro.config.mjs
```

## License

The source code is available for learning and reference. Unless explicitly stated otherwise, personal content, project descriptions, images, and other portfolio materials remain the property of their respective authors.

---

<p align="center">
  <sub>Built with curiosity and a hands-on engineering mindset.</sub>
</p>
