# Trinkgeld

A small offline web app for delivery drivers to track tips per shift, with cash and online tips kept apart.

## Features

- Add a tip with a finger slider (0 to 20 €, 0,10 € steps) or type a larger amount
- Cash (Bargeld), online, or both from the same customer in one entry
- Totals per shift and per month, with a cash and online split
- Works without internet once installed on the home screen
- Backup to a file and restore from it
- Light and dark mode, German interface

## Install on iPhone

1. Open the site in Safari.
2. Tap Share, then "Add to Home Screen".
3. Open it from the home screen. It now works offline.

## Privacy

All tips are stored only on the device, in the browser's local storage. Nothing is sent to a server, and this repository contains no personal data.

## How it works

A single `index.html` with plain HTML, CSS and JavaScript, a web app manifest, and a service worker (`sw.js`) that caches the app for offline use. The fonts (Barlow, SIL Open Font License) are bundled in `fonts/`.

Made with help from Claude (Anthropic).
