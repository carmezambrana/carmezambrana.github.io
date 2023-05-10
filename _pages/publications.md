---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publication reversed %}
  {% include archive-single-cv.html %} 
{% endfor %}



Refereed Journal Publications
===

{% for post in site.journal reversed %}
<<<<<<< Updated upstream
  {% include archive-single-cv.html %} 
=======
{% include archive-single-cv.html %} 
>>>>>>> Stashed changes
{% endfor %}


Refereed Conference Papers
===
{% for post in site.proceeding reversed %}
<<<<<<< Updated upstream
  {% include archive-single-cv.html %} 
{% endfor %}
=======
{% include archive-single-cv.html %} 
{% endfor %}
>>>>>>> Stashed changes
