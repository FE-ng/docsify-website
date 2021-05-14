# 工欲善其事 必先利其器

mac 系统之于前端而言,是用过就再也回不去的霸道;

?> _TODO_ 软件 icon

## **系统功能设置类**

从 window 到 mac 触控板就是我无法割舍的一个重点：  
MacBook 提供了强大的触控板硬件，支持用力点按和多指触控。  
配合 macOS 的软件调教，触控板的使用如虎添翼，对于前端开发而言已经能够完全脱离鼠标。  
但游戏和抠图等需要标进行精细操作的也可以另配键鼠；

### 触控板设置

<img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/settingEnter.png"  alt="设置入口" align=center />

---

1. 系统偏好设置 > 触控板

   <img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/cursor.png"  alt="光标与点按" align=center />

   ***

   <img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/transform.png"  alt="滚动与缩放" align=center />

   ***

   <img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/moreGesture.png"  alt="更多手势" align=center />

2. 系统偏好设置 > 辅助功能 > 指针控制 > 三指拖拽(个人感觉体验非常棒的功能)

  <img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/pointerControl.png"  alt="入口" align=center />

---

  <img style="width:600px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/thrFingerDrag.png"  alt="设置" align=center />

!> **建议全部拉满**  
具体配置可参考图片,光标移动速度可以按照自己的习惯设置

### 软件安装设置

1. 允许来自任意来源的应用
   很多时候，我们需要安装第三方途径的软件包，对于某些软件，苹果会因为过高的安全管理权限而拒绝安装，想要处理，可以在系统的设置内解决。

![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210426141736.png ':class=image800')

如果找不到 “任意来源” 这个选项，可以通过一行终端的命令解决，按住 command + 空格 ，输入 “终端.app” 打开终端。在终端中输入命令：

```bash
sudo spctl --master-disable
```

![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210507114206.png)

### 常用快捷键 (可自行摸索)

command + option + D : 能够控制程序坞与菜单栏是否常驻

command + option + ESC : 可以查看未响应的程序并快速清除
![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210514162013.png ':class=image600')

command + M : 将当前窗口快速缩小 在程序坞与菜单栏中能够查看
![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210514162149.png ':class=image600')

command + W : 关闭或者缩小, 缩小时

command + H : 将当前窗口所属的软件快速缩小 并且程序坞与菜单栏中也查看不到

command + Q : 退出程序

command + D : 在 finder 文件聚焦在文件上时是快速生产副本的方式 === ( command + C ) + (command + V )

command + C | command + V : 复制 | 粘贴

command + N : 新窗口

...

## **软件类**

### 通用类

- [Homebrew](https://brew.sh/)

一款几乎必装的软件包管理工具,只是很多时候由于 GFW 的存在下载的速度堪忧,有必要更换一下国内的源;
下载之后能够非常简单的按照很多软件

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506191852.png ':class=image30') [chrome](https://www.google.com/intl/zh-CN/chrome/)
  开发人员使用的最多浏览器,不多赘述,好用的插件另起一遍介绍;

  !> [插件传送门](https://docsify-website-lf.vercel.app/#/tools/chromePlugin)

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506192359.png ':class=image30') [Paste (强化剪切板)](https://pasteapp.io/)  
   可以将常用的一些操作和内容进行分类重命名储存

  <img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/%E4%BC%81%E4%B8%9A%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_6b0749fb-d939-4618-8262-64c5b6e4f594.png" style="width:600px;"/>

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506192438.png ':class=image30') [iStat Menus （电脑性能监控）](https://bjango.com/mac/istatmenus/)  
   功能非常的强大 能够查看 mac 的各种信息并且支持自定义自己喜欢的表现形式和颜色;  
  <img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210426140334.png" style="width:600px;"/>

[^_^]: # (https://juejin.cn/post/6844904185134055438 )
[^_^]: # (邮箱：982092332@qq.com )
[^_^]: # (SN：GAWAE-FCWQ3-P8NYB-C7GF7-NEDRT-Q5DTB-MFZG6-6NEQC-CRMUD-8MZ2K-66SRB-SU8EW-EDLZ9-TGH3S-8SGA )

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506192908.png ':class=image30') [IINA （推荐的 macOS 视频播放器）](https://iina.io/)

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506193103.png ':class=image30') [hammerspoon](http://www.hammerspoon.org/)
  这是一个用于 OS x 强大自动化的工具。在其核心上，Hammerspoon 只是操作系统和 Lua 脚本引擎之间的桥梁。  
  赋予 Hammerspoon 强大功能的是一组向用户公开系统功能特定部分的扩展。  
  小锤子! 它能做到什么? 可以给 mac 的软件设置开启(切换)的快捷键,可以迅速给当前运行的窗口分屏二分之一屏(三分之一屏幕),  
  更能够在我们使用多屏开发时使用设置好的,将选中的窗口在多个屏幕转移,能够通过预设来切换语言中英文输入法等等等等!异常的强大;  
  只是配置起来稍有门槛,但是社区早已有前辈为我们铺好了道路;

  !> [这是我的配置](https://github.com/FE-ng/.hammerspoon);

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210506193204.png ':class=image30') [Parallels Desktop](https://www.parallels.cn/)  
  官网介绍: 无需重启即可在 Mac（包括新型 Apple M1 芯片）上运行 Windows 的应用程序，  
  同时具有速度更快、操作更简单且功能更强大的优点。包括 30 余种实用工具，可简化 Mac 和 Windows 上的日常任务  
  平时用的不多,不过在 mac 上能够做到不切换系统而使用 windows 必要的时候倒是很方便

- [Aerial]()
  一款炫酷的 mac 屏保软件,内置了其他高清 4K 的屏保动效,

### 开发类

- [Zsh](https://ohmyz.sh/) Shell  
  Oh-my-zsh 是一个开源的、基于社区驱动的框架，用于管理 Zsh 配置。它拥有非常多的功能，辅助，插件，主题,使用起来非常的便捷;

  !> [我使用的 zsh 配置](https://github.com/FE-ng/docsify-website/blob/main/.zshrc.md);

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210512200050.png ':class=image30') [vscode](https://code.visualstudio.com/)

  ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210503234003.png ':class=image400')  
  现阶段前端使用最多的 IDE,由微软开发维护,支持非常多的语言,有茫茫多的开发插件和活跃的社区;

  ?> _TODO_ 这里的插件也需要另起一篇文章介绍

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210512195827.png ':class=image30') [ITerm2](https://iterm2.com/)
  推荐的终端软件 ( iTerm2 )
  这是一款 macOS 用于替代 终端.app 的软件。因为它的定制化和功能非常强大，所以在配置 mac 的时候，它也会作为我使用的终端应用。

- ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210512200137.png ':class=image30') [SwitchHosts](https://github.com/oldj/SwitchHosts)

  ![效果图](https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210430172813.png ':class=image400')

  快速切换 hosts 方案
  hosts 语法高亮
  支持从网络加载远程 hosts 配置
  可从系统菜单栏图标快速切换 hosts

## [部分软件下载地址推荐 xclient](https://xclient.info/)
