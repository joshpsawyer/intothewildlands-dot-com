---
title: houses
layout: base
---

<ul>
{% for house in collections.houses %}
<li><a href="{{ house.url }}">{{ house.data.indexname }}</a></li>
{% endfor %}
</ul>
