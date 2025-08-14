# David Fule — Portfolio

A modern, responsive single-page portfolio built with HTML, Tailwind CSS (CDN), and vanilla JavaScript.

## Preview

- Local: open `index.html` in a browser, or serve the folder with a static server.
- Hero image: `hero.jpg`
- Resume download: `Resume David Fule.pdf` (linked from the site)

## Features

- Sticky, glassmorphism navbar with active-section highlight
- Dark/light theme toggle with system preference + localStorage
- Modern hero image container with layered glow, depth, and subtle motion
- Projects grid with animated cards and tech chips
- Skills section with categorized, responsive tags
- About section with two-column readable layout
- Contact form (front-end only) with email, location, phone, and social links
- Smooth scrolling, back-to-top button, and small interaction details

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Font Awesome icons
- Vanilla JavaScript (no frameworks)

## Project Structure

```text
.
├─ index.html                 # Main page
├─ hero.jpg                   # Hero image
├─ Resume David Fule.pdf      # Downloadable resume
└─ README.md                  # This file
```

## Run Locally

Option A: open the file directly

```text
index.html
```

Option B (recommended): serve with a local static server

```bash
npx serve .
# or
python -m http.server 8000
```

Then open the printed URL (e.g. <http://localhost:3000> or <http://localhost:8000>).

## Customize

- Edit content in `index.html` (hero, projects, skills, about, contact)
- Replace `hero.jpg` with your image
- Replace `Resume David Fule.pdf` with your updated resume
- Update social links in the contact section

## License

MIT
