# PhpStorm配置

> - File -> Default Settings 默认设置。
> - File -> Settings 当前项目设置。注意：有些默认设置也通过此设置来实现。
> - 所有设置完毕后都要 Apply（应用）或OK（确认）后才能生效。

### 取消自动保存并标识修改的文件为星星标记
- 取消自动保存：File -> Settings -> Appearance & Behavior ->System Settings 去掉勾选Save files on frame deactivation
- 使用星星标记：File -> Settings -> Editor -> General -> Editor Tabs 勾选Mark modifyied tabs with asterisk

### 如何显示行号？
如果你的编辑区没有显示行号，可以通过以下设置来进行显示 File -> Settings -> Editor -> General -> Appearance 标签项，勾选 Show line numbers。

### 启动时不打开项目？
File -> Settings -> Appearance & Behavior ->System Settings 去掉勾选Reopen last project on startup

### 常用文件模板设置
File -> Settings -> Editor -> File and Code Templates

### 单行注释符号后加空格？
File -> Default Settings -> Editor -> Code Style -> PHP -> Other 标签项，去掉勾选 Line comment at first column 而勾选 Add a space at comment start。

### 取消方法(函数)的参数值前面的文字提示？
File -> Settings -> Editor -> General -> Appearance 去掉勾选 Show parameter name hints。

### jQuery 代码提示？
File -> Settings -> Languages & Frameworks -> JavaScript -> Libraries
1. 自动安装(推荐)：右边 Download... -> TypeScript community stubs 选择 jquery 来自动下载安装。
2. 手动安装：右边 Add... （后面步骤跟自动安装后的填写差不多，可以先自动安装后再自定义自己的）。
提示：说明文档 Documentation URLs 那里的 http://api.jquery.com 可以下载到本地以加快显示速度。

### 如何添加插件？
File -> Settings -> Plugins -> Browse repositories -> 搜索  
常用的代码提示插件有：Bootstrap、AngularJS(有些版本已自动带了)、Vue.js 等等

### 如何去掉右上角浏览器图标？
File -> Settings -> Tools -> Web Browsers 去掉勾选 Show Browsers popup in the editor

### 默认展开头部注释
File -> Settings -> Editor -> Genaral -> Code Folding 去掉勾选 File header

### 默认展开 use 语句
File -> Settings -> Editor -> Genaral -> Code Folding 去掉勾选 PHP imports

### PHP版本设置
默认设置 File -> Default Settings -> Languages & Frameworks -> PHP -> PHP language level 选择PHP版本。（当前项目设置请选择 File -> Settings）

### 是否保存相关密码
配置搜 password 项

### 是否显示代码里的空格
配置搜 Show whitespaces 项

### 取消在文字里按 Enter 键后自动缩进
File -> Settings -> Editor -> Genaral -> Smart Keys -> Enter 去掉勾选 Smart indent

### 数组对齐
File -> Settings -> Editor -> Code Style -> PHP -> Other 标签项，勾选 Array declaration Style 项中的 Align key-value pairs。

### Node.js设置
File -> Default Settings -> Languages & Frameworks -> Node.js and NPM 设置一下 Node.js 和 NPM 包的所在位置，并启动助手来增加语法提示功能。如Node.js位置`D:\nodejs\node.exe` NPM 包位置`D:\nodejs\node_modules\npm`。（当前项目设置请选择 File -> Settings）

### 快捷键设置
File -> Settings -> Keymap