# 余音 · Reverb

> 余音绕梁，隽永悠长。 · *Every echo lingers.*

一款轻量的多端播客客户端，四个原生端：**Android**(Kotlin / Compose)、**HarmonyOS**(ArkTS / ArkUI)、**macOS**(Swift / SwiftUI)、**iOS**(Swift / SwiftUI)。水墨底 + 青瓷 + 梁金配色，图标以「金色横梁 + 环绕向上的声波」诠释「余音绕梁」。

---
本仓库提供 Android 端和 macOS 端的安装包。HarmonyOS 端可以在华为应用商店下载；iOS 的正式分发走 TestFlight。

## 当前版本：1.0.8（2026-11-18）

下载：[Releases](https://github.com/cxyxlxdm/revert-cast/releases/latest)

| 文件 | 平台 | 大小 | SHA-256 |
|---|---|---|---|
| `reverb.apk` | Android | 270,204,108 B | `f993443f69dfd48d4c3b4384d67a58330fd0fa17e4a903c998d4ba5d9373c973` |
| `Reverb.dmg` | macOS（universal：Intel 与 Apple 芯片同一份） | 6,305,244 B | `f746855898782e3f63ff86c6c51a53976324079716c579b8d30cd817f79829de` |

下载后可自行核对：`shasum -a 256 <文件>`，应与上表逐字相同。

> Android 安装包自 1.0.8 起约 270 MB：离线语音识别改用 SenseVoice 模型，模型随包提供，装完即离线可用。
