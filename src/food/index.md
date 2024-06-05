---
title: Food
layout: article
---

<ul>
{% for food in collections.foods | reverse %}
    <li>
        <a href="{{ food.url }}">{{ food.data.indexname }}</a>
    </li>
{% endfor %}
</ul>
