---
layout: 'page'
title: 'life Category'
permalink: '/category/life/'
category: life
---
{% for category in site.category %}
  <h3>{{ category[1] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
