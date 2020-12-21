---
layout: page
title: Cookies
---
{% for cookie in site.publications %}
  <div class="cookie">
    <h2><img src="{{ cookie.title }}" alt="{{ cookie.title }}">{{ cookie.title }}</a></h2>
    {{ cookie.content }}
  </div>
{% endfor %}