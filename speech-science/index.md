---
layout: page
title: Speech-science
permalink: /speech-science/
---
# Speech science


<ul>
  {% for post in site.categories.speech-science %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%b %d, %Y" }})</span>
    </li>
  {% endfor %}
</ul>
