# SwipeRise

Android photo review and staging app. Review your photo library one card at a time: swipe left to stage, right to keep, or up to archive to Photos in the Play build.

- **F-Droid flavor (offline):** works offline. Its manifest does not declare `android.permission.INTERNET`.
- **Play flavor:** offers optional Google backup (Google Drive / Google Photos).

Per the v5.0.0 release notes, cleanup is unlocked: Android Trash is always available (30-day recovery), and permanent delete only happens when every file has a verified backup. Backups can go to Google Photos, Google Drive, or any folder / cloud app from Android's file picker.

## Download

**Latest version: v5.0.0** · [Always get the newest release](https://github.com/grloper/SwipeRise-releases/releases/latest) · [All releases](https://github.com/grloper/SwipeRise-releases/releases)

| File | What it is |
|------|------------|
| [`SwipeRise-5.0.0-fdroid-offline.apk`](https://github.com/grloper/SwipeRise-releases/releases/download/v5.0.0/SwipeRise-5.0.0-fdroid-offline.apk) | Offline F-Droid flavor. SHA-256 `b6d9ce8299269494b153eccb24c3813b78b8f77084fc0f179512c602e69ea344` |
| [`SwipeRise-5.0.0-play-google-backup.apk`](https://github.com/grloper/SwipeRise-releases/releases/download/v5.0.0/SwipeRise-5.0.0-play-google-backup.apk) | Play flavor with optional Google backup. SHA-256 `92875588d7a8d46413e965e84ca226fb04dfb01f3abb9fafa57899e860d4c775` |

Both APKs are debug-signed with the repo keystore (per the v5.0.0 release notes) and can be installed directly. They are not Play Store builds. If this table is behind, the [latest release](https://github.com/grloper/SwipeRise-releases/releases/latest) page is authoritative.

## Install

1. Download an `.apk` from the latest release on your Android device.
2. Open it and allow installing from unknown sources if prompted.
3. Grant media access on first launch.

Requires Android 10 (API 29) or newer. Google sign-in in the Play flavor requires the owner's OAuth setup for the installed app's package and signing certificate.

## Privacy

See the [privacy policy](PRIVACY_POLICY.md). The Play flavor can send files to your own Google Drive / Google Photos only when you opt in; the F-Droid flavor requests no internet access.

## License

SwipeRise source code is licensed under the GNU General Public License v3.0. This repository only hosts release binaries and documentation; the source repository is not publicly linked here.

Older releases were published under the earlier name "SwipeDelete Zero" and are mirrored here under their original tags and notes.
