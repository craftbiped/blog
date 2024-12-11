---
layout: page
title: Новости
permalink: /news/
---


<ul>
{% for category in site.categories.news %}
    <ul>
    {% for post in category.last %}
      <li><a href="/blog{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>
