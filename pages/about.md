---
layout: page
permalink: /about.html
title: 关于
tags: [关于, 博客, 阿川, blog]
---

{% comment %}
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" height="52" style="width:280px;margin:0;" src="http://music.163.com/outchain/player?type=2&id=165614&auto=0&height=32"></iframe>

{% endcomment %}


自 2018 年 08 月 31 日起，本站已运行 <span id="days"></span> 天，截至 {{ site.time | date: "%Y 年 %m 月 %d 日" }}，写了博文 {{ site.posts.size }} 篇，{% assign count = 0 %}{% for post in site.posts %}{% assign single_count = post.content | strip_html | strip_newlines | remove: ' ' | size %}{% assign count = count | plus: single_count %}{% endfor %}{% if count > 10000 %}{{ count | divided_by: 10000 }} 万 {{ count | modulo: 10000 }}{% else %}{{ count }}{% endif %} 字。

## 博主


* Email: mailto:{{ site.author.email }}
* WeChat: 阿川（[二维码]({{ site.IMG_PATH }}/wechat.jpg)）

## 博客进程



## 赞赏奖励

若您觉得鄙人所创造的内容对您有所帮助，可考虑略表心意，支持本博。

以下是微信赞赏码：

![微信赞赏码]({{ site.IMG_PATH }}/wechat-reward.png){:width="150"}

### 财主列表

* [1900](http://1900.live)
* [Lexus](http://leiminnet.cn)