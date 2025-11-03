# Hello Space — Tiny Single-File Tailwind Page

A minimal, beautiful, single-file HTML application that says "Hello Space". The page is fully responsive, uses the Tailwind CSS CDN, includes a lightweight animated starfield, accessible motion preferences, a theme toggle, and a tiny utility to copy the greeting to the clipboard.

This repository contains three files:

- index.html — The complete single-file web app (Tailwind via CDN, inline JavaScript/CSS).
- README.md — This file.
- LICENSE — MIT License.

Features

- Single-file production-ready HTML page.
- Responsive layout and typography using Tailwind CSS CDN.
- Animated starfield background (respects "prefers-reduced-motion").
- Gradient heading with subtle glow: "Hello Space".
- Theme toggle (dark/light) persisted to localStorage.
- Copy-to-clipboard button for the greeting.
- Accessible markup and keyboard focus considerations.

Usage

1. Download or clone the repository.

2. Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

   - No build tools required — the page is a single HTML file and uses the Tailwind CDN.

3. Host it on any static hosting (GitHub Pages, Netlify, Vercel, S3) by serving the index.html.

Customization

- Modify the text directly in index.html around the <h1> element to change the displayed message.
- Tailwind config is included via the CDN script to allow small theme extensions. For bigger changes, consider migrating to a Tailwind build pipeline.
- The starfield canvas and its parameters can be tuned in the inline script if you want more or fewer stars.

Accessibility

- The application respects the user's "prefers-reduced-motion" setting (disables animations and the starfield when set).
- Buttons include ARIA labels and keyboard-focus-friendly styles.

License

This project is released under the MIT License. See the LICENSE file for details.
