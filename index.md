---
layout: page
title: 欢迎来到冬日煮男的博客
tagline: 在曲折中前行...
---
{% include JB/setup %}


文章列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
