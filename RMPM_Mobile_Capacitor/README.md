# RMPM Mobile App (Crossplay) — Capacitor wrapper

This project builds a phone app that opens your live game:

**https://play.amresidences.site**

## Why this matches your goal
- **Crossplay:** browser + phone play together (same Socket.io backend).
- **Easy updates:** update the website/server once; the app shows the same update immediately.

## Requirements
- Node.js 18+ (LTS)
- Android Studio (Android)
- Xcode (iOS, macOS only)

## Setup
```bash
cd RMPM_Mobile_Capacitor
npm install
```

## Android build
```bash
npx cap add android
npx cap sync android
npx cap open android
```
Build/Run from Android Studio.

## iOS build (macOS)
```bash
npx cap add ios
npx cap sync ios
npx cap open ios
```
Build/Run from Xcode.

## Notes
- The app loads the live URL from `capacitor.config.json`. Change it there if needed.
- For normal game UI/logic updates, you **do not** need to publish a new app version.
