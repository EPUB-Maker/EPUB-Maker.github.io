---
title: 导入 TXT 或 EPUB
linkId: Import-TXT-or-EPUB
layout: doc
date: 2019-10-10 08:01:00
tags: 
- Guide
---

`导入 TXT` 将会首先创建一个章节，并导入所有的行到这个章节中。如果行数超过 1000，你将无法编辑这个章节（详情参见[可编辑](#Editable)）。

`导入 EPUB` 将会保持 EPUB 的章节结构并转化 HTML 页面变成 EPUBMaker 的文章结构。同时也会解压媒体资源到如下路径： 

`C:\Users\${Users}\AppData\Roaming\epubmaker\epubmaker-resource\${timestamp}`

EPUBMaker 可以快速处理大数据文件。你可以轻松导入超过 2MB 的 TXT 文件或 20MB 的 EPUB 文件（大数据 EPUB 文件可能会需要较多时间转化）。 ■