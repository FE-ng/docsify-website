# picGo 图床

工具: <https://github.com/Molunerfinn/picgo/releases>  
教程: <https://learnku.com/articles/48574>  
配置手册: <https://picgo.github.io/PicGo-Doc/zh/guide/config.html>

hexo + vercel
<https://neroasmar.top/hexo-building/>

## 其他图床信息

<https://blog.cyfan.top/p/eb490c73.html>

## gitalk 评论系统

<https://www.jianshu.com/p/536421eec50c>
<https://segmentfault.com/a/1190000018072952>

```js
<script src='//cdn.jsdelivr.net/npm/md5.js@1.3.5/index.min.js'></script>
```

```md
!> 一段重要的内容，可以和其他 **Markdown** 语法混用。

?> _TODO_ 完善示例
```

!> 一段重要的内容，可以和其他 **Markdown** 语法混用。

?> _TODO_ 完善示例

```md
![logo](https://docsify.js.org/_media/icon.svg ':size=WIDTHxHEIGHT')
![logo](https://docsify.js.org/_media/icon.svg ':size=50x100')
![logo](https://docsify.js.org/_media/icon.svg ':size=100')

<!-- 支持按百分比缩放 -->

![logo](https://docsify.js.org/_media/icon.svg ':size=10%')
```

![logo](https://docsify.js.org/_media/icon.svg ':size=WIDTHxHEIGHT')
![logo](https://docsify.js.org/_media/icon.svg ':size=50x100')
![logo](https://docsify.js.org/_media/icon.svg ':size=100')

<!-- 支持按百分比缩放 -->

![logo](https://docsify.js.org/_media/icon.svg ':size=10%')

<details>
 <summary>设置 Vercel 的指导</summary>

1. 前往 [vercel.com](https://vercel.com/)
1. 点击 `Log in`
   ![](https://files.catbox.moe/tct1wg.png)
1. 点击 `Continue with GitHub` 通过 GitHub 进行登录
   ![](https://files.catbox.moe/btd78j.jpeg)
1. 登录 GitHub 并允许访问所有存储库（如果系统这样提示）
1. Fork 这个仓库
1. 返回到你的 [Vercel dashboard](https://vercel.com/dashboard)
1. 选择 `Import Project`
   ![](https://files.catbox.moe/qckos0.png)
1. 选择 `Import Git Repository`
   ![](https://files.catbox.moe/pqub9q.png)
1. 选择 root 并将所有内容保持不变，并且只需添加名为 PAT_1 的环境变量（如图所示），其中将包含一个个人访问令牌（PAT），你可以在[这里](https://github.com/settings/tokens/new)轻松创建（保留默认，并且只需要命名下，名字随便）
   ![](https://files.catbox.moe/caem5b.png)
1. 点击 deploy，这就完成了，查看你的域名就可使用 API 了！

</details>
