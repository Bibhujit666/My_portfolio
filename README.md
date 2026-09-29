# Bibhujit Panigrahi — Portfolio

A single-file, dependency-free personal portfolio website. Everything (HTML, CSS, JS) lives in `index.html`.

Live demo: https://portfolio-hzboeivf.devinapps.com

## Features

- Animated aurora/grid background, glassmorphism cards, custom cursor
- Typing hero, scroll reveal animations, animated stat counters
- Project grid with category filtering (Full Stack / Machine Learning / Systems)
- Skills, timeline and contact sections
- Fully responsive, reduced-motion friendly

## Run locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a repository (e.g. `portfolio`) on GitHub.
2. Push these files:

```bash
git init
git add .
git commit -m "Add portfolio site"
git branch -M main
git remote add origin https://github.com/Bibhujit666/portfolio.git
git push -u origin main
```

3. In the repo: **Settings → Pages → Source: GitHub Actions**. The included workflow
   (`.github/workflows/deploy.yml`) publishes the site on every push to `main`.

Your site will be at `https://bibhujit666.github.io/portfolio/`.
To serve it at `https://bibhujit666.github.io/` instead, name the repo `Bibhujit666.github.io`.

## Customising

- Text, projects and links: edit the corresponding sections in `index.html`.
- Colours: change the `--a`, `--b`, `--c` variables in the `:root` block at the top of the `<style>` tag.
- LinkedIn: replace `https://www.linkedin.com/` in the socials block with your profile URL.
