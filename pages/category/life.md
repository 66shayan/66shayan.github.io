---
layout: 'page'
title: 'life Category'
permalink: '/category/life/'
category: life
---
{% for categories in site.categories %}
  <h3>{{ categories[1] }}</h3>
  <ul>
    {% for post in categories[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
