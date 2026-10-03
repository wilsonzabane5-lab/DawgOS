# DawgOS APK build

This project is configured to build a real Android APK with GitHub Actions.

1. Create a GitHub repository and upload the contents of this folder (not the ZIP itself).
2. Open the repository's **Actions** tab.
3. Run **Build DawgOS APK** (or push to `main`).
4. Open the completed run and download the **DawgOS-debug-apk** artifact.
5. Extract the artifact and install `app-debug.apk` on Android.

The build uses Gradle 8.7, Android Gradle Plugin 8.5.2, Java 17 and Android SDK 35.
