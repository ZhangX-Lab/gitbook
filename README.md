# 😄 README

## Overview

#### 什么是gitbook？

顾名思义，gitbook就是git和book，就是一个交互式的文档、书籍管理与编写工具。我们可以将其与github进行同步，这样我们可以摘gitbook上很容易的编写文档，以及很容易的同步到github上，在使用github相关工具生成一个github网页，可以做成一个自制的网页在线博客或者更方便的给其他人看。

gitbook的优势在于编写文档上的优势，一个space就是一个仓库分支，里面可以创建group（文件夹）、创建pages(一个.md文件)。同时git会生成一个SUMMARY.md的文件，里面包含了目录大纲以及文档索引。

```c
#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("hello world\n");
    
    return 0;
}

```

Here are a couple of example overviews from products with really great docs:

> Loom is a video messaging tool that helps you get your message across through instantly shareable videos.
>
> With Loom, you can record your camera, microphone, and desktop simultaneously. Your video is then instantly available to share through Loom's patented technology.
>
> — From the [Loom Docs](https://support.loom.com/hc/en-us/articles/360002158057-What-is-Loom-)



## Quick links

##

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Bearer <token>`   |

**Body**

| Name   | Type   | Description      |
| ------ | ------ | ---------------- |
| `name` | string | Name of the user |
| `age`  | number | Age of the user  |

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "id": 1,
  "name": "John",
  "age": 30
}
```
{% endtab %}

{% tab title="400" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}
{% endtabs %}



| 11   | 55     | 66 | 77 |
| ---- | ------ | -- | -- |
| 11   | 312    |    |    |
| 111  | 231cdc |    |    |
| 1111 | ccc    |    |    |
|      |        |    |    |

