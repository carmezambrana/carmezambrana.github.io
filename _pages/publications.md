---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

Refereed Journal Publications
===

{% for post in site.journal reversed %}
{% include archive-single-cv.html %} 
{% endfor %}


Refereed Conference Papers
===
{% for post in site.proceeding reversed %}
{% include archive-single-cv.html %} 
{% endfor %}

