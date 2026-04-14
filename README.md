# Digital AD PWA

A static offline-ready PWA for indie filmmakers.

## What it does
- Create projects by type: feature film, short film, music video, commercial
- Store title, page count, budget, shoot days, start/lunch/wrap times, setup gaps, shooting ratio
- Add scenes per shoot day with pages, planned time, duration override, notes
- Run a countdown for the current scene
- Track additional expenses against the total budget
- Move scenes to another day or add extra time dynamically
- Export full project JSON or single day JSON
- Import project backups back into the app
- Generate a printable day report and email draft from the device
- Install to phone home screen as a PWA
- Works offline after first load

## Storage
This version uses localStorage in the browser, so no backend, login, or account is needed.
For safety, export project JSON regularly.

## Files
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png

## How to host
Upload the files to any static host or subdomain root.
Examples:
- ad.yourdomain.com
- GitHub Pages
- Cloudflare Pages
- Netlify

## Notes
- Browser notifications require permission.
- On iPhone, install from Safari using Share > Add to Home Screen.
- Email report opens the default mail app with a summary. Use Print / Save as PDF for the full report attachment.
