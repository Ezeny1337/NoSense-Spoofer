<h1 align="center">NoSense Spoofer</h1>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Ezeny1337/NoSense-Spoofer" />
  <img src="https://img.shields.io/badge/Language-Kotlin-orange?logo=kotlin" />
  <img src="https://img.shields.io/badge/Android-10%2B-brightgreen?logo=android" />
</p>

<p align="center">
  📑 <a href="#-overview">Overview</a> • <a href="#-features">Features</a> • <a href="#-usage">Usage</a> • <a href="#-ui-preview">UI Preview</a> • <a href="#-compatibility">Compatibility</a>
</p>

<p align="center">
  🌐 <a href="./README.md">中文</a> | English
</p>

---

## 📖 Overview

**NoSense Spoofer** is a spoofing tool that requires `Root` privileges. It can spoof various device identifiers and fingerprints that may be collected by other apps, and clean up your system environment.  
The project is still under development and temporarily closed source to prevent unauthorized modifications or reselling.

> ⚠️ **Disclaimer**: This project is intended for **educational and research purposes only**. Do **not** use it in any way that **violates laws, service agreements, or infringes on others' rights**. The developer is **not responsible** for any misuse of this tool.

## 🚀 Features

- ### Spoofer

  Spoof identifiers like `Serial Number` `Android ID` `WLAN MAC` `ADID` and more.

- ### Cleaner

  Clean up system logs, cache, and residual data. Modify certain device parameters to make the environment **cleaner**.

## 🛠 Usage

1. **Select**: Choose the device identifiers you want to spoof and specify the target app scope (some identifiers may affect normal system behavior, so scoping is recommended).
2. **Seed**: Each `Seed` is unique and corresponds to a set of random but valid device data. Only refresh it when necessary.
3. **Spoof**: After spoofing according to the seed, please reboot the device as soon as possible to apply the changes. (It will reboot automatically at present)
4. **Reset**: Some changes are temporary and take effect after the first restart and become invalid after the second reboot. But some changes are permanent, so when you are in a spoofed state and need to reset, manually click Reset.

## 🧐 UI Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/27ac24c8-581d-449b-86a9-93ebd42453d3" width="30%" />
  <img src="https://github.com/user-attachments/assets/7358152c-5416-45bf-9842-49c657d00960" width="30%" />
  <img src="https://github.com/user-attachments/assets/d96bc247-e642-427c-a668-5adef377ca91" width="30%" />
</p>

## 🧪 Compatibility

- Android 10 to 15
- Rooted environments supported: `Magisk` `KernelSU` `APatch`
