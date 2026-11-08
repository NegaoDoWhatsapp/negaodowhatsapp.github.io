# SunBeaten

A dark, woodcut-inspired portfolio, published at https://sunbeaten.github.io/.

Plain HTML and CSS. No dependencies or build step.

## Add a project

1. Edit `index.html` and remove the `empty-state` block when adding your first project.
2. Copy the commented-out `project` link inside the Projects section. Number each entry in order.
3. Replace its URL, title, and description, and remove its surrounding comment markers.
4. Commit and push to `main`. GitHub Pages publishes the changes automatically.

Update `style.css` to change the appearance.

## Artwork and palette

`assets/andarilho.webp` is an optimized copy of the approved Andarilho do Sol
artwork, with no sun or trees in the background. The portrait is also used for
`assets/favicon.png`. The original artwork was created with the built-in image
generation tool and selected by the account owner.

The site uses near-black ink (`#080807`), parchment (`#f2d3a3`), and ochre
(`#d6a45e`), with system serif and sans-serif fonts. No third-party font requests
or JavaScript are needed.

## Preview locally

Run `python3 -m http.server 8000` in this directory, then open http://localhost:8000.

## Publishing

GitHub Pages serves the repository root from the `main` branch. The `.nojekyll`
file enables direct static publishing.
