---
layout: page
title: Recommendations
permalink: /recommendations/
---

<h1>Recommendations</h1>
<ul>
{% for recommendation in site.recommendations %}
  <li><a href="{{ recommendation.url }}">{{ recommendation.title }}</a></li>
{% endfor %}
</ul>
