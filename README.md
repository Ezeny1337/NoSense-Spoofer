<h1 align="center">NoSense Spoofer</h1>

<p align="center">
  <img src="https://img.shields.io/github/v/release/Ezeny1337/NoSense-Spoofer" />
  <img src="https://img.shields.io/badge/Language-Kotlin-orange?logo=kotlin" />
  <img src="https://img.shields.io/badge/Android-10%2B-brightgreen?logo=android" />
</p>

<p align="center">
  📑 <a href="#-概述">概述</a> • <a href="#-功能">功能</a> • <a href="#-使用说明">使用说明</a> • <a href="#-用户界面">用户界面</a> • <a href="#-支持环境">支持环境</a>
</p>

<p align="center">
  🌐 简体中文 | <a href="./README_en.md">English</a>
</p>

---

## 📖 概述

**NoSense Spoofer** 是一个在 `Root` 权限下使用的伪造工具，可伪造设备标识符、指纹等可能被其他应用收集的信息，清理设备环境。  
项目仍在开发中，暂时闭源，以防二改与倒卖。

> ⚠️  **免责声明**：本项目仅供**学习与研究**使用。请勿将其用于任何**违反法律法规、服务条款或侵犯他人权益**的场景。开发者不对任何滥用本工具所造成的后果负责。

## 🚀 功能

- ### Spoofer

  对 `Serial Number` `Android ID` `OAID` 等标识符进行**伪造**。

- ### Cleaner

  清理设备的一些日志、缓存和残留数据，对一些设备参数进行修改，使环境更**干净**。

## 🛠 使用说明

1. **选择**：选择需要伪造的设备信息以及应用程序作用域（伪造后对系统功能正常使用有影响或对于应用程序唯一的设备信息，仅对作用域生效）。
2. **种子**：每个 `Seed` 都是唯一的，对应一套唯一、随机、合理的设备信息，请仅在需要的时候刷新它。
3. **伪造**：根据 `Seed` 进行伪造后，请尽快重启以应用更改（目前会自动重启）。
4. **重置**：一些更改是临时性的，即重启后生效，再次重启失效；但一些更改是永久性的，所以请在每次处于伪造状态、需要重置时手动点击重置。

## 🧐 用户界面

<p align="center">
  <img src="https://github.com/user-attachments/assets/27ac24c8-581d-449b-86a9-93ebd42453d3" width="30%" />
  <img src="https://github.com/user-attachments/assets/7358152c-5416-45bf-9842-49c657d00960" width="30%" />
  <img src="https://github.com/user-attachments/assets/d96bc247-e642-427c-a668-5adef377ca91" width="30%" />
</p>

## 🧪 支持环境

- Android 10 ~ 15
- 具备 Root 权限：支持 `Magisk` `KernelSU` `APatch`
