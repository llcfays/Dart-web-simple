
# Dart 创建 web 项目

[Dart 官方教程](https://dart.dev/tutorials/web/get-started#3-get-cli-tools-or-an-ide-or-both)

**本教程使用 Windows**

## 下载 Dart sdk

选择最新的 [Dart sdk](http://www.gekorm.com/dart-windows/) 安装程序下载。

**如果只开发移动端项目可以不下载 Dart sdk 。**

## 配置 Dart sdk 环境变量

拷贝 Dart 安装目录如： "D:\Dart\dart-sdk\bin",添加到系 Windows 系统环境变量 Path 中。

**一般来说默认会自动添加的。**

## 安装必要工具
在命令提示符窗口运行以下两条命令

~~~
 pub global activate webdev
 pub global activate stagehand
 ~~~

 **如果找不到 pub 命令，检查以下 Dart 环境变量是否添加。**
 **安装的时候可能会提示你配置以上两个工具的环境变量，注意看警告就可以了。**

 ## 创建项目

### 使用 vsCode 创建项目
- 打开 命令面板
- Flutter: new web project
- 输入项目名称即可


**前提是安装好以上环境**

### 使用命令提示符创建项目

~~~
mkdir quickstart
cd quickstart
stagehand web-simple
pub get
~~~

**如果找不到 stagehand 命令，可使用完整路径，完整路径在c:\users\user name\AppData\Roaming\Pub\Cache\bin 文件夹中。**

## 运行
~~~
webdev serve
~~~

**如果找不到 webdev 命令，可使用完整路径，完整路径在 c:\users\user name\AppData\Roaming\Pub\Cache\bin 文件夹中。**


