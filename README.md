# CopyQ_lazy
个人的[CopyQ](https://github.com/hluk/CopyQ)仓库，包括自定义的命令和配置。

所有命令基本上来自官方的命令示例或Issue区的评论，经过汉化和修改得到。

**主窗口**

![](images/main-window.png)

**简洁模式**

![](images/pure-mode.png)


**右键菜单**

![](images/menu.png)


**导入通知**

![](images/import-notification.png)

## 功能增强

* 支持复制/粘贴文件
* 完善的删除/撤销/确认删除功能
* 按时清理标签页
* 自动预览图片/长文本
* 切换 大写/小写/首字母大写
* 排序（按条目大小、字母、复制时间、置顶固定条目）
* 简洁模式及相应主题
* 官方命令的汉化及细节优化

## 命令的使用方法

### 一键导入
如果你是第一次安装CopyQ，可以选择[一键导入](一键导入/%E4%B8%80%E9%94%AE%E5%AF%BC%E5%85%A5.cpq)我的配置。但请注意，这会包含一些我个人的个性化设置，不过相比默认设置不会有太大的调整。

方法是：安装完CopyQ后，在菜单栏-文件-导入，选择下载的一键导入文件，确定即可。

如果只想导入全部命令，可以按下面的方法导入[全部命令](命令/%E5%85%A8%E9%83%A8%E5%91%BD%E4%BB%A4.ini)这一个文件。

### 逐个导入
首先安装[复制命令时通知导入](命令/%E5%A4%8D%E5%88%B6%E5%91%BD%E4%BB%A4%E6%97%B6%E9%80%9A%E7%9F%A5%E5%AF%BC%E5%85%A5.ini)。方法：全选并复制命令，在CopyQ主窗口按F6打开`命令/全局快捷键`，点击右下角的粘贴命令，点OK即可。

之后每次复制命令，都会弹出通知，点击导入并确定即可。


### 须知
* 按时间[排序](命令/%E6%8E%92%E5%BA%8F.ini)命令依赖于[保存复制时间](命令/%E4%BF%9D%E5%AD%98%E5%A4%8D%E5%88%B6%E6%97%B6%E9%97%B4.ini)命令。


* [居中显示/隐藏主窗口](命令/%E5%B1%85%E4%B8%AD%E6%98%BE%E7%A4%BA%E6%88%96%E9%9A%90%E8%97%8F%E4%B8%BB%E7%AA%97%E5%8F%A3.ini)需按实际屏幕分辨率和缩放系数调整参数，或者关闭居中显示，否则窗口尺寸和位置可能异常。

## 主题的使用方法
在主窗口-文件-首选项-外观-加载主题，选择下载好的主题即可。

## 参考
[CopyQ官方文档](https://copyq.readthedocs.io/en/latest/scripting-api.html)

[CopyQ官方命令仓库](https://github.com/hluk/copyq-commands)

[暗黑主题](https://github.com/dracula/copyq) 来自 `Dracula Theme`

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=GFDGIT/CopyQ_lazy&type=Date)](https://www.star-history.com/#GFDGIT/CopyQ_lazy&Date)