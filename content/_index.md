---
title: 谷歌工程实践
type: docs
---

# 谷歌工程实践文档

Google 有许多通用工程实践，几乎涵盖所有语言和项目。此文档为长期积累的最佳实践，是集体经验的结晶。我们尽可能地将其公之于众，您的组织和开源项目也会从中受益。

当前包含以下文档：

- [Google 代码审查指南](docs/review)，实则两套指南：
  - [代码审查者指南](docs/review/reviewer)
  - [代码开发者指南](docs/review/developer)

## 术语

文档中使用了 Google 内部术语，在此为外部读者澄清：

- **CL**：代表“变更列表（changelist）”，表示已提交到版本控制或正在进行代码审查的自包含更改。有的组织会将其称为“变更（change）”或“补丁（patch）”。
- **LGTM**：意思是“我觉得不错（Looks Good to Me）”。这是批准 CL 时代码审查者所说的。

## 译者序

此仓库翻译自 [google/eng-practices](https://github.com/google/eng-practices)，目前为止的主要内容为 Google 总结的如何进行 **Code Review（代码审查）** 指南，根据原 Github 仓库的标题判断以后会追加更多 Google 工程实践的内容。

- 本文档的 Github 地址：<https://github.com/rootsongjc/eng-practices>，点击页面底部的 `Edit this page` 链接可以编辑页面。
- 其他语言的版本请访问 <https://github.com/eng-practices/eng-practices>。
- 感谢 [Ta-Ching Chen](https://github.com/life1347) 的审阅。
- 译者：[Jimmy Song](https://jimmysong.io)
- 本网站使用 [Hugo](https://gohugo.io) 构建。
- 本网站使用 [hugo-book](https://github.com/alex-shpak/hugo-book) 主题。

## License

本项目中的文档适用于 CC-By 3.0 许可证，该许可证鼓励您共享这些文档。有关详细信息，请参阅 <https://creativecommons.org/licenses/by/3.0/>。

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>