# Aruthalpuram LM Church App

Android app (Kotlin + Jetpack Compose) for church member management.

## Build the APK

The APK is built automatically by GitHub Actions on every push to `main`.

1. Open the **Actions** tab of this repository.
2. Click the latest **Build Android APK** run.
3. Download `app-debug` from **Artifacts** and unzip it to get `app-debug.apk`.

## Notes

- `design/index.html` is only a visual mockup of the screen, not part of the app build.
- The numbers on the home screen are placeholder data.
- Change `com.yourname` to your own package name in `app/build.gradle.kts` and move the `MainActivity.kt` folder to match.
