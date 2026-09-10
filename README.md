# Monazah Azhar — Portfolio

A responsive, static DevOps/Platform Engineering portfolio built with plain HTML, CSS and JavaScript.

## Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- GitHub Pages

No Docker, Kubernetes, Node.js or build server is required.

## Run locally

Open `index.html` directly in a browser, or use any simple static server.

Example with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

### Option A — easiest

1. Create a new GitHub repository.
2. Recommended repository name: `monazah-azhar.github.io`
3. Put `index.html`, `style.css` and `script.js` in the repository root.
4. Commit and push.
5. In GitHub open:
   **Settings → Pages**
6. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
7. Save.
8. GitHub Pages will publish the site at:

`https://YOUR-GITHUB-USERNAME.github.io/`

### Option B — project repository

If the repository is named `portfolio`, the URL will normally be:

`https://YOUR-GITHUB-USERNAME.github.io/portfolio/`

## Git commands

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## Before publishing

Replace the GitHub placeholder link in `index.html`:

```html
https://github.com/
```

with your actual GitHub profile/repository URL.

You can also add:
- Profile photo
- Resume PDF
- Individual project GitHub links
- Certification verification links
- GitHub contribution/project cards
- Custom domain
