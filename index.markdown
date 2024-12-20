---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Главная
layout: page
---

## Добро пожаловать в официальный блог CraftBiped! Тут мы публикуем наши главные новости, различные посты и т.д. 
В данный момент на нашем блоге могут встречаться проблемы (например: неполный перевод некоторых частей сайта). Мы постараемся это исправить в будущем. 
{% for post in site %}
<span class="post-meta">{{ post.date | date: '%b %d, %Y' }}</span>
          <h3><a class="post-link" href="/blog{{ post.url }}">
            {{ post.title }}
          </a></h3>
<br>
{% endfor %}
