---
title: 友人帐
date: 2020-06-07 22:17:49
type: "link"
aside: false
top_img: false
---

<h1>我的友链</h1>

{% tabs Mylink%}

<!-- tab 🙋 butterfly-💭candy -->

```yml
- name: morty's blog
  link: https://mortyzhaoy.github.io
  avatar: https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png
  descr: 别急，慢慢来。终会做成的。
  siteshot: "https://xxx.jpg"
```

<!-- endtab -->

<!-- tab ☀️Volantis -->

```json
{
  "title": "morty's blog",
  "screenshot": "https://xxx.jpg",
  "url": "https://mortyzhaoy.github.io",
  "avatar": "https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png",
  "description": "别急，慢慢来。终会做成的。",
  "keywords": "morty"
}
```

<!-- endtab -->

<!-- tab 🌴General -->

| 名称       | 数值                                                                      |
| :--------- | :------------------------------------------------------------------------ |
| 站点名称   | morty's blog                                                              |
| 站点截图   | https://xxx.jpg |
| 站点链接   | https://mortyzhaoy.github.io                                              |
| 站长头像   | https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png       |
| 站点描述   | 别急，慢慢来。终会做成的。                                                        |
| 站点关键词 | morty                                                   |

<!-- endtab -->

<!-- tab Fuild -->

```yml
- {
    title: "morty's blog",
    intro: "别急，慢慢来。终会做成的。",
    link: "https://mortyzhaoy.github.io",
    image: "https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png",
  }
```

<!-- endtab -->

<!-- tab Volantis -->

```yml
{
  "title": "morty's blog",
  "avatar": "https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png",
  "screenshot": "https://xxx.jpg",
  "url": "https://mortyzhaoy.github.io",
  "description": "别急，慢慢来。终会做成的。",
  "group": ,# 根据你的博客来定义
}
```

<!-- endtab -->

<!-- tab Html -->

```html
<a href="https://mortyzhaoy.github.io" rel="external nofollow">morty-blog</a>
```

<!-- endtab -->

<!-- tab Jade -->

```code
a(href='https://mortyzhaoy.github.io' rel="external nofollow") morty-blog
```

<!-- endtab -->

{% endtabs %}

{% folding , ✅加入本站友链方式 %}

## 本站添加的友链要求

1. 能够正常访问
2. 含本站友链
3. 网站类型为<strong>个人博客</strong>

请（<a onclick="anzhiyu.addFriendLink()" href="#post-comment">点击这里快速添加</a>） 站点信息申请友情链接，申请后在我不忙的时候会统一添加，即使不通过也会给予邮件回复。

## 你提交的信息有可能被修改

如果有修改，我会将修改内容进行告知

1. 为了友链相关页面和组件的统一性和美观性，可能会对你的昵称进行缩短处理，例如昵称包含`博客`、`XX 的 XX`等内容或形式将被简化。
2. 为了图片加载速度和内容安全性考虑，头像实际展示图片均使用博客自己图床，所以无法收到贵站自己的头像更新，如果有迫切的更改信息需求，请在本页的评论中添加。
3. 为了保证鱼塘能够正确抓取文章，所有的友链链接要求为博客主页链接，而不是个人主页链接。

## 提交友链信息

为了避免图床问题，建议你将头像存储到贵站图床。

1. 我的名称：morty's blog
2. 网站地址：https://mortyzhaoy.github.io
3. 描述：别急，慢慢来。终会做成的。
4. 头像：https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png
5. 站点截图：https://xxx.jpg

参照以下格式留言 📋 即可。

```yml
昵称（请勿包含博客等字样）：
网站地址（要求博客地址，请勿提交个人主页）：
头像图片url（请提供尽可能清晰的图片，我会上传到我自己的图床）：
描述：
站点截图:(可选)：
```

示例 📢：

```yml
昵称：morty's blog
网站地址：https://mortyzhaoy.github.io
头像图片url：https://raw.githubusercontent.com/MortyZhaoy/blog_image/main/images/111164782.png
描述：别急，慢慢来。终会做成的。
站点截图:(可选)：https://xxx.jpg
```

{% tip faa-horizontal animated %}

站点截图建议自己提供，尺寸尽量不要大于 300\*300。

未提供站点预览图的，本站会根据贵站链接调用以下 API 自动获取贵站的站点截图。

对于做了反扒措施的站点，API 获取的将是反扒页面，望知悉。

{% endtip %}

站点截图建议使用以下 API 获取以匹配本站样式。

```markdown
https://image.thum.io/get/width/400/crop/800/allowJPG/wait/20/anzhiy.cn/https://<你的域名>/
```

{% endfolding %}

{% folding , 友情链接页免责声明 %}

## 免责声明

本博客遵守中华人民共和国相关法律。本页内容仅作为方便学习而产生的快速链接的链接方式，对与友情链接中存在的链接、好文推荐链接等均为其他网站。我本人能力有限无法逐个甄别每篇文章的每个字，并无法获知是否在收录后原作者是否对链接增加了违反法律甚至其他破坏用户计算机等行为。因为部分友链网站甚至没有做备案、域名并未做实名认证等，所以友链网站均可能存在风险，请你须知。

所以在我力所能及的情况下，我会包括但不限于：

1. 针对收录的博客中的绝大多数内容通过标题来鉴别是否存在有风险的内容
2. 在收录的友链好文推荐中检查是否存在风险内容

但是你在访问的时候，仍然无法避免，包括但不限于：

1. 作者更换了超链接的指向，替换成了其他内容
2. 作者的服务器被恶意攻击、劫持、被注入恶意内容
3. 作者的域名到期，被不法分子用作他用
4. 作者修改了文章内容，增加钓鱼网站、广告等无效信息
5. 不完善的隐私保护对用户的隐私造成了侵害、泄漏

最新文章部分为机器抓取，本站作者未经过任何审核和筛选，本着友链信任原则添加的。如果你发现其中包含违反中华人民共和国法律的内容，请及时联系和举报。该友链会被拉黑。

如果因为从本页跳转给你造成了损失，深表歉意，并且建议用户如果发现存在问题在本页面进行回复。通常会很快处理。如果长时间无法得到处理，建议联系`morty.zhaoy@gmail.com`。

{% endfolding %}

{% folding , 出现问题的友链 %}

## 出现问题的友链

如果友链出现问题会展示在这里，如果已解决问题还请告知。

```yml
- name: xxx # 无友链
  link: https://www.xxx.com
  avatar: https://xxx.jpg
  descr: xxx
  siteshot: https://xxx.jpg
```

{% endfolding %}
