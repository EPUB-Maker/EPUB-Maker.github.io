---
title: Create Chapter
linkId: Create-Chapter
layout: doc
date: 2019-10-10 08:04:00
tags: 
- Guide
---

`Chapter` -> `Add Chapter` and `Chapter` -> `Insert Chapter` are both the ways to create a chapter. 

`Add Chapter` will add a new chapter to the bottom of the chapter list.

For `Insert Chapter`, it will add a new chapter behind the selected chapter and keep the level of the selected chapter.

For example, There has a Chapter list:

```
Level 1-1
-- Level 2-1
---- Level 3-1
-- Level 2-2
```

If I select the `Level 2-1` and `Add Chapter`, the new Chapter List will be

```
Level 1-1
-- Level 2-1
---- Level 3-1
-- Level 2-2
New Chapter
```

But if you select the `Level 2-1` and `Insert Chapter`, the new Chapter List will be

```
Level 1-1
-- Level 2-1
---- Level 3-1
-- New Chapter
-- Level 2-2
```

■