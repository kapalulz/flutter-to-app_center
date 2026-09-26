# Flutter Platform Channels Sample

A Flutter application demonstrating communication between Dart and platform-specific code.

## Demonstrations

- `MethodChannel` for invoking platform methods
- `EventChannel` for receiving event streams
- `BasicMessageChannel` for structured message exchange
- Platform-provided image handling
- A small pet list workflow built on platform messaging

## Requirements

- Flutter SDK compatible with Dart `>=2.17.0 <3.0.0`
- Android Studio or Xcode for device-specific builds
- An emulator, simulator, or physical device

## Run

```bash
flutter pub get
flutter analyze
flutter test
flutter run
```

## Structure

```text
.
├── lib/        # Dart UI and channel examples
├── android/    # Android platform implementation
├── ios/        # iOS platform implementation
├── assets/     # Sample assets
└── test/       # Flutter tests
```

## CI/CD note

The repository name reflects an earlier App Center pipeline experiment. This snapshot contains the Flutter sample application; deployment credentials and a complete App Center pipeline are intentionally not stored here.
