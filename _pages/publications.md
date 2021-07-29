---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---
<H2>Journal Publications</H2>
1. N. Irtija, F. Sangoleye and E. E. Tsiropoulou, "Contract-Theoretic Demand Response Management in Smart Grid Systems," in IEEE Access, vol. 8, pp. 184976-184987, 2020, doi: 10.1109/ACCESS.2020.3030195. 
2. Sangoleye, Fisayo, Nafis Irtija, and Eirini Eleni Tsiropoulou. "Smart Energy Harvesting for Internet of Things Networks." Sensors 21.8 (2021): 2755. 
3. F. Sangoleye, J. Jao, E. E. Tsiropoulou, and S. Papavassiliou,  "Reinforcement Learning-based Demand Response Management in Smart Grid Systems with Prosumers" in IEEE TRANSACTIONS ON COGNITIVE AND DEVELOPMENTAL SYSTEMS, 2021. (Under Review). 
4. F. Sangoleye, N. Irtija, E. E. Tsiropoulou, and S. Papavassiliou, "Prospect-theoretic Demand Response Management in Smart Grid Systems" in IEEE Systems Journal, 2021. (Under Review).

<H2>Conference Publications</H2>
1. Sangoleye, F; Irtija, N; Tsiropoulou, E.E. “Data Acquisition in Social Internet of Things based-on Contract Theory” in IEEE ICC, 2021. (to appear). 




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
