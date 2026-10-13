# REVÉ Culinary Android

This repository wraps the supplied REVÉ HTML app in an Android WebView. GitHub Actions builds a debug APK; Android Studio is not required.

## Build the APK on GitHub

1. Create a new GitHub repository named `ReveCulinaryAndroid`.
2. Upload the contents of this ZIP, keeping the `.github/workflows/build.yml` path intact.
3. Commit the files to the `main` branch.
4. Open the repository's **Actions** tab and open the latest **Build Android APK** run.
5. When it succeeds, download `reve-culinary-debug-apk` from the **Artifacts** section and extract the ZIP to get `app-debug.apk`.
6. Transfer the APK to your Android phone and install it. Android may ask you to allow installation from that source.

The generated APK is a debug build for testing, not a Play Store release. The app loads the HTML bundled at `app/src/main/assets/index.html`.
