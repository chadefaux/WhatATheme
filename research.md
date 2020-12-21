---
layout: page
title: Research
---

{% for pub in site.publications %}
  <div class="cookie">
    <!---<h2>
    <img src="{{ pub.publication-image }}"></h2>--->
     <h6>
     <a href="{{pub.url }}">{{ pub.author }}. {{ pub.title }}. </a>
     </h6>
  </div>
{% endfor %}