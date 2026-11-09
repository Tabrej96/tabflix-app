# TabFlix for Android

Official public release channel for the TabFlix Android app.

- **Download the latest APK:** [TabFlix.apk](https://github.com/Tabrej96/tabflix-app/releases/latest/download/TabFlix.apk)
- **All releases:** [GitHub Releases](https://github.com/Tabrej96/tabflix-app/releases)
- **Website:** https://tabflix.online

## Install

1. Download `TabFlix.apk`.
2. Allow installs from this source if Android asks.
3. Open TabFlix.

Requires Android 7.0 (API 24) or newer.

## Features

- Movies, TV series, anime, live TV, reels and TFX Theatre watch parties.
- All UI assets are bundled in the APK, so navigation is instant; content and APIs load from TabFlix cloud services.
- In-app TFX Downloads library with live progress, pause/resume/cancel/delete, audio and subtitle choices, and companion audio for split-audio HLS streams.
- Track-aware offline player with audio/subtitle selection, volume and synced companion audio.
- YouTube-style floating mini player and native Picture-in-Picture outside the app.
- Live TV guide with TVMaze What to watch, current/next programme banners, channel details and a minimizable player that keeps playing while you browse.
- Reels feed includes live TV channel slides with direct Live TV links.
- 3D TFX Theatre with host-shared stream playback, chat, reactions, host controls, room regeneration and guest moderation.
- Automatic update checks every 15 minutes and on resume; the app downloads and verifies the signed APK and opens Android's installer. Updates install in place and keep app data.

## Releases and updates

`latest.json` is the update manifest consumed by the app. It contains the current `versionCode`, `versionName`, APK URL, SHA-256 and release notes.

The release APK is signed with the TabFlix release certificate. Updating from a debug-signed build requires uninstalling the old build first. Official builds from this repository can update each other normally.

## Verify a download

Compare the SHA-256 in `latest.json` with the downloaded APK:

```powershell
Get-FileHash .\TabFlix.apk -Algorithm SHA256
```

The private application source is not published here; this repository contains only public release metadata and APK assets.
