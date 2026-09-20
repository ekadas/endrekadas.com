---
layout: page
title: Recommendations
permalink: /recommendations/
body_class: index-page
---

<h1>Recommendations</h1>
<ul>
{% for recommendation in site.recommendations %}
  <li><a href="{{ recommendation.url }}">{{ recommendation.title }}</a></li>
{% endfor %}
</ul>
