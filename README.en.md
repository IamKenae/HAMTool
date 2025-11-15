# HamTool by BG5EGG - Amateur Radio Tool Software

<div align="center">

![HamTool Logo](public/icon.png)

**Professional Amateur Radio Log Management and QSO Recording Tool**

[🌐 English](./README.en.md) | [🇨🇳 简体中文](./README.md)

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-blue.svg)](#downloads)
[![Version](https://img.shields.io/badge/Version-3.0.0-green.svg)](../../releases)
[![Beta](https://img.shields.io/badge/Beta-Available-orange.svg)](#beta-versions)

[📥 Downloads](#downloads) • [✨ Features](#features) • [🚀 Quick Start](#quick-start) • [📖 User Guide](#user-guide) • [📄 License](#license) • [📞 Contact Us](#contact-us)

</div>

## 📖 Project Overview

HamTool is a modern desktop application designed specifically for amateur radio enthusiasts (HAM), integrating comprehensive QSO log management, call sign queries, QTH location management, and other core features. Built with Electron + Vue 3 technology stack, it provides cross-platform support and an elegant user interface. The software supports multi-language internationalization, dark mode switching, offering HAMs a professional, efficient, and convenient user experience.

## ✨ Features

### 🎯 Core Features
- **📝 QSO Log Management** - Complete QSO recording, editing, searching, and statistical analysis
- **📚 Callbook Management** - Built-in call sign database with fast queries and batch management
- **🌍 QTH Location Services** - Intelligent location input supporting Pinyin, Chinese, and detailed regional data
- **💾 Database System** - Multi-database support with backup/restore and version conflict handling

### 🎨 User Experience
- **🌍 Multi-Language Support** - Supports Simplified Chinese and English, extensible for more languages
- **🌙 Dark Mode** - Supports automatic and manual light/dark theme switching
- **📱 Responsive Design** - Adapts to different screen sizes, supports mobile access
- **⚡ High Performance** - Built with Electron + Vue 3 for smooth operation
- **🔒 Data Security** - Local data storage with privacy protection and automatic backup

### 🚀 Advanced Features
- **📤 Data Import/Export** - Supports JSON and Excel formats with CC BY-NC-SA 4.0 license protection
- **🔍 Advanced Search & Filter** - Multi-condition filtering, sorting, and full-text search
- **📈 Statistical Analysis** - QSO data statistics and chart visualization
- **🌐 Web Sync Service** - Lab feature supporting LAN access and data synchronization
- **🏷️ Multiple Operation Modes** - Roll call mode and personal QSO recording mode

### 🛠️ Technical Features
- **🔧 Beta Version Support** - Independent beta release channel with data import functionality
- **📊 Database Version Management** - Intelligent version conflict detection and resolution
- **🌐 Internationalization Framework** - Complete i18n support with translator information display
- **🔌 Plugin Architecture** - Modular design for easy extensibility

## 📥 Downloads

### Stable Releases

**Latest Version: 3.0.0**

Download from [GitHub Releases](../../releases):

| Platform | File Name | Description |
|----------|-----------|-------------|
| 🪟 Windows | `HamTool-Setup-3.0.0.exe` | Windows Installer |
| 🍎 macOS | `HamTool-3.0.0.dmg` | macOS Disk Image |
| 🐧 Linux | `HamTool-3.0.0.AppImage` | Linux Application Image |

### Beta Versions

> **Note**: Beta versions include new features under development and may contain bugs. Use for testing purposes only.

Visit [HAMTool-Beta Releases](https://github.com/IamKenae/HAMTool-Beta/releases) to download the latest beta versions:

| Platform | File Name | Description |
|----------|-----------|-------------|
| 🪟 Windows | `HAMTool-Beta-Setup-x.x.x.exe` | Windows Installer |
| 🍎 macOS | `HAMTool-Beta-x.x.x.dmg` | macOS Disk Image |
| 🐧 Linux | `HAMTool-Beta-x.x.x.AppImage` | Linux Application Image |

### System Requirements

| Platform | Minimum Requirements | Recommended Configuration |
|----------|----------------------|---------------------------|
| 🪟 Windows | Windows 10 (1903) or higher | Windows 11 |
| 🍎 macOS | macOS 10.15 (Catalina) or higher | macOS 12 (Monterey) or higher |
| 🐧 Linux | Modern Linux distribution with AppImage support | Ubuntu 20.04+ / CentOS 8+ |

**Hardware Requirements**:
- **Memory**: Minimum 4GB RAM, recommended 8GB or more
- **Storage**: At least 500MB available space
- **Network**: Optional, for license verification and automatic updates

## 🚀 Quick Start

### Installation

1. **Download**: Download the appropriate installer for your platform from the releases page
2. **Install**: Run the installer and follow the installation wizard
3. **Launch**: Start HamTool from your applications menu

### First Time Setup

1. **License Activation**: On first launch, enter your license key
   - Community users can obtain a free license from the activation website
   - Commercial users should contact support for commercial licensing

2. **Language Settings**: Choose your preferred interface language
   - Go to **Settings** → **Interface Language**
   - Select from available languages (Chinese/English)

3. **Database Setup**: Create your first QSO database
   - Go to **Database Management** → **New Database**
   - Enter a descriptive name for your database

### Basic Usage

1. **Add QSO Records**: Click **Log Management** → **Add New Record**
2. **Search Call Signs**: Use **Callbook Management** for quick call sign lookups
3. **Export Data**: Use **Import/Export** → **Export** to save your logs in various formats

## 🛠️ Technical Architecture

### Frontend Stack
- **Framework**: Vue 3 (Composition API) + Element Plus
- **Build Tool**: Vite + electron-vite
- **Styling**: Bootstrap 5 + Custom CSS + FontAwesome
- **Internationalization**: Vue I18n
- **State Management**: Vue 3 Reactive API

### Desktop Application
- **Framework**: Electron (latest version)
- **Packaging**: electron-builder
- **Auto Updates**: electron-updater
- **Cross-Platform**: Windows/macOS/Linux

### Data Storage
- **Local Database**: IndexedDB
- **Backup System**: JSON/Excel import/export
- **Version Management**: Database version control and migration

### Backend Services
- **License Service**: Node.js + Express (Vercel deployment)
- **Activation Website**: Nuxt.js
- **Web Sync**: Express + WebSocket (for LAN access)

### Development Tools
- **Package Manager**: npm
- **Code Standards**: ESLint
- **Version Control**: Git
- **Release**: GitHub Actions + GitHub Releases

## 📄 License

This software is distributed under a proprietary license. Please see the [LICENSE](LICENSE) file for details.

### License Types

#### 🆓 Community License (Free)
- ✅ **Non-Commercial Use**: Free for personal, educational, and research purposes
- 📊 **Excel Export**: Subject to CC BY-NC-SA 4.0 agreement, requires attribution
- 🌐 **Basic Features**: Includes all core functionality
- ⚠️ **Usage Restrictions**: Not for commercial purposes

#### 💼 Commercial License
- 💼 **Commercial Use**: Can be used in business environments and for profit
- 📊 **Unrestricted Export**: Excel export without additional license restrictions
- 🌐 **All Features**: Includes all advanced features and lab features

#### 🌐 Online License
- 🔧 **Advanced Features**: Includes Web Sync service and other lab features
- 📊 **Unrestricted Export**: Excel export without additional license restrictions
- 📊 **Cloud Services**: Online data synchronization and backup
- 🔄 **Auto Updates**: Automatic updates to latest version
- 📱 **Mobile Support**: Mobile-friendly web interface access

### Excel Export License Terms

According to Article 3 of the license, all Excel exports follow **CC BY-NC-SA 4.0**:

- **Attribution Required**: Must include "This Excel spreadsheet was recorded and generated using HamTool" with GitHub link
- **Non-Commercial**: May not be used for commercial purposes
- **Share-Alike**: Derivative works must use the same license

### Legal Terms

- 🔒 **Source Code**: Not open source, protected by copyright
- ⚖️ **Legal Jurisdiction**: Governed by laws of People's Republic of China
- 📧 **Contact**: License inquiries at imkenae@outlook.com

## 📞 Contact Us

### Developer Information
- **Author**: IamKenae (BG5EGG)
- **Email**: imkenae@outlook.com
- **QQ**: 468292535
- **GitHub**: [@IamKenae](https://github.com/IamKenae)

### Support & Feedback
- **Bug Reports**: Please report issues with detailed descriptions and screenshots
- **Feature Suggestions**: Welcome to propose new features and improvements
- **Usage Questions**: Feel free to contact us via email or QQ
- **Community Support**: Join our community for discussions and sharing

## 📝 Changelog

### v3.0.0 (2025-11-02) - Major Update 🆕
- 🌍 **Multi-Language Support**: Complete Chinese and English internationalization system
- 🔧 **Beta Version System**: Independent beta version release channel
- 📊 **Database Version Management**: Intelligent version conflict detection and resolution
- 📤 **Excel Export License**: CC BY-NC-SA 4.0 compliance and confirmation
- 🌐 **Web Sync Service**: Lab feature for LAN access support
- 🏷️ **Multi-Mode Operations**: Roll call mode and personal QSO recording mode
- 🎨 **UI Improvements**: Dark mode, theme switching, responsive design
- ⚡ **Performance Improvements**: Data processing speed and memory usage optimization

### v2.1.3 (2025-08-30) - Security Update
- 🔒 **License System**: Enhanced verification logic and security mechanisms
- 🐛 **Bug Fixes**: Resolved stability issues and user experience problems
- ⚡ **Performance Optimization**: Database operations and interface response speed improvements

### v2.1.2 (2025-08-29) - Feature Optimization
- 🔧 **Feature Improvements**: UI interaction and user experience optimization
- 🐛 **Bug Fixes**: Fixed known issues and stability improvements
- ⚡ **Performance Boost**: Data processing and memory usage optimization

### v2.1.1 (2025-08-29) - Quick Fix
- 🐛 **Emergency Fix**: Resolved critical functionality issues
- 🔧 **Adjustment Optimization**: UI detail adjustments and improvements
- ⚡ **Stability**: Improved application runtime stability

### v2.1.0 (2025-08-29) - Feature Enhancement
- 📱 **Mobile Support**: Responsive design and mobile optimization
- 🌙 **Dark Mode**: Complete theme switching system
- 📊 **Statistics**: QSO data visualization charts
- 🔍 **Search Optimization**: Advanced search and filter functionality

### v2.0.0 (2025-08-29) - Major Version Release
- 🎯 **Core Features**: Complete QSO logging and call sign management
- 💾 **Data System**: Multi-database support with backup and restore
- 🌍 **QTH Management**: Intelligent location input and management
- 📊 **Import/Export**: JSON and Excel data exchange functionality

## 🗺️ Development Roadmap

### Coming Soon (v3.1.0)
- 🗺️ **Map Visualization**: QTH location map display and heat maps
- 📡 **Device Integration**: Radio equipment control and data synchronization
- 📱 **Mobile App**: Native mobile application development
- ☁️ **Cloud Sync**: Cloud data backup and synchronization services

### Long-Term Plans
- 🤖 **AI Assistant**: Intelligent QSO assistant and recommendation system
- 📡 **SDR Integration**: Software Defined Radio support
- 🌐 **Community Features**: HAM community communication and data sharing
- 🔧 **Plugin System**: Third-party plugin development framework

## 🤝 Contributing Guidelines

We welcome feedback and suggestions from the HAM community:

- **Bug Reports**: Please provide detailed problem descriptions in [Issues](../../issues)
- **Feature Suggestions**: Welcome new feature ideas and improvement suggestions
- **Testing Feedback**: Beta version testing feedback is especially appreciated
- **Translation Contributions**: Help improve multi-language support

## 🙏 Acknowledgments

Thank you to all amateur radio enthusiasts for your support and feedback, especially:
- Users who provided valuable suggestions for testing
- Constructive feedback that helped improve software functionality
- Support and encouragement from the amateur radio community

---

<div align="center">

**HamTool - Making Amateur Radio Simpler** 📻

[📧 Contact Us](#contact-us) • [📄 License](#license) • [⭐ Support Project](../../stargazers)

Copyright © 2025 IamKenae (BG5EGG). All rights reserved.

Made with ❤️ for the HAM community

</div>