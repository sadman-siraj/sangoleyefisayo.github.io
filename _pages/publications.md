---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---
Journal Publications
1. Irtija, N; Sangoleye, F; Tsiropoulou, E.E. "Contract-theoretic Demand Response Management in Smart Grid Systems" in IEEE Access 2020.

Conference Publications
1. Sangoleye, F; Irtija, N; Tsiropoulou, E.E. "Data Acquisition in Social Internet of Things basedon Contract Theory" in IEEE ICC, 2021. (under review).




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
