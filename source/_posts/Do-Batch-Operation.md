---
title: Do Batch Operation
linkId: Do-Batch-Operation
layout: doc
date: 2019-10-10 08:10:00
tags: 
- Guide
---
EPUBMaker has some batch operations, some are for chapter list, some are for article editor:

#### Chapter List

##### `Chapter` -> `Take First Line as Chapter Name` 

It will get the first line of each article and rename the chapter name as the first line text.

If the first line is empty, EPUBMaker will continue to find the next line until it gets the non-empty text.

If EPUBMaker is unable to find any text in an article, it will keep the original name of the chapter.

- `Chapter` -> `Take Chapter Name as First Line ` 

It will add each chapter's name to the head of its article.

- `Tool` -> `Delete Blank Chapter`

It will delete all the blank chapter. Space is recognized as the blank.

#### Article Editor

- `Tool` -> `Reformat`

It's the same as the `Edit` ->  `remove format`. But you needn't select all the content of the article. It will directly remove all the formats in the article.

- `Tool` -> `Remove Blank Line`

Blank lines will be removed at once.

- `Tool` -> `Remove Duplicate Line`

It uses the algorithm of Levenshtein-Distance to calculate the similarity between two sentences. To get more information. Please go to [Levenshtein Distance](#Levenshtein-Distance).■