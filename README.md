# Cafe EPOS approved Android updates

This separate repository contains approved Android app downloads, signed release information and public instructions only. It contains no cafe records, backups, private project source or signing keys.

## Automatic updates

Automatic updates are opt-in in the existing app. This channel is for the original supervised Cafe EPOS installation, not a public app-store release or commercial-readiness certificate. Initial setup and device-specific verification are required.

- Cafe EPOS checks the independently signed release information and the actual package, signing identity, version, file size, SHA-256 and declared compatibility.
- Approved files can download ahead of time. Installation waits for 02:00-04:00 Europe/London, charging, sufficient battery/storage, verified local recovery copy, idle original screens and compatible approved devices.
- Orders, payments, closing, printer transmissions or unresolved operations block installation. Drafts and original device identities remain preserved. No automatic uninstall, data clear, downgrade or rollback.
- A user-confirmation prompt, failed reopen or failed authenticated reconnection is a failed unattended result. Android restrictions or revoked permissions may require owner attention.
- The owner can pause future automatic updates in Back Office > Automatic updates. Ordinary local ordering does not depend on this repository or internet.

## Current approved demonstration release

Version 0.9.109-home-test (Android version code 125); requires Android 15 or later.
Package: com.cafeepos.androidlite.test
APK SHA-256: e344e1192a6b28151e31a57886756019dc90ee8de5626cd3f30708c8f16e81a3
APK signer SHA-256: 7cc09cc3622266446cc794b7da18d3cb5bb907e53757c9ecb2feb1e5f932f75c

This release adds the owner-requested Scrambled egg shortcut to the original swap picker, preserving existing explicit rules and uncharged custom-swap behaviour. Tablet/phone checks pass against a private isolated full saved menu copy; no cafe data is in the download. Physical installation of this release is pending. The original tablets have received a checked correction: an unchanged saved menu-editor copy no longer blocks an idle update. Edited or stale menu drafts and unfinished price inputs still postpone installation. Complete hands-off installation/reopening/reconnection on both real tablets remains pending; software checks alone do not prove it. This is not a general installer for unapproved devices.

Only explicitly promoted releases are published here. A source-code checkpoint is not automatically an approved update. There is no monthly hosting subscription introduced by this setup; ordinary internet/data costs can still apply. Local recovery copies are not off-device backups or proven replacement-tablet recovery.
