# 律迹

<p align="center"><img src="luji-icon.svg" width="112" alt="律迹图标"></p>
<p align="center"><strong>把日子记下来，看见自己的节律。</strong></p>
<p align="center">Android · 离线记录 · 本地数据 · 无账号</p>

> 这是 **律迹的 APK 发布与反馈仓库**。这里提供安装包、更新说明和使用文档；应用源码、个人记录及签名密钥不在本仓库。

## ⬇️ 下载与更新

| 版本 | 内容 | 下载 |
| --- | --- | --- |
| **[0.6.2](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.6.2)** · 当前版 | 连续经期补记修复；详情自动收起；日历与配色优化 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.6.2/flight-log-android.apk) · [SHA-256](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.6.2/flight-log-android.apk.sha256) |
| [0.6.1](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.6.1) | 经期记录与预测、连续痛感、历史补记；首页及活动表单交互升级 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.6.1/flight-log-android.apk) · [SHA-256](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.6.1/flight-log-android.apk.sha256) |
| [0.5.7](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.5.7) | 新名称与图标；新导出文件使用「律迹」名称，兼容旧备份 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.7/flight-log-android.apk) · [SHA-256](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.7/flight-log-android.apk.sha256) |
| [0.5.6](https://github.com/XinMakerR/flight-log-updates/releases/tag/v0.5.6) | GitHub / Gitee 更新渠道；应用内下载与安装；多渠道反馈 | [APK](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.6/flight-log-android.apk) · [SHA-256](https://github.com/XinMakerR/flight-log-updates/releases/download/v0.5.6/flight-log-android.apk.sha256) |

[查看所有发行版](https://github.com/XinMakerR/flight-log-updates/releases) · [完整版本记录](CHANGELOG.md)

**首次安装**：在手机打开上方 APK 链接下载，点下载完成的文件，按 Android 系统提示安装。若系统拦截，请只为当前下载入口授予必要的“安装未知应用”权限。

**从旧版更新**：直接安装新版 APK 覆盖旧版。应用 ID `app.quietdays` 与原签名保持一致，正常覆盖安装会保留本地记录。**不要先卸载旧版，也不要清除应用数据。** 也可以在 App「设置 → 更新」选择 Gitee，检查后在 App 内下载并调用系统安装程序。下载前可用同版 .sha256 文件核对 APK。

**0.6.1 已在 GitHub 与 [Gitee](https://gitee.com/CM_acker/flight-log-updates/releases/tag/v0.6.1) 双渠道发布，安装包 SHA-256 一致。**

## ✨ 主要功能

| | 功能 |
| --- | --- |
| 📅 | 日历查看每日记录；新增、编辑、删除独立条目，同日可记多次 |
| 📊 | 按年、月、周、星期查看趋势与间隔，可按行为筛选 |
| ⏱️ | 手机传感器实时记录；显示估计频率、往返次数和曲线，可暂停及标记临界点 |
| 📥 | 宽松文本、标准 TXT / XLSX 导入；预览错误与重叠日期 |
| 📤 | 导出 TXT / XLSX，以及包含实时曲线的完整备份 TXT |
| 🌸 | 独立经期模式、每日流量/颜色/连续痛感、历史补记、周期分析及日期预测 |
| 👤 | 多用户资料、独立记录与色调；中文 / English、温和用语选项 |

**开始使用**：打开后先在首页日历选日期添加记录；想使用动作分析时，进入「实时记录」，将手机固定在合适位置再开始。传感器只测量**手机自身的运动**，频率与次数是估计值，不能作为医学或锻炼效果判断。结束前可手动修正次数。经期预测仅为日期推算，不能确认排卵或判断避孕安全。

[🌸 经期记录与格式](PERIODS.md) · [📥 活动导入规则](IMPORT.md) · [📖 详细使用说明](USAGE.md) · [🔒 隐私与数据说明](PRIVACY.md)

## 💬 反馈与交流

- [Gitee Issues](https://gitee.com/CM_acker/flight-log-updates/issues)：提交问题或功能建议。
- [GitHub Issues](https://github.com/XinMakerR/flight-log-updates/issues/new/choose)：备用反馈渠道。
- QQ 群：**922792074**（App 设置页可一键复制群号）。

Issues 公开可见。请描述 App 版本、操作步骤与实际现象，**不要上传个人记录、导出文件、含隐私的截图或日志**。

## 🔐 数据归属

律迹不要求账号。记录存储在手机的应用私有空间；没有云同步，系统云备份已关闭。手动导出的文件是**明文**，请保存在可信位置。卸载 App 或清除应用数据会删除本地记录，更新前可先导出完整备份。详见[隐私与数据说明](PRIVACY.md)。

---

下载请以本仓库发行版为准；[Gitee 备用渠道](https://gitee.com/CM_acker/flight-log-updates/releases)请核对实际版本。这个仓库不包含应用源码。

## 0.6.2 更新

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

