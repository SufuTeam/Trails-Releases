# Trails 安装与反馈

Trails 是一个用于记录徒步、管理路线和收藏、同步个人户外资料的应用。本仓库用于发布安装包、更新说明，以及收集 Android / iOS 用户的问题和建议。

| 平台 | 安装入口 | 更新方式 |
| --- | --- | --- |
| Android | [GitHub 最新安装包](https://github.com/SufuTeam/Trails-Releases/releases/latest) | 下载新版 APK，由 Android 系统确认安装 |
| iPhone / iPad | [加入 TestFlight](https://testflight.apple.com/join/Zn7j9ugp) | 在 TestFlight 更新，也可在 TestFlight 中开启自动更新 |

Android 最新测试版以 GitHub Release 为准，沿用正式签名，可覆盖安装现有版本。GitHub 下载页面中，请选择以 `.apk` 结尾的附件；`Source code` 压缩包是本仓库的说明文件，不能安装。

## 安装与升级

- 当前应用标识为 `com.sufu.trails`。使用相同标识、相同签名且构建号更高的 APK，可以覆盖升级；升级前请保留重要轨迹的备份。
- Android 首次从浏览器安装时，按系统提示允许该浏览器安装应用，并自行确认安装。
- 旧版 Android `com.celtis.trails` 与当前应用是两个独立应用，不能直接覆盖，也不自动继承本地资料。请保留旧应用直到确认资料已处理妥当。
- iOS 测试版通过 TestFlight 安装。GitHub 不提供可供普通 iPhone 直接安装的 IPA。
- [蒲公英](https://www.pgyer.com/trails-android-x) 是独立分发渠道，构建号可能与 GitHub 不同，请以该渠道页面标注为准。

## 反馈问题和提出建议

[提交问题或建议](https://github.com/SufuTeam/Trails-Releases/issues/new/choose) · [查看已有反馈](https://github.com/SufuTeam/Trails-Releases/issues)

请先搜索是否已有相同问题，填写平台、版本及构建号、设备与系统版本、复现步骤，并尽可能附上处理过私人信息的截图。提交反馈需要 GitHub 账号。Issues 是公开页面，请不要上传密码、恢复码、访问凭据、私人照片、完整轨迹或住址。

## 发布信息

[更新记录及安装包](https://github.com/SufuTeam/Trails-Releases/releases) · [公开版本清单](updates.json)

版本清单按 Android 与 iOS 分别记录构建号。只有已发布的 Android 包、已获准公开测试且仍有效的 iOS 构建才会标记为可更新。

新接入的 App 更新功能支持启动后的温和提醒、手动检查和稍后提醒；此功能需要安装包含它的新版 App 后才生效。建立此仓库不会让此前安装的旧版 App 自动获得新的提示功能。

应用源码在单独维护的私有仓库中。本仓库不授予应用二进制或品牌素材的开源许可。
