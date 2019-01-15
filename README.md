# HelloGit
GitHub笔记


**简单快速认识GitHub**: 
通过两篇文章快速认识Github即可（只看不动手），然后接着向下学习：
- [初识 GitHub](https://www.jianshu.com/p/94e2794cb270)
- [加入 GitHub](https://www.jianshu.com/p/d9f9bba4da0f)

**GitHub入门练习**
下面学习过程要练习，结合之前的初识提到的注意点慢慢操作。
- [Class01. HelloWord](https://guides.github.com/activities/hello-world/)
- [Class02. Git入门](https://guides.github.com/introduction/git-handbook/)
- [Class03. 入门VsCode & Markdown基本语法](https://www.cnblogs.com/LuckyZLi/p/9776143.html)

**Git系列全面学习**
需要进一步了解学习的，可在此找更多信息全面深入学习：
 - [全面学习Github（guides.github.com）](https://guides.github.com/)
 - [廖雪峰 Git电子书系列](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

**Git常用工具**
- [GitHub桌面版. GitHub Desktop](https://desktop.github.com/)

```
-------------------------------------------------
```

# HelloGitBook
   下面介绍一款电子书制作工具，利用GitHub平台的 `Markdown` 语法习惯编写电子书，方便易用，且可以发布为到 `GitBook`网站（类似于GitHub专用于发布代码性质），或者发布为 `PDF`或`ePub` 格式的文件，或者编译发布为纯 html文件站点。 
   
   该工具应用场景灵活，例如：个人电子书，学术主题电子书，产品说明文档，团队知识库...等.

**GitBook使用入门**：
网上找入门方法一堆，但是有些质量不高，这里结合我的学习经验，列出2-3个最佳参考，以节约学习时间。
- [Blankj总结的使用教程 - GitBook 使用教程 ★★★](https://www.jianshu.com/p/421cc442f06c)
- [较全面的中文版教程 - GitBook笔记（教程本身就是用gitbook制作发布的电子书） ★★★★](https://dunwu.gitbooks.io/gitbook-notes/)
- [官方全面的英文版教程 - GitBook Toolchain Documentation ★★★★★](https://toolchain.gitbook.com/ebook.html)

**GitBook相关资源下载**
- [下载 NodeJs](https://nodejs.org/zh-cn/)
- [下载 GitBook Editor](https://legacy.gitbook.com/editor)
- 编辑器还可以使用 `vs-code` 支持`markdown`语法的编辑器.

**GitBook使用经验特别提醒**：
结合自己的入门过程，有些东西是以上教程都没提及的细节，但我认为有必要写明确的，在此列举。
- 命令 `npm install gitbook-cli -g` 执行如果很慢，可能需要翻墙工具。
- 命令 `gitbook init` 注意先在准备好新电子书的文件夹，然后命令行中定位到当前文件夹，再执行此命令。
- `book.json` 支持配置电子书基本属性(标题,作者,语言...)，详情参见 [Gitbook 配置](https://dunwu.gitbooks.io/gitbook-notes/basics/settings.html).

```
其它：寻找NodeJs过程发现一个第三方站点`http://nodejs.cn/` ，以最简单的站点成本，通过挂阿里云的广告赚取卖服务器的提成。
```

