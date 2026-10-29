# Kareem Wael | Automation Specialist

Single-page portfolio for Kareem Wael (Kem): n8n and AI automation work.

## Files
- `index.html`: the whole site (HTML, CSS, JS). Loads Lenis smooth scroll and Google Fonts from CDNs.
- `assets/portrait.webp`: the hero portrait.

## Run locally
Open `index.html` in a browser.

## Deploy on GitHub Pages
1. Create a new repository on GitHub (for example `portfolio`).
2. Upload `index.html` and the `assets` folder, or run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/KemWael/portfolio.git
   git push -u origin main
   ```
3. In the repository, go to Settings > Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site will be live at `https://kemwael.github.io/portfolio/`.
