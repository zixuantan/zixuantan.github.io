# Zi Xuan Tan — Portfolio

A responsive, static portfolio for **https://zixuantan.github.io/**. Built with HTML and CSS; no application dependencies or build step.

## Preview locally

Run `python3 -m http.server 8000 --directory site`, then visit http://localhost:8000.

## Publish

1. Sign in to GitHub as `zixuantan` and create a **public** repository named exactly `zixuantan.github.io`. Leave README, license, and .gitignore initialization unchecked.
2. From this project directory, run:

   ```sh
   git init -b main
   git add .gitignore README.md site .github
   git commit -m "Build personal portfolio"
   git remote add origin https://github.com/zixuantan/zixuantan.github.io.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages → Build and deployment → Source**, and choose **GitHub Actions**.
4. Open **Actions → Deploy portfolio to GitHub Pages → Run workflow** if the initial run has already failed before Pages was enabled.
5. Once deployment succeeds, visit https://zixuantan.github.io/. The site may take a few minutes to appear.

## Edit

- `site/index.html`: biography, projects, experience, contact, and metadata.
- `site/styles.css`: design and responsive layouts.
- `.github/workflows/pages.yml`: automatic deployment on pushes to `main`.

Project illustrations are abstract decorative graphics, not performance charts. Project-specific URLs are intentionally omitted until confirmed. Google Fonts are optional; system fallbacks work without them. Content and interactions work without JavaScript.

The source resume is excluded from version control and the deployed `site` directory. The website includes the professional email address but omits the phone number. Experience dates and project results reflect the supplied resume; update the AMD “Present” status when needed.
