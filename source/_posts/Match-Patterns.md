---
title: Match Patterns
linkId: Match-Patterns
layout: doc
date: 2019-10-10 08:00:01
tags: 
- Concepts
---
There are two ways to [Split Chapter](#Split-Chapter) in EPUBMaker. One of them is to split by patterns.

The Regex expression will be set up to match every line of the article. Once the regex expression matched, EPUBMaker will create a new Chapter and put all the lines which are ahead of the matched line in it. Then EPUBMaker keeps matching the next lines until the end of this article.

So the match pattern should be accurate.

![](/images/concepts-match-pattern-1.png)

You could add prefix, number or suffix to compose the regex. For example, if the prefix is **Chapter** and **Section**, the number is the roman number **I**, **V**, **X**, the suffix is none and less than **50** words in one line.

Can be matched:

- Chapter I. one
- Chapter XII
- test Section X

Can NOT be matched:

- Chapter One
- XI. example
- Chapter I. a long long long long ...(over 50 words) words

#### How to add or delete prefix/number/suffix

To add words, you could type the word in input and click add icon.

To delete words, you could click the word you want to delete.

#### Save your configuration

Once save your configuration, you can use it in every language. ■