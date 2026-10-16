# Cinna Bookkeeping

English | [简体中文](./README.zh-CN.md)

A personal bookkeeping app for iOS and Android, with a soft cloud-and-dessert visual style. Record everyday income and expenses, keep an eye on your monthly budget, and see where your money goes.

## What you can do

- Add income and expenses with a category, date, and note.
- Browse, search, filter, edit, and delete transactions.
- View monthly income, spending, balance, and budget progress.
- Explore category breakdowns, spending trends, and daily activity.
- Spot possible duplicate entries and export records as CSV.

Records are stored locally on the device, so everyday bookkeeping works offline.

## Try it from source

**iOS:** Requires macOS, Xcode 16, XcodeGen, and an iOS 17 or newer device or simulator.

```sh
cd ios
xcodegen generate
open CinnaBookkeeping.xcodeproj
```

Choose a device or simulator in Xcode and run the app.

**Android:** Open the `android` directory in Android Studio with JDK 17, then run the app on an Android 8.0 or newer device or emulator.

## Related project

[Cinna Design](https://github.com/icelemon233/cinna-design) provides the visual direction shared by the Cinna projects.

## License

[MIT](./LICENSE).
