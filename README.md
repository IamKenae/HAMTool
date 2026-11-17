# HAMTool

<div align="center">

![HAMTool Logo](public/icon.png)

**面向业余无线电爱好者的通联日志与协作工具**

[English](./README.en.md) | 简体中文

[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](LICENSE)
[![Platforms](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android-blue.svg)](#下载)
[![Latest release](https://img.shields.io/badge/Release-v6.2.0-green.svg)](https://github.com/IamKenae/HAMTool/releases/latest)

[下载](#下载) · [功能](#功能概览) · [快速开始](#快速开始) · [版本渠道](#版本渠道) · [反馈与联系](#反馈与联系)

</div>

HAMTool 帮助业余无线电爱好者记录和管理 QSO，提供呼号与 QTH 资料管理、数据导入导出，以及在线协作等功能。应用提供 Windows、macOS、Linux 桌面版、Android 安装包和 Web 体验版。

## 下载

当前稳定版：**v6.2.0**。请从[正式版 GitHub Release](https://github.com/IamKenae/HAMTool/releases/tag/v6.2.0)下载。以下安装包也可直接下载；`.blockmap` 是 Electron 自动更新使用的元数据文件，通常不需要手动下载。

### Windows

- [HAMTool-6.2.0-x64.exe](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0-x64.exe) — Windows x64 安装程序

### macOS

- [HAMTool-6.2.0.dmg](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0.dmg) — Intel (x64)
- [HAMTool-6.2.0-arm64.dmg](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0-arm64.dmg) — Apple silicon (arm64)

### Linux

- [HAMTool-6.2.0.AppImage](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/HAMTool-6.2.0.AppImage) — AppImage
- [hamtool_6.2.0_amd64.deb](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/hamtool_6.2.0_amd64.deb) — Debian / Ubuntu x64

### Android

- [app-release.apk](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/app-release.apk) — Android 安装包
- [app-release.aab](https://github.com/IamKenae/HAMTool/releases/download/v6.2.0/app-release.aab) — Android App Bundle，供应用商店分发使用

### Web

打开[官方 Web 体验版](https://hamtool.kenae.dev/app)。建议使用新域名；旧地址可能仍可访问，但不再作为首选入口。

## 功能概览

- **QSO 日志**：记录、编辑、搜索和统计个人通联及点名记录。
- **呼号与 QTH 资料**：管理呼号词条、地名与常用输入词库，支持拼音检索。
- **数据管理**：支持 JSON、Excel 和 ADIF 等格式的导入导出，以及备份与恢复。
- **协作与主控屏**：在线协作并同步最新记录，主控屏可实时阅读记录。
- **AI 辅助**：从历史记录提取词库内容，或辅助解析表格并导入 QSO。
- **无线电与工作流**：包含 FT8、CAT 等相关功能；不同平台或设备的可用能力可能不同。
- **多平台与主题**：桌面、Web、Android 体验，支持多语言、主题和深色模式。

## 快速开始

1. 从上方选择与设备匹配的安装包，或前往[正式版下载页](https://github.com/IamKenae/HAMTool/releases/latest)。
2. 安装并启动 HAMTool。首次使用时创建或选择日志数据库。
3. 如有现存日志，可使用数据导入功能；建议在导入或升级前先备份数据。

## 版本渠道

- **正式版**：面向所有用户，通过 [HAMTool Releases](https://github.com/IamKenae/HAMTool/releases) 发布。
- **Beta 版已停止提供**：HAMTool 不再发布或维护独立 Beta 下载渠道，原 [HAMTool-Beta 仓库](https://github.com/IamKenae/HAMTool-Beta)已归档。
- **Nightly 版**：用于受邀用户提前体验开发构建，取代原 Beta 测试渠道。请访问私有的 [HAMTool-Nightly 仓库](https://github.com/IamKenae/HAMTool-Nightly)；仅受邀账号可以访问。如需申请邀请，请填写[Nightly 申请表（中文）](https://forms.cloud.microsoft/r/WChAR8iBsi)，也可通过[开发者 GitHub 主页](https://github.com/IamKenae)联系维护者。Nightly 构建可能不稳定，不建议用于唯一或未备份的数据。

## 数据与隐私

日志和设置由应用本地数据存储功能管理。在线账户、云同步、AI、许可证验证和协作等功能会按使用情况连接 HAMTool 服务或相应第三方服务。请在使用前阅读应用中的隐私与许可说明，并定期导出备份。

## 反馈与联系

- **问题反馈与功能建议**：[GitHub Issues](https://github.com/IamKenae/HAMTool/issues)
- **开发者**：IamKenae (BG5EGG)
- **电子邮件**：bg5egg@outlook.com
- **项目主页**：[github.com/IamKenae/HAMTool](https://github.com/IamKenae/HAMTool)
- **官方 Web 体验版**：[hamtool.kenae.dev/app](https://hamtool.kenae.dev/app)

## 许可

HAMTool 使用专有许可证。使用软件及其导入、导出功能时，请阅读仓库中的 [LICENSE](LICENSE) 并遵守其中条款。第三方组件和导出数据可能分别受其各自许可约束。

## 开发技术

HAMTool 使用 Svelte 5 与 Vite 构建界面，Electron 提供桌面容器，Capacitor 用于 Android，Rust/WASM 提供部分底层能力。仓库还包含 PHP 后端服务。开发与构建说明见项目中的 `package.json`、`backend/` 和 `android/`。

## 更新记录

查看 [完整更新记录](./CHANGELOG.md) 或[全部 Releases](https://github.com/IamKenae/HAMTool/releases)。
