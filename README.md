# 介绍

记录一下gitbook上传到github步骤。

------

​		在认识 GitBook 之前，毋容置疑，**Git** 是目前世界上最先进的分布式版本控制系统。

​		我认为 Git 不仅是程序员管理代码的工具，它的分布式协作方式同样适用于很多场合，其中一个就是写作（这会是一个引起社会变革的伟大的工具！）。所以在我发现 GitBook 之前，实际上我已经无数次想象过它的使用场景了。

​		咋一看 GitBook 的名字，你可能会认为它是关于 Git 的一本书。而当你有所了解之后，你也许会认为它是一个使用 Git 构建电子书的工具。其实不然，GitBook 与 Git 的关系，就像雷锋塔和雷锋那样，没有一点关系！

​		实际上，GitBook 是一个基于 Node.js 的命令行工具，支持 Markdown 和 AsciiDoc 两种语法格式，可以输出 HTML、PDF、eBook 等格式的电子书。

​		所以，GitBook 不是 Markdown 编辑工具，也不是 Git 版本管理工具。市面上我们可以找到很多 Markdown 编辑器，比如 Typora、MacDown、Bear、MarkdownPad、MarkdownX、JetBrains’s IDE（需要安装插件）、Atom、简书、CSDN 以及 GitBook 自家的 GitBook Editor 等等。

​		**但 GitBook 又与 Markdown 和 Git 息息相关**，因为只有将它们结合起来使用，才能将它们的威力发挥到极致！因此，通常我们会选择合适的 Markdown 编辑工具以获得飞一般的写作体验；使用 GitBook 管理文档，预览、制作电子书；同时通过 Git 管理书籍内容的变更，并将其托管到云端（比如 GitHub、GitLab、码云，或者是自己搭建的 Git 服务器），实现多人协作。

​		实际上，GitBook Editor 对于新手来说是个不错的选择，它集成了 GitBook、Git、Markdown 等功能，还支持将书籍同步到 gitbook.com 网站，使我们可以很方便地编辑和管理书籍。但是不幸的是，GitBook Editor 的注册和登录需要翻墙，即便注册成功了也可能登录不上，似乎是因为网站最近在升级。

​		因此，我推荐，也是我目前使用的搭配是 `GitBook + Typora + Git`。

------

​		通常，我们最开始学习和使用的办公软件就是 Word、Excel 和 PowerPoint。这里不是说它们已经过时了，不是说 GitBook 能够替代它们。

​		相反，Microsoft 的办公软件很优秀并且经受了时间的考验，但是正因为它功能丰富，导致稍显臃肿（二八定律：80%的时间里我们只会只用20%的功能），同时因为它存在以二进制格式保存、软件不兼容、格式不兼容、难以进行版本控制、难以实时分享预览、难以多人协作等短板。而这恰恰是 GitBook + Markdown + Git 的长处。

​		简单来说，GitBook + Markdown + Git 带来的好处有：

> - 语法简单
> - 兼容性强
> - 导出方便
> - 专注内容
> - 团队协作

​		所以，如果你和我一样，不满足于传统的写作方式，正在寻找一种令人愉悦的写作方式，那么该尝试使用 GitBook 啦！

​		当然，GitBook 不是万能的，当我们需要复杂排版时，依然需要依托于 Word 等工具。但不用担心，因为我们可以把 Markdown 格式的文档导出为 Word 格式，再进一步加工。