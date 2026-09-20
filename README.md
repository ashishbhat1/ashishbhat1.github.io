# Portfolio Website for GitHub Pages

This repository contains a clean, responsive portfolio website for Ashish Bhat designed to be hosted on GitHub Pages.

## Files

- `index.html` – main portfolio page
- `styles.css` – all visual styling and responsiveness
- `script.js` – mobile nav and reveal animations

## GitHub Pages setup

1. Push this folder to a GitHub repository.
2. In GitHub, go to **Settings** → **Pages**.
3. Set the source to **Deploy from a branch**.
4. Choose the `main` branch and root folder (`/`).
5. Save.
6. Your site will be available at:
   `https://<your-github-username>.github.io/<repository-name>/`

## Update personal details

Before publishing, customize:

- Name and title in `index.html`
- Email, LinkedIn, and GitHub links
- Project descriptions and skills
- `Ashish Bhat Resume.pdf` file in the project root, if you want to use the resume download button

## Local preview

Open the project folder in a browser, or run:

```bash
cd portfolio-site
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

This is a static site, so it works perfectly with GitHub Pages without needing a build step.
