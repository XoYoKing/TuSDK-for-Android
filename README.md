# TuSDK for Android

移动平台图像处理解决方案

## 使用

### 文件说明

* `TuSDKUIDefault`：默认主题包（GeeV1），包含了「相机组件」，「相册组件」，「多选相册组件」，「头像组件」，「照片美化组件」和「裁切 + 滤镜组件」等基础模块的所有功能；
可以单独与项目集成或是同时和 `TuSDKUIGeeV2` 库与项目集成。

* `TuSDKUIGeeV2`：GeeV2 主题包，包含了「相机组件」+「多选相册组件」+「多图片编辑组件」等整体调用的功能，并且使用了全新的界面主题；可以单独与项目集成或是同时和 `TuSDKUIDefault` 库与项目集成。


### 集成说明

* 如果想要同时使用 `TuSDKUIDefault` 和 `TuSDKUIGeeV2` 中的功能，需要同时将这两个库与项目集成，即需要同时将这两个库作为项目的库依赖，集成步骤与可以参看 [安装与更新](https://tusdk.com/docs/android/install-and-update) 文档

* 如果只想要使用 `TuSDKUIDefault` 中的功能，可以将 `TuSDKUIDefault` 单独拿出来与项目集成，集成步骤可以参看 [安装与更新](https://tusdk.com/docs/android/install-and-update) 文档

* 如果只想要使用 `TuSDKUIGeeV2` 中的功能，需要将 `TuSDKUIDefault/libs` 下的所有文件（`TuSDKGee-xxx.jar` 除外）复制到 `TuSDKUIGeeV2/libs` 目录下，然后将 `TuSDKUIGeeV2` 库单独拿出与项目集成，集成步骤可以参看 [安装与更新](https://tusdk.com/docs/android/install-and-update) 文档

## 链接

* [示例项目 Google Play](https://play.google.com/store/apps/details?id=org.lasque.tusdkdemo)
* [示例项目 APK](http://tusdk.com/android)
* [示例项目源码](https://github.com/TuSDK/TuSDK-for-Android-demo)
* [SDK](https://github.com/TuSDK/TuSDK-for-Android)
* [文档索引](http://tusdk.com/doc)

## 关注

* 博客 [blog.tusdk.com](http://blog.tusdk.com/)
* 微博 [@TuSDK](http://weibo.com/tusdk)
* Twitter [@TuSDKHQ](https://twitter.com/TuSDKHQ)
* 微信 [TuSDK-HQ](http://tusdk.com/img/tusdk-wechat-qrcode.png)
* Telegram [@TuSDK](https://telegram.me/TuSDK)

更多信息请访问 [tusdk.com](http://tusdk.com/)，欢迎通过 [contact@tusdk.com](mailto:contact@tusdk.com) 与我们联系。