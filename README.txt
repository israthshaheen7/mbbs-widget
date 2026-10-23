MBBS Countdown widget (Android)

Build free with GitHub (no Android Studio):
1. Make a free account at github.com and create a new repository (any name, Public or Private).
2. Upload ALL files and folders of this project into the repository (including the hidden .github folder).
3. Open the Actions tab -> "Build APK" -> wait about 3-5 minutes for the green tick.
4. Open the finished run -> Artifacts -> download MBBS-Countdown-APK (a zip) -> unzip -> app-debug.apk.
5. Copy the APK to your phone, tap it, allow "Install unknown apps" for your file manager or browser, install.
6. Home screen: long-press empty space -> Widgets -> MBBS Countdown -> drag it out.

Change the date: app/src/main/java/com/opulent/mbbscountdown/CountdownWidget.java -> target()
Change the website link: SITE in the same file.
Change the text/language: app/src/main/res/values/strings.xml
