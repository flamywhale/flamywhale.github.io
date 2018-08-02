---
title: Markdown Gramma Test
date: 2018-06-14 14:22:36
tags: 
    - markdown
categories: test
description: 用于测试markdown的语法和css格式。
---

# 中文测试

这是一段中文。

# Heading test

`# Heading test`

## H2. Heading

`## H2. Heading`

<!-- more -->

### H3. Heading

`### H3. Heading`

#### H4. Heading

`#### H4. Heading`

##### H5. Heading

`##### H5. Heading`

###### H6. Heading

`###### H6. Heading`

------

# Font style test

## Italic：

`*Italic*`: *Italic*

## Bold：

`**Bold**`: **Bold**

## Italic & Bold：

`***Italic & Bold***`: ***Italic & Bold***

`**Markdown is _fun_**`: **Markdown is _fun_**

------

# List Test

## Ordered list

`1. 2. 3.`

1. First
2. Second
3. Third

## Unordered list

`* AAA`

* AAA
* BBB
* CCC

# Block quote test

`> flamywhale is funny.`
> flamywhale is funny.

`> Books, like friends, should be few and well chosen.`
`> This blog is well orgnaized.`
`> You are awesome.`
> Books, like friends, should be few and well chosen.
> This blog is well orgnaized.
> You are awesome.

You can also do this:
`> * Books, like friends, should be few and well chosen.`
`> * This blog is well orgnaized.`
`> * You are awesome.`

> * Books, like friends, should be few and well chosen.
> * This blog is well orgnaized.
> * You are awesome.

# Link test

## Simple link test

`<https://flamywhale.github.io>`

<https://flamywhale.github.io>

## Complex link test

`[complex link](https://flamywhale.github.io)`

[complex link](https://flamywhale.github.io)

`[about this link][1]`

`[1]: link address`

[about this link][1]

[1]: https://flamywhale.github.io

## Link description test

`[link](https://flamywhale-wu.top "the description of link")`

[link](https://flamywhale-wu.top "the description of link")

# Image insertion test

`![img](/images/icon.png)`

![img](/images/icon.png)

`![Codes](/images/icon.png "Title")`

![Codes](/images/icon.png "Title")

# Code block test

## Inline code block

\`inline code\` - `inline code`

## Code block

### C

``` C
#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("Hello, world!\n");
    return 0;
}
```

### Python

``` Python
import os
files = os.listdir()

def hello():
    return "Hello, world."

if __name__ == "__main__":
    print(hello())
```

# Others

## Breaker

`------`

------

## Footnote

`Something needs a footnote[^1].`

`[^1]: This is a footnote.`

Something needs a footnote[^1].

[^1]: This is a footnote.

Then this footnote will show at the end of this post.

## Delete

`~~There is no tree waiting for me.~~`

~~There is no tree waiting for me.~~

## Table

### A simple way

`A     | B     | C     | D`

`----- | ----- | ----- | -----`

`a     | b     | c     | d`

A     | B     | C     | D
----- | ----- | ----- | -----
a     | b     | c     | d

## Make words at left, center or right

`left      | center       | center       | right`

`:-------- | :----------: | :----------: | -----:`

`a         | b            | c            | d`

left      | center       | center       | right
:-------- | :----------: | :----------: | -----:
a         | b            | c            | d

# To be continued