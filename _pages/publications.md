---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}


Refereed Journal Publications
===

{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}


Refereed Conference Papers
===

{% for post in site.publications reversed %}
  {% if post.pubtype == 'booktitle' %}
      {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}

