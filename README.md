# COCO STUDY OS — Android Studio Project

This project wraps the COCO STUDY OS HTML application in an Android WebView.

## Included
- Offline bundled HTML in `app/src/main/assets/index.html`
- Kotlin WebView host
- WebViewAssetLoader
- JavaScript + DOM storage
- Android back-button handling
- Portrait phone layout
- Your uploaded COCO STUDY OS logo
- Adaptive Android launcher icon
- Android 12+ splash icon configuration

## Open in Android Studio
1. Extract the ZIP.
2. Android Studio → Open.
3. Select the outer `coco_android_project` folder.
4. Wait for Gradle Sync.
5. Enable USB debugging on your Android phone.
6. Press Run ▶.

## Logo files
- `app/src/main/res/drawable/coco_logo.png` = complete uploaded logo for branding/splash use.
- `app/src/main/res/drawable/coco_launcher_foreground.png` = emblem-focused foreground designed for the small launcher icon.
- `app/src/main/res/mipmap-anydpi-v26/ic_launcher.xml` = adaptive launcher icon.
- `app/src/main/res/values/strings.xml` = icon background color.

## Important
The HTML application is intentionally kept as the main application layer. Test all existing modules on a real phone before adding native Android features such as notifications, widgets, backup, or sharing.
