# Android Calculator

A native Android calculator with a custom interface, expression parsing, input validation, and adaptive result sizing.

## Features

- Addition, subtraction, multiplication, and division
- Decimal and parenthesized expressions
- Prevention of consecutive operators
- Clear-all and single-character deletion controls
- Automatic result text resizing
- Error handling for invalid expressions

## Technology

- Java
- Android SDK
- XML layouts
- View Binding-compatible Gradle project structure
- exp4j expression evaluation

## Run locally

1. Clone the repository and open it in Android Studio.
2. Allow Gradle to synchronize dependencies.
3. Run the app on an Android emulator or physical device.

```bash
git clone https://github.com/danielTongu/Calculator-Android-App.git
cd Calculator-Android-App
./gradlew assembleDebug
```

The debug APK is produced under `app/build/outputs/apk/debug/`.
