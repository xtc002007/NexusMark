# NexusMark

> 极速、极简、无缝双栏与实时预览的 Markdown 写作工作台。

[![Release](https://img.shields.io/github/v/release/xtc002007/NexusMark?style=flat-square)](https://github.com/xtc002007/NexusMark/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20(x64)-blue.svg?style=flat-square)](https://nexustools.tech)
[![License](https://img.shields.io/badge/license-Proprietary-lightgrey.svg?style=flat-square)](./LICENSE)

---

## 📖 简介 / Overview

**NexusMark** 是 [NexusTools](https://nexustools.tech) 团队打造的专业桌面工具。  
轻量极速的 Markdown / CommonMark 沉浸式创作与高性能技术写作桌面工具。

本仓库为 **官方公开发布与分发门面仓库**，专门用于对外发布稳定安装包、版本更新日志（Release Notes）以及 Windows Package Manager (winget) 的自动化分发通道。

---

## ✨ 核心亮点 / Features

- **毫秒级启动与超低内存开销（基于 Tauri 2.x）**
- **标准 Markdown / GFM 规范全面支持，包含公式、图表与代码高亮**
- **平滑双栏同步滚动与零闪烁预览引擎**
- **多格式专业导出（HTML、PDF 等）与版本快照支持**

---

## 🚀 安装与下载 / Installation

### 方式 1: 通过 Windows Package Manager (winget) 推荐

只需在 Windows Terminal / PowerShell 中输入：

```powershell
winget install NexusTools.NexusMark
```

升级现有版本：

```powershell
winget upgrade NexusTools.NexusMark
```

### 方式 2: GitHub Releases 直接下载

访问 [Releases 页面](https://github.com/xtc002007/NexusMark/releases/latest)，下载最新版本的 Windows 安装包：
- `NexusMark_<version>_windows_x64_setup.exe`（推荐，支持应用内平滑自动升级）
- `NexusMark_<version>_windows_x64_portable.zip`（免安装绿色便携版）

### 方式 3: NexusTools 官方网站

前往 [NexusTools 官网](https://nexustools.tech) 了解详情并一键下载。

---

## 🔄 自动更新与安全保障

- **应用内自动更新**：软件内置静默更新检测与差分安全下载机制，由 NexusTools 官方分发端点提供稳定支持。
- **数字验签与防篡改**：所有官方发布资产均附带 minisign ed25519 防篡改数字签名与 Windows Authenticode 代码签名。

---

## 📄 软件使用许可 / License

本项目采用 [NexusTools 软件专有许可协议 (EULA)](./LICENSE)。  
免费基础功能可永久免费使用；高级专业特性受 NexusTools 统一账号与订阅协议约束。

- **问题反馈与建议**：欢迎在 [GitHub Issues](https://github.com/xtc002007/NexusMark/issues) 提交反馈。
- **官方技术支持**：https://nexustools.tech
