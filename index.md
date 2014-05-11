---
layout: page
title: Zuck Blog
tagline: 记录时间的脚印
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <h3 class="main-article-title"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.date | date_to_string }}</p>
	  <div class="main-article-content">{{ post.content }}</div>
    </li>
  {% endfor %}
</ul>


