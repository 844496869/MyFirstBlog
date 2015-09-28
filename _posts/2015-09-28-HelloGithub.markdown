---
date:   2015-09-28 20:56:19
title: Hello GitHub!
---
<ul class="posts">
{% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>