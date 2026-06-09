## Rishi Ranjan Portfolio

Personal portfolio website showcasing profile, experience, certifications, projects, testimonials, and contact details.

## Overview

This is a static portfolio built with:

- HTML
- CSS
- Vanilla JavaScript
- JSON-driven content rendering

Most content is loaded dynamically from files in the `data` folder.

## Features

- Sidebar profile with social links
- About section with technology stack badges
- Resume timeline (experience and education)
- Certifications section
- Filterable projects with modal details
- Testimonials carousel and modal
- Contact form using `mailto`

## Project Structure

- `index.html`: Main page layout
- `assets/css/style.css`: Styles
- `assets/js/BuilderKit.js`: Dynamic section rendering from JSON
- `assets/js/Script.js`: UI interactions
- `data/experiences.json`: Work experience timeline
- `data/educations.json`: Education, certifications, workshops
- `data/projects.json`: Project cards and modal details
- `data/services.json`: What I am doing section
- `data/testimonials.json`: Testimonials data
- `data/posts.json`: Blog posts data
- `assets/images/`: Images used by the site
- `assets/pdf/`: Resume and downloadable documents

## Run Locally

Because this project fetches JSON files, run it through a local server (not by opening HTML directly).

Example:

```bash
cd /path/to/aronno1920.github.io-main
python3 -m http.server 8000
```

Then open:

`http://localhost:8000`

## Updating Content

Update these files based on section:

- About/contact/static text: `index.html`
- Experience: `data/experiences.json`
- Education/certifications/workshops: `data/educations.json`
- Projects: `data/projects.json`
- Services: `data/services.json`
- Testimonials: `data/testimonials.json`

## Notes

- Contact form currently uses `mailto:rishiranjan1604@gmail.com`.
- LinkedIn and GitHub links are configured in the sidebar social icons.
- Career Journey currently uses logo assets for Monocept and Masai.
