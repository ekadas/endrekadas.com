---
layout: page
title: Recommendation
permalink: /recommendations/
---

<ul>
{% for recommendation in site.recommendations %}
  <li><a href="{{ recommendation.url }}">{{ recommendation.title }}</a></li>
{% endfor %}
</ul>
