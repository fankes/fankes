## 开发者公开要饭啦 👋

非常抱歉占用你的一点宝贵时间，请允许我向你推荐一些我精心维护的开源项目，如果你对这些项目感兴趣，并能给予它们一些关注和支持，我将不胜感激。

我一直在用爱发电做着这些微小的事情，希望这些项目能对你有用，如果你觉得它们好用的话，不妨给项目点个 star 或者关注一下我的 GitHub 账号吧，非常感谢你的支持！

我的 GitHub 账号，[点击这里前往查看](https://github.com/fankes)。

下面的内容分为 `开发者相关`、`Xposed 模块相关`、`更多项目`、`联系方式`、`捐赠支持` 版块。

## 开发者相关

为开发人员提供帮助的依赖库。

### SweetDependency

一个轻松自动装配和管理依赖的 Gradle 插件。

**推荐指数** ⭐⭐⭐⭐⭐

Gradle 复杂的依赖管理以及依赖更新功能是否让你感到十分麻烦？快来使用 `SweetDependency`，它无需任何第三方依赖，无需使用 `buildSrc`，无需使用 `includeBuild`，
一键集成即插即用，使用 YAML 人性化语言作为依赖管理的配置文件，你的项目所有依赖都可以快速管理，一键升级，还有更多功能等你来发现！

[点击这里前往查看](https://github.com/HighCapable/SweetDependency)

### SweetProperty

一个轻松在任意地方获取项目属性的 Gradle 插件。

**推荐指数** ⭐⭐⭐⭐⭐

如果你的项目正在使用 Kotlin DSL 作为构建脚本，那么这一款 Gradle 插件绝对能帮助到你，快来使用 `SweetProperty`，它能自动分析你的项目中 `gradle.properties`
甚至是系统环境变量中的属性键值， 自动生成对构建脚本以及项目中使用的属性键值调用代码，能够实现使用代码直接调用对应的属性键值内容！

[点击这里前往查看](https://github.com/HighCapable/SweetProperty)

### FlexiLocale

一个自动为 Android 项目生成国际化字符串调用的 Gradle 插件。

**推荐指数** ⭐⭐⭐⭐⭐

如果你厌倦了 Android 开发中 `context.getString(R.string.xxx)` 超级麻烦的国际化字符串适配，那么这一款 Gradle 插件绝对能帮助到你，快来使用 `FlexiLocale`，
它能自动分析你的项目中 `res/values` 目录中声明的国际化字符串并自动生成调用类，只需几步即可完成国际化字符串的调用！

[点击这里前往查看](https://github.com/BetterAndroid/FlexiLocale)

### YukiHookAPI

一个使用 Kotlin 构建的高效 Hook API 与 Xposed 模块解决方案。

**推荐指数** ⭐⭐⭐⭐⭐

你想快速拥有一个自己的 Xposed 模块吗，你只需要拥有基础的 Android 开发经验以及掌握基础的 Kotlin 编程语言即可，快来试试 `YukiHookAPI`，
这是一个专为你打造的高效 Hook API 与 Xposed 模块解决方案，助你的开发变得更轻松！

[点击这里前往查看](https://github.com/fankes/YukiHookAPI)

### YukiReflection

一个使用 Kotlin 构建的 Java、Android 平台高效反射 API。

**推荐指数** ⭐⭐⭐⭐⭐

正在使用 Kotlin 的你厌倦了 Java 繁琐而一成不变的反射 API 吗，快来试试 `YukiReflection`，
它是 `YukiHookAPI` 中正在使用的用 Kotlin 实现的高效 Java 反射 API，能在你的任何 Java 和 Android 项目中使用！

[点击这里前往查看](https://github.com/fankes/YukiReflection)

### maven-repository-template

这是一个使用 GitHub 管理依赖的简单 Maven 存储库。

**推荐指数** ⭐⭐⭐⭐

你可以使用这个模版项目来创建自己的 Maven 存储库，无需服务器，无需第三方插件，使用 GitHub 直接管理你的私有依赖！

[点击这里前往查看](https://github.com/HighCapable/maven-repository-template)

## Xposed 模块相关

为 Android 设备实现拓展功能的小工具。

### TSBattery

TSBattery 是一个旨在使 QQ、TIM、微信 变得更省电的开源 Xposed 模块。

**推荐指数** ⭐⭐⭐⭐

如果你觉得 QQ、TIM、微信在你的设备上消耗了过多的电量，不妨来试一下 `TSBattery`，它能够有效地¹减少你设备不必要的耗电，设备待机时让这些应用安静地保持运行。

**备注**

(1) 在一定条件下是有效的，具体请仔细阅读模块界面的说明。

[点击这里前往查看](https://github.com/fankes/TSBattery)

### MIUINativeNotifyIcon

修复被 MIUI 开发组丢弃的原生通知图标，支持 MIUI 11、12、12.5、13、14 以及最新版本。

**推荐指数** ⭐⭐⭐⭐

MIUI 破坏原生规范无法容忍，这将导致大量 AOSP 提供的 API
失效，我出于无奈而写了这个模块，并衍生出了 [Android 通知图标规范适配计划](https://github.com/fankes/AndroidNotifyIconAdapt)。

后期这个项目的功能会合并到一个新的通知图标优化模块上。

[点击这里前往查看](https://github.com/fankes/MIUINativeNotifyIcon)

### ColorOSNotifyIcon

为 ColorOS 优化通知图标以及适配原生通知图标规范，理论支持 OxygenOS 和 RealmeUI。

**推荐指数** ⭐⭐⭐⭐

这个项目是我根据 MIUI 原生通知图标的基础上加以修改并分离，让其适配了
ColorOS，此项目同样对接到了 [Android 通知图标规范适配计划](https://github.com/fankes/AndroidNotifyIconAdapt)。

后期这个项目的功能会合并到一个新的通知图标优化模块上。

[点击这里前往查看](https://github.com/fankes/ColorOSNotifyIcon)

### AppErrorsTracking

为原生 FC 对话框增加更多功能并修复国内定制 ROM 删除 FC 对话框的问题，给 Android 开发者带来更好的体验。

**推荐指数** ⭐⭐⭐⭐⭐

国内的定制 Android 基本上删除了 FC 弹窗，且拥有 FC 弹窗时的有限信息也不能清晰地展示或记录错误日志，开发者只有通过 ADB
连接电脑或厂商提供的抓取设备调试日志等功能才能获得不完全清晰的错误日志，无法准确地分析应用崩溃的原因，
这也是这个项目诞生的原因，它能够使用模块的方式，在不连接电脑的情况下，直接捕获任意应用的异常，清晰地展示出完整的错误日志。

[点击这里前往查看](https://github.com/KitsunePie/AppErrorsTracking)

## 更多项目

一些未分类的更多我的开源项目。

### AndroidNotifyIconAdapt

这是一个在线规则平台，为国内 Android 不规范的 APP 和厂商适配原生通知图标与规范图标修复。

**推荐指数** ⭐⭐⭐⭐⭐

随着国内 Android 应用生态的日渐恶化，越来越多地厂商不会刻意去为 Android 适配原生的通知图标，即使是适配了也会被 ROM 厂商魔改掉，
但这也会造成正在使用原生或类原生的 Android 通知图标出现黑块或者白块，严重影响使用体验。

在线规则平台靠的是你们的贡献和建议，欢迎为应用的通知图标适配做出你的贡献👏🏻

[点击这里前往查看](https://github.com/fankes/AndroidNotifyIconAdapt)

## 联系方式

- [Telegram 群组](https://t.me/XiaofangInternet)
- [Telegram 群组 (开发者)](https://t.me/HighCapable_Dev)
- [QQ 群](https://qm.qq.com/cgi-bin/qm/qr?k=dp2h5YhWiga9WWb_Oh7kSHmx01X8I8ii&jump_from=webapi&authKey=Za5CaFP0lk7+Zgsk2KpoBD7sSaYbeXbsDgFjiWelOeH4VSionpxFJ7V0qQBSqvFM)
- [QQ 频道](https://pd.qq.com/s/44gcy28h)
- [酷安](http://www.coolapk.com/u/876977)
- [Twitter (X)](https://twitter.com/fankesyooni)

## 捐赠支持

工作不易，无意外情况这些项目将继续维护下去，提供更多可能，欢迎打赏。

<img src="https://raw.gitmirror.com/fankes/fankes/main/img-src/payment_code.jpg" width = "500" alt="Payment Code"/>