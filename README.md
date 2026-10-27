# Elato Kitchen (Android)
WebView wrapper for https://adminpanel.elato.in/kitchen

## Get the APK (no Android Studio needed)
1. Create a new GitHub repo and upload everything in this folder (keep the .github folder).
2. Open the repo > Actions > "Build APK" > Run workflow (it also runs on every push).
3. When it finishes (~3 min), download the `elato-kitchen-apk` artifact, unzip it, and install the .apk on your phone.

## Or build locally
Install Android Studio, open this folder, then Build > Build APK(s).

## Customize
- URL: START_URL / HOST in app/src/main/java/com/elato/kitchen/MainActivity.java
- Name: app/src/main/res/values/strings.xml
- Icon: app/src/main/res/drawable/ic_fg.xml and values/colors.xml
