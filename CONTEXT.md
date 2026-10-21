# 靶域发布入口

更新：2026-10-21。

本仓库由用户指定，用于靶域 Range Zero 的公开 APK 分发与后续版本检查。当前正在准备首个公开版本 0.1.2；最终发布状态以 GitHub Releases 为准。

游戏为 Android 离线 FPS 试玩，包含一张石城练场、一把 M4A1、12 款涂装、靶场和少量人机。对局无需网络；用户手动检查更新时从本仓库读取版本清单。

本仓库不保存游戏源码和签名材料。发布时将 APK、latest.json 与 SHA256SUMS.txt 放到同一 Release，核对后发布，再更新 main 分支的 latest.json。
