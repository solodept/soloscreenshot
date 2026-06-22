# SoloScreenshot

[English](README.md) | [简体中文](README.zh-CN.md)

---

[![Platform](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows-blue.svg)](#)
[![Flutter](https://img.shields.io/badge/Made%20with-Flutter-02569B.svg?logo=flutter)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](#)

SoloScreenshot is a **local app store screenshot generator and mockup studio** for macOS and Windows.

It helps indie developers and global app teams design product screenshots, reuse localized copy from local translation JSON files, and export store-ready image folders without uploading unreleased UI to a cloud tool.

**Official Website:** [https://screenshot.solodept.com/](https://screenshot.solodept.com/)

![SoloScreenshot Preview](assets/screenshot-en.jpg)

---

## Why SoloScreenshot

*   **Local-first workflow:** Screenshots, mockups, and translation files stay on your computer.
*   **Localized screenshot production:** Load translation JSON once, then preview and export screenshots for multiple languages.
*   **Store-ready exports:** Generate folders for App Store, Google Play, Fastlane, and custom sizes in a predictable structure.
*   **Reusable projects:** Save layout, device, background, and text settings so UI or copy updates can be re-exported quickly.
*   **Practical templates:** Start from device frames, backgrounds, typography settings, and screenshot layouts designed for product pages.

---

## Download

Download the latest production builds from [GitHub Releases](https://github.com/solodept/soloscreenshot/releases).

| OS | Download Link | Notes |
| :--- | :--- | :--- |
| **macOS** | [Download macOS DMG](https://github.com/solodept/soloscreenshot/releases) | DMG package, see macOS first launch notes below |
| **Windows** | [Download Windows ZIP](https://github.com/solodept/soloscreenshot/releases) | ZIP package, unzip and run the app |

---

## Typical Web Tools vs SoloScreenshot

| Workflow | Typical Web Tools | SoloScreenshot |
| :--- | :--- | :--- |
| **Privacy** | Upload draft screens to a remote service | Render and export on your own computer |
| **Localization** | Copy text into each design manually | Load local translation JSON and batch export locales |
| **Delivery** | Download scattered images one by one | Generate structured folders for store submission |

---

## Pricing

| Tier | Price | Included Features |
| :--- | :--- | :--- |
| **Free** | **$0** | Design, preview, and export individual screenshots. |
| **Lifetime Pro** | **$4.99** Early Bird | Batch export all screens, sizes, and configured languages. One-time payment, no subscription. |

---

## macOS First Launch

SoloScreenshot is distributed outside the Mac App Store. On first launch, macOS Gatekeeper may show a warning such as **"SoloScreenshot cannot be opened because the developer cannot be verified"** or **"App is damaged"**.

Try one of the following options:

1. Open **System Settings > Privacy & Security**, find the SoloScreenshot warning, and click **Open Anyway**.
2. If macOS still blocks the app, drag `SoloScreenshot.app` to your `Applications` folder, open **Terminal**, and run:

   ```bash
   xattr -cr /Applications/SoloScreenshot.app
   ```
