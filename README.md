# Åss nye app - 2025/2026

Dette er Åss sin nye app.

les wiki til flutter: [online documentation](https://docs.flutter.dev/)

### instruks dev: 

det er litt krongelete å komme igang, men etter det er det realtivt straight forward. Start med å laste ned flutter. 

Her har du to valg, last ned flutter extensionen i vs code, hvis det ikke fungere følge wiki til flutter: [install documentation](https://docs.flutter.dev/install)

når dette er gjort sjekk om chrome dev funker først. bruk control, shift og p til å få opp meny og deretter skriv flutter: select device -> velg chrome.

om dette fungerer kan du gå videre. 

for dev på telefon har du 2 valg, har du apple pc, kan du følge oppskriften for ios dev: [ios](https://docs.flutter.dev/platform-integration/ios/setup)

hvis du har windows/linux kan man IKKE teste med iphone, følg derfor denne oppskriften for android dev : [adnroid](https://docs.flutter.dev/platform-integration/android/setup)

# viktig:

- ikke programer kjapt, dette kan vare mange år. gjør det sikkelig.

## Development Commands

### Setup and Dependencies
```bash
# Install dependencies
flutter pub get

# Check Flutter installation and connected devices
flutter doctor

# List available devices
flutter devices
```

### Development and Testing
```bash
# Run app on Chrome (recommended for initial development)
flutter run -d chrome

# Run on specific device
flutter run -d <device_id>

# Run with hot reload enabled (default)
flutter run

# Run tests
flutter test

# Run specific test file
flutter test test/widget_test.dart

# Run widget tests only
flutter test test/

# Run tests with coverage
flutter test --coverage
```

### Code Quality and Analysis
```bash
# Analyze code (lint checking)
flutter analyze

# Format code
dart format .

# Format specific file
dart format lib/main.dart
```

### Building
```bash
# Build for iOS testing (macOS only)
flutter build ios

# Build for Android testing
flutter build apk

# Build for mobile testing (both)
flutter build apk && flutter build ios

# Build for Play Store (.aab) & App Store (.ipa)
flutter build appbundle && flutter build ipa
```
