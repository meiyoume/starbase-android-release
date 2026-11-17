# 星幕影院 安卓版 · 安装包与自动更新源

星幕影院（平板版 / 手机版）的公开安装包仓库。应用内「设置 → 关于 → 检查更新」会读取本仓库的最新 Release：

- 最新版本：<https://github.com/meiyoume/starbase-android-release/releases/latest>
- 接口：`https://api.github.com/repos/meiyoume/starbase-android-release/releases/latest`

## 下载

每次 Release 附带两个 APK：

| 文件 | 说明 |
| --- | --- |
| `星幕影院-平板版-x.y.z.apk` | 侧栏导航 + 横竖屏都支持 |
| `星幕影院-手机版-x.y.z.apk` | 底部标签栏 + 锁竖屏 |

两个包应用 ID 不同（`com.starbase.tablet` / `com.starbase.phone`），可以装在同一台设备上。

## 应用内更新

安卓版在「设置 → 关于」点「检查更新」：查到新版会显示更新说明，点「下载并安装」直接下载并在系统安装器里确认安装。
安装前会校验下载包的包名和版本号（不比当前新就不装）。
第一次使用需要允许「星幕影院」安装应用（系统设置 → 安装未知应用）。
