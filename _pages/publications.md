---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.es/citations?user=9d5iV8oAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Refereed Journal Publications
===

{% for post in site.publications %}
{% include archive-single-cv.html %} 
{% endfor %}


Refereed Conference Papers
===
