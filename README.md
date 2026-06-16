# 训练秒表

一个最小化的 Android WebView 项目，用来把本地 `HTML` 秒表页面封装成安卓应用。

## 项目内容

- 应用名称：`训练秒表`
- 运行方式：离线本地 `WebView`
- 页面入口：`app/src/main/assets/index.html`
- 方向：竖屏

## 适合发布到 GitHub 的部分

建议提交这些内容：

- `app/src/main`
- `app/build.gradle.kts`
- `build.gradle.kts`
- `settings.gradle.kts`
- `gradle.properties`
- `proguard-rules.pro`
- `.gitignore`

不建议提交这些内容：

- `local.properties`
- `.gradle/`
- `build/`
- `app/build/`
- 已生成的 `apk`

## 本地打开

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

这个仓库默认适合源码托管和测试包构建。

如果要对外正式分发，建议另外生成一个 `release APK`，并配置你自己的签名信息。
