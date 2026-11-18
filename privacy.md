---
title: Privacy Policy - MVPro Simple Emulator
---

# Privacy Policy - MVPro Simple Emulator

Last updated: 17 November 2026

MVPro Simple Emulator ("the app") is a free Windows tool that helps you set up and manage Android emulators. It is made by Novan ("I", "me").

## Short version

The app does not collect, store on a server, sell, or share any personal data. It has no accounts, no analytics, no advertising, and no tracking. Everything the app saves stays on your own computer.

## What the app saves on your computer

The app stores these files locally, in `%LocalAppData%\MVPro` (or the private folder of the Microsoft Store package):

- `settings.json`: your settings (SDK folder, Java folder, default RAM/CPU for new emulators).
- `emulators.json`: the list of emulator folders you created or imported. A copy is also kept next to your Android SDK folder (for example `C:\adb`).
- `logs\mvpro.log`: a log of what the app did. The Windows user name is replaced by `%USERPROFILE%` in the log.

This data never leaves your computer unless you choose to send it yourself (for example by sharing the log file when asking for help). You can delete these files at any time.

## Network connections

The app connects to the internet only when you ask it to set something up, to download software you need:

- **Google (`dl.google.com`)**: Android command-line tools, the Android Emulator, platform-tools, and system images. This software is provided by Google and covered by the Android Software Development Kit License Agreement (https://developer.android.com/studio/terms). The app asks you to accept it before the first download.
- **Eclipse Adoptium (`api.adoptium.net` and its download hosts)**: a portable Java (JDK 17), only if Java is not already installed on your computer.

Those servers can see your IP address and the files you request, as with any download. I do not receive that information. Please see the privacy policies of Google and Eclipse Adoptium for how they handle it.

The Android emulators you run are separate virtual devices. What you do inside them (for example signing in to a Google account in an image that includes Google Play) is between you and the apps or services you use there. The app does not see it.

## Children

The app is not directed at children and does not knowingly collect any information from anyone.

## Changes

If this policy changes, the new version will be posted on this page with a new date.

## Contact

Questions or requests: please open an issue at https://github.com/novanandriyono/mvpro-emulator/issues

## Trademarks

Android is a trademark of Google LLC. MVPro Simple Emulator is an independent tool and is not affiliated with or endorsed by Google.
