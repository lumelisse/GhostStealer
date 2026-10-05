# GhostStealer

<p align="center">
  <strong>GhostStealer</strong> is an advanced security research tool for testing local data storage vulnerabilities in web browsers and Discord applications on Windows systems.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D4?logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/Builder-Payload%20Model-6366F1" alt="Builder">
  <img src="https://img.shields.io/badge/Obfuscation-LZMA%20%7C%20XOR%20%7C%20Base85-EF4444" alt="Obfuscation">
  <img src="https://img.shields.io/badge/Browsers-8%20Supported-10B981" alt="Browsers">
  <img src="https://img.shields.io/badge/Discord-4%20Clients-5865F2?logo=discord&logoColor=white" alt="Discord">
  <img src="https://img.shields.io/badge/Status-Active-22C55E" alt="Status">
</p>

> **GhostStealer** is built for authorized security testing, defensive research, and controlled lab environments.

---

## ✦ Overview

**GhostStealer** is an advanced security research tool designed to test and demonstrate local data storage vulnerabilities in web browsers and Discord applications on Windows systems. It follows a **Builder → Payload** model — the operator compiles a fully customized final payload, then deploys it for testing on authorized systems.

---

## ✦ Features

| Feature | Description |
|---|---|
| 🧱 **Payload Builder** | Dark-themed GUI to configure modules, options, icon, and output name. |
| 🔑 **KeyAuth Gate** | Login / Register / License-based authentication with optional 2FA. |
| 🎯 **Module Toggles** | Pick exactly which data modules to include in the payload. |
| 🔐 **Obfuscation Engine** | Three-layer obfuscation (LZMA + XOR + Base85 ×3 + shuffle). |
| 🧩 **Auto Build** | Compiles payload to a single silent `.exe` via PyInstaller. |
| 🖼️ **Icon Support** | Accepts `.ico`, images (`.png`, `.jpg`, …), or extracts from `.exe`. |
| 📦 **Single-File Delivery** | Everything bundled into one executable. |
| 🚀 **Startup Persistence** | Optional self-copy to Windows startup folder. |
| 📡 **Webhook Delivery** | Sends collected ZIP to a Discord webhook with an embedded summary. |

---

## ⚙️ Build Pipeline

```mermaid
flowchart LR
    A[Builder GUI] --> B[Configure Modules]
    B --> C[Configure Options]
    C --> D[Generate Source]
    D --> E[Obfuscate]
    E --> F[PyInstaller Build]
    F --> G[Payload.exe]
    G --> H[Authorized Target]
    H --> I[Discord Webhook]
## 📞 Contact For Buy It
- Discord: [@Server](https://discord.gg/5-6)
- Discord: [@lumelisse](https://discordapp.com/users/970282290905231390)
