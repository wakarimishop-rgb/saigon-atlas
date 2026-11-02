# SAIGON ATLAS

A mobile-first map notebook for Ho Chi Minh City.

## Deploy with GitHub Pages

1. Create a **public** repository named `saigon-atlas`.
2. Upload `index.html`, `manifest.webmanifest`, and `icon.svg` to the root of the `main` branch.
3. Go to Settings > Pages > Build and deployment, select **Deploy from a branch**, then `main` and `/(root)`, and save.
4. Open `https://YOUR-USERNAME.github.io/saigon-atlas/` on Safari.

Notes: the district overlay is fetched from a third-party GIS service and may fail; map tiles and search require internet. Pin notes are stored in the browser's localStorage, not synchronized between devices. Use the app's JSON export for backup. Do not assume overlay reflects post-2025 administrative borders.