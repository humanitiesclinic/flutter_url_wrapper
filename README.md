# Flutter URL Wrapper

A minimal Flutter app that wraps https://everythinginperspective.vercel.app/ in a native WebView.

## Setup

1. **Install Flutter** (if not already installed):
   ```bash
   brew install flutter
   ```

2. **Get dependencies**:
   ```bash
   flutter pub get
   ```

## Build

### macOS
```bash
flutter build macos
```
App will be in `build/macos/Build/Products/Release/flutter_url_wrapper.app`

### iOS
```bash
flutter build ios
```
Requires Xcode, Apple Developer account, and provisioning profiles.

### Android
```bash
flutter build apk
```
or for Google Play:
```bash
flutter build appbundle
```

## Run (Dev)

```bash
flutter run
```

## Features

- ✅ All links work correctly (navigation maintained within WebView)
- ✅ JavaScript enabled
- ✅ Loading indicator
- ✅ Error handling
- ✅ Cross-platform (iOS, Android, macOS)
