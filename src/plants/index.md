---
title: Plants
layout: plant
---

<ul>
{% for plant in collections.plants %}
<li><a href="{{ plant.url }}">{{ plant.data.indexname }}</a></li>
{% endfor %}
</ul>
