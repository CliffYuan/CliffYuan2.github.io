---
layout: page
title: 首页-小牛犊的领地
tagline: Supporting tagline
---
{% include JB/setup %}

发现很多使用过的东西一段时间不用就忘记了，使用evernote剪切了一些内容，但基本上没有看。因此使用这个记录一些总结。

## 流水

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


#### 博客使用说明
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)
