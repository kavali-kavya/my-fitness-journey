MY FITNESS JOURNEY — ANDROID PWA

Files:
- index.html: complete workout tracker
- manifest.json: installable app settings
- service-worker.js: offline app shell
- icon-192.png and icon-512.png: app icons

FASTEST PHONE SETUP:
1. Upload these files to a free static host that supports HTTPS, such as GitHub Pages.
2. Open the hosted URL in Chrome on Android.
3. Use Chrome menu > Install app or Add to Home screen.
4. Open the app from your home screen.

Data:
Workout progress is stored locally in the browser/app on your phone.
Use Settings > Download backup occasionally.
If you clear browser data or uninstall the app, local data may be lost unless backed up.

This is a PWA package, not a native APK. Hosting is needed for the first install and service-worker offline caching.
