CORRECTED CO CALCULATOR — PWA PACKAGE

Files:
- index.html: calculator (defaults to 4-stroke)
- manifest.webmanifest: installable app settings
- sw.js: offline cache/service worker
- icons/: 192px and 512px app icons

INSTALL:
1. Upload the CONTENTS of this folder to an HTTPS static host (GitHub Pages is suitable).
2. Open the hosted URL in Chrome on Android while online.
3. Wait a few seconds for the offline cache to install.
4. Chrome menu (⋮) > Install app / Add to Home screen.
5. Open it once. It should then launch as a standalone app and work offline.

Important:
- Service workers and PWA installation require HTTPS (except localhost).
- Opening index.html directly from Downloads does NOT enable PWA installation/offline service-worker caching.
- If you update the app later, change CACHE_NAME in sw.js (for example v2) so devices fetch the new files.
