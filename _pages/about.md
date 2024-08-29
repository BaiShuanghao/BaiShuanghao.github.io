---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  h1 { font-size: 28px !important; }
  h2 { font-size: 24px !important; }
  h3 { font-size: 20px !important; }
  p, li { font-size: 18px !important; }
  .paper-box-text { font-size: 14px !important; }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a 3rd-year Ph.D. student of artificial intelligence at [Xi'an Jiaotong University](http://www.aiar.xjtu.edu.cn/), advised by Prof. [Badong Chen](https://gr.xjtu.edu.cn/web/chenbd). 
I am currently serving as a visiting student at the [MiLab](https://milab.westlake.edu.cn/index.html) at Westlake University, advised by Prof. [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN). 
Previously, I obtained my bachelor’s degree from School of autamation in Chongqing University in 2022. 

🔭My research interests lie in generalization in computer vision and vision-language models.
I’m also currently learning robotics, including generalization in robot learning, vision language action models, and 3D techniques.

✉️ Welcome to contact me for any discussion and cooperation!

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- \[2024/07\]: One paper ([SPG](https://arxiv.org/abs/2404.19286v2)) on VLM-based domain generalization got accepted by ECCV 2024.
- \[2024/05\]: One paper ([JRNGC](https://arxiv.org/abs/2405.08779)) on causal discovery got accepted by ICML 2024.
- \[2023/12\]: One paper ([PDA](https://arxiv.org/abs/2312.09553v2)) on VLM-based unsupervised domain adaptation got accepted by AAAI 2024, and one [paper](https://arxiv.org/abs/2312.09589) on cross-domain few-shot classification got accepted by ICASSP 2024.


# 📝 Publications 
_* denotes equal contribution._

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">arXiv 2024</div>
      <img src='images/paper/arxiv-2024-mmcoa.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **Revisiting the Adversarial Robustness of Vision Language Models: a Multimodal Perspective**

  Wanqi Zhou*, <u><strong>Shuanghao Bai*</strong></u>, Qibin Zhao, Badong Chen

  [arXiv](https://arxiv.org/abs/2404.19287)｜[Code](https://github.com/ElleZWQ/MMCoA)

  <!-- [![GitHub Stars](https://img.shields.io/github/stars/ElleZWQ/MMCoA?style=social)](https://github.com/ElleZWQ/MMCoA) 
  [![](https://img.shields.io/github/forks/ElleZWQ/MMCoA)](https://github.com/ElleZWQ/MMCoA/forks?include=active%2Cinactive)  -->
  <!-- <span class='show_paper_citations_badge' data='xhd94DIAAAAJ:Tyk-4Ss8FVUC'></span>  -->
  <!-- <a class="paper_citations_badges" data="xhd94DIAAAAJ:Tyk-4Ss8FVUC" href="https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=xhd94DIAAAAJ&citation_for_view=xhd94DIAAAAJ:Tyk-4Ss8FVUC" target="_blank"><img src="https://img.shields.io/badge/citations-0-blue?style=social&amp;logo=googlescholar"></a> -->
  <!-- <a href="https://huggingface.co/anyeZHY/3dvla-diffusion"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace-Goal%20DM-FFD21E?style=flat&labelColor=f6f6f6"></a>
  [![Demo views](https://img.shields.io/youtube/views/6ik2qNcId8g)](https://www.youtube.com/watch?v=6ik2qNcId8g) -->
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECCV 2024</div>
      <img src='images/paper/eccv-2024-spg.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **Soft Prompt Generation for Domain Generalization**

  <u><strong>Shuanghao Bai*</strong></u>, Yuedi Zhang*, Wanqi Zhou, Yicong He, Zhirong Luan, Badong Chen

  [arXiv](https://arxiv.org/abs/2404.19286v2)｜[Code](https://github.com/renytek13/Soft-Prompt-Generation)

  ECCV 2024

  <!-- [![GitHub Stars](https://img.shields.io/github/stars/renytek13/Soft-Prompt-Generation?style=social)](https://github.com/renytek13/Soft-Prompt-Generation) 
  [![](https://img.shields.io/github/forks/renytek13/Soft-Prompt-Generation)](https://github.com/renytek13/Soft-Prompt-Generation/forks?include=active%2Cinactive)  -->
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICML 2024</div>
      <img src='images/paper/icml-2024-jrngc.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **Jacobian Regularizer-based Neural Granger Causality**

  Wanqi Zhou, <u><strong>Shuanghao Bai</strong></u>, Shujian Yu, Qibin Zhao, Badong Chen

  [arXiv](https://arxiv.org/abs/2405.08779)｜[Code](https://github.com/ElleZWQ/JRNGC)

  ICML 2024

  <!-- [![GitHub Stars](https://img.shields.io/github/stars/ElleZWQ/JRNGC)](https://github.com/ElleZWQ/JRNGC) 
  [![](https://img.shields.io/github/forks/ElleZWQ/JRNGC)](https://github.com/ElleZWQ/JRNGC/forks?include=active%2Cinactive)  -->
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">SSRN 2024</div>
      <img src='images/paper/ssrn-2024-mee.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **An Information-Theoretic Approach for Heterogeneous Differentiable Causal Discovery**

  Wanqi Zhou, <u><strong>Shuanghao Bai</strong></u>, Qibin Zhao, Badong Chen

  [ssrn](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4837242)
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">AAAI 2024</div>
      <img src='images/paper/aaai-2024-pda.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **Prompt-based Distribution Alignment for Unsupervised Domain Adaptation**

  <u><strong>Shuanghao Bai</strong></u>, Min Zhang, Wanqi Zhou, Siteng Huang, Zhirong Luan, Donglin Wang, Badong Chen

  [arXiv](https://arxiv.org/abs/2312.09553v2)｜[Code](https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment)

  AAAI 2024
  
  <!-- [![GitHub Stars](https://img.shields.io/github/stars/BaiShuanghao/Prompt-based-Distribution-Alignment?style=social)](https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment) 
  [![](https://img.shields.io/github/forks/BaiShuanghao/Prompt-based-Distribution-Alignment)](https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment/forks?include=active%2Cinactive)  -->
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICASSP 2024</div>
      <img src='images/paper/icassp-2024-mlp.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
  **Improving Cross-domain Few-shot Classification with Multilayer Perceptron**

  <u><strong>Shuanghao Bai</strong></u>, Wanqi Zhou, Zhirong Luan, Donglin Wang, Badong Chen

  [arXiv](https://arxiv.org/abs/2312.09589)｜[Code](https://github.com/BaiShuanghao/CDFSC-MLP)

  ICASSP 2024
  <!-- [![GitHub Stars](https://img.shields.io/github/stars/BaiShuanghao/CDFSC-MLP?style=social)](https://github.com/BaiShuanghao/CDFSC-MLP) 
  [![](https://img.shields.io/github/forks/BaiShuanghao/CDFSC-MLP)](https://github.com/BaiShuanghao/CDFSC-MLP/forks?include=active%2Cinactive)  -->
  </div>
</div>

<!-- - <img src="https://img.shields.io/badge/CVPR-2020-blue?style=flat-square"> <u>A</u>, B, C, <strong>Paper Name</strong>, <em>In CVPR 2020</em>. -->


# 🏅 Awards
* Outstanding Undergraduate Thesis of College of Automation, Chongqing University, 2022
* National Scholarship, 2021, 2019
* Outstanding Student of Chongqing University, 2019

<!-- 
# 📖 Work experience
* March 2021 - Now: Research Assistant
  * Microsoft Research Asia, Beijing, China.
  * Duties included: 1. Design more powerful and simple object detection architecture based on the Transformer. 2. Understand NLP tasks such as NLI and exploit new paradigms to solve them more efficiently.
  * Advisor: Prof. [Jingdong Wang](https://jingdongwang2017.github.io/)

* August 2020 - Now: Research Assistant
  * University of Chinese Academy of Sciences, Beijing, China.
  * Duties included: 1. learning deep generative model for pedestrian generation. 2. cross-domain Re-ID from a causal view. 3. designing an efficient method to tackle problems in object detection and partial pedestrian re-identification.
  * Advisor: Prof. [Tieniu Tan](http://people.ucas.ac.cn/~tantieniu)
  * Co-Advisors: Prof. [Zhang Zhang](https://scholar.google.com/citations?user=rnRNwEMAAAAJ&hl=en) and Prof. [Liang Wang](https://scholar.google.com/citations?user=8kzzUboAAAAJ&hl=zh-CN)

* April 2018 – July 2020: Research Assistant
  * South China University of Technology, Guangzhou, China.
  * Duties included: Incentive mechanism design for crowdsourcing platforms, edge computing
platforms, and federal learning platforms.
  * Advisor: Prof. Xinglin Zhang
 -->


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->

---
