# OpenNutriTracker – custom macro goals build

An Android build of [OpenNutriTracker](https://github.com/simonoppowa/OpenNutriTracker)
with one addition: **Settings → Goals → Custom macro goals**, where you enter your
own daily grams of carbs, fat and protein instead of having them calculated.

## Install

1. On your Android phone, download
   **[OpenNutriTracker-custom-macros-arm64.apk](https://github.com/Hiamf0/ont-custom-build/raw/main/OpenNutriTracker-custom-macros-arm64.apk)**.
2. Open the downloaded file. If asked, allow your browser to install unknown apps.
3. Tap **Install**. The app appears as **ONT Develop** and can sit alongside the
   official OpenNutriTracker app.

## Notes

- Based on upstream commit `1ab4940` (version 2.5.0), 64-bit Android (arm64), Android 8.0+.
- Searches of the upstream project's own food database (Supabase) are not available
  in this build; Open Food Facts search and barcode scanning are.
- Crash reporting is disabled.

## Source and license

OpenNutriTracker is licensed under the GNU GPL v3.0 (see [LICENSE](LICENSE)).
This build is upstream commit
[`1ab4940`](https://github.com/simonoppowa/OpenNutriTracker/tree/1ab4940)
with [`custom-macro-goals.patch`](custom-macro-goals.patch) applied
(`git apply custom-macro-goals.patch`).
