# Find the Artifact (ROM Edition)

Static HTML classroom game ready for GitHub Pages.

## Project files
- `index.html` - app entry point
- `.github/workflows/deploy-pages.yml` - auto-deploy to GitHub Pages on push to `main`

## First-time GitHub setup
1. Create a new empty GitHub repository.
2. In this folder, run:

```bash
git init
git branch -M main
git add .
git commit -m "Initial static site"
git remote add origin https://github.com/<YOUR_USER>/<YOUR_REPO>.git
git push -u origin main
```

## Enable GitHub Pages
1. Open your repo on GitHub.
2. Go to **Settings -> Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Pushes to `main` will deploy automatically.

## Site URL
- Project site: `https://brandonlines.github.io/therom/`
- User/org site (repo named `brandonlines.github.io`): `https://brandonlines.github.io/`

## Local preview
Open `index.html` in a browser, or run a local static server.
