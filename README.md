# Reproduction steps
- `npm install`
- `npx expo start`
- Connect a Bluetooth headset to an Android device.
- Open the app using the Expo Go app on an Android device. On startup, the app will set the audio mode for recording (see `setAudioModeAsync()` in `app/(tabs)/index.tsx`).
- Activate VoiceOver (screen reader).
- All the audio will come out of the device speaker instead of the Bluetooth headset.
