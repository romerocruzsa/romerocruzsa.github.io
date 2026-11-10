---
permalink: /
title: "About"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Sebastián A. Cruz Romero is the founder and CEO of [Capicú Technologies](https://capicu.ai). He builds tiny AI that helps scientists make medicines from living cells. He is a former M.Sc. student in Bioengineering at the University of Puerto Rico at Mayagüez, where he earned his B.Sc. in Computer Science and Engineering.

His training spans research, industry, and startup experience at OcyonBio (biotech CDMO), Apple–USC, NVIDIA, MIT, and the University of Iowa, with support from 20+ scholarships and fellowships, including from the National Science Foundation (NSF), the National Institutes of Health (NIH), Apple, and the Hispanic Scholarship Fund. He also founded a mentorship program to foster biomedical engineering and bioengineering career development at his university, despite the lack of an academic program. Today, 82% of its mentees have landed internships at R1 institutions and leading life science and MedTech organizations.

News
======
<!-- News items live in _data/news.yml -->
<ul class="news-list">
{% for item in site.data.news.items %}
  <li><strong>{{ item.date }}</strong>: {{ item.body | markdownify | remove: "<p>" | remove: "</p>" | strip }}</li>
{% endfor %}
</ul>
