---
layout: page
title: Nursery rhymes
permalink: /nursery-rhymes/
---

<h2>Nursery rhymes</h2>
<ul>
{% for rhyme in site["nursery-rhymes"] %}
  <li><a href="{{ rhyme.url }}">{{ rhyme.title }}</a></li>
{% endfor %}
</ul>
