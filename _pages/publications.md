---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---

<H2>Conference Publications</H2>

<ol>
  <li><p align="justify"><b>Siraj, M. S.</b>, Rahman, A. B., Diamanti, M., Tsiropoulou, E. E., Papavassiliou, S., & Plusquelic, J., "Positioning, Navigation, and Timing enabled by Reconfigurable Intelligent Surfaces, Phase Shift Optimization, and Reinforcement Learning", IEEE MILCOM, 2022. (Under Review)</p></li>
  <li><p align="justify"><b>Siraj, M. S.</b>, Hossain, M. S., Brown, R., Tsiropoulou, E. E., & Papavassiliou, S., "Incetives to Learn: A Location-based Federated Learning Model", IEEE GLOBECOM, 2022. (Under Review)</p></li>
  <li><p align="justify">Rahman, A. B., <b>Siraj, M. S.</b>, Kubiak, N., Tsiropoulou, E. E., & Papavassiliou, S., "Network Economics-based Crowdsourcing in Online Social Networks", IEEE GLOBECOM, 2022. (Under Review)</p></li> 
  <li><p align="justify">Faisal, M. A. A., <b>Siraj, M. S.</b>, Abdullah, M. T., Shahid, O., Abir, F. F., & Ahad, M. A. R. (2020, September). A pragmatic signal processing approach for nurse care activity recognition using classical machine learning. In Adjunct Proceedings of the 2020 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2020 ACM International Symposium on Wearable Computers (pp. 396-401). [doi: 10.1145/3410530.3414337]</p></li>
  <li><p align="justify"><b>Siraj, M. S.</b>, Faisal, M. A. A., Shahid, O., Abir, F. F., Hossain, T., Inoue, S., & Ahad, M. A. R. (2020, September). UPIC: User and position independent classical approach for locomotion and transportation modes recognition. In Adjunct Proceedings of the 2020 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2020 ACM International Symposium on Wearable Computers (pp. 340-345). [doi: 10.1145/3410530.3414343]</p></li> 
  <li><p align="justify"><b>Siraj, M. S.</b>, & Ahad, M. A. R. (2020, August). A Hybrid Deep Learning Framework using CNN and GRU-based RNN for Recognition of Pairwise Similar Activities. In 2020 Joint 9th International Conference on Informatics, Electronics & Vision (ICIEV) and 2020 4th International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 1-7). [doi: 10.1109/ICIEVicIVPR48672.2020.9306630]</p></li>
  <li><p align="justify">Khabir, K. M., <b>Siraj, M. S.</b>, Ahmed, M., & Ahmed, M. U. (2019, May). Prediction of gender and age from inertial sensor-based gait dataset. In 2019 Joint 8th International Conference on Informatics, Electronics & Vision (ICIEV) and 2019 3rd International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 371-376). [doi: 10.1109/ICIEV.2019.8858521]</p></li> 
  <li><p align="justify">Khabir, K. M., <b>Siraj, M. S.</b>, Habib, M. A., Hossain, T., & Ahad, M. A. R. (2018, June). A study on DSR routing protocol in Adhoc network for daily activities of elderly living. In 2018 Joint 7th International Conference on Informatics, Electronics & Vision (ICIEV) and 2018 2nd International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 573-577). [doi: 10.1109/ICIEV.2018.8640994]</p></li>
  <li><p align="justify">Saha, S. S., <b>Siraj, M. S.</b>, & Habib, W. B. (2017, December). FoodAlytics: A formalin detection system incorporating a supervised learning approach. In 2017 IEEE Region 10 Humanitarian Technology Conference (R10-HTC) (pp. 26-29). [doi: 10.1109/R10-HTC.2017.8288898]</p></li>
</ol>

<H2>Book Chapters</H2>

<ol>
<li><p align="justify"><b>Siraj, M. S.</b>, Shahid, O., & Ahad, M. A. R. (2021). Cooking Activity Recognition with Varying Sampling Rates Using Deep Convolutional GRU Framework. In Human Activity Recognition Challenge (pp. 115-126). [doi: 10.1007/978-981-15-8269-1_10]</p></li>
</ol>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
