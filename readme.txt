OB/GYN Coding Aid - installable web app

CONTENTS
  index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png

HOSTING
  Upload all files, unchanged, to one folder on any HTTPS web server (e.g., Holy Name intranet/web server).
  HTTPS is required for installation and offline use. No server-side code, database, or PHI is involved;
  the page runs entirely in the browser and sends no data anywhere.

INSTALL ON A PHONE
  iPhone (Safari): open the link > Share > Add to Home Screen > Add.
  Android (Chrome): open the link > menu (three dots) > Install app (or Add to Home screen).

UPDATING
  Redeploy the whole folder to the SAME site (Netlify: Site > Deploys > drag the new folder onto the
  deploy area; do not create a new site, which would change the address).
  Installed phones load the new version the next time the app is opened online (network-first;
  the _headers file stops Netlify from caching the app files). Offline, the last version is used.
