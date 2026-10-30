# 老电视专用｜红果 TV 老安卓播放优化版

![红果](hongguo-icon.png)

面向 Android 5 老电视的非官方修复版，基于 flywingjie/hongguoTV v1.0.6，恢复搜索、修复空结果报错和老电视图标显示等问题。**康佳 KKTV U65 / Android 5.1.1 实测可搜索并进入播放。**

- **下载 APK：** [hongguo-1.0.7-repair.apk](hongguo-1.0.7-repair.apk)（打开后点 Download raw file 下载）。
- **完整开源代码：** [源码、补丁与构建说明 ZIP](hongguotv-android5-repair-v1.0.7-repair-source.zip)，解压后包含完整上游源码、实际搜索补丁、构建入口、图标素材及许可证。
- **原作者：** [N3urda/hongguoTV](https://github.com/N3urda/hongguoTV)；**Android 5 兼容分支作者：** [flywingjie/hongguoTV](https://github.com/flywingjie/hongguoTV/tree/v1.0.6)；本次修复分享：eba367，Codex 辅助完成。

| 适配信息 | 说明 |
|---|---|
| 最低系统声明 | Android 5.0 / API 21 |
| 实测系统 | Android 5.1.1 / API 22 |
| 实际电视型号 | 康佳 KKTV U65（用户提供） |
| 系统上报型号 | Konka Android TV 2998 |
| 实测架构 | ARMv7 / armeabi-v7a |
| 软件版本 | 1.0.7-repair，com.hongguotv.nativeapp |

本版侧重老安卓兼容、搜索恢复和桌面显示；综合搜索支持剧名筛选、去重和分页。搜索「反派拿捏」返回三季，并从搜索结果播放第三季第 2 集，已出现真实首帧。

**播放范围说明：** 实测电视此前单独完成了匿名播放设备登记，该状态没有包含在 APK；本包不含新设备自动登记修复，全新安装播放尚未验证。没有大范围片源成功率或卡顿对比测试，不能保证每台电视、每个片源都可播放。

安装包使用独立签名，与上游签名不同；替换前先用应用自带功能导出资料，直接卸载会删除数据。建议关闭上游自动下载更新，避免签名冲突或修复被覆盖。

GPL-3.0-only，见 [LICENSE](LICENSE)。来源和依赖声明见源码包内 NOTICE；根目录 [NOTICE.md](NOTICE.md) 提供署名摘要（其相对路径以源码包解压目录为准）。不包含个人设备标识、观看记录或签名私钥，与内容平台官方无关联。
