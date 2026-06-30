# Bookmote — APK Releases

Sideload APKs for **Bookmote**: use your Android phone as a Bluetooth remote to turn
pages on your e-reader (BOOX, recent Bluetooth Kobo, and other readers that accept a
Bluetooth keyboard).

This repository hosts **only the installable APK** for each release. The app source
is closed; this is just a public download mirror so you can sideload on devices
without the Play Store (e.g. de-Googled Android).

> The "Source code (zip/tar.gz)" links that GitHub auto-adds to each release contain
> only this README — not the app source. To install, download the `.apk` asset.

## Install

1. Open [Releases](../../releases) and download the latest `Bookmote-vX.Y.Z.apk`.
2. On your Android phone, allow installing from unknown sources.
3. Open the downloaded APK to install.

No Google Play Services required — the core app has no Google/GMS dependencies.
(The optional voice-command feature uses Android's on-device speech recognizer, which
may be missing on fully de-Googled devices; everything else is fully local.)

## Updates

Sideloaded builds **do not auto-update from the Play Store** — the APK here is signed
with a different key than the Play Store copy, so Play won't update it. To get a new
version, download the latest APK from [Releases](../../releases) and install over the
old one (your settings are kept). Tip: press **Watch → Custom → Releases** on this
repo to get notified of new versions.

## Easier option

If your device has the Play Store, installing from there is simpler and gives
automatic updates — just search **Bookmote**.
