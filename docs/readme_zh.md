# Preprint-Style

*一种适用于arXiv和bioRxiv等预印本的简洁美观的LaTeX样式。*

可用语言: [English](../readme.md) | [中文说明](readme_zh.md)

### 项目简介

该项目提供了一个**简洁、美观的 LaTeX 预印本模板**，非常适合在 **arXiv**、**bioRxiv** 等平台投稿使用。
本模板基于 [**arxiv-style**](https://github.com/kourgeorge/arxiv-style) 修改而来，而后者又源于 [**nips_2018.sty**](https://media.nips.cc/Conferences/NIPS2018/Styles/nips_2018.sty)。

它同时支持**双栏（two-column）**与**单栏（single-column）**两种布局，可自由切换。

---

### 使用方法

1. 使用文档类 `article`。
2. 将 `arxiv.sty` 复制到 `.tex` 文件所在目录。
3. 在 `\documentclass{article}` 之后添加：

   ```latex
   \usepackage{arxiv}
   ```

> ⚠️ 注意：此模板仅使用 `geometry` 宏包，请勿重复导入。

完整示例请参考 `main.tex`。

---

### 项目文件说明

| 文件名                    | 说明                        |
| ---------------------- | ------------------------- |
| **main.tex**           | 示例模板，展示了如何使用 `arxiv` 样式   |
| **references.bib**     | 参考文献数据库文件                 |
| **style/arxiv.sty**    | 预印本样式文件，提供 arXiv 风格的排版    |
| **style/roundenv.sty** | 提供圆角彩色背景的定理环境，让论文定理区更美观醒目 |

