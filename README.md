# TXT转EPUB转换器

一个专为安卓15设计的TXT格式小说转EPUB格式的转换器应用。

## 功能特点

- 📱 专为安卓15优化，支持最新的Material Design 3设计语言
- 🎨 采用谷歌蓝和纯白色配色方案，界面简洁美观
- 📖 支持TXT文件读取和EPUB格式转换
- 📑 智能章节分割功能，自动识别章节标题
- 🖼️ 可选的默认封面添加
- 💾 转换后的EPUB文件自动保存到设备存储

## 技术特性

- 使用Kotlin和Jetpack Compose构建
- Material Design 3设计系统
- 响应式UI设计
- 异步文件处理
- 完整的EPUB格式支持

## 系统要求

- Android 7.0 (API 24) 或更高版本
- 推荐Android 15以获得最佳体验
- 需要存储权限用于文件读写

## 使用方法

1. 启动应用
2. 点击"选择TXT文件"按钮选择要转换的TXT文件
3. 根据需要调整转换选项：
   - 自动分割章节：开启后会自动识别并分割章节
   - 添加默认封面：为EPUB添加一个简单的封面页
4. 点击"转换"按钮开始转换
5. 转换完成后，EPUB文件会保存到设备的应用专用目录

## 项目结构

```
app/
├── src/main/
│   ├── java/com/example/txttoepubconverter/
│   │   ├── MainActivity.kt              # 主Activity
│   │   ├── TxtToEpubConverterApp.kt    # 主UI组件
│   │   ├── ConverterViewModel.kt       # 转换逻辑ViewModel
│   │   └── EpubGenerator.kt            # EPUB生成器
│   ├── res/
│   │   ├── values/
│   │   │   ├── strings.xml             # 字符串资源
│   │   │   ├── themes.xml              # 主题配置
│   │   │   └── colors.xml              # 颜色资源
│   │   ├── drawable/
│   │   │   └── ic_launcher_foreground.xml  # 应用图标
│   │   └── mipmap-*/                   # 不同分辨率的图标
│   └── AndroidManifest.xml             # 应用清单
└── build.gradle.kts                    # 应用构建配置
```

## 构建说明

1. 确保已安装Android Studio和Android SDK
2. 克隆项目到本地
3. 在Android Studio中打开项目
4. 等待Gradle同步完成
5. 点击"Build" -> "Build Bundle(s) / APK(s)" -> "Build APK(s)"
6. 生成的APK文件位于`app/build/outputs/apk/debug/`目录

## 许可证

本项目采用MIT许可证。

## 贡献

欢迎提交Issue和Pull Request来改进这个项目。 