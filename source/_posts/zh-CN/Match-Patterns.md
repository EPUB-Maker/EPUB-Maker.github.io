---
title: 模式匹配
linkId: Match-Patterns
layout: doc
date: 2019-10-10 08:00:01
tags: 
- Concepts
---
在 EPUBMaker 中，有两种方式[拆分章节](#Split-Chapter)。其中之一是按模式拆分。

首先会创建一个正则表达式来匹配文章中的每一行。一旦正则表达式匹配成功，EPUBMaker 就会创建一个新章节并将匹配行之前的所有章节放到这个新章节中。接着 EPUBMaker 将会继续匹配下一行，直到文章结束。

所以匹配的模式必须较为精准。

![](/images/concepts-match-pattern-1.png)

你可以添加前缀、数字、后缀来组成正则表达式。这里有一个范例，如果前缀是 **Chapter** 和 **Section** 数字是罗马数字 **I**、 **V**、 **X**，后缀没有，并且一行内的字数少于**50**字。

以下可以被匹配：

- Chapter I. one
- Chapter XII
- test Section X

以下不能被匹配：

- Chapter One
- XI. example
- Chapter I. a long long long long ...(over 50 words) words

#### 如何添加或删除前缀、数字、后缀

想要添加的时候，你可以在输入框中键入，并且点击加号图标。

想要删除的时候，你可以直接点击你想要删除的词语。

#### 保存配置

只要你保存了配置，你就可以在任何语言环境下使用。 ■