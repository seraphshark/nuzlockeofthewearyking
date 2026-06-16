---
title: Home
layout: home
nav_order: 1
---
<html>
<ul>
  {% for post in site.posts %}
    <li>
      {{ site.posts.content }}
    </li>
  {% endfor %}
</ul>
</html>
