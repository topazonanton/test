# Blenderizm – 3D Freelancer Portfolio

A professional portfolio and client engagement website for a freelance 3D artist specializing in Blender modeling, V-Ray rendering, and hard surface design. The site showcases photorealistic 3D work, allows clients to request project quotes, and provides information about services including product visualization, STL modeling, and game assets.

## Overview

**Blenderizm** is the portfolio brand of Anton Topaz, a freelance 3D artist. This repository contains the web presence for the Blenderizm business, built with HTML and optimized for search engines and client discovery.

### What's Included

- **Portfolio Gallery** – Showcases 3D modeling and rendering work
- **Project Request Form** – Allows clients to submit custom project briefs with detailed requirements
- **Services Overview** – Details on offered services: 3D modeling, product visualization, hard surface modeling, STL files, game assets, and photorealistic rendering
- **SEO & Accessibility** – Structured data (JSON-LD), Open Graph meta tags, semantic HTML, and ARIA labels for maximum discoverability

## Tech Stack

- **Language:** HTML5, CSS3
- **Hosting:** GitHub Pages (deployed at blenderizm.com)
- **Notable Features:**
  - Server-side routing support with `.htaccess`
  - Responsive design with CSS Grid and Flexbox
  - Dark theme with accent color (#ff6a00 orange)
  - Custom fonts: Orbitron, Rajdhani, JetBrains Mono

## Repository Structure

```text
3DFreelancer/
├── index.html               # Main portfolio landing page
├── offer.html               # Project quote request form
├── 404.html                 # Custom error page with navigation fallbacks
├── assets/                  # Media directory (images, 3D previews, etc.)
├── robots.txt               # SEO configuration for search engines
├── sitemap.xml              # XML sitemap for discoverability
├── .gitattributes           # LFS/binary handling for large assets
├── .htaccess                # Web server routing & rewrite rules
├── .thumbnail.jpg           # Repository thumbnail for GitHub
└── index.html.srcmap.json   # Source map for index.html debugging
```

## How It Fits Together

The site is a static HTML portfolio with a two-tier structure:

1. **Landing Page** (`index.html`) – Displays the full portfolio with embedded 3D previews, past projects, and brand information.
2. **Client Engagement** (`offer.html`) – A dedicated form page where clients can submit project briefs with specific requirements, deliverables, and timelines.
3. **Error Handling** (`404.html`) – A friendly fallback that redirects lost visitors back to the portfolio or the quote form.

SEO is optimized through JSON-LD schema markup (Person, ProfessionalService, WebSite), Open Graph and Twitter Card meta tags, and a sitemap for indexing.

## Getting Started

### View the Site Locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/topazonanton/3DFreelancer.git
cd 3DFreelancer
start index.html
```

### Request a Quote
Navigate to `offer.html` to see the client intake form, or visit the live site at **blenderizm.com/offer.html**.

### Deploy to GitHub Pages
This repo is configured for GitHub Pages hosting. Push changes to the `main` branch:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

The site will be live at `https://blenderizm.com` (custom domain configured in repo settings).

## Services Offered

- **3D Modeling & Asset Creation** – Product models, hard surface design, game-ready assets
- **Product Visualization** – Photorealistic renders for e-commerce and marketing
- **STL & 3D Printing** – Print-ready models and mesh optimization
- **Retopology Services** – Clean topology for 3D scans and exports in .fbx, .stl, .dxf formats
- **Rendering & Texturing** – V-Ray rendering and Substance Painter workflows

## Support & Contact
For project inquiries, use the **Request Offer** form on the site, or email **Blenderizm@gmail.com**.

## License
This portfolio site is the proprietary work of Anton Topaz (Blenderizm). All 3D artwork, designs, and branding are copyrighted.

---
**Website:** [blenderizm.com](https://blenderizm.com/)
**Repository:** [github.com/topazonanton/3DFreelancer](https://github.com/topazonanton/3DFreelancer)