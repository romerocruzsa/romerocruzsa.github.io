---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Sebastián A. Cruz Romero is the founder and CEO of [Capicú Technologies](https://capicu.ai). He builds tiny AI that helps scientists make medicines from living cells. He is a former M.Sc. student in Bioengineering at the University of Puerto Rico at Mayagüez, where he earned his B.Sc. in Computer Science and Engineering. His training spans research, industry, and startup experience at OcyonBio (biotech CDMO), Apple-USC, NVIDIA, MIT, and the University of Iowa, with support from 20+ scholarhips and fellowships including: the National Science Foundation (NSF) and National Institute of Health (NIH), Apple, and the Hispanic Scholarship Fund. He also founded a mentorship program to foster biomedical engineering & bioengineering career development in his university despite the lack of an academic program. Now, 82% of mentees landed internships at R1 institutions and leading Life Science & MedTech organizations.

News
======
<!-- News items live in _data/news.yml -->
<ul class="news-list">
{% for item in site.data.news.items %}
  <li><strong>{{ item.date }}</strong>: {{ item.body | markdownify | remove: "<p>" | remove: "</p>" | strip }}</li>
{% endfor %}
</ul>
