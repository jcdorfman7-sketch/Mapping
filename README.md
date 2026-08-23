# Augsburg Adventure Radius

Mobile-friendly interactive trip planner centered on Augsburg.

## Publish with GitHub Pages

1. Upload **all files in this folder** to the root of your `mapping` repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then Save.
5. GitHub will show the public site URL after deployment.

The app is a static PWA. After the first successful online load, its core files are cached for offline use.

Files:
- `index.html` — app
- `manifest.webmanifest` — install metadata
- `sw.js` — offline cache
- `icon.svg` — app icon
- `.nojekyll` — tells GitHub Pages to serve the static files directly
