# Color Lyric 16

Live **Fluid Cloud** word-by-word lyrics, multi-language translation, and **Lock Screen / AOD** lyrics bridge built specifically for **ColorOS 16 (Android 16)**.

> **Note:** This repository hosts module metadata and compiled APK releases for the LSPosed Modules Repository. For issue reports, feature requests, and release discussions, please visit [HungNoPro/Color-Lyric-16](https://github.com/HungNoPro/Color-Lyric-16).

## Key Features

- **Fluid Cloud Live Lyrics:**
  - True millisecond word-by-word karaoke sweep powered by **Apple Music / LyricsPlus v2** syllable timing, with smooth synthetic fallback for line-synced sources.
  - Dual-line lyrics & translation display, album-art dynamic color tinting, camera cutout awareness, and interlude compacting.
  - **Capsule Auto-Collapse Guard:** Prevents ColorOS 16 from automatically shrinking or hiding the status-bar media capsule after timeouts while keeping interlude compacting intact.
  - **Smooth Unlock & Card-Exit Transitions:** Seamless native spring expansion without half-width stuttering.
- **All-in-One Online Lyrics & Auto-Translation:**
  - 5 built-in online sources with automatic fallback: `Apple Music (LyricsPlus)`, `Better Lyrics`, `LRCLIB`, `Kugou`, and `lyrics.ovh`.
  - Batched auto-translation across 13 languages (`System`, `VI`, `EN`, `ZH-CN`, `ZH-TW`, `JA`, `KO`, `ES`, `FR`, `DE`, `RU`, `ID`, `TH`).
  - Local disk cache with live size indicator and optional automatic pruning.
- **Lock Screen & Always-On Display (AOD) Bridge:**
  - Bridges live lyrics to ColorOS 16 Lock Screen / Notification / AOD media views.
  - Unlocks the ColorOS 16 AOD media player whitelist beyond Spotify so all music apps are supported.
- **Liquid Glass COUI Settings:**
  - Real-time settings sync without rebooting, live 3-row Hook Status (`Fluid Cloud`, `Lock Screen`, `AOD`), and automatic startup update notifications.

## Requirements

- **OS:** ColorOS 16 (Android 16)
- **Framework:** LSPosed 2.2.0+ (Xposed API 102+)

## Installation & Setup

1. Download and install the latest `.apk` from [Releases](https://github.com/HungNoPro/Color-Lyric-16/releases).
2. Open **LSPosed Manager** → enable **Color Lyric 16**.
3. Ensure **`System UI` (`com.android.systemui`)** is checked in the module scope (the only required scope).
4. Restart **System UI** (or reboot your device).
5. Open **Color Lyric 16** to customize layout, lyrics source, translation language, and Fluid Cloud behavior.

## Credits

- **Original Upstream Project:** [Luckyumimi/Color-lyric](https://github.com/Luckyumimi/Color-lyric)
- **ColorOS 16 Adaptation & Maintainer:** [HungNoPro](https://github.com/HungNoPro/Color-Lyric-16)
