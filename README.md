# FdzLite Downloads

Public APK downloads for FdzLite, an Android phone and Android TV app with a simplified card interface and native playback controls.

## Download

[Download FdzLite 0.1.8 APK](https://github.com/uart-aplex/FdzLite-releases/releases/download/v0.1.8/FdzLite-0.1.8.apk)

[All releases](https://github.com/uart-aplex/FdzLite-releases/releases)

## Installation

Requires Android 6.0 or later and Android System WebView. Download the APK on your Android device and allow installation from the browser or file manager when prompted. This is a debug-signed sideload build, not a Google Play release. Install over an existing build signed with the same certificate to preserve application data.

## Version 0.1.8

- Episode completion offers Play next episode or Stop.
- Episode selection returns to the current or most recently opened episode.
- Unfinished episodes automatically resume from the saved position on supported players.
- Hold Left/Right on the playback timeline to seek faster: 10 seconds initially, 30 seconds after 1.5 seconds, and 60 seconds after 4 seconds. Release and press again to return to 10 seconds. Dedicated fast-forward/rewind keys use the same acceleration.
- Retains phone and TV browsing, native playback controls and 0.5x-2x speeds.
- Automated logic tests and Android TV integration tests using synthetic media state and key events passed.

Viewing history stays on each device, separately for each playback route. Clearing app data or uninstalling removes it. Resume and completion detection require a player that exposes media state; live streams are excluded.

Playback depends on the original website and media source availability. FdzLite does not host or download films and is not affiliated with the source website.

APK SHA-256: `A0E595262D75B7CB349123F7586786F3812B4600C47A0C632798089E47EC5DE7`

This repository contains download information and release binaries only. Application source code is maintained separately.
