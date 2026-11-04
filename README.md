# 易卜奇门 · 内测发布

这个仓库只用于易卜奇门 Android 内测版的自动更新与安装包分发。

- `update.json`：客户端启动时读取的版本清单，放在每个 Release 的资产中。
- `yibu-qimen-<version>-debug.apk`：对应版本的调试签名安装包。
- 客户端通过 `releases/latest/download/update.json` 读取最新版本。

> 当前 APK 使用 Android debug 签名，只用于内测和功能验证，不应作为应用商店正式包。
