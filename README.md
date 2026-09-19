# PetKit

PetKit is a native Android-first pet medication tracker built with React Native + Expo.

## What changed

The project was rebuilt from the browser/PWA implementation into a native mobile application. There is no Vite entry point and no `index.html`.

## V1

- Multiple pet profiles
- Medication schedules with exact times
- Today dashboard: NOW, UPCOMING, COMPLETED
- One-tap dose recording
- Medication history
- Edit/delete medications and pets
- Persistent on-device storage with AsyncStorage
- Android local notification permission and scheduled daily reminders
- Offline-first operation
- Reserved advertisement component
- Veterinary safety boundary

## Run

```bash
npm install
npx expo start
```

For Android:

```bash
npx expo start --android
```

For a distributable Android build, use Expo/EAS when ready.

PetKit records owner-entered veterinary instructions. It does not diagnose, prescribe, recommend doses, or replace veterinary care.
