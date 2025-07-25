# Android 技术栈思维导图

## 1. 编程语言
- Kotlin (官方首选)
- Java (传统支持)
- C/C++ (NDK 开发)

## 2. 基础组件
- **四大组件**
  - Activity
  - Service
  - BroadcastReceiver
  - ContentProvider
- **应用资源**
  - 布局资源
  - 值资源 (strings.xml/dimens.xml)
  - 图片资源 (drawable/mipmap)
  - 原始资源 (raw)

## 3. UI/UX 开发
- **核心UI组件**
  - View / ViewGroup
  - 常用控件 (TextView, Button, RecyclerView 等)
- **布局系统**
  - XML 布局
  - 约束布局 (ConstraintLayout)
  - 线性布局 (LinearLayout)
  - 帧布局 (FrameLayout)
- **现代UI工具**
  - Jetpack Compose (声明式UI)
  - Material Design 组件
- **动画**
  - 属性动画 (Property Animation)
  - 视图动画 (View Animation)
  - Lottie 动画库

## 4. 架构模式
- MVC (Model-View-Controller)
- MVP (Model-View-Presenter)
- MVVM (Model-View-ViewModel)
  - Jetpack ViewModel
  - LiveData / Flow
- MVI (Model-View-Intent)
- Clean Architecture

## 5. Jetpack 组件库
- **生命周期管理**
  - Lifecycle
  - ViewModel
- **数据管理**
  - Room (数据库)
  - DataStore (替代 SharedPreferences)
- **后台任务**
  - WorkManager
- **导航**
  - Navigation Component
- **其他**
  - Hilt (依赖注入)
  - Paging 3 (分页加载)
  - CameraX

## 6. 网络通信
- 协议
  - HTTP/HTTPS
  - WebSocket
- 库
  - Retrofit + OkHttp
  - Volley (传统)
  - gRPC
- 数据格式
  - JSON (Gson/Moshi)
  - Protocol Buffers
  - XML

## 7. 数据存储
- 轻量级存储
  - SharedPreferences
  - DataStore
- 数据库
  - SQLite
  - Room ORM
  - Realm
- 文件存储
  - 内部存储
  - 外部存储
- 云存储
  - Firebase Storage
  - AWS S3

## 8. 依赖注入
- Dagger 2 / Hilt (官方推荐)
- Koin (Kotlin 轻量级方案)

## 9. 异步处理
- Kotlin 协程 (Coroutines)
- RxJava / RxKotlin
- Handler / Looper
- Executors

## 10. 性能优化
- **内存优化**
  - 内存泄漏检测 (LeakCanary)
  - 内存分析 (Profiler)
- **渲染优化**
  - 过度绘制检测
  - 布局层级优化
- **网络优化**
  - 缓存策略
  - 数据压缩
- **启动优化**
  - 冷启动优化
  - 启动时序分析

## 11. 测试
- **单元测试**
  - JUnit
  - MockK / Mockito
- **UI 测试**
  - Espresso
  - UI Automator
- **集成测试**
  - 端到端测试
- **性能测试**
  - Benchmark 库

## 12. 安全
- 数据加密
  - Android Keystore
  - EncryptedSharedPreferences
- 网络安全
  - SSL Pinning
  - HTTPS 证书校验
- 代码混淆
  - ProGuard/R8
- 权限管理
  - 运行时权限

## 13. 构建系统
- Gradle (Groovy/Kotlin DSL)
- 构建变体 (Build Variants)
- 插件开发
  - 自定义 Gradle 插件

## 14. 部署与监控
- **应用分发**
  - Google Play Store
  - App Bundle
  - 第三方商店
- **监控工具**
  - Firebase Crashlytics
  - Sentry
  - Google Analytics
- **CI/CD**
  - Jenkins
  - GitHub Actions
  - GitLab CI

## 15. 新兴技术
- 跨平台开发
  - Flutter
  - React Native
- Kotlin Multiplatform (KMP)
- 机器学习
  - ML Kit
  - TensorFlow Lite
- AR/VR
  - ARCore

## 16. 调试工具
- Android Studio 调试器
- ADB (Android Debug Bridge)
- 布局检查器 (Layout Inspector)
- 网络分析器 (Network Profiler)
- Stetho (Facebook 调试工具)