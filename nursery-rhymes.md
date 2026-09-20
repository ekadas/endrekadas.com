---
layout: page
title: Nursery rhymes
permalink: /nursery-rhymes/
---

<h1>Nursery rhymes</h1>
<ul>
{% for rhyme in site["nursery-rhymes"] %}
  <li><a href="{{ rhyme.url }}">{{ rhyme.title }}</a></li>
{% endfor %}
</ul>
