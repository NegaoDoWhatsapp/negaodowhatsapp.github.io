# SunBeaten

A minimal dark portfolio, published at https://sunbeaten.github.io/.

Plain HTML and CSS. No dependencies or build step.

## Add a project

1. Edit `index.html` and remove the `empty-state` block when adding your first project.
2. Copy the commented-out `project` link inside the Projects section.
3. Replace its URL, title, and description, and remove its surrounding comment markers.
4. Commit and push to `main`. GitHub Pages publishes the changes automatically.

Update `style.css` to change the appearance.

## Preview locally

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000.

## Publishing

GitHub Pages serves the repository root from the `main` branch. The `.nojekyll`
file enables direct static publishing.
