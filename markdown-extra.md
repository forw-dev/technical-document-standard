---
mode: web
width: 40
---

# 技术文档 Markdown 扩展<br> Technical Document Markdown Extra

## 概述

基于 [GitHub Flavored Markdown(GFM)](https://github.github.com/gfm/) ，按[《技术文档标准》](http://forw.cc/tech-doc/standard.pdf)的需要，进行简单扩展。

## 元信息扩展语法 

- 内容放置在标记为 metas 的注释中。
- 内容为 YAML 格式的键值对。

<pre>
```meta
文档名称: XXXXXX
文档编号: DDDDDD  
文档版本: 1.00  
控制范围: 公开  
```
</pre>

## 多级编号段落扩展语法

- 以 `m.` 开始的段落。 
- 段落末尾应有两个空格。

```markdown
m. 段落内容。  
m. 段落内容。  
```
