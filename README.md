# Sonia Thomas — Personal Site

A static personal-brand website for Sonia Thomas.

## Structure

- `index.html` — page content
- `styles.css` — all styling
- `netlify.toml` — tells Netlify to publish the repo root as-is (no build step needed)

## Making changes

This is plain HTML/CSS — no build step, no dependencies. Edit `index.html` for content, `styles.css` for styling (colors are CSS variables at the top of the file under `:root`), then commit and push. If the repo is connected to Netlify, the change goes live automatically within a minute or two of the push.

## Adding the photo

Drop the image file into this folder (e.g. `sonia.jpg`), then in `index.html` replace the placeholder `<div class="hero-photo">...</div>` block with an `<img>` tag pointing at it, and adjust `.hero-photo` in `styles.css` as needed (e.g. `object-fit: cover`).
