---
layout: default
title: My Spiritual Writing Collection
permalink: /spiritualwriting/
---

## Spiritual Writing

My spiritual writing is listed below.

<ul>
    {% assign sorted = site.spiritualwriting | sort: 'date' %}
    {% for item in sorted %}
<li><a href="{{ item.url }}">{{ item.title }}</a> {{ item.topic }}</li>
    {% endfor %}
</ul>
{% include footer.html %}
