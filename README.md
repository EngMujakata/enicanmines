# Enican Mines System

Web app (PWA) + Android APK build.

## Files
- `index.html` – the whole app
- `manifest.json`, `sw.js` – PWA files
- `logo.png` – YOUR logo (replace the placeholder with a square PNG, 512x512 or larger). It is used for the app icon.
- `logo-192.png`, `logo-512.png` – web icons (rebuilt automatically from `logo.png` when the APK is built)
- `.github/workflows/build-apk.yml` – builds the APK

## Get the APK
1. Replace `logo.png` with your real logo.
2. Upload everything to a GitHub repository (branch `main`).
3. Open the **Actions** tab. The "Build Android APK" workflow runs on every push (or press **Run workflow**).
4. When it finishes (about 5-8 minutes), open the run and download **Enican-Mines-APK** from *Artifacts*.
5. Unzip it and install `app-debug.apk` on the phone (allow "install unknown apps").

The backend (`Code.js` in Google Apps Script) is not part of this repository.
