# FRIDAY App Starter (phone-friendly)

This is a small installable web app (PWA) starter with:
- A cinematic FRIDAY startup sequence
- A custom icon
- A basic diagnostic panel
- A voice test using the browser's built-in speech synthesis
- Offline caching after the first successful load on a secure HTTPS host

## Important
This is an installable web app, not a compiled native APK yet. It can be added to an Android home screen from a supported browser after hosting it on HTTPS. It does not track location or access private phone data.

## Easiest free publishing path
1. Extract this ZIP on your phone.
2. Create a new public repository on GitHub called `friday-app`.
3. Upload `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder (upload the files inside the folder too).
4. In the repository, open Settings → Pages.
5. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.
7. Open the published HTTPS site in Chrome on Android.
8. Chrome menu (⋮) → Add to Home screen or Install app.

If GitHub's mobile UI is difficult, tell ChatGPT what screen you see and continue one step at a time.
