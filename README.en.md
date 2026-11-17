# HAMTool

<div align="center">

![HAMTool Logo](public/icon.png)

**QSO logging and collaboration for amateur radio operators**

[English](./README.en.md) | [简体中文](./README.md)

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android-blue.svg)](#downloads)
[![Latest release](https://img.shields.io/badge/Release-v6.2.0-green.svg)](https://github.com/IamKenae/HAMTool/releases/latest)

[Downloads](#downloads) · [Features](#features) · [Quick start](#quick-start) · [Release channels](#release-channels) · [Support](#support)

</div>

HAMTool helps amateur radio operators record and manage QSOs. It includes callsign and QTH data management, data import and export, and online collaboration. HAMTool is available as a desktop app for Windows, macOS, and Linux, an Android package, and a web experience.

## Downloads

Current stable release: **v6.2.0**. Download it from the [official GitHub Release](https://github.com/IamKenae/HAMTool/releases/tag/v6.2.0), or use the direct links below. `.blockmap` files are metadata used by Electron's auto-updater and generally do not need to be downloaded manually.

### Windows

- [HAMTool-6.2.0-x64.exe](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0-x64.exe) — Windows x64 installer

### macOS

- [HAMTool-6.2.0.dmg](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0.dmg) — Intel (x64)
- [HAMTool-6.2.0-arm64.dmg](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0-arm64.dmg) — Apple silicon (arm64)

### Linux

- [HAMTool-6.2.0.AppImage](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0.AppImage) — AppImage
- [hamtool_6.2.0_amd64.deb](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/hamtool_6.2.0_amd64.deb) — Debian / Ubuntu x64

### Android

- [app-release.apk](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/app-release.apk) — Android installer package
- [app-release.aab](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/app-release.aab) — Android App Bundle for app-store distribution

### Web

Open the [official web experience](https://hamtool.kenae.dev/app). The new domain is recommended; the previous address may remain available but is no longer the preferred entry point.

## Features

- **QSO logs:** Record, edit, search, and review personal QSOs and roll-call logs.
- **Callsign and QTH data:** Manage callsign entries, place names, and frequently used input terms, with pinyin search support.
- **Data management:** Import and export formats including JSON, Excel, and ADIF; back up and restore data.
- **Collaboration and control-room display:** Collaborate online with synchronized latest records and a live reading display.
- **AI assistance:** Extract dictionary entries from past records or help parse spreadsheets into QSO data.
- **Radio and workflow tools:** Includes FT8- and CAT-related features; availability can vary by platform and equipment.
- **Multiple platforms and themes:** Desktop, web, and Android experiences, with localization, themes, and dark mode.

## Quick start

1. Choose the installer for your device above, or visit the [stable releases page](https://github.com/IamKenae/HAMTool/releases/latest).
2. Install and launch HAMTool. Create or select a log database on first use.
3. Import existing logs if needed. Back up your data before importing or upgrading.

## Release channels

- **Stable:** Available to all users from [HAMTool Releases](https://github.com/IamKenae/HAMTool/releases).
- **Beta has been discontinued:** HAMTool no longer publishes or maintains a separate Beta download channel. The former [HAMTool-Beta repository](https://github.com/IamKenae/HAMTool-Beta) has been archived.
- **Nightly:** Early development builds for invited testers replace the former Beta testing channel. Visit the private [HAMTool-Nightly repository](https://github.com/IamKenae/HAMTool-Nightly); access is limited to invited accounts. To request an invitation, submit the [Chinese-language application form](https://forms.cloud.microsoft/r/WChAR8iBsi) or contact the maintainer through the [developer's GitHub profile](https://github.com/IamKenae). Nightly builds may be unstable; do not use them with your only copy of important data.

## Data and privacy

Logs and settings are managed by the app's local data-storage features. Online accounts, cloud sync, AI, license validation, and collaboration connect to HAMTool services or relevant third-party services as needed. Review the privacy and license notices in the app and export backups regularly.

## Support

- **Bug reports and feature requests:** [GitHub Issues](https://github.com/IamKenae/HAMTool/issues)
- **Developer:** IamKenae (BG5EGG)
- **Email:** bg5egg@outlook.com
- **Project:** [github.com/IamKenae/HAMTool](https://github.com/IamKenae/HAMTool)
- **Web experience:** [hamtool.kenae.dev/app](https://hamtool.kenae.dev/app)

## License

HAMTool is distributed under a proprietary license. Read the repository's [LICENSE](LICENSE) and comply with its terms when using the software and its import/export features. Third-party components and exported data may be subject to their own licenses.

## Development

HAMTool uses Svelte 5 and Vite for its interface, Electron for the desktop shell, Capacitor for Android, and Rust/WASM for selected low-level capabilities. The repository also contains PHP backend services. See `package.json`, `backend/`, and `android/` for development and build details.

## Changelog

See the [full changelog](./CHANGELOG.md) or [all releases](https://github.com/IamKenae/HAMTool/releases).
