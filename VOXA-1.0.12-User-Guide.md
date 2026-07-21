# Voxa 1.0.12 Installation & User Guide

**English** | [简体中文](./VOXA-1.0.12-User-Guide.zh-CN.md)

Voxa turns an Apple TV Siri Remote into a remote input device for your Mac, with button mapping, touch controls, and configurable scenes.

Microphone Edition (paid) lets you use the built-in microphone on a supported Apple TV Siri Remote directly as a microphone input on your Mac.

## System Requirements

- Apple Silicon Mac (M1, M2, M3, M4, or newer)
- macOS 13 Ventura or later
- Apple TV Siri Remote paired with the Mac over Bluetooth

> The current installer is arm64-only. It supports Apple Silicon Macs and does not support Intel Macs.

## Installation

1. Download `VOXA-1.0.12.dmg`.
2. Double-click the DMG to open it.
3. Drag `Voxa.app` into the Applications folder shown on the right.
4. Open Applications in Finder and double-click `Voxa.app`.
5. If macOS says the developer cannot be verified or blocks the app, open System Settings → Privacy & Security.
6. In the Security section, find the message about Voxa, click Open Anyway, authenticate when prompted, and open Voxa again.

This version uses an Apple Development signature and has not yet completed Developer ID notarization, so macOS may show a security prompt on first launch. Do not disable Gatekeeper or run terminal commands from unknown sources.

## First Use

1. Open Voxa.
2. Grant Accessibility and Input Monitoring permissions when prompted. After changing permissions, quit Voxa completely and reopen it.
3. In macOS System Settings → Bluetooth, confirm that the Siri Remote is connected.
4. Open the device or remote settings in Voxa and configure the buttons, touch surface, and clickpad ring actions you want.
5. In language settings, choose Simplified Chinese, English, Japanese, French, or follow the system language.

## Updating an Older Version

1. Quit Voxa if it is running.
2. Open the new DMG.
3. Drag the new `Voxa.app` into Applications and choose Replace.
4. Reopen Voxa. Existing button mappings and settings are normally preserved.

## Troubleshooting

### Voxa Does Not Open

Confirm that Voxa has been moved into Applications. Then open System Settings → Privacy & Security, find the blocked-app message for Voxa in the Security section, and click Open Anyway. You do not need to permanently enable apps from anywhere.

### Button Mappings Do Not Respond

Check that Accessibility and Input Monitoring permissions are enabled, then quit Voxa completely and reopen it. Avoid keeping multiple copies of the same Voxa version.

## Highlights in This Version

- Fixes a crash when opening the Software Update page.
- Lowers the minimum supported system version to macOS 13.
- Adds Simplified Chinese, English, Japanese, and French interfaces.
- Keeps the new visual treatment on macOS 26 while providing compatible styling for macOS 13–15.

## Contact

For questions or feedback, email [huabeijinzongma@icloud.com](mailto:huabeijinzongma@icloud.com).
