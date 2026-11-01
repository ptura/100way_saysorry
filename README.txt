# 100 Ways to Say Sorry — installable web app

## Install on iPhone
1. Put the contents of this folder on a secure HTTPS website (for example, GitHub Pages).
2. Open the website in **Safari** on the iPhone.
3. Tap **Share** → **Add to Home Screen** → **Add**.
4. Open the new “Say Sorry” icon from the Home Screen. It runs like an app and can work offline after its first successful load.

## Install on Android
Open the HTTPS website in Chrome and choose **Install app** or **Add to Home screen**.

## Important: native iPhone app
This package is an installable web app (PWA), not a signed Apple `.ipa`. A native App Store/TestFlight app requires an Apple Developer account and an iOS build/signing process in Xcode on a Mac. The same web experience can be wrapped in a native iOS project if you later want that route.

## Files
- `index.html` — complete wheel app
- `manifest.json` — install metadata
- `sw.js` — offline caching
- `icon-192.png`, `icon-512.png` — app icons
