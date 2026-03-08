---
layout: page
title: Food
permalink: /food/
---
# My Food Adventures

<ul>
  {% for post in site.categories.food %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%b %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
