# Cinna Bookkeeping

English | [简体中文](./README.zh-CN.md)

Personal bookkeeping for iOS and Android.

Record income and expenses with a category, date, and note. Transactions stay on the device, and everyday recording works offline.

## Records and reports

- Browse transactions by month, search, filter, edit, and delete entries.
- Check income, spending, balance, and monthly budget progress.
- View category breakdowns, recent trends, and daily activity.
- Review possible duplicates and export records as CSV.

## Run from source

| Platform | Requirements | Start |
| --- | --- | --- |
| iOS | macOS, Xcode 16, XcodeGen; iOS 17+ | Generate the Xcode project, then run on a device or simulator. |
| Android | Android Studio, JDK 17; Android 8.0+ | Open `android` and run the app. |

For iOS:

```sh
cd ios
xcodegen generate
open CinnaBookkeeping.xcodeproj
```

[Cinna Design](https://github.com/icelemon233/cinna-design) is the visual reference for the app. Licensed under [MIT](./LICENSE).
