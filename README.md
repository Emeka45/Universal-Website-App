# Universal Website App

Android app for the C. O. Eric website.

Website: https://emeka45-github-io.pages.dev/

## Current architecture
The app uses Android WebView to display the website as the primary experience. Website content can therefore be updated without rebuilding the Android app.

## Package
com.coeric.websiteapp

## Build

Debug APK builds are produced by GitHub Actions for testing.
Run:
gradle assembleDebug
gradle assembleRelease

The release build is currently unsigned. A production signing identity should be added through protected GitHub Actions secrets before store submission.
