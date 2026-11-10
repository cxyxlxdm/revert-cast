# 余音 · Reverb

> 余音绕梁，隽永悠长。 · *Every echo lingers.*

一款轻量的多端播客客户端，四个原生端：**Android**(Kotlin / Compose)、**HarmonyOS**(ArkTS / ArkUI)、**macOS**(Swift / SwiftUI)、**iOS**(Swift / SwiftUI)。水墨底 + 青瓷 + 梁金配色，图标以「金色横梁 + 环绕向上的声波」诠释「余音绕梁」。

---
本仓库提供 Android 端和 macOS 端的安装包。HarmonyOS 端可以在华为应用商店下载；iOS 的正式分发走 TestFlight，本页那份 ipa 只是归档用的**未签名**产物（见下表说明）。

## 当前版本：1.0.7（2026-11-10）

下载：[Releases](https://github.com/cxyxlxdm/revert-cast/releases/latest)

| 文件 | 平台 | 大小 | SHA-256 |
|---|---|---|---|
| `reverb.apk` | Android | 65,180,564 B | `2278c1016e0b3614bfaf6bd6f00876f9e07b7d166d88d886883d5d775b8adf24` |
| `Reverb.dmg` | macOS（universal：Intel 与 Apple 芯片同一份） | 5,481,722 B | `75d8d509e5d62756e966e4ef31677a3079862b8df35d569e2b1e45fac2e2b735` |
| `reverb-ios-1.0.7-1-unsigned.ipa` | iOS（**未签名，不能直接安装**） | 2,623,640 B | `ec57dc9ff1e3014bf70c87a0a5afa5bff848a550c646ae4179af731856483f61` |

下载后可自行核对：`shasum -a 256 <文件>`，应与上表逐字相同。

> ⚠️ iOS 那份 ipa 没有签名：本机唯一的开发描述文件已于 2026-11-09 到期，且 Xcode 当前没有登录任何
> Apple 账号，无法生成新的签名。它只用于归档与包内结构校验（`codesign -dv` 会报
> `code object is not signed at all`），**不能装到 iPhone 上**；iOS 的可用版本请走 TestFlight。
