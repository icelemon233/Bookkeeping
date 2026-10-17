<p align="center"><img src="./docs/brand/cinna-app-icon.png" alt="Cinna Bookkeeping Cinna icon" width="128"></p>

<h1 align="center">Cinna Bookkeeping · 肉桂卷记账</h1>

<p align="center"><a href="./README.md">English</a> · 简体中文</p>

面向 iOS 和 Android 的个人记账应用。

按分类、日期和备注记录收支。账单保存在设备本机，日常记账可离线使用。

## 账单与统计

- 按月浏览账单，支持搜索、筛选、编辑和删除。
- 查看收支、结余和月度预算进度。
- 查看分类占比、近期趋势和每日记录。
- 提醒可能重复的账单，支持导出 CSV。

## 从源码运行

| 平台 | 环境要求 | 启动方式 |
| --- | --- | --- |
| iOS | macOS、Xcode 16、XcodeGen；iOS 17+ | 生成 Xcode 工程，在设备或模拟器运行。 |
| Android | Android Studio、JDK 17；Android 8.0+ | 打开 `android` 目录，运行应用。 |

iOS 工程生成命令：

```sh
cd ios
xcodegen generate
open CinnaBookkeeping.xcodeproj
```

应用视觉参考 [Cinna Design](https://github.com/icelemon233/cinna-design)。采用 [MIT 许可证](./LICENSE)。
