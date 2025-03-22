---
layout: page
title: Оффтоп
permalink: /offtop/
---

Публикации, не связанные с проектом.

{% for post in site.categories.offtop %}
<span class="post-meta">{{ post.date | date: '%b %d, %Y' }}</span>
          <h3><a class="post-link" href="/blog{{ post.url }}">
            {{ post.title }}
          </a></h3>
<br>
{% endfor %}
