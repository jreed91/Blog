---
layout: page
title: Stream-of-Consciousness
---

##Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> &raquo; <span>{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>




