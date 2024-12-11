---
layout: page
title: Новости
permalink: /news/
---


{% for post in site.categories.news %}
<span class="post-meta">{{ post.date }}</span>
          <h3><a class="post-link" href="/blog{{ post.url }}">
            {{ post.title }}
          </a></h3>
{% endfor %}
