# 技术文档 <br> Technical Document

文档，按写作目的不同，可分为“艺术文档”和“技术文档”两大类。

“艺术文档”的追求是“一千个人眼里有一千个哈姆雷特”。但若“技术文档”也写成这样，那真是糟透了！实际上，“技术文档”的追求刚好相反，一千个人眼里最好只有一个哈姆雷特。

同为文档，价值取向刚好相反。随之而来，形式结构、排版布局、遣词造句等等诸多方面，其做法也必然大相径庭。

写好技术文档最直接的方法是标准化。但一直未能找到一个简单有效、可以快速上手、面向技术文档写作的现成标准。本着“没有就自己造一个”的朴素想法，我们编写了：

> **<big> [《技术文档标准》](standard.pdf)(Technical Document Standard / TDS)</big>**

标准都不是孤立的存在，他们都站在巨人的肩膀上，TDS 也不例外。为了用好他，你应该知道更多：

> [规范性引用的标准及其现行版本](gb.html)  
> [参考的标准及其现行版本](gb.html)

**_<big>你完全可以使用 Microsoft Word 或 Apple Pages 等文档编辑工具，按照 TDS 的规则，编写自己的高质量技术文档。</big>_**

但是，用这类流式文件编辑器生成的文件，无法用 Git 进行字符粒度的版本控制，这对专业程序员来说，是无法接受的。为此，我们还提供一个基于 Markdown 的解决方案。

首先，对 Markdown 进行了简单的扩充：

> [《技术文档 Markdown 扩展》](markdown-extra.pdf)(Technical Document Markdown Extra / TDME)

其次，我们为 Chrome / Edge / Firefox / Opera 开发了浏览器扩展：

> [技术文档浏览器扩展](browser-extension.html) (Technical Document Browser Extension / TDBE)

**_<big>现在，你可以遵循 TDS 的规则，用 Markdown 和 TDME 起草自己的技术文档，然后用 TDBE 将其渲染成自己想要的样子和格式。</big>_**

实践“基于 Markdown 的解决方案”，最好的示例莫过于 TDS 自己的源码：

> [《技术文档标准》的 Markdown 源码](standard.md)


