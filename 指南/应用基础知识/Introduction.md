# Android 简介


- 要了解应用的工作原理，请从[应用基础知识](https://developer.android.com/guide/components/fundamentals.html)开始入手。
- 要立即开始编码，请仔细阅读[构建您的第一个应用](https://developer.android.com/training/basics/firstapp/index.html)。


## 应用提供多个入口点

Android 应用都是将各种可单独调用的不同组件加以组合开发而成。例如，组件可以是为用户界面提供一个屏幕的单个“Activity”，也可以是在后台独立执行工作的“服务”。

您可以使用 intent 从一个组件启动另一个组件。甚至，您还可以启动不同应用中的组件，例如，启动地图应用中的 Activity 以显示地址。此模式可为单个应用提供多个入口点，并使任何应用均能够像用户“默认设置”一样处理其他应用可能调用的操作。

**了解详情：**

- [应用基础知识](https://developer.android.com/guide/components/fundamentals.html)
- [Intent 和 Intent 过滤器](https://developer.android.com/guide/components/intents-filters.html)
- [Activity](https://developer.android.com/guide/components/activities.html)


## 应用可适应不同的设备

Android 提供了一个自适应应用框架，可用以为不同的设备配置提供独特的资源。例如，您可以针对不同的屏幕尺寸创建不同的 XML 布局文件，系统将根据当前设备的屏幕尺寸确定要应用的布局。

如有任何应用功能需要相机等特定的硬件，则可在运行时查询设备功能的可用性。如有必要，您还可以声明您的应用所必需的功能，使 Google Play 商店等应用市场不得在不支持这些功能的设备上安装您的应用。

**了解详情：**

- [设备兼容性](https://developer.android.com/guide/practices/compatibility.html)
- [资源概览](https://developer.android.com/guide/topics/resources/overview.html)
- [UI 概览](https://developer.android.com/guide/topics/ui/overview.html)