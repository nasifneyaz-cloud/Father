FATHERCARE PWA — INSTALLATION NOTES

Files:
- index.html: the dashboard
- manifest.json: installable app metadata
- service-worker.js: offline app shell
- icon-192.png, icon-512.png, icon-maskable-512.png: app icons (kept individually at the repository root)

DEPLOY TO GITHUB PAGES
1. Create/open a GitHub repository.
2. Upload ALL seven files directly into the repository's root (not inside a nested folder).
3. Commit changes.
4. Open repository Settings > Pages and enable deployment from the main branch / root (if not already enabled).
5. Wait for GitHub Pages to publish. Open the HTTPS Pages URL in Chrome on Android.
6. Refresh once, then use Chrome menu > Install app / Add to Home screen. The in-page Install app button appears when Chrome makes the install prompt available.

IMPORTANT
- The app needs HTTPS for service-worker installation; GitHub Pages provides HTTPS.
- This is a local-first tracker. Records stay in the browser storage on that device/browser. Export a JSON backup regularly. Clearing browser data can erase records.
- Installing a new version does not merge records across devices.
- The first tab is the timed Daily Routine (the old check-and-log tab has been removed). The glucose report button prints only the glucose summary.
- Follow the father's clinician for medication, glucose targets, meals and exercise. Do not change medication based only on app averages.

UPDATE: The Daily Routine tab now has a checkbox for every timed routine step. Ticks save automatically for today's date on this device; use Reset today to clear them.
