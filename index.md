---
layout: page
title: 记录
tagline: Supporting tagline
---
{% include JB/setup %}
# **我的个人日志**

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



