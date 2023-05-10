---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}


{% for post in site.publications reversed %}
{% include archive-single-cv.html %} 
{% endfor %}


Refereed Journal Publications
===

{% for post in site.publications reversed %}
{% if post.collection contains "journal" %}
  {% include archive-single-cv.html %} 
{% endif %}
{% endfor %}


Refereed Conference Papers
===
{% for post in site.publications reversed %}
{% if post.collection contains "procedding" %}
{% include archive-single-cv.html %} 
{% endif %}
{% endfor %}

