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

Version 0.9.117-home-test (Android version code 133); requires Android 15 or later.
Package: com.cafeepos.androidlite.test
APK SHA-256: 5e000a9b9441bf7fe250dfe78fb7b105cd679e1ccc706f8132e1d2016e555be9
APK signer SHA-256: 7cc09cc3622266446cc794b7da18d3cb5bb907e53757c9ecb2feb1e5f932f75c

This approved forward release retains the existing .116 Android connection, background-service, Back-button and retry repairs, plus the original menu, trading and printing functionality. It supports the exact original 132/0.9.116 and 133/0.9.117 rolling pair. Both actual devices remain .116 at the last verification; hands-off installation/reopening/preservation/reconnection of this forward version is PENDING. Downloads or software checks alone are not a completed update. Keep both charging on the same working local Wi-Fi with EPOS open. Locked, stopped, busy or uncertain operations safely postpone installation. No lock bypass, remote click or ASUS/VPN installation is used. Existing Install now remains a separate deliberate owner option with the same safety gates. This is not a general installer for unapproved devices.

Only explicitly promoted releases are published here. A source-code checkpoint is not automatically an approved update. There is no monthly hosting subscription introduced by this setup; ordinary internet/data costs can still apply. Local recovery copies are not off-device backups or proven replacement-tablet recovery.
