# Breeno Keyboard

| Name| Contents |
| --- | --- |
| Package | `com.oplus.keyboard` |
| Source | OPPO App Market |
| Tested version | [1.8.33-mkt](https://t.me/colorapkshare/7039) |
| Language | English · [简体中文](../zh-CN/breeno-keyboard.md) |

---

## Features

### [Liquid Glass (Click to preview)](https://github.com/user-attachments/assets/51fb888b-9fa4-42fe-9e29-a8ac28e2124a)

Removes the scope restriction

Custom background blur / key blur intensity

Custom light and dark mask color and opacity

Quick preview button, changes take effect in real time

### [Keyboard Effects (Click to preview)](https://github.com/user-attachments/assets/54431cfb-412a-42f2-915b-c0f2e4b21b34)

A port of the light and motion effects from [Keys Cafe](https://galaxystore.samsung.com/detail/com.samsung.android.keyscafe)

Quick preview button, changes take effect in real time

### Enhancements

Supports inline password manager suggestions (requires modifying the system framework, or adding the declaration to the XML inside the app package)

Adds autofill as a shortcut on the keyboard toolbar

---

## FAQ

If hot reload does not take effect, try force-stopping the app

```adb
adb shell am force-stop com.oplus.keyboard
```
