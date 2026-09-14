# Raja International Travel — Android APK

Private Android ticket and ledger app for Raja International Travel.

## Build APK on GitHub

1. Upload all project files to your GitHub repository.
2. Keep `.github/workflows/build-apk.yml` in the repository.
3. Open **Actions** on GitHub.
4. Select **Build Raja International Travel APK**.
5. Tap **Run workflow** (or push to `main`/`master`).
6. Wait for the build to finish.
7. Open the completed workflow run and find **Artifacts**.
8. Download **Raja-International-Travel-debug-APK**.
9. Extract it and install `app-debug.apk` on your Android phone.

The workflow uses Java 17 and Gradle 8.9.
APK output: `app/build/outputs/apk/debug/app-debug.apk`
