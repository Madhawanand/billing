# Gift Shop Tools Android App

This Android Studio project wraps the two business HTML tools into one Android app.

## Screens

- Home page: choose a calculator.
- Gift Shop Price Tool: calculate selling prices, create secret codes, and decode purchase prices.
- Weight Price Calculator: calculate selling price from grams, or grams from selling price, using the rate per KG.

## Build

### Build with GitHub, no Android Studio needed

1. Create a free GitHub account if you do not already have one.
2. Create a new repository on GitHub.
3. Upload all files from this `GiftShopAndroid` folder into the repository.
4. Open the repository's **Actions** tab.
5. Click **Build Android APK**.
6. Click **Run workflow**.
7. Wait for the build to finish.
8. Open the finished workflow run and download the artifact named `GiftShopTools-debug-apk`.
9. Unzip the artifact to get `app-debug.apk`.
10. Copy `app-debug.apk` to your Android phone and install it.

Android may ask you to allow installing apps from unknown sources. Enable that only for the app you use to open the APK, such as Files or Chrome.

### Build with Android Studio

1. Open this folder in Android Studio: `GiftShopAndroid`.
2. Let Android Studio sync the Gradle project.
3. Click **Run** to test on a phone or emulator.
4. To create an APK, use **Build > Generate App Bundles or APKs > Generate APKs**.

The HTML files are stored in `app/src/main/assets`, so the app works offline.
