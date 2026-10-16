# Simple Calculator for Android

A small offline Android WebView app wrapping the included calculator interface.

## Build an APK with Android Studio
1. Open this project folder in Android Studio.
2. Allow Gradle sync to finish.
3. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
4. The debug APK is normally at `app/build/outputs/apk/debug/app-debug.apk`.

## Build an APK with GitHub Actions (no Android Studio required on your phone)
1. Create a GitHub repository and upload the contents of this project.
2. Open the repository's **Actions** tab.
3. Select **Build Android APK** and press **Run workflow** (or push to `main`).
4. Open the completed workflow run, find **Artifacts**, and download `SimpleCalculator-debug-apk`.
5. Extract the ZIP on your Android phone and tap `app-debug.apk` to install. Android may ask you to allow installs from that source.

This workflow creates a debug APK for personal testing. A release-ready, signed APK requires a private signing key.
