---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an Associate Professor in the [Department of Mathematics](http://math.hanyang.ac.kr/frontpage.asp?catalogid=math&language=en&calltype=redirect) at [Hanyang University](https://www.hanyang.ac.kr/web/eng) and hold an affiliated faculty position at the [Department of Computer Science](http://cs.hanyang.ac.kr) at Hanyang University. My research mainly focuses on Privacy-Enhancing Cryptography (PEC), which aims to develop advanced cryptographic primitives to protect sensitive data of individuals. 
In particular, I have been actively working on the development of homomorphic encryption, which enables to compute any function on encrypted data without decryption. Also, I have been working on privacy-preserving protocols in a wide range of applications such as data query processing, genomic analysis, and machine learning. 


# Advertisement
Positions are available for postdocs, graduate students, and interns (junior or senior student) in areas in security, privacy, and deep learning. If you are interested in applying for a position, please send an email to me.

# 🔥 News
- Our paper titled [Accelerating HE Operations from Key Decomposition Technique](https://link.springer.com/chapter/10.1007/978-3-031-38551-3_3) appeared in _Crypto 2023_.
- Our paper titled [COLLAGENE enables privacy-aware federated and collaborative genomic data analysis](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-03039-z) appeared in _Genome Biology_. 


% &nbsp;🎉🎉 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

