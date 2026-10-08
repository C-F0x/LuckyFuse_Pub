# Breeno Keyboard（小布输入法）

| 项目 | 内容 |
| --- | --- |
| 应用包名 | `com.oplus.keyboard` |
| 应用来源 | OPPO应用商店|
| 测试版本 | [1.8.33-mkt](https://t.me/colorapkshare/7039) |
| 文档语言 | [English](../en-US/breeno-keyboard.md) · 简体中文 |

---

## 功能

### [液态玻璃 (点击预览)](https://github.com/user-attachments/assets/51fb888b-9fa4-42fe-9e29-a8ac28e2124a)

解除作用域限制

自定义背景模糊/按键模糊 系数

自定义浅色/暗色遮罩的颜色/透明度

提供快捷预览按钮，修改实时生效

### [键盘效果 (点击预览)](https://github.com/user-attachments/assets/54431cfb-412a-42f2-915b-c0f2e4b21b34)

对于 [Keys cafe](https://galaxystore.samsung.com/detail/com.samsung.android.keyscafe) 的光效/动效移植

提供快捷预览按钮，修改实时生效

### 功能增强

支持内嵌密码管理器气泡 ( 需修改系统框架/修改安装包内 XML添加声明 )
把自动填充作为快捷方式，添加到输入法工具表单

---

## 常见问题

热重载不生效的情景下，可以尝试强制停止

```adb
adb shell am force-stop com.oplus.keyboard
```

