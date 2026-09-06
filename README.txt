# Class 10 Study Hub — PWA Version

This version can be installed like an app when hosted over HTTPS (for example GitHub Pages).

## Android / Chrome
1. Open the website URL in Chrome.
2. Tap the **Install** button shown by the website, or Chrome menu → **Install app / Add to Home screen**.
3. The Study Hub icon will appear on the home screen.
4. Open it from the icon like an app.

## Important
A local `file://` HTML file can be opened, but browser PWA installation requires the site to be served from HTTPS (or localhost for development). The service worker provides basic offline caching after the site has been opened online at least once.

The website itself does not need Google Search indexing. Google Search and PWA installation are separate.
