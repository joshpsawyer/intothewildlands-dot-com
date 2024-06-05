---
title: stories
layout: story
---

<ul>
{% for story in collections.stories %}
<li><a href="{{ story.url }}">{{ story.data.indexname }}</a></li>
{% endfor %}
</ul>
