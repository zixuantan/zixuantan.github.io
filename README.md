# Zi Xuan Tan — Portfolio

A responsive, static portfolio for **https://zixuantan.github.io/**. Built with HTML and CSS; no application dependencies or build step.

## Preview locally

Run `python3 -m http.server 8000 --directory site`, then visit http://localhost:8000.

## Publish updates

The repository is connected to GitHub Pages using GitHub Actions. Commit changes and push to `main`; the workflow publishes the `site` directory automatically.

```sh
git add site README.md
git commit -m "Update portfolio"
git push origin main
```

Check deployment progress in the repository’s Actions tab.

## Edit

- `site/index.html`: biography, projects, experience, contact, and metadata.
- `site/styles.css`: design and responsive layouts.
- `.github/workflows/pages.yml`: automatic deployment on pushes to `main`.

A minimal black-and-white design with fully clickable project rows. The backtester and macro dashboard link directly to their Streamlit apps, with separate GitHub source links. The Goodreads project links to its repository. Destinations were confirmed from the public project READMEs. The site uses system fonts and works without JavaScript or external font requests.

The source resume is excluded from version control and the deployed `site` directory. The website includes the professional email address but omits the phone number. Experience dates and project results reflect the supplied resume; update the AMD “Present” status when needed.
