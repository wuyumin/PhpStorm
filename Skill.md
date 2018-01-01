# PhpStorm技巧

### 基于 IntelliJ 框架软件的通用性
基于 IntelliJ 框架的软件大多数的技巧是相似的，比如 IntelliJ IDEA、PyCharm、Android Studio 等软件的技巧大多数能用到 PhpStorm 上，同理，PhpStorm 的技巧也大多数能应用到基于 IntelliJ 框架的软件。

### 多点编辑？
按住"ALT"键并点击需要编辑的地方。（也可长按Alt+j，自动选择<u>相同的元素</u>并进入多点编辑状态）。

### 如何快速选中某一行？
鼠标移动到要选中的行，先双击选中任意一个字符，再次双击，即可选中整行。

### 如何快速的复制某行？
快速复制某行，只需将鼠标光标移动到目标行，直接ctrl+D，即可复制目标行到下一行，同时也可以进行对代码片段进行快速复制。

### 如何让屏幕分栏显示？
右键标签->Split Vertically(垂直分栏)或者 Split Horizontally(水平分栏)显示。

### 移除无用的use？
菜单Code -> Optimize Imports

### 自动生成一对标签
输入标签名(一般只要标签名没有对应模板代码就可以)，然后按 Tab 键就能自动生成一对标签。

### 打开文件对应的资源管理器
已打开文件的 Tab 标签上使用：Ctrl键 + 鼠标左键。(补充：在项目目录列表里得使用 鼠标右键 -> Show in Explorer)。

### 后缀自动补全功能(Postfix Completion)
比如你输入`$foo.fe`后敲一下 tab 键后就会输出：
```php
foreach ($foo as ) {
    
}
```
你可以在设置项里搜索`postfix`来了解一下有哪些 postfix。

### 如何在 Git 版本库里了解该行代码是谁写的？
在代码编辑框里左侧(显示行号那里)，右键打开“Annotate”功能。
