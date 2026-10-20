FATHERCARE — DIABETES & HEALTH DASHBOARD — HOME-SCREEN PACKAGE

CONTENTS
- index.html: dashboard application
- manifest.json: home-screen app metadata
- service-worker.js: offline app-shell support
- icon-192.png and icon-512.png: app icons

IMPORTANT
Android Chrome generally requires the app to be served over HTTPS before it can be installed as a proper home-screen PWA. Opening index.html directly from Downloads does not provide the full PWA installation experience.

DEPLOYMENT
1. Extract this ZIP into its own folder.
2. Upload the contents to its own GitHub repository or separate HTTPS static-hosting path.
3. On GitHub, enable Pages in Settings -> Pages, using the main branch and root folder.
4. Open the resulting HTTPS URL in Chrome on Android and wait for the app to load.
5. Open Chrome's three-dot menu and choose Install app or Add to Home screen (wording varies).
6. Confirm the name and add it.

Keep the two applications in separate repositories or separate HTTPS paths. They use separate storage namespaces, but browser data can still be lost if site data is cleared; use each app's backup feature. This package has not been verified through a live Android installation. Test logging, editing and backups before relying on it for daily records.
