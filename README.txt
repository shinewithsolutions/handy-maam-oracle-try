THE HANDY MA’AM ORACLE — GITHUB / PWA FILES

FOLDER STRUCTURE
handy-maam-oracle/
├── index.html
├── manifest.json
├── service-worker.js
├── README.txt
└── icons/
    ├── icon-192.png
    └── icon-512.png

HOW TO PUBLISH WITH GITHUB PAGES

1. Go to GitHub and sign in.
2. Click New repository.
3. Name it handy-maam-oracle (or another name).
4. Choose Public, then click Create repository.
5. Upload ALL files and the icons folder from this package. index.html must stay at the repository root.
6. Commit the files.
7. Open the repository Settings.
8. In the left menu, choose Pages.
9. Under Build and deployment, choose Deploy from a branch.
10. Select the main branch and / (root), then click Save.
11. Wait a few minutes for GitHub Pages to publish the site. GitHub will show the live HTTPS address in Settings > Pages.

HOW TO INSTALL / DOWNLOAD THE APP

Desktop (Microsoft Edge / Chrome):
1. Open the GitHub Pages URL.
2. Wait for the page to load fully.
3. In Edge, click the App available / Install icon in the address bar, or open the three-dot menu > Apps > Install The Handy Ma’am Oracle.
4. Confirm Install. The app will open in its own window and can be pinned to Start/taskbar.

Android (Chrome):
1. Open the GitHub Pages URL in Chrome.
2. Tap the three-dot menu.
3. Tap Install app or Add to Home screen.
4. Confirm.

iPhone / iPad (Safari):
1. Open the GitHub Pages URL in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Tap Add.

IMPORTANT
- Do not rename index.html.
- Keep manifest.json, service-worker.js, and the icons folder beside index.html.
- GitHub Pages uses HTTPS, which is required for normal PWA/service-worker installation.
- If you update the app later, replace index.html and change CACHE_NAME in service-worker.js from v1 to v2 (then v3, etc.) so installed copies refresh cleanly.
- This package is an installable web app (PWA). It is not an .exe or Android .apk file.
