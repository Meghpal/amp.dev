---
$title: Выполняйте предварительное подключение к Google Fonts
$order: 150
tags:
- lcp
---

Современные браузеры поддерживают подсказки для загрузки ресурсов, такие как `preconnect`, которые позволяют ускорить работу сайта и сократить время загрузки страниц. <br><br>Вы можете использовать их вручную; например, добавьте на страницу следующий код:

```
<link href="https://fonts.gstatic.com" rel="dns-prefetch preconnect" crossorigin>
```
