---
title: "Hugo Sample 6"
date: 2018-04-08T14:45:11+09:00
categories:
- Develop
tags:
- "testtag"
- "sample"
---

テスト投稿6

Hugoでブログを作成しています。

このページはテストページです。

簡単なソースコードのサンプルと画像、instagram、twitterの埋め込みコンテンツを載せます。

```c
#include <stdio.h>

int main()
{
    /* サンプル */
    printf("test¥n");
}
```

{{< tweet 979134471181164544 >}}


https://www.instagram.com/p/BhBdaHujYuF/

{{< instagram BhBdaHujYuF >}}

1

{{< figure src="/images/bg.jpg" title="Steve Francia" >}}

2

{{< img src="top.jpg" >}}

{{< img src="/images/apple-touch-icon.png" >}}
{{< img src="/images/bg.jpg" >}}

3
{{< img src="top.jpg" title="tmp.jpg" class="center" width="320" height="640" >}}

4
画像 ![](/images/tmp.jpg)

5
画像 ![](https://pbs.twimg.com/profile_images/1843439342/same_400x400.png)

6
<img src="https://pbs.twimg.com/profile_images/1843439342/same_400x400.png" width="200px">

7
画像 ![](https://raw.githubusercontent.com/yuzuafro/hugosample/gh-pages/images/tmp.jpg)
