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

Hello! I am Yujia Cai, a third-year undergraduate student majoring in Computer Science at Xidian University. I am currently a research intern at Stony Brook University, advised by Prof. [Chenyu You](https://chenyuyou.me/), and I also collaborate closely with [Qin Ren](https://soonera.github.io/qinren/). Previously, I worked on Style-adaptive Retrieval with [Jiexi Yan](https://faculty.xidian.edu.cn/YANJIEXI/zh_CN/index.htm).
My research experience spans Multimodal Learning and Medical image analysis, with prior work on Retrieval, Domain adaptation, and  Parameter-efficient fine-tuning.

I am particularly interested in learning robust and efficient representations that generalize across domains and modalities, with the goal of building practical models for vision, multimodal understanding, and scientific discovery.


# 🔥 News
- *2026.01*: 🎉 Our paper **Hystar: Hypernetwork-Driven Style-Adaptive Retrieval via Dynamic SVD Modulation** was accepted to ICLR 2026.

# 📝 Publications 
<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">ICLR 2026</div>
<img src='images/hystar.png' alt="Hystar framework" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[Hystar: Hypernetwork-Driven Style-Adaptive Retrieval via Dynamic SVD Modulation](https://openreview.net/forum?id=tiWCvwi4b8)

**Yujia Cai**, Boxuan Li, Chenghao Xu, Jiexi Yan

International Conference on Learning Representations (ICLR), 2026

[**Paper**](https://openreview.net/forum?id=tiWCvwi4b8)

- We propose **Hystar**, a hypernetwork-driven style-adaptive retrieval framework 
that dynamically modulates the singular values of attention layers via hypernetworks 
to improve robustness under diverse visual styles. The method introduces an 
OT-weighted StyleNCE loss to reweight hard negatives and mitigate cross-style 
semantic confusion. Experiments on DomainNet and DSR demonstrate consistent 
improvements in cross-style retrieval and zero-shot classification.

</div>
</div>

<!--
- [Hystar: Hypernetwork-Driven Style-Adaptive Retrieval via Dynamic SVD Modulation](https://openreview.net/forum?id=tiWCvwi4b8), ICLR, 2026
-->

<!--
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📖 Educations
- *2023.09 – Present*, B.S. in Computer Science, National Top-Notch Student Training Program 2.0 in Basic Disciplines, Xidian University, Xi’an, China. Expected Jun. 2027.

# 📝 Academic Service

- *2026.01 – Present* Journal Reviewer, *Pattern Recognition*.
- *2025 – Present* Journal Reviewer, *IEEE Transactions on Neural Networks and Learning Systems*.

<!--  
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships
- *Oct 2024 – Present*, Research Intern, OPTIC Lab, Xidian University, China.
- *Jan 2026 – Present*, Research Intern, Stony Brook University, USA.
