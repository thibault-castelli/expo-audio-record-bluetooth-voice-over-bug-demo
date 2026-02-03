# Reproduction steps
- Get a physical Android device connected to a Bluetooth audio device, either earbuds or headphones.
- `npm install`
- Run the example using the Expo Go app (`npx expo start`).
- Open the app on the Android device. On startup, the app will set the audio mode for recording (see `setAudioModeAsync()` in `app/(tabs)/index.tsx`).
- Activate VoiceOver (screen reader) on the Android device.
- All the audio will come out of the device speaker instead of the Bluetooth audio device.
