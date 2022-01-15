---
name: 报告问题
about: 描述需要修复的问题
title: "[BUG]"
labels: bug
assignees: ''

---
<!-- 说明文档问题可以不按这个复杂的格式填写 -->

## 前提
<!-- 如需勾选某一项，请将开头的 [ ] 改成 [x] -->

- [ ] 我已尝试更新模板版本
- [ ] 我已检索模板手册
- [ ] 我已检索项目 wiki
- [ ] 我已检索既有 issue

## 描述

**预期行为**
<!-- 本来应该是什么效果。 -->

**问题现象**
<!-- 实际发生了什么偏差。 -->

**截图**
<!-- 加上图片也许能更好地呈现出问题状况。 -->

**最小工作示例**
<!-- 请务必附上一段完整的可供编译的 TeX 代码，用来复现上述问题。这段代码应当从 `\documentclass` 开始，到 `\end{document}` 结束。请删除所有不会引起该问题的内容。譬如，对于正文格式出现的问题，不必添加 `\njusetup` `\tableofcontents` 等命令。 -->
```
\documentclass[]{njuthesis}
...
\end{document}
```

**额外信息**
<!-- 任何你认为有帮助的信息。 -->

## 平台信息
<!-- 请提供编译平台以便更有针对性地排查问题。 -->

- 操作系统：<!-- [e.g. Windows 10] -->
- TeX 发行版：<!-- [e.g. TeX Live 2021] -->
- 编译命令：<!-- [e.g. xelatex] -->
- 模板版本：<!-- [e.g. v0.14.0] 版本信息可以从 log 文件搜索 njuthesis 得到 -->
- 获取途径
    - [ ] 使用包管理器从 CTAN 安装 <!-- 包括南大 TeX 内置版本 -->
    - [ ] 通过 GitHub Releases 或镜像站下载 <!-- 最新发布版本 -->
    - [ ] 从 Git 仓库下载 <!-- 最新开发版本，包括 Github 和 NJU Git -->