# 靶域发布入口

更新：2026-10-21。

本仓库由用户指定，用于靶域 Range Zero 的公开 APK 分发与后续版本检查。首个公开版本 [0.1.2](https://github.com/junnhwan/range-zero/releases/tag/v0.1.2) 已于 2026-10-21 发布并设为 latest，版本码为 3。

APK 为 `RangeZero-0.1.2-android.apk`，91,234,823 字节，SHA-256 为 `a281402da2e449236b9a5b4310c6b1dd3a36e93a2dbe3922f19d77d135bdc3a4`。四个 Release 资产已核对 GitHub 服务端大小与 SHA-256；已通过 31 项玩法、23 项更新规则、5 项本地 HTTP 和 19 项 Android 模拟器检查，并实测原签名从 0.1.1 覆盖升级保留皮肤。真实手机仍待用户试玩。

游戏为 Android 离线 FPS 试玩，包含一张石城练场、一把 M4A1、12 款涂装、靶场和少量人机。对局无需网络；用户手动检查更新时从本仓库读取版本清单。

0.1.2 提供最多两路并发、整体 10 秒内的查新，以及三条固定加速下载线路和 GitHub 直连。下载由系统浏览器接管，失败可返回换线。APK 额外修复一次返回被重复通知而切换两次状态的问题。

本仓库不保存游戏源码和签名材料。发布时将 APK、latest.json 与 SHA256SUMS.txt 放到同一 Release，核对后发布，再更新 main 分支的 latest.json。
