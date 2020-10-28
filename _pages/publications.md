---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---

"Irtija, N; Sangoleye, F; Tsiropoulou, E.E. "Contract-theoretic Demand Response Management in Smart Grid Systems" in IEEE Access 2020."


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
