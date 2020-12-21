---
layout: page
title: Cookies
---

{% for pub in site.publications %}
  <div class="cookie">
    <h2><img src="{{ pub.publication-image }}" alt="{{ pub.title }}">{{ pub.title }}</a></h2>
    {{ pub.content }}
  </div>
{% endfor %}