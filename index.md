---
layout: page
title: a Programmer Loving Horse Driding 
---
{% include JB/setup %}

## 自我介绍


* 我是一个程序员，喜欢骑马（不怕你笑话，骑过3-5次）。

* 喜欢踢球，美女，电影和音乐。 

* 对微博（包括新浪和twitter），动漫，看书和美食`不`感兴趣。

* 没有信仰，无所敬畏。对啥都好奇，对啥都不坚定。

* 湖南，长沙人，`不`能吃辣。

    
## 文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

