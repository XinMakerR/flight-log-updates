# 律迹 0.6.2 · 连续经期补记修复

- 相邻日期的“月经来了”快捷操作直接合并同一次经期，不再弹出区间编辑或间隔错误。
- 补记前一天会保留已记录的结束日；在结束的次日记录开始，会继续原经期。
- 补齐两段中间的一天时自动衔接，原有每日详情保留，用户之间互不影响。
- 未记录经期的日期收起流量、经血颜色和痛感，症状与备注常驻；详情随当天经期状态平滑展开、收起，不因误触弹窗。
- 今日标识改为日期下方短横线；五个日历图例等宽对齐，模式切换时淡入滑动过渡。
- 调整性生活的棕色系配色，改用珊瑚粉和蔷薇色，并同步筛选、符号和统计底色。
- 日历预测计算移到日期循环外，避免重复计算。
- 每日详情更新使用同一事务，避免快速编辑痛感、备注时覆盖刚写入的经期确认标记。

版本0.6.2，内部版本17。包名与签名保持兼容，可覆盖安装；请勿先卸载或清除数据。


# 版本记录

[返回首页](README.md) · [全部发行版](https://github.com/XinMakerR/flight-log-updates/releases)

| 版本 | 发布说明 | 安装包 |
| --- | --- | --- |
| [0.6.1](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.6.1) | 按用户独立的经期模式、问卷、历史补记、流量/颜色/连续痛感、周期与日期预测；完整备份2及专用导入导出；紧凑活动表单、选日添加、固定编辑和翻页动画 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.6.1/flight-log-android.apk) |
| [0.5.7](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.5.7) | 应用名称改为「律迹」，启用新 SVG / 自适应图标；新导出及完整备份使用新名称，仍支持旧名称备份导入；包名与签名不变 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.7/flight-log-android.apk) |
| [0.5.6](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.5.6) | 新增 GitHub / Gitee 更新渠道选择；可在 App 内下载并调起系统安装程序；提供 Gitee Issues、GitHub Issues 和 QQ 群反馈入口 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.6/flight-log-android.apk) |

这里列出 **GitHub 仓库已公开发布**的版本。每个发行版同时提供校验文件 `flight-log-android.apk.sha256`；请从对应版本页面下载配套文件，不要混用。

0.6.0 为研发阶段，相关经期功能在0.6.1首次正式发布。详见[0.6.1完整说明](RELEASE-0.6.1.md)。
