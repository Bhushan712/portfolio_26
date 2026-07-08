# Bhushan Patil — Portfolio

A single-page portfolio site (HTML/CSS/JS, no build step required).

## Adding your photos

The page expects an `images/` folder sitting next to `index.html`, with these files:

| File | Used for |
|---|---|
| `images/headshot.jpg` | Your profile photo, shown circular in the hero section |
| `images/project-h5p.jpg` | H5P Interactive Learning Portfolio card |
| `images/project-nutrition.jpg` | Government Nutrition & Food Safety Training card |
| `images/project-esuvidha.jpg` | eSuvidha Software Training card |

Steps:
1. Create a folder named `images` in the repo root.
2. Add your photos into it using **exactly** those filenames (or edit the `src="images/..."` paths in `index.html` to match your own filenames).
3. Headshot works best as a square photo (it's cropped into a circle). Project images work best landscape, roughly 800×500px or larger — screenshots, certificates, or any relevant visual.
4. Commit and push both the `index.html` and the `images/` folder together.

If a photo is missing, that spot will just show a soft amber/teal gradient placeholder instead of breaking the layout.

## Hosting on GitHub Pages

1. Copy `index.html` into the root of your GitHub repo (replace or add alongside existing files).
2. Commit and push:
   ```bash
   git add index.html
   git commit -m "Add portfolio site"
   git push
   ```
3. On GitHub, go to your repo → **Settings** → **Pages**.
4. Under "Build and deployment" → **Source**, select **Deploy from a branch**.
5. Choose branch `main` (or `master`) and folder `/ (root)`, then **Save**.
6. GitHub will give you a live URL, usually:
   `https://<your-username>.github.io/<repo-name>/`
   (It can take 1–2 minutes to go live after the first save.)

## Editing later
Everything — text, colors, fonts — lives in the single `index.html` file: content in the `<body>`, styling in the `<style>` block at the top. No dependencies to install.
