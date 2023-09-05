---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A complete list can be found in [Google Scholar](https://scholar.google.com/citations?user=iUdr3DIAAAAJ&hl=en).

## 2018 and Before


1. **Cong Peng**, Jianhua Chen, Sherali Zeadally, Debiao He. Isogeny-based cryptography: a promising post-quantum technique. *IT Professional*, vol. 21, no. 6, pp. 27-32, 2019. [![doi](../images/DOI_logo-svg.png)]](10.1109/MITP.2019.2943136)
2. **Cong Peng**, Jianhua Chen, Mohammad S Obaidat, Pandi Vijayakumar, Debiao He. Efficient and provably secure multi-receiver signcryption scheme for multicast communication in edge computing. 
3. Yuanyuan Zhang, Jianhua Chen, Baojun Huan, **Cong Peng**. An efficient password authentication scheme using smart card based on elliptic curve cryptography. *Information Technology And Control*, vol. 43, no. 4, pp. 390-401, 2014.

\* Corresponding / Co-corresponding author 

\# Co-first author


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
