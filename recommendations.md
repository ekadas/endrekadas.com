---
layout: page
title: Recommendations
permalink: /recommendations/
---

<h2>Recommendations</h2>
<ul>
{% for recommendation in site.recommendations %}
  <li><a href="{{ recommendation.url }}">{{ recommendation.title }}</a></li>
{% endfor %}
</ul>
