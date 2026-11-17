# WorkAtmo AI releases

Public installers for [WorkAtmo AI](https://bot.workatmo.in). This repository holds binaries only; the source is private in [workatmo/workatmobot](https://github.com/workatmo/workatmobot) (Apache-2.0).

Published under **Releases**:

- **Android:** `WorkAtmo-<version>.apk`
- **Windows:** `WorkAtmo-Setup-<version>.exe`, plus `latest.yml` and the `.exe.blockmap` that the desktop app uses to update itself
- **Linux:** `latest-linux.yml` and the AppImage, when that build is included
- **version.json:** Android version metadata (`version`, `versionCode`, `apkUrl`, `apkSha256`)

The Android app and the Windows desktop app check this repository for updates. No GitHub login is required to download.

## Warnings

- Windows builds are currently **unsigned**. SmartScreen may show "Windows protected your PC". Use **More info** → **Run anyway** if you trust the download.
- Android requires **Install unknown apps** (or "Install from this source") for WorkAtmo, because these APKs are not from Google Play.

macOS and iOS builds will be added once developer accounts are available.
