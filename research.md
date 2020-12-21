---
layout: page
title: Research
---

{% for pub in site.publications %}
  <div class="cookie">
    <!---<h2>
    <img src="{{ pub.publication-image }}"></h2>
     <h2>--->
     <a href="{{pub.baseurl }}">{{ pub.title }}</a>
     </h2>
  </div>
{% endfor %}