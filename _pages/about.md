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

I am a master's student (2023) at the School of Computer Science and Technology, Beijing Jiaotong University. I received my bachelor's degree in Intelligent Science and Technology from China University of Petroleum (East China). My research interests include graph machine learning and large language models, with a focus on designing efficient algorithms for dynamic graph learning and natural language processing.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition</div><img src='images/signn.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SiGNN: A Spike-induced Graph Neural Network for Dynamic Graph Representation Learning](https://doi.org/10.1016/j.patcog.2024.111026)

**Dong Chen**, Shuai Zheng, Muhao Xu, Zhenfeng zhu, Yao Zhao

- Propose a spike-induced DGL framework: SiGNN, which integrates GNN and SNN for efficient representation learning on dynamic graph.
- Novel spiking neuron model: BLIF.
- Multi-time-resolution dynamic graph modeling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Undereview</div><img src='images/signn.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Graph Condensation](https://arxiv.org/abs/2506.13099)

**Dong Chen**, Shuai Zheng, Yeyu Yan, Muhao Xu, Zhenfeng Zhu, Yao Zhao, Kunlun He


- Pioneer the study of dynamic graph condensation and propose the first condensation framework for dynamic graph.
- Novel spiking structure generation mechanism.
- Tailored distribution matching approach that performs fine-grained spatiotemporal state alignment to guide the optimization of the condensed graph.
</div>
</div>


# 🎖 Honors and Awards
- *2024.12*  National Scholarship for Graduate Students, Ministry of Education of China. 

# 📖 Educations
- *2023.09 - 2025.06 (now)*, M.S. in Information and Communication Engineering, School of Computer Science and Technology, Beijing Jiaotong University.
- *2019.09 - 2023.06*, B.S. in Intelligent Science and Technology (Science Experimental Class), School of Computer Science and Technology, China University of Petroleum (East China).

