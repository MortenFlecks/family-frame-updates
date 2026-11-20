# Family Frame downloads

[Download the latest installer](https://github.com/MortenFlecks/family-frame-updates/releases/latest), then tap the FamilyFrame APK asset. Android 8.0 or newer, including Android 12.

## Install and update

Open the downloaded APK and confirm installation in Android. If asked, allow installation from the browser or file app you used.

Family Frame checks for updates daily while open. Tap **App updates**, then **Open download page**. Your browser opens the new version on GitHub. Download its APK, open it and confirm **Update**. Keep the existing app installed to retain saved albums, settings and cached photos. Reopen Family Frame afterwards if needed.

Family Frame itself has no permission to install apps. Version 0.4.3 passed Play Protect scanning and normal installation on the Android 17 test emulator, with settings and cached photo bytes retained. Please use 0.4.3 or newer; earlier test builds 0.4.1 and 0.4.2 are superseded.

## One-time migration from the original prototype

Its original signing key was lost during a Windows reinstall. If you still have that old prototype, uninstall it once before installing a permanently signed release, then enter your album again. This resets local settings and cached previews; Google Photos originals are unaffected. Later releases signed with the permanent key update in place.

## Privacy

This public repository contains software installers, release notes and latest.json update metadata only. No photos, album links, accounts or signing keys are stored here. The source code is backed up separately in a private repository. Photos download directly from Google to the frame; software checks send no photo or album data to GitHub.
