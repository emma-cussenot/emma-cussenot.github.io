---
layout: page
permalink: /publications/
title: Publications
description: Selected publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

{% for entry in site.bibliography %}
  {% if entry[1].bibtex_show %}
    {% include bib.liquid entry=entry %}
  {% endif %}
{% endfor %}

</div>
