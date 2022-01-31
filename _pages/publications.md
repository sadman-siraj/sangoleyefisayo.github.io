---
layout: archive
title: "Publications"
permalink: /publications/
#author_profile: true
---

<H2>Conference Publications</H2>
1. Faisal, M. A. A., Siraj, M. S., Abdullah, M. T., Shahid, O., Abir, F. F., & Ahad, M. A. R. (2020, September). A pragmatic signal processing approach for nurse care activity recognition using classical machine learning. In Adjunct Proceedings of the 2020 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2020 ACM International Symposium on Wearable Computers (pp. 396-401). [<a href = "https://dl.acm.org/doi/abs/10.1145/3410530.3414337" target="_blank">https://dl.acm.org/doi/abs/10.1145/3410530.3414337</a>]
2. Siraj, M. S., Faisal, M. A. A., Shahid, O., Abir, F. F., Hossain, T., Inoue, S., & Ahad, M. A. R. (2020, September). UPIC: User and position independent classical approach for locomotion and transportation modes recognition. In Adjunct Proceedings of the 2020 ACM International Joint Conference on Pervasive and Ubiquitous Computing and Proceedings of the 2020 ACM International Symposium on Wearable Computers (pp. 340-345). [<a href = "https://dl.acm.org/doi/abs/10.1145/3410530.3414343" target="_blank">https://dl.acm.org/doi/abs/10.1145/3410530.3414343</a>] 
3. Siraj, M. S., Shahid, O., & Ahad, M. A. R. (2021). Cooking Activity Recognition with Varying Sampling Rates Using Deep Convolutional GRU Framework. In Human Activity Recognition Challenge (pp. 115-126). Springer, Singapore. [<a href = "https://link.springer.com/chapter/10.1007/978-981-15-8269-1_10" target="_blank">https://link.springer.com/chapter/10.1007/978-981-15-8269-1_10</a>] 
4. Siraj, M. S., & Ahad, M. A. R. (2020, August). A Hybrid Deep Learning Framework using CNN and GRU-based RNN for Recognition of Pairwise Similar Activities. In 2020 Joint 9th International Conference on Informatics, Electronics & Vision (ICIEV) and 2020 4th International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 1-7). IEEE. [<a href = "https://ieeexplore.ieee.org/document/9306630" target="_blank">https://ieeexplore.ieee.org/document/9306630</a>] 
5. Khabir, K. M., Siraj, M. S., Ahmed, M., & Ahmed, M. U. (2019, May). Prediction of gender and age from inertial sensor-based gait dataset. In 2019 Joint 8th International Conference on Informatics, Electronics & Vision (ICIEV) and 2019 3rd International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 371-376). IEEE. [<a href = "https://ieeexplore.ieee.org/document/8858521" target="_blank">https://ieeexplore.ieee.org/document/8858521</a>] 
6. Khabir, K. M., Siraj, M. S., Habib, M. A., Hossain, T., & Ahad, M. A. R. (2018, June). A study on DSR routing protocol in Adhoc network for daily activities of elderly living. In 2018 Joint 7th International Conference on Informatics, Electronics & Vision (ICIEV) and 2018 2nd International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 573-577). IEEE. [<a href = "https://ieeexplore.ieee.org/document/8640994" target="_blank">https://ieeexplore.ieee.org/document/8640994</a>] 
7. Saha, S. S., Siraj, M. S., & Habib, W. B. (2017, December). FoodAlytics: A formalin detection system incorporating a supervised learning approach. In 2017 IEEE Region 10 Humanitarian Technology Conference (R10-HTC) (pp. 26-29). IEEE [<a href = "https://ieeexplore.ieee.org/document/8288898" target="_blank">https://ieeexplore.ieee.org/document/8288898</a>]


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
