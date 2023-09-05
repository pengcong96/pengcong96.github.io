---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A complete list can be found in [Google Scholar](https://scholar.google.com/citations?user=iUdr3DIAAAAJ&hl=en).

## 2020

An Identity-Based Blind Signature Scheme with Message Recovery from Pairings

* **Cong Peng**, Jianhua Chen, Lu Zhou, Kim-Kwang Raymond Choo, Debiao He. CsiIBS: A post-quantum identity-based signature scheme based on isogenies. _Journal of Information Security and Applications_, vol. 54, pp. 102504, 2020.

* **Cong Peng**, Jianhua Chen, Mohammad S Obaidat, Pandi Vijayakumar, Debiao He. Efficient and provably secure multi-receiver signcryption scheme for multicast communication in edge computing. _IEEE Internet of Things Journal_, vol. 7, no. 7, pp.6056-6068, 2020.

## 2019

* **Cong Peng**, Jianhua Chen, Sherali Zeadally, Debiao He. Isogeny-based cryptography: a promising post-quantum technique. _IT Professional_, vol. 21, no. 6, pp. 27-32, 2019.

## 2018 and Before



   
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
