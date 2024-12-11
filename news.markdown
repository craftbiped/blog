---
layout: page
title: Новости
permalink: /news/
---

<h1>Новости CraftBiped</h1>
<ul>
{% for category in site.categories.news %}
  <li><a name="{{ category | first }}">{{ category | first }}</a>
    <ul>
    {% for post in category.last %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    </ul>
  </li>
{% endfor %}
</ul>

