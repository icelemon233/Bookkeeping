# Cinna Bookkeeping · 肉桂卷记账

[English](./README.md) | 简体中文

面向 iOS 和 Android 的个人记账应用，采用柔和的云朵甜点风格。随手记录日常收支，掌握月度预算，看看钱都花在了哪里。

## 可以做什么

- 记录收入与支出，添加分类、日期和备注。
- 按月浏览账单，支持搜索、筛选、编辑与删除。
- 查看月度收入、支出、结余和预算进度。
- 通过分类占比、消费趋势和每日记录了解支出习惯。
- 提醒可能重复的账单，将记录导出为 CSV。

账单保存在设备本机，日常记账可离线使用。

## 从源码体验

**iOS：** 需要 macOS、Xcode 16、XcodeGen，以及 iOS 17 或更新版本的设备或模拟器。

```sh
cd ios
xcodegen generate
open CinnaBookkeeping.xcodeproj
```

在 Xcode 中选择设备或模拟器，运行应用。

**Android：** 使用配置了 JDK 17 的 Android Studio 打开 `android` 目录，在 Android 8.0 或更新版本的设备或模拟器上运行。

## 相关项目

[Cinna Design](https://github.com/icelemon233/cinna-design) 提供 Cinna 系列项目共用的视觉方向。

## 许可证

[MIT](./LICENSE)。
