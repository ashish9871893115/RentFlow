# RentFlow Android app

Build the APK with no installs, using GitHub's free cloud build:

1. Create a free account at github.com and make a new repository (any name).
2. Upload ALL files from this folder, including the hidden .github folder (easiest from a computer).
3. Open the repository's Actions tab. The "Build APK" job starts by itself (about 5 minutes).
4. Open the finished run, download the "RentFlow-APK" file at the bottom, and unzip it to get app-debug.apk.
5. Send app-debug.apk to your Android phone, open it, and allow "Install unknown apps" when asked.

To change the app, edit www/index.html and upload it again; a new APK is built.
