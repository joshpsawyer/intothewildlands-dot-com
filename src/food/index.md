---
title: Overnight Holiday Cinnamon Rolls
layout: base
---

<ul>
{% for food in collections.foods %}
<li><a href="{{ food.url }}">{{ food.data.indexname }}</a></li>
{% endfor %}
</ul>
