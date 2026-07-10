SHOTBRU VERSION 1 — INSTALLABLE WEB APP

WHAT THIS PACKAGE IS
ShotBru Version 1 is a Progressive Web App (PWA). It installs from Chrome onto an
Android phone and opens in its own full-screen app window. After the first load it
works offline, except for WhatsApp sharing, which requires WhatsApp or an internet
connection.

IMPORTANT
A PWA must be opened from a secure website (HTTPS) for the Install button and offline
service worker to work. Opening index.html directly from the Files app will run the
scoring app, but it will not enable proper installation or offline caching.

QUICK DEPLOYMENT
1. Upload every file and folder in this package to a secure web host.
2. Open the HTTPS website in Chrome on Android.
3. Tap the Chrome menu.
4. Select "Install app" or "Add to Home screen".
5. ShotBru will appear with its own icon and open like a normal app.

DATA
Rounds, payment statuses, history and leaderboard are stored locally in the browser
on that phone. Clearing Chrome site data or uninstalling the PWA may remove the data.
Cloud backup and multi-device syncing are not included in Version 1.

FILES
index.html
manifest.webmanifest
service-worker.js
icons/
