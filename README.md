# Selin — Academic Website

This repository contains the source for an academic website built on GitHub Pages with Jekyll.

## Quick start
1. Create a new GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload these files to the repository root (or push via git).
3. In repository **Settings → Pages**, ensure the source is **Deploy from a branch**, **Branch: `main`**, **Folder: `/ (root)`**.
4. Add your content:
   - Edit `_config.yml` (title, scholar link, social).
   - Update `index.md` (bio and news).
   - Add PDFs in `/assets/papers/` and your CV at `/assets/cv/selin-cv.pdf`.
   - Replace `/assets/img/profile.jpg` with your headshot.
5. Commit changes — Pages will build automatically. Your site will be available at `https://YOUR-USERNAME.github.io/`.

## Local testing (optional)
Install Ruby and Jekyll, then run:
```
bundle install
bundle exec jekyll serve
```
Visit http://localhost:4000

## License
Template adapted from a minimal Jekyll theme.
