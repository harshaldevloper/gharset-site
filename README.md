# GharSet Site

This folder contains the static landing and APK download site scaffold for GharSet.

## Intended deployment

- Preferred host: Vercel
- Alternative host: GitHub Pages for static-only pages

## What still needs to be dropped in

- Real app screenshots in `site/assets/`
- Final APK download URL
- Privacy policy and support links
- App version, build date, and checksum

## Download link strategy

Use one of these approaches:

1. Point the download button at the latest GitHub Release asset URL
2. Point the button at a stable external file host
3. Host the APK separately and keep the site static

Avoid committing large APK binaries into the repository itself unless there is a specific reason to do so.
