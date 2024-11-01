# 协作者指南：参与GraphRAG开发

首先由衷感谢你对**GraphRAG**作出的贡献！我们对帮助改进项目的社区贡献表示欢迎。

## 开发行为准则

本项目欢迎贡献和建议。绝大多数贡献都要求您签署同意**贡献者许可协议**（以下简称CLA），以声明您有权利并实际授予我们使用您的贡献的权利。有关详细信息，请访问：https://cla.microsoft.com.

当您提交拉取请求时，CLA机器人将自动确定您是否需要提供CLA并适当地修改**PR**（例如：标签、评论）。您只需按照机器人提供的说明进行操作即可，在所有存储库中，只需使用CLA执行此操作一次。

本项目基于[Microsoft开源项目开发行为准则](https://opensource.microsoft.com/codeofconduct/)。<br>
更多详细信息，请参阅：[Microsoft开源项目开发行为准则 FAQ](https://opensource.microsoft.com/codeofconduct/faq/)，或者联系[opencode@microsoft.com](mailto:opencode@microsoft.com)以提出其他问题、意见等。

## 开发参与指南

1. 创建库分支，并将其复制到本地主机。
2. 为您的贡献内容创建一个新分支： `git checkout -b my-contribution`.
3. 尝试您的修改，并**确保代码全部过测**。
4. 提交更改：`git commit -m "Add my contribution"`.
5. 通过运行： `poetry run semversioner add-change -t <major|minor|patch> -d <description>`创建并提交 semver 影响文档。
6. 将更改推送到 fork 存储库： `git push origin my-contribution`.
7. 新建对源库的拉取申请。

## 有关安全性问题的反馈
**请不要通过 GitHub Issues 公共板块报告安全漏洞！** 如有安全性漏洞，请向微软安全响应中心（MSRC）报告它们。有关更多信息请参照 [SECURITY.md](./SECURITY.md)。

## 协作开发：公共基本规则

在您开始参与开发协作之前，请先建立Issues档案。<br>
请遵循这个简单的规则，以便帮助我们避免产生一切不必要挫败感，以及精力浪费；确保能高效地利用每个人的时间————你的，我们的，以及其他一切社区成员的时间：

> 👉 如果你有疑问、且认为你发现了一个问题，或者想提出一个新功能等等；在你开始工作之前，希望您先在Issue板块检索、或提交一个Issue，来尝试修复/实施它（而不是自己一个人直接开干）。

### （提交新Issue之前）先搜索现有的Issues

在提交新 Issue 之前，请先搜索现有的未解决和已关闭的 Issue：这个项目进展很快！其他人可能已经发现了您看到的问题，并且有人可能正在处理或已经提供了修复程序！

如果没有现有项目描述您的问题/功能，那恭喜您发现了华点 - 请新建一个新Issue档案：

### 新建Issue档案

- 不知道您需要报告问题还是请求功能？新建Issue档案；
- 存在疑问，但在文档、视频等中看不到答案？新建Issue档案；
- 想知道我们是否计划构建特定功能？新建Issue档案；
- 对新功能有个好想法？新建Issue档案；
- 不明白有些工程怎么做？还是新建Issue档案！
- 发现了描述您的问题的现有Issue？那真是太方便了 - 点赞并添加额外的评论 / 信息 / 复现步骤 / 等等等等。

如果基于先前的流程规则，您发现自己最终还是需要提交Issue，请使用 [issue tracker](https://github.com/microsoft/graphrag/issues)。
提供尽可能多的详细信息，以帮助我们了解和解决问题。

### 补充信息

**填写新的Issue表单，并提供尽可能多的信息**。您提供的信息越多，您的问题或建议就越有可能被理解和采纳。有用信息的例子包括但不限于：

- 用于运行的设备信息(包括CPU类型、内存、硬盘等等)；
- 用于运行的操作系统；
- 您所使用的工具，APP等(例如VS 2022、VSCode等等)；
- **详细的重现步骤使相当受欢迎的**！我们需要重复哪些步骤来重现该问题？请假想我们爱死读取重现步骤这个环节了，您所能提供尽可能多的细节对我们来说可能都远远不够！
- 如果可能的话，附上错误消息文本使首选项；如果无法捕获该文本，那么可以用错误信息的屏幕截图来代替；
- 如果您打算自己进行修复或功能实现，请务必注明！如果您没有注明的话，我们将假定该问题是需要由我们来解决的，或者我们可能会将该问题标记为`寻求帮助中`。

### 请不要发布 “+1” 类型的评论

> ⚠ 不要在板块中发布 “+1”、“我也是这样” 以及类似的评论————这些只是一些废话，对问题的解决毫无帮助。

如果你没有任何其他要补充的信息或上下文，但想表明你受到该问题的影响，请点击 [+😊] 按钮，并点击 👍 （+1） 图标来为原始问题投赞成票。**通过这种方式，我们实际上就能衡量这个 issue 的影响范围有多大**。

---

## 再次致谢

再一次感谢您对**GraphRAG**的贡献！
