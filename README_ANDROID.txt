NEXUS MOBILE — ANDROID PWA PACKAGE
==================================
This package is an installable Progressive Web App (PWA), not an APK. A genuine APK needs an Android build toolchain/signing step; this environment does not have Android SDK/Gradle installed to compile and verify one.

WORKING FEATURES INCLUDED
- Mobile-first dashboard/navigation
- Local task list with complete/delete
- Local notes with export
- NEXUS local command assistant (no cloud AI required)
- Optional speech input/output when supported by the Android browser and permissions
- Website Studio with HTML preview and export
- App Studio with preview and export
- Click game with score and saved score projects
- Project save/open/delete and JSON backup import/export
- Offline caching after first load when installed from HTTPS

IMPORTANT LIMITS
- The included functions work on the phone in its browser/PWA.
- Windows PC controls (Windows app launching, Windows file browsing, CPU/process control, startup settings) do NOT run on Android.
- AI replies are local command responses; Gemini/cloud AI is not connected in this mobile package.
- Browser storage is local to that browser profile. Export backups before clearing browser data or switching devices.
- PWA installation requires the files to be served over HTTPS (or localhost for development). Opening index.html directly from a file manager is not sufficient for full PWA installation/offline caching.

INSTALL ON ANDROID
1. Host the contents of this folder on an HTTPS static host you control (for example GitHub Pages), or serve it from a trusted HTTPS server.
2. Open the resulting HTTPS URL in Google Chrome on Android.
3. Open ⋮ menu and choose “Install app” or “Add to Home screen”.
4. Launch NEXUS from the new home-screen icon.
5. Open it once while online so offline caching can be installed.

This package is not the full desktop NEXUS backend and does not need run_nexus.bat.
