SOS Library PWA
===============
Files: index.html, app.js, manifest.webmanifest, sw.js

DEPLOYMENT
Upload all four files together to the root of an HTTPS static site.
Suitable choices include GitHub Pages, Cloudflare Pages, or Netlify.

IMPORTANT
Camera APIs should be tested from the deployed HTTPS URL, not by opening index.html as a local file.
The ISBN lookup uses Open Library over the Internet. Inventory is stored locally in the browser.

ANDROID
Open the HTTPS URL in Chrome, grant camera permission, then use Chrome's Add to Home screen / Install app option if offered.
