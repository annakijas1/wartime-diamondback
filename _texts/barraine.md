---
layout: page
title: Barraine, Elsa (1910-1999)
category: incipits
century: 20th
permalink: /barraine/
---

<ul class="texts">
    {% for item in site.texts %}
      {% if item.author == "Barraine, Elsa" %}
          <li class="text-title">
          <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
              </a>
    </li>
      {% endif %}
    {% endfor %}
</ul>