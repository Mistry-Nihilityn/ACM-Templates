# ACM Notes — XCPC 模板手册

面向 XCPC 赛场的纸质速查手册，A4 双面，265 页。按编、章、节组织，覆盖数据结构、图论、数学、字符串、动态规划与杂项。

## 下载

[ACMNotes.pdf](ACMNotes.pdf)

## 样本

两份出行/参赛手册，可作为排版与信息组织的参考（人名已匿名化）：

- [CCSP 2026 出行手册](CCSP2026.pdf) · [LaTeX 源文件](CCSP2026.tex)
- [ICPC 2026 成都参赛手册](ICPC2026Chengdu.pdf) · [LaTeX 源文件](ICPC2026Chengdu.tex)

## 编译

需要 XeLaTeX、ctex 宏包与 JetBrains Mono 字体：

```bash
xelatex main.tex
xelatex main.tex
```

## 目录

```text
main.tex        封面、目录与各编入口
preamble.tex    版式、字体、代码环境与提示框
chapters/       各编正文（由模板库自动生成）
assets/         插图、ICPC 标志与延伸阅读 PDF
```

章节文件随工程提供；模板库的 markdown 源文件不在本仓库内。
