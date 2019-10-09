---
title: Sort Chapter
linkId: Sort-Chapter
layout: doc
date: 2019-10-10 08:08:00
tags: 
- Guide
---
You may have the need to sort and structure your chapter list, So this one could help you.

You can use the Right-Click to open the Right context menu like this:

![](/images/guide-sort-chapter-1.png)

You could find four operations are related to sort chapter:

- Up Chapter
- Down Chapter
- Up Level
- Down Level

#### Up/Down Chapter

The first two operations are used to sort your chapter list.

If you `Up Chapter` , the selected chapter will move forward to the chapter ahead of it and **its children chapters will move together**. But If the selected chapter is the first chapter in its level, it will do nothing. The same as `Down Chapter`. Here we will show you some examples:

```
Level 1-1
-- Level 2-1
---- Level 3-1
-- Level 2-2
---- Level 3-2
-- Level 2-3
```

Select the `Level 2-2` to `Up Chapter`:

```
Level 1-1
-- Level 2-2
---- Level 3-2
-- Level 2-1
---- Level 3-1
-- Level 2-3
```

If you select the `Level 2-1` to `Up Chapter`, it will do nothing. Because `Level 2-1` is the first chapter in its level.

#### Up/Down Level

The rest two of the operations are used to adjust the level of chapter.

If you `Up Level` , the selected chapter will up its level and **its children chapters will up together**. But If the selected chapter is the top level, it will do nothing. The same as `Down Level`. Here we will show you some examples:

```
Level 1-1
-- Level 2-1
---- Level 3-1
-- Level 2-2
---- Level 3-2
-- Level 2-3
```

Select the `Level 2-2` to `Up Chapter`:

```
Level 1-1
-- Level 2-1
---- Level 3-1
 Level 2-2
-- Level 3-2
-- Level 2-3
```

If you select the `Level 1-1` to `Up Level`, it will do nothing. Because the `Level 1-1` is the top level. ■

