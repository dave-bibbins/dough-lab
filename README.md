# Dough Lab

A single-file baker's-percentage dough calculator for pizza, bagels, and donuts —
live ticket, preferments, pantry costing, and finished-pie cost.

This repo is the **public web deployment** (app only). It's served via GitHub Pages
so it can be opened on any device, including iPad ("Add to Home Screen" for an
offline app icon).

## Storage

- **Desktop Chrome/Edge:** saves to a local JSON data file you own (File System Access API).
- **iPad Safari / other browsers:** auto-saves to on-device storage.
- **Export / Import** buttons (in the Pantry tab) move a JSON file between devices —
  this is the no-backend way to sync recipes. Your data never lives in this repo.

Files: `index.html` (the app), `manifest.webmanifest`, `sw.js` (offline service worker).
