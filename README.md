# 训练秒表

一个极简 Android WebView 项目，用来把本地 HTML 秒表页面封装成可安装的安卓 APK。它的优势是体积轻、启动快、离线可用、无需 OBB，安装和分发都更简单。

## 项目说明

- 应用名称：`训练秒表`
- 运行方式：离线本地 `WebView`
- 页面入口：`app/src/main/assets/index.html`
- 屏幕方向：竖屏
- 是否需要 OBB：不需要

## 当前发布内容

当前仓库已经包含：

- Android 项目源码
- 已发布的 GitHub Release
- 可直接测试安装的 APK

Release 页面：

- [v1.0.0](https://github.com/hanghu5820/training-stopwatch-android/releases/tag/v1.0.0)

## 适合提交到 GitHub 的内容

建议提交这些内容：

- `app/src/main`
- `app/build.gradle.kts`
- `build.gradle.kts`
- `settings.gradle.kts`
- `gradle.properties`
- `proguard-rules.pro`
- `.gitignore`
- `LICENSE`
- `README.md`

不建议提交这些内容：

- `local.properties`
- `.gradle/`
- `build/`
- `app/build/`
- 已生成的 `apk`
- 已生成的 `aab`

## 本地打开方式

1. 用 Android Studio 打开项目根目录。
2. 等待 Gradle 同步完成。
3. 在项目根目录创建 `local.properties`。
4. 把 `sdk.dir` 指向你自己的 Android SDK。
5. 运行 `app` 模块，或直接构建 APK。

## local.properties 示例

参考 `local.properties.example`：

```properties
sdk.dir=/path/to/your/android/sdk
```

## 说明

这个仓库适合：

- 源码托管
- 本地调试
- 测试包构建
- GitHub 发布

当前 Release 中提供的是测试用途的 APK。

如果后续要正式对外分发，建议另外生成：

- `release APK`
- 正式签名包
- 对应版本号的发布记录

## License

本项目使用 `MIT License`。
