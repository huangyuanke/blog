一、JDK

（本地编译器：编译PC-X86-AMD64的Android-Java程序)
* 推荐使用java 1.8
* 设置环境变量JAVA_HOME，TOMCAT会用到。

二、Android的SDK

（交叉编译器：将PC-X86-AMD64的Android-Java程序，交叉编译为指定版本的安卓手机APK）
* 下载AndroidSdkManger，并解压到/Users/huangyuanke/dtool/android-sdk-macosx
* 通过命令行或AndroidStudio打开sdkManager，下载相关不同版本的android-sdk-build-tools

三、Gradle

（Java依赖包管理）
* android代码的构建工具
* 设置环境变量 GRADLE_USER_HOME ?什么用？

四、Android Studio
* Android SDK Location : /Users/huangyuanke/dtool/android-sdk-macosx
* Gradle user home: /Users/huangyuanke/.sdkman/candidates/gradle/current/bin  （告诉Android Studio使用哪个Gradle来构建APP程序）


五、Android-Studio-APP-Gradle项目
* 指定AS项目所用的Gradle是由我们的工程中下面这个文件决定的: {your project}/gradle/wrapper/gradle-wrapper.properties  （操作系统，可以使用高版本Gradle，App项目可使用低版本Gradle）
* 不同版本的Gradle下载后，保存在 ~/.gradle/wrapper/dists

