# Android Demo By ttdevs

这是一个关于Android的Demo，主要用于记录日常使用的代码。仅供参考！

## 项目结构

``` shell
Android
|--app
|--apps
|----bolts
|----sqlcipher
|--doc
|----image
|--modules
|----indicator
|----jniutils
|----markdown
|----reactive
|--android.jks
|--build.gradle
|--config.gradle
|--CONTRIBUTING.md
|--gradle.properties
|--LICESE
|--README.md
|--settings.gradle
```

# Application

## [bolts][bolts_md]

[bolts][bolts_src]和[Rxjava][rxjava_src]类似，但是比[Rxjava][rxjava_src]更早的框架。

## [SQLCipher][sqlcipher_md]

[SQLCipher][sqlcipher_src]，一个本地数据库加密工具类。

# Module

## [indicator][indicator_md]

一个自定义View，展示效果如下：
![indicator_line](modules/indicator/indicator_line.png)
![indicator_progress](modules/indicator/src/indicator_progress.png)

## [jniutils][]

## [markdown][]

## [reactive][]

# Tools

## [Conceal][conceal_md]

[Conceal][conceal_src]，一个本地文件加密工具类。

## [Endless][endless]

自己实现的 `RecycleView` 的onLoadMore。

## Tablayout

系统自带 `TabLayout` 的demo。

## Ucrop

很火的一个图片处理工具，集成了图片的放大、缩小、旋转、裁剪等。


------
[bolts_md]:src/main/java/com/ttdevs/demo/bolts/README.md
[bolts_src]:https://github.com/BoltsFramework/Bolts-Android
[rxjava_src]:https://github.com/ReactiveX/RxJava
[sqlcipher_md]:src/main/java/com/ttdevs/demo/sqlcipher/README.md
[sqlcipher_src]:https://github.com/sqlcipher/android-database-sqlcipher
[sqlcipher_blog]:http://blog.csdn.net/ttdevs/article/details/50700630
[conceal_md]:src/main/java/com/ttdevs/demo/conceal/README.md
[conceal_src]:https://github.com/facebook/conceal
[endless]:http://blog.csdn.net/ttdevs/article/details/48194885
[indicator_md]:modules/indicator/src/README.md
