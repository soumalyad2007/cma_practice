# CMA Inter Paper 5 (Business Laws & Ethics) — Android APK Project

This package contains the complete 1,937-question CMA Inter Paper 5 MCQ app (`app/src/main/assets/index.html`) wrapped inside a native Android WebView application (`com.rahul.cmalawmcq`) with `domStorageEnabled` so your **⭐ Important MCQs**, **Mistake Vault**, and **Personal Revision Notes** persist offline on your phone.

## Fastest Way to Use on Your Android Phone (Zero Build Needed)
1. Copy `app/src/main/assets/index.html` (or the standalone `cma_inter_law_mcq_hub.html`) to your phone.
2. Open it in **Google Chrome** on Android.
3. Tap **⋮ (Menu) → Add to Home screen**. It launches full-screen like a native app!

## How to Compile the Installable `.apk` File
- **Option A (Free Cloud Build via GitHub Actions):** Upload this project folder to a GitHub repository. The included `.github/workflows/build-apk.yml` workflow automatically runs Android SDK + Gradle and gives you the ready-to-install `app-debug.apk` under the **Actions** tab.
- **Option B (Local Android Studio / CLI):** Open this folder in Android Studio (or run `gradle assembleDebug`) to output `app/build/outputs/apk/debug/app-debug.apk`.
