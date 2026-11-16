<img src="icon.png" width="96" height="96" alt="">

# Iqal Blocker for Android

Blocks distracting apps and websites on your phone, with locks that really
cannot be undone until they end: a time lock, a password lock, a lock until a
date, a lock while you are at a place, and more. Adult content can be blocked
with one switch.

This repository only holds the download. Get the APK from the
[Releases page](../../releases/latest).

- Needs **Android 11 or newer**.
- Free, no account, no ads, no tracking. See the [privacy policy](privacy-policy.md).
- English and Arabic.
- Version 0.3.0: tested on Android 17.

## Install

1. On your phone, open the [latest release](../../releases/latest) and tap
   **`iqal-blocker-<version>.apk`** to download it.
2. Open the downloaded file. Android asks to allow installs from your browser
   (or Files app): tap **Settings**, switch on **Allow from this source**, go back.
3. Tap **Install**. If Google Play Protect warns that the app is unknown, tap
   **More details → Install anyway**. (It warns about every app that does not
   come from the Play Store.)

To update later, install the new APK the same way: it installs over the old one
and keeps your blocks.

## Setup ("Full lock", done once)

To make locks impossible to undo, Iqal becomes the phone's **manager** (Android
calls it "device owner"). Android only allows this on a phone with
**no accounts and only one user**, so:

1. **Remove every account** (Google, work, email…) in
   *Settings → Passwords, passkeys & accounts*. Your data in the cloud is not
   deleted; you add the accounts back right after.
2. **Remove extra users** in *Settings → System → Users*, and switch off
   Parental controls if they are on (they add a hidden "Supervising" user).
3. Open Iqal. Its guide takes you through the rest, one step at a time
   (tap **How?** on a step for its instructions):
   - allow notifications and "find devices on the local network";
   - make Developer options appear (*Settings → About phone*, tap
     **Build number** seven times), connect to Wi-Fi, and switch on
     **Wireless debugging** in *Settings → System → Developer options*;
   - tap **Start pairing**, then tap the words *Wireless debugging*,
     choose **Pair device with pairing code**, pull down the notifications and
     type the six-digit code into the Iqal notification.
4. When Iqal says it is the manager, add your accounts back.

If something goes wrong, Iqal explains why in plain words. Under
**Other ways to set up** it also shows a one-line computer command.

## Good to know

- **A lock means it.** While a lock runs you cannot weaken or delete the block,
  switch off Iqal, or uninstall it. Start with a short time lock to try it.
- **Getting out:** when no lock is running, open Iqal's **Settings** (the gear
  at the top) and tap **Stop being the manager** at the bottom. After that Iqal
  can be uninstalled like any other app.
- Websites are blocked in **Chrome**. Other browsers are switched off while a
  block is on.

## Check the download (optional)

Signing certificate SHA-256:
`DE:E7:EB:87:8E:40:78:2D:6D:C5:1E:C4:7B:45:84:AC:28:A2:A3:10:78:3D:73:70:65:2A:A7:CC:4B:FA:D6:43`

Iqal for Windows and Linux is a separate program.
