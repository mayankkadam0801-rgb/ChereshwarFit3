# Chereshwar Fit – Android APK project

## Easiest: build online with GitHub (no installs)
1. Create a free GitHub account and a new empty repository.
2. Upload everything in this folder (keep the .github folder).
3. Open the Actions tab -> "Build APK" -> wait about 5 minutes.
4. Open the finished run -> Artifacts -> download ChereshwarFit-APK -> unzip -> app-debug.apk.
5. Copy it to your phone and install (allow "Install unknown apps" when asked).

## Or build on your PC
Needs Node 18+, JDK 17 and Android Studio.
    npm install
    npx cap add android
    npx cap sync android
    npx cap open android      # then Build > Build APK(s)

The app lives in www/index.html. Edit it, run `npx cap sync android`, rebuild.
