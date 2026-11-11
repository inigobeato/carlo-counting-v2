CARLO COUNTING - GitHub / Netlify PWA files

Upload the CONTENTS of this folder to the ROOT of your GitHub repository (not the folder itself).

Files:
- index.html: complete CARLO COUNTING application
- manifest.webmanifest: install name, colors, and app icons
- sw.js: service worker for offline app-shell caching
- icons/icon-192.png and icons/icon-512.png: clearer app logos

Expected repository layout:
index.html
manifest.webmanifest
sw.js
icons/icon-192.png
icons/icon-512.png

Then commit/push and let Netlify deploy the repository. Open the HTTPS site in Chrome and use the browser menu > Install app / Add to Home screen.

IMPORTANT: If replacing an existing deployment, upload all files while preserving the same site/repository. The app stores its records in the browser's local storage; avoid clearing site data.
