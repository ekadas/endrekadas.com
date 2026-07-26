---
layout: page
title: Recipes
permalink: /recipes/
---

<h2>Recipes</h2>
<ul>
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.url }}">{{ recipe.title }}</a></li>
{% endfor %}
</ul>
