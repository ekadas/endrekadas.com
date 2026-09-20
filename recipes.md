---
layout: page
title: Recipes
permalink: /recipes/
---

<h1>Recipes</h1>
<ul>
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.url }}">{{ recipe.title }}</a></li>
{% endfor %}
</ul>
