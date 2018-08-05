---
layout: home
---

{% for product in site.products %}
  <h2>{{ product.title }}</h2>
  <p>{{ product.description }}</p>
  <p><a href="{{ product.url }}">{{ product.title }}</a></p>
{% endfor %}