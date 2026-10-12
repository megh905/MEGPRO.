# MEGPRO Android project

This project wraps your existing MEGPRO HTML app in an Android WebView so it can be installed as an Android app with a launcher icon.

## Build an APK using Android Studio
1. Install Android Studio on a computer.
2. Extract `MEGPRO-Android.zip`.
3. In Android Studio, choose **Open** and select the extracted `MEGPRO-Android` folder.
4. Let Gradle sync. Install Android SDK Platform 35 if Android Studio asks for it.
5. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. When the build finishes, select **locate**. The debug APK will be under `app/build/outputs/apk/debug/`.
7. Transfer the APK to your Android phone and install it. Android may ask you to allow installation from that source.

## Important
- App ID: `com.megpro.fitness`
- App name: `MEGPRO`
- The HTML app is bundled locally, so its main interface does not need internet.
- Browser local storage is used for app data. Clearing app storage or uninstalling the app can erase data; export a backup regularly.
- This is a project source package, not a precompiled APK. It must be built with Android Studio/Android SDK.
- Test file import, export, progress photos, and backup/restore on your phone before relying on them.
