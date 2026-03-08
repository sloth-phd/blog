---
layout: page
title: Music
permalink: /music/
---
# Music


<ul>
  {% for post in site.categories.music %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%b %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
