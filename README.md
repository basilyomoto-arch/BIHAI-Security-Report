# BIHAI Security Report - Android APK Builder

This project packages the existing BIHAI Security Report Portal inside an Android WebView.

## IMPORTANT
The original portal file is preserved as:

app/src/main/assets/index.html

It was copied directly from the original BIHAI_Security_Report_Portal.html file.

## EASIEST PHONE-ONLY METHOD: GITHUB ACTIONS

1. Create a GitHub account if you do not already have one.
2. Create a new empty repository.
3. Upload ALL contents of this project to that repository.
   Do NOT open or tap build.gradle.
4. Make sure the uploaded files include the `.github/workflows/build-apk.yml` file.
5. Open the repository's Actions tab.
6. Open "Build BIHAI Security Report APK".
7. Press "Run workflow".
8. Wait for the build to finish successfully.
9. Open the completed workflow run.
10. Download the artifact named `BIHAI_Security_Report_APK`.
11. Extract the downloaded artifact ZIP.
12. Install `BIHAI_Security_Report.apk`.

The APK is a debug APK signed automatically for installation/testing. It can be installed on Android phones, but it is not intended for Google Play Store publication.

## FEATURES INCLUDED
- Existing BIHAI portal preserved
- JavaScript enabled
- LocalStorage / DOM storage enabled
- File selection
- Multiple file/image selection
- Camera option for image inputs
- Android back button support
- Full-screen app interface

## IF INSTALLATION IS BLOCKED
Android may ask you to allow the browser or file manager to install unknown apps.
Allow that permission only for the app you are using to install this APK.
