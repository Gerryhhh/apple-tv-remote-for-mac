# Voxa 1.0.12 安装与使用教程

[English](./VOXA-1.0.12-User-Guide.md) | **简体中文**

Voxa 可以把 Apple TV Siri Remote 用作 Mac 的遥控输入设备，支持按键映射、触控操作和场景切换。

麦克风版（付费功能）可将支持的 Apple TV Siri Remote 内置麦克风直接作为 Mac 的麦克风使用。

## 系统要求

- Apple Silicon Mac（M1、M2、M3、M4 或更新型号）
- macOS 13 Ventura 或更高版本
- Apple TV Siri Remote 已通过蓝牙与 Mac 配对

> 当前安装包为 arm64，仅支持 Apple Silicon，不支持 Intel Mac。

## 安装

1. 下载 `VOXA-1.0.12.dmg`。
2. 双击打开 DMG。
3. 将 `Voxa.app` 拖入右侧的“应用程序”文件夹。
4. 在 Finder 中打开“应用程序”，双击 `Voxa.app`。
5. 如果 macOS 提示无法验证开发者或阻止启动，请进入“系统设置 → 隐私与安全性”。
6. 在“安全性”区域找到关于 Voxa 的拦截提示，点击“仍要打开”，按系统要求验证后再次打开 Voxa。

当前版本使用 Apple Development 签名，尚未完成 Developer ID 公证，因此首次启动可能出现系统安全提示。不要关闭 Gatekeeper，也不要执行来源不明的终端命令。

## 第一次使用

1. 打开 Voxa。
2. 按照提示授予“辅助功能”和“输入监控”权限；修改权限后，建议完全退出并重新打开 Voxa。
3. 在 macOS“系统设置 → 蓝牙”中确认 Siri Remote 已连接。
4. 在 Voxa 中打开设备或遥控器设置，选择需要的按键、触控板和圆环操作。
5. 可在语言设置中选择简体中文、English、日本語、Français，或跟随系统。

## 更新旧版本

1. 退出正在运行的 Voxa。
2. 打开新版 DMG。
3. 将新版 `Voxa.app` 拖入“应用程序”，选择“替换”。
4. 重新打开 Voxa；通常会保留现有按键映射和设置。

## 常见问题

### 无法打开 Voxa

确认 Voxa 已经拖入“应用程序”，然后进入“系统设置 → 隐私与安全性”的“安全性”区域，找到 Voxa 的拦截提示并点击“仍要打开”。macOS 不需要永久开启“允许任何来源”。

### 按键映射没有反应

检查“辅助功能”和“输入监控”权限是否已开启，然后完全退出并重新打开 Voxa。不要同时保留多个同版本 Voxa 副本。

## 本版本重点

- 修复打开“软件更新”页面时的闪退问题。
- 最低系统版本调整为 macOS 13。
- 支持简体中文、英文、日文和法文界面。
- 保留 macOS 26 的新视觉效果，并为 macOS 13–15 提供兼容样式。

## 联系方式

如有问题或建议，请联系问题反馈邮箱：[huabeijinzongma@icloud.com](mailto:huabeijinzongma@icloud.com)。
