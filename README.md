# NexusMark

> **High-Performance, Dual-Engine Desktop Markdown Studio with Source-Fidelity Live Preview.**

[![GitHub Release](https://img.shields.io/github/v/release/xtc002007/NexusMark?style=flat-square&color=blue)](https://github.com/xtc002007/NexusMark/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20x64-blue.svg?style=flat-square)](https://nexustools.tech)
[![Frontend](https://img.shields.io/badge/frontend-Svelte%205%20(Runes)%20%7C%20CodeMirror%206-ff3e00.svg?style=flat-square)](https://svelte.dev)
[![Backend](https://img.shields.io/badge/backend-Rust%20%7C%20Tauri%20v2-orange.svg?style=flat-square)](https://tauri.app)
[![License](https://img.shields.io/badge/license-Proprietary-lightgrey.svg?style=flat-square)](./LICENSE)

---

## 📌 Overview

**NexusMark** is a next-generation desktop Markdown live-preview editor engineered specifically for technical documentation authors, researchers, engineers, and long-form prose writers. Built with **Tauri v2 + Svelte 5 (Runes) + Rust**, NexusMark solves the core dilemma of modern markdown editors: delivering instant, rich visual formatting while guaranteeing **100% Source-Text Fidelity**. Your `.md` files remain pristine, completely standard CommonMark/GFM, and seamlessly interchangeable with Obsidian, VS Code, Typora, and GitHub.

This repository serves as the **official public distribution and release portal** for NexusMark binaries, release assets, and package manager feeds (including [winget](https://github.com/microsoft/winget-pkgs)).

---

## ⚡ Key Highlights & Core Capabilities

### 1. Dual-Parser Engine & Source-Fidelity
- **Dual-Parser Architecture**: Combines **Lezer** (CodeMirror 6 incremental syntax parser) for zero-latency editing and tokenization with **comrak** (C-based Rust CommonMark/GFM engine) for pixel-perfect standard-compliant semantic rendering.
- **Zero Syntax Pollution**: Never rewrites or injects proprietary tags into your documents. A file opened, edited, and saved in NexusMark remains byte-for-byte compatible with Git repositories, static site generators (VitePress, Astro, Docusaurus), and Obsidian.

### 2. Immersive Live Preview & Interactive Editing
- **Fluid In-Place Rendering**: Renders headings, blockquotes, lists, checklists, and code fences seamlessly in the active viewport with unobtrusive cursor-sensitive line decorations.
- **Interactive Table Editor**: Visual inline table editing—add rows, delete columns, reorder cells, and format tabular data effortlessly without wrestling with raw pipe characters.
- **Typewriter Scrolling Mode**: Automatically centers the active cursor line vertically, keeping your gaze fixed in the optimal reading zone.
- **Focus Mode**: Selectively highlights the active paragraph or block while gently dimming surrounding text to eliminate distractions.

### 3. Asynchronous Mathematical & Diagrammatic Typesetting
- **KaTeX via Web Workers**: Offloads heavy LaTeX mathematical formula typesetting ($\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}$) to background worker threads, ensuring the main typing thread never drops a single frame.
- **Comprehensive Mermaid Diagrams**: Embedded rendering for flowcharts, sequence diagrams, class diagrams, state machines, entity-relationship diagrams, and Gantt charts.
- **Multi-Language Code Blocks**: Powered by CodeMirror 6 with syntax highlighting for over 50 programming and configuration languages.

### 4. Lightning-Fast SQLite FTS5 Workspace Search
- **Full-Text Search Engine**: Embedded SQLite FTS5 index enables instantaneous substring and boolean search across thousands of workspace documents.
- **Live Search Highlighting**: Real-time keyword highlighting with one-click navigation directly to the matching line.
- **Structured Front Matter Support**: Parse, inspect, and edit YAML Front Matter metadata through an intuitive visual form or raw editor view.

---

## 🚀 Installation & Downloads

### Method 1: Windows Package Manager (winget) — Recommended

Install NexusMark in one step using Windows Terminal or PowerShell:

```powershell
winget install NexusTools.NexusMark
```

Upgrade to the latest release:

```powershell
winget upgrade NexusTools.NexusMark
```

---

### Method 2: Direct Download from GitHub Releases

Download release packages from the [GitHub Releases](https://github.com/xtc002007/NexusMark/releases/latest) page:

| Asset | Description | Recommended For |
| :--- | :--- | :--- |
| `NexusMark_<version>_windows_x64_setup.exe` | Standard Windows NSIS Installer | General desktop use (with desktop shortcut & auto-updates) |
| `NexusMark_<version>_windows_x64_portable.zip` | Standalone Portable Archive | Portable storage and environments without administrator rights |

---

### Method 3: Official NexusTools Suite

Discover NexusMark and the complete ecosystem at [https://nexustools.tech](https://nexustools.tech).

---

## 🔒 Security, Authenticity & Verification

- **Code Signing**: All release executables are protected with Windows Authenticode digital signatures.
- **Minisign Verification**: Releases include cryptographic hashes and Ed25519 signatures.
- **Secure Auto-Updates**: Built-in background update service checks official endpoints with full signature enforcement.

---

## ⚖️ License & EULA

NexusMark is distributed under the [NexusTools End-User License Agreement (EULA)](./LICENSE).  
- Core editing, Live-Preview, KaTeX, Mermaid, and local workspace search are permanently free for personal and professional use.  
- Cloud AI writing enhancements and cross-device sync are managed through NexusTools account subscriptions.

---

## 💬 Community & Support

- **Bug Reports & Feedback**: [GitHub Issues](https://github.com/xtc002007/NexusMark/issues)
- **Official Portal**: [https://nexustools.tech](https://nexustools.tech)
