# ai-samples

# Android Hello World

This is a simple "Hello, World!" application for Android.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Android SDK (can be installed via Android Studio)

## How to Build

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```
2.  Ensure you have an Android device connected or an emulator running.
3.  Build the application using Gradle:
    ```bash
    ./gradlew assembleDebug
    ```
    The APK will be located in `app/build/outputs/apk/debug/app-debug.apk`.

## How to Install and Run

You can install the APK on a connected device or emulator using ADB:

```bash
adb install app/build/outputs/apk/debug/app-debug.apk
```

Alternatively, you can build and run directly from Android Studio.