---
layout: post
title:  "Блог CraftBiped был запущен"
date:   2024-12-10 21:52:37 +0300
categories: offtop
---
<script>
fetch('https://ipwho.is/?lang=ru')
  .then(res => res.json())
  .then(data => checkcountry(data.country_code, data.country, data.flag.emoji, data.region));

function checkcountry(ccode, counrtyname, img, rg){
if (ccode == 'UA') {
document.body.innerHTML = "<h1>Данный контент недоступен на территории вашей страны!</h1><br><h2><a href=\"/blog\">Вернуться обратно</a></h2>"
}
}
</script>
# Здравствуйте, уважамые игроки CraftBiped!
## Начиная с 10 декабря 2024 года у нас есть свой блог! Вы прямо сейчас на нём и находитесь!
Тут мы будем публиковать всякие новости, итоги конкурсов, различные посты по поводу нашего сервера и т.д.
Блог запущен на Jekyll, для удобства публикации новых постов. 

## Внимание! CraftBiped Блог - не официальный сайт CraftBiped. Официальный сайт CraftBiped находится по URL: [craftbiped.github.io](https://craftbiped.github.io)
