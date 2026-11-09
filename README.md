# Grizzam

Grizzam quiz library frontend. The original teacher authentication, quiz CRUD,
HTML upload, external-link handling, Google Apps Script API bridge, local
caching, filters, search, and refresh flow are retained.

## Run
Open `index.html` in a browser or serve this folder from a static web server.
Font Awesome is loaded from its existing CDN dependency, so an internet
connection is needed for those icons. The Google Apps Script web app must also
be reachable for live data operations; cached quiz data remains available
according to the existing offline-first behavior.

## Configuration
The Apps Script URL and teacher login values remain in `script.js` under
`CONFIG`. They were intentionally not changed as part of this UI repair.

## Interface updates
The latest repair includes explicit high-contrast light/dark theme colors, a
Grizzam-branded logout confirmation dialog, and a content-driven responsive
layout for desktop, tablet, mobile, and short landscape screens.

## Repair notes
See `AUDIT-REPORT.md` for the scope of changes and validation limitations.
