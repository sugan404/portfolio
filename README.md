# Personal Portfolio

Static portfolio website for Sugan Raj H, AI Engineer and Full-Stack Developer.

## Description

Personal portfolio website showcasing projects, skills, work experience, and contact information. The site is built as a single-page application with smooth scrolling navigation and a floating dock menu for quick links. All content is contained in static HTML with Tailwind CSS for styling.

## Main Features

- Hero section with name, role, and headline
- About section with biography and skills
- Projects showcase with detailed project cards
- Work experience timeline
- Languages and technical stack
- Contact section with email, phone, and social links
- Floating dock navigation for quick section jumping
- Resume download functionality
- Responsive design for mobile and desktop

## Technology Stack

- **Framework**: Static HTML with Tailwind CSS v4.3.3 (inline)
- **Fonts**: Fraunces (serif), Manrope (sans-serif) via Google Fonts
- **Icons**: SVG icons in the floating dock navigation
- **Deployment**: GitHub Pages

## Prerequisites

- A web browser (Chrome, Firefox, Safari, Edge)
- Git (optional, for cloning the repository)
- Text editor (VS Code, or any preferred editor)

## Installation

```bash
# Clone the repository
git clone https://github.com/sugan404/portfolio.git

# Change into the project directory
cd portfolio

# No installation needed — all dependencies are loaded via CDN
```

## Development

```bash
# Open index.html in your preferred browser
open index.html

# Or serve the files locally using any static file server
npx serve
# or
python3 -m http.server
# or
npx http-server
```

Open http://localhost:3000 (or the port indicated by your server) to view the portfolio.

## Production Build

No build step is required — the project is pure static HTML/CSS. All Tailwind CSS is inlined, and Google Fonts are loaded via CDN. To "build" the project for deployment, simply copy all HTML files, the favicon.svg, and the assets to your web server or GitHub Pages repository.

## Environment Configuration

No environment variables or configuration are required. The project does not use any API keys, backend services, or environment-dependent features.

## Repository

https://github.com/sugan404/portfolio

## Notes

This project is maintained independently of Lovable. The original website was created using the Lovable builder platform, and all builder-specific references, branding, and generated metadata have been removed or replaced for independent publication.
