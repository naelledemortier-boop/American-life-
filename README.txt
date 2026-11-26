# American Life — Prototype 0.1

A small mobile-first Progressive Web App prototype for learning American English through an interactive New York setting.

## Files
- `index.html`: app interface, lessons, interactions, quiz and local progress.
- `manifest.json`: PWA metadata.
- `sw.js`: basic offline cache.
- `icon.svg`: app icon.

## Run
Open `index.html` in a browser for a basic preview. PWA installation and service-worker offline support require hosting over HTTPS (or localhost).

## Install on iPhone
1. Publish these files to an HTTPS static host (for example GitHub Pages).
2. Open the published website in Safari on iPhone.
3. Tap Share → Add to Home Screen.

## Current limitations
This is an early prototype, not a native iOS App Store app. The conversations are scripted choices, not live AI. Progress is stored locally in the browser. The speech buttons use device speech synthesis when available. A live AI service, secure backend, privacy review and further testing would be needed for real voice conversations and multi-device sync.
