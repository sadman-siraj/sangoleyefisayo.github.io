---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---
<H2>Journal Publications</H2>
1. N. Irtija, F. Sangoleye and E. E. Tsiropoulou, "Contract-Theoretic Demand Response Management in Smart Grid Systems," in IEEE Access, vol. 8, pp. 184976-184987, 2020, doi: 10.1109/ACCESS.2020.3030195. 
2. Sangoleye, F; Irtija, N; Tsiropoulou, E.E. “Smart Energy Harvesting for Internet of Things Networks” (Under review). 

<H2>Conference Publications</H2>
1. Sangoleye, F; Irtija, N; Tsiropoulou, E.E. “Data Acquisition in Social Internet of Things based-on Contract Theory” in IEEE ICC, 2021. (to appear). 




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
