---
layout: page
title: Research
---

{% for pub in site.publications %}
  <div class="cookie">
    <h2><img src="{{ pub.publication-image }}" alt="{{ pub.title }}">{{ pub.title }}</a></h2>
     <h2><a href="{{ pub.url }}">{{ pub.title }}</a></h2>
  </div>
{% endfor %}