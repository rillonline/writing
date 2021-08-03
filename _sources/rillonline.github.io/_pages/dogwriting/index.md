---
layout: default
title: Dog Writing Collection
permalink: /dogwriting/
---

## Dog Writing

All the writing I have done about my [Seeing Eye](http://www.seeingeye.org) dogs is listed below.

<ul>
    {% assign sorted = site.dogwriting | sort: 'date' %}
    {% for item in sorted %}
<li><a href="{{ item.url }}">{{ item.title }}</a> {{ item.topic }}</li>
    {% endfor %}
</ul>
{% include footer.html %}
