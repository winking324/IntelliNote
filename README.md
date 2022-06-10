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
- 采用文本式？还是 Block 式？
  - 参考 [verse](https://verse.app.yinxiang.com/product/) 是一种很不错的想法
- 快捷键小窗口快速记录闪念想法
  - 参考 App：Zettelbox
- 双链
  - 知识星图
    - 大小怎么界定？时间？链接数？
- 服务端
