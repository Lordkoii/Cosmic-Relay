# Cosmic Relay

**A lightweight, customizable in-game media overlay built for Star Citizen.**

> **Current status:** Alpha testing  
> **Current tester version:** `v0.7.0-alpha.3`

Cosmic Relay is an unofficial Star Citizen companion utility designed to keep currently playing media visible in a compact overlay while you stay in-game. This public repository is used for **tester downloads, release notes, bug reports, and quality-of-life feedback**.

The application source code is maintained separately in a private repository and is **not distributed here**.

## What Cosmic Relay does

Cosmic Relay provides a compact media overlay intended for use while playing **Star Citizen**, with customizable layouts and media-detection behavior designed to blend into your gameplay setup without forcing you to constantly leave the game to check what's playing.

Current testing areas include:

- Media detection using `AUTO` and `WEB` modes
- YouTube/media playback detection
- Overlay positioning and movement
- Settings window anchoring
- Layout and appearance behavior
- Multi-monitor/window-edge behavior
- General usability and quality-of-life improvements

## Download

**v0.7.0-alpha.3 — Public Test Build is now available.**

➡️ **[Download Cosmic Relay v0.7.0-alpha.3](https://github.com/Lordkoii/Cosmic-Relay/releases/tag/v0.7.0-alpha.3)**

Download `Cosmic-Relay-v0.7.0-alpha.3-win-x64.zip` from the release assets, extract the entire ZIP to a folder, and run `CosmicRelay.exe`.

This is a self-contained Windows x64 build, so a separate .NET installation should not be required.

Only download Cosmic Relay from releases published by **Lordkoii**.

> Cosmic Relay is currently alpha software. Test builds may contain bugs or incomplete features. Because the application is not yet code-signed, Windows may display an unknown-publisher or security warning on some systems.

### Windows first launch

Because current alpha builds are not yet digitally code-signed, Windows may mark the downloaded ZIP or application as coming from the Internet.

For the smoothest first launch:

1. Download the ZIP from the official Cosmic Relay GitHub Release.
2. Before extracting it, right-click the ZIP and select **Properties**.
3. If an **Unblock** checkbox appears near the bottom of the Properties window, check it, select **Apply**, then **OK**.
4. Extract the entire ZIP to a folder.
5. Run `CosmicRelay.exe`.

If Microsoft Defender SmartScreen displays **Windows protected your PC**, verify that you downloaded the file from the official **Lordkoii/Cosmic-Relay** release page and that the SHA-256 matches the value below. On systems where Windows offers the option, select **More info** and then **Run anyway**.

This first-launch step is temporary while Cosmic Relay remains unsigned. Digitally signed builds are planned for a future release.

## Help test Cosmic Relay

Feedback is welcome and is one of the main reasons this repository exists.

If something breaks, please open a **Bug Report** and include:

- What you were doing when the problem occurred
- Which media source/player you were using
- Whether Cosmic Relay was set to `AUTO` or `WEB`
- Steps that reproduce the issue
- Screenshots when useful

If the app works but you think something could feel better, open a **QOL / Feature Suggestion**. Small usability ideas are especially useful during alpha testing.

## Version

Current tester baseline: **v0.7.0-alpha.3 — Window Polish**

Highlights:

- Working `AUTO` / `WEB` media detection
- Settings window anchors to the main overlay
- Settings follows the overlay while preserving its relative position
- Improved monitor-edge window placement
- Corrected close-button alignment
- Release-protection and application ownership metadata

## File verification

SHA-256 for `Cosmic-Relay-v0.7.0-alpha.3-win-x64.zip`:

`f701251eb6beb1021555f27128245788901b9a2378f5dbd6c84334f7e50471d6`

## License and distribution

Cosmic Relay is **proprietary software**. It is not open source.

Copyright © 2026 **Lordkoii**. All rights reserved.

Tester builds are provided for personal, non-commercial evaluation and use under the terms in the repository's `LICENSE` file. Redistribution, resale, repackaging, or claiming Cosmic Relay as your own work is not permitted.

## Star Citizen disclaimer

Cosmic Relay is an independent, unofficial fan-made utility and is not affiliated with, endorsed by, or sponsored by Cloud Imperium Games or Roberts Space Industries. Star Citizen and related marks belong to their respective owners.

## Creator

**Lordkoii**

Thanks for testing Cosmic Relay and helping shape what comes next.
