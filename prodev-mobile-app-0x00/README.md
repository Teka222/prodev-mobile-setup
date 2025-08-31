cat > ../README.md <<'EOF'
# prodev-mobile-app-0x00

## Scaffolding Steps
1. `npx create-expo-app@latest app-example` → chose **Tabs (TypeScript)** (Expo Router).
2. Ran `npx expo start --tunnel` and opened in Expo Go.
3. Edited `app-example/app/(tabs)/index.tsx` → changed **Welcome!** to `** First App Created**`.
4. Added `app-example/constants/Colors.tsx` as required.

## What `npm run reset-project` did
- Removed demo routes/components/assets from the tabs template.
- Left a minimal app structure ready to customize.
- After reset, I restarted with `npx expo start --tunnel` and verified it still loads.

## Notes
- Device used:
- Tunnel notes:
EOF

# Commit Task 1
cd ..
git add README.md app-example/app/(tabs)/index.tsx app-example/constants/Colors.tsx
git commit -m "Task 1: Scaffold router app, edit Welcome text, add Colors.tsx, document reset"
git push
