# 工欲善其事 必先利其器

mac 的系统对于前端而言,是使用过就无法再舍弃的状态了;

## **系统功能设置类**

触控板设置
从 window 到 mac 触控板就是我无法割舍的一个重点：
MacBook 提供了强大的触控板硬件，支持用力点按和多指触控。配合 macOS 的软件调教，触控板的使用如虎添翼，对于前端开发而言已经能够完全脱离鼠标。
但游戏和抠图等需要标进行精细操作的也可以另配键鼠；

### 系统偏好设置:

<img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/settingEnter.png"  alt="设置入口" align=center />

---

1. 系统偏好设置 > 触控板

- <img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/cursor.png"  alt="光标与点按" align=center />

---

- <img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/transform.png"  alt="滚动与缩放" align=center />

---

- <img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/moreGesture.png"  alt="更多手势" align=center />

2. 系统偏好设置 > 辅助功能 > 指针控制 > 三指拖拽(个人感觉体验非常棒的功能)

- <img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/pointerControl.png"  alt="入口" align=center />

---

- <img style="width:400px;" src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/thrFingerDrag.png"  alt="设置" align=center />
  **建议全部拉满** 并且具体配置可以看图片,光标移动速度可以按照自己的习惯设置

3. 允许来自任意来源的应用
   很多时候，我们需要安装第三方途径的软件包，对于某些软件，苹果会因为过高的安全管理权限而拒绝安装，想要处理，可以在系统的设置内解决。
   <img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210426141736.png" style="width:400px;"/>
   如果找不到 “任意来源” 这个选项，可以通过一行终端的命令解决，按住 command + 空格 ，输入 “终端.app” 打开终端。在终端中输入命令：

```bash
sudo spctl --master-disable
```

<img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210426142947.png" style="width:400px;"/>

## **软件类**

- [iStat Menus （电脑性能监控）](https://bjango.com/mac/istatmenus/)  
   功能非常的强大 能够查看 mac 的各种信息并且支持自定义自己喜欢的表现形式和颜色
  <img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/20210426140334.png" style="width:400px;"/>

[^_^]: # (https://juejin.cn/post/6844904185134055438 )
[^_^]: # (邮箱：982092332@qq.com )
[^_^]: # (SN：GAWAE-FCWQ3-P8NYB-C7GF7-NEDRT-Q5DTB-MFZG6-6NEQC-CRMUD-8MZ2K-66SRB-SU8EW-EDLZ9-TGH3S-8SGA )

- [Paste (强化剪切板)](https://pasteapp.io/)  
   可以将常用的一些操作和内容进行分类重命名储存
  <img src="https://raw.githubusercontent.com/FE-ng/picGo/main/blog/%E4%BC%81%E4%B8%9A%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_6b0749fb-d939-4618-8262-64c5b6e4f594.png" style="width:400px;"/>

- [IINA （推荐的 macOS 视频播放器）](https://iina.io/)
- [Parallels Desktop](https://www.parallels.cn/)  
  官网介绍: 无需重启即可在 Mac（包括新型 Apple M1 芯片）上运行 Windows 的应用程序，同时具有速度更快、操作更简单且功能更强大的优点。包括 30 余种实用工具，可简化 Mac 和 Windows 上的日常任务  
  平时用的不多,不过能够不切换倒是很方便
