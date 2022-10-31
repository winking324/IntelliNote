# IntelliNote

用了很多 Note 工具，没有遇到一款用起来非常舒服的，打算用 Electron 来自己打造一款。

鉴于 Electron 还在学习过程中，先把一些想法和需求记录下来。

## 想法与需求

- 兼容 Markdown
- 支持笔记分类，且笔记需要支持 Tag 标签，并通过标签进行双链关联
  - 闪念笔记本：自动定期清理
  - 项目笔记本：按照项目周期存档，存档后关联 Tag 不显示在 Graph 中，其他笔记中 Tag 变灰色等
  - 永久笔记本
  - 文献笔记本
- 多人协作
  - 可以定义 Group
  - 区分命名空间，每个空间具有不同的权限 private，public
  - private 可以搜索添加 public 中的 Tag
- 标签系统
  - 自动标签，例如在某个目录下，则自动具有该目录的标签
  - 路径式标签，例如 `Vos/Web`
  - [如何用 I.A.R.P 规划标签](https://help.flomoapp.com/thinking/iarp.html)
- 采用文本式？还是 Block 式？
  - 参考 [verse](https://verse.app.yinxiang.com/product/) 是一种很不错的想法
- 快捷键小窗口快速记录闪念想法
  - 参考 App：Zettelbox
- 双链
  - 知识星图
    - 大小怎么界定？时间？链接数？
- 服务端
- 事件/通知功能，当某个 TODO 或者 Checkbox 被完成事，关注者能收到相关的通知
- 如何标记某个 block 是由谁在什么时间记录的？根据 Markdown 文件做记录？
- 文档可以跟 ReadTheDocs 一样有版本管理的功能？

## 可进化🧬

时代不断发展，信息越来越多，碎片化也越来越严重，想要在互联网上学习某项知识，需要检索很多资料，并且资料良莠不齐，那么怎么能让“知识”可以自己进化呢？

## 参考

* [Vditor](https://github.com/Vanessa219/vditor) 是一款浏览器端的 Markdown 编辑器，支持所见即所得、即时渲染（类似 Typora）和分屏预览模式。它使用 TypeScript 实现，支持原生 JavaScript 以及 Vue、React、Angular 和 Svelte 等框架；
* [vscode-office](https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-office) 是 VSCode 一个预览文件的插件；
* [Flomo](https://help.flomoapp.com/)《卡片笔记写做法》推荐的一款笔记工具；
* [语雀](https://www.yuque.com/winking324/ncyz10/bqigy3) 功能看起来跟想象中的很一致；


