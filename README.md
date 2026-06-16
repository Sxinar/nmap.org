# Nmap Homepage Redesign

A modern, responsive, and minimalist redesign of the official Nmap (nmap.org) homepage. This project revitalizes the classic look of Nmap using Tailwind CSS v4, maintaining its original deep purple identity and premium technical feel without relying on generic web templates or heavy assets.

## Features

- Single HTML File: The entire layout is contained within a single `index.html` file.
- Tailwind CSS CDN: Styled entirely using the official Tailwind CSS browser CDN. No build steps, Node.js, or external CSS/JS libraries are required.
- Preserved Content: All original text, links, SEO metadata, Schema.org definitions, and Google Analytics scripts from nmap.org remain completely untouched.
- Responsive Design: Fully optimized for mobile, tablet, and desktop viewports using CSS Grid and Flexbox architectures.
- Premium Dark Theme: Employs a custom dark purple color palette (#0b0510 background) that pays homage to Nmap's historic design, complete with minimalist cards, sharp borders, and monospace technical accents.

## Usage

Simply open `index.html` in any modern web browser to view the design. 

To host it on GitHub Pages or any static hosting service, upload the `index.html` file. Note that for images to render correctly, the original `/images` and `/shared` directories from nmap.org must also be present in the root directory, or the relative image paths in the HTML must be updated to absolute URLs.

## Technologies Used

- HTML5 (Semantic Structure)
- Tailwind CSS v4 (via CDN)
