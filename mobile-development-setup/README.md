cat > mobile-development-setup/README.md <<'EOF'
# Mobile Development Environment — Expo Go Setup

## Prerequisites
- Node.js LTS installed (local or Codespaces image)
- VS Code (or GitHub Codespaces)
- macOS / Linux / Windows
- Physical device with **Expo Go** installed (Android or iOS)

## Why Expo Go?
Running on a real device avoids heavy local emulators and works reliably across many phone models.

## Install Expo Go on your phone
1. Open https://expo.dev/go
2. Install:
   - **Android**: Google Play → “Expo Go”
   - **iOS**: App Store → “Expo Go”
3. Open the app and sign in / create an Expo account.

## Using Expo from Codespaces
- Start your app with: `npx expo start --tunnel`
- Scan the QR from the **terminal** (Android: Expo Go app; iOS: Camera app).

## Notes & Challenges (fill this in)
- What device you used:
- Any sign-in issues:
- Tunnel/QR notes:
- Fixes/workarounds you tried:

EOF

git add mobile-development-setup/README.md
git commit -m "Task 0: Add Expo Go setup README"
git push
