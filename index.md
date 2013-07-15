---
layout: page
title: Zuck Blog
tagline: 记录时间的脚印
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <a href="{{ BASE_PATH }}{{ post.url }}"><h3>{{ post.title }}</h3></a>
      <p>{{ post.content }}</p>
    </li>
  {% endfor %}
</ul>


