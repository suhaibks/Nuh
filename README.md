# Nuh

A simple static photo gallery intended for **GitHub Pages** hosting.

## Host on GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your preferred branch)
   - **Folder**: `/ (root)`
4. Save and wait for deployment.

## Add new photos
1. Put new image files into the `images/` folder.
2. Add those filenames to `images/manifest.json`.
3. Commit and push.

The site reads `images/manifest.json` first, so files listed there will appear on the gallery.
