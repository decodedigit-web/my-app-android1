# My App — Website to Android APK

This Android WebView project opens your hosted website in a full-screen Android app.

Website configured: https://misty-field-dd18.decodedigit.workers.dev/
App label: My App

## Build the APK using your Android phone
1. Download and extract this ZIP on your phone.
2. In your mobile browser, sign in to GitHub and create a repository named `my-app-android`.
3. Upload all extracted files and folders into the repository, preserving folder paths. Include the hidden `.github/workflows/build-apk.yml` file. If needed, use Chrome's **Desktop site** mode.
4. Ensure the repository's default branch is `main`.
5. Open the repository's **Actions** tab and enable GitHub Actions if asked.
6. Select **Build My App APK** and tap **Run workflow**, or wait for the workflow triggered by your upload.
7. Open the completed workflow run and download the `My-App-debug-APK` artifact.
8. Extract that downloaded artifact ZIP and tap `app-debug.apk` to install. Android may ask you to allow your browser or file manager to install unknown apps.

## Notes
- This produces a debug APK for personal testing, not a Google Play release build.
- Internet is required to load the website. This wrapper does not add offline support.
- Only package websites you own or are authorized to distribute.
