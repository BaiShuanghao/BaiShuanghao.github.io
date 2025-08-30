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

I am a fourth-year direct Ph.D. student in Artificial Intelligence at [Xi'an Jiaotong University](http://www.aiar.xjtu.edu.cn/), where I am advised by Prof. [Badong Chen](https://gr.xjtu.edu.cn/web/chenbd).
Prior to my doctoral studies, I received my Bachelor’s degree in Automation from Chongqing University in 2022, under the supervision of Prof. [Zhao Min](https://accu.cqu.edu.cn/info/1375/9156.htm).

🔭 My research interests lie in generalization in computer vision and robot learning, vision-language models, and vision language action models.

✉️ Welcome to contact me for any discussion and cooperation!

<!-- 💻 I am actively seeking academic and industrial exchange opportunities for Fall 2025, specifically focusing on joint Ph.D. programs and internship projects. I would greatly appreciate any information regarding potential opportunities that match my research interests and career aspirations. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=xhd94DIAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->



# 🔥 News
- \[2025/08/02\]: [Long-VLA](https://arxiv.org/abs/2508.19958) - the first VLA model to enable skill chaining in long-horizon tasks, accompanied by the introduction of a new benchmark, L-CALVIN; accepted to CoRL 2025! See [Project page](https://long-vla.github.io/).
- \[2025/05/06\]: We released [OpenHelix](https://arxiv.org/abs/2505.03912), which provides a short survey and empirical analysis of dual-system VLA, and introduces a novel open-source dual-system VLA model.
- \[2025/05/01\]: [BC-IB](https://arxiv.org/abs/2502.02853), the first to introduce information bottleneck theory into robotic manipulation through visual imitation learning under the lens of information theory, got accepted for ICML 2025! See [Project page](https://baishuanghao.github.io/BC-IB.github.io/).
- \[2025/03/24\]: One [paper](https://www.sciencedirect.com/science/article/pii/S0893608025002965) on causal discovery that integrates Minimum Error Entropy to enable dynamic adaptation to varying levels of complexity and noise got accepted for Neural Networks 2025!
- \[2025/01/23\]: [VLAS](https://arxiv.org/abs/2502.13508), the first vision-language-action model that incorporates speech instructions for robotic manipulation, got accepted for ICLR 2025!

<details>
  <summary>📜 Historical News</summary>
  <ul>
    <li>[2024/12/21]: <a href="https://arxiv.org/abs/2409.14163">PromptTA</a>, a novel VLM-based source-free domain generalization method integrating a text adapter and diverse prompt inputs, got accepted by ICASSP 2025!</li>
    <li>[2024/10/23]: The GitHub repository <a href="https://github.com/BaiShuanghao/Awesome-Robotics-Manipulation">Awesome-Robotics-Manipulation</a> is now public! Let’s work together to build a comprehensive and valuable resource for the robotics and AI community!</li>
    <li>[2024/07/04]: <a href="https://arxiv.org/abs/2404.19286">SPG</a>, a novel VLM-based domain generalization method that introduces generative concepts into prompt learning, got accepted by ECCV 2024.</li>
    <li>[2024/05/02]: <a href="https://arxiv.org/abs/2405.08779">JRNGC</a>, a unified causal discovery method that leverages the Jacobian matrix to address high-dimensional multivariate causal discovery, got accepted by ICML 2024!</li>
    <li>[2024/12/14]: One <a href="https://arxiv.org/abs/2312.09589">paper</a> on cross-domain few-shot classification got accepted by ICASSP 2024.</li>
    <li>[2023/12/09]: <a href="https://arxiv.org/abs/2312.09553">PDA</a>, a novel VLM-based prompt learning approach for unsupervised domain adaptation that integrates and thoroughly evaluates diverse prompt learning methods, got accepted by AAAI 2024!</li>
  </ul>
</details>



# 📝 Publications

## Published

<div style="display: flex; align-items: center; margin-top: 10px; margin-bottom: 30px;">
  <img src="images/paper/arxiv-2025-bcib.gif" alt="BCIB" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Rethinking Latent Redundancy in Behavior Cloning: An Information Bottleneck Approach for Robot Manipulation</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Shuanghao Bai</u></strong>, Wanqi Zhou, Pengxiang Ding, Wei Zhao, Donglin Wang, Badong Chen</p>
    <p style="margin: 0 0 10px 0;"><em>ICML 2025</em></p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2502.02853">arXiv</a>| 
      <a href="https://baishuanghao.github.io/BC-IB.github.io/">Project</a> | 
      <a href="https://github.com/BaiShuanghao/BC-IB">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/eccv-2024-spg.jpg" alt="SPG" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Soft Prompt Generation for Domain Generalization</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Shuanghao Bai*</u></strong>, Yuedi Zhang*, Wanqi Zhou, Yicong He, Zhirong Luan, Badong Chen</p>
    <p style="margin: 0 0 10px 0;"><em>ECCV 2024</em></p>
    <p style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-72646-0_25">Paper</a> | 
      <a href="https://arxiv.org/abs/2404.19286">arXiv</a> | 
      <a href="https://github.com/renytek13/Soft-Prompt-Generation">Code</a> |
      <a href="https://zhuanlan.zhihu.com/p/719329220">Chinese Intro</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icml-2024-jrngc.jpg" alt="JRNGC" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Jacobian Regularizer-based Neural Granger Causality</h3>
    <p style="margin: 0 0 10px 0;">Wanqi Zhou, <strong><u>Shuanghao Bai</u></strong>, Shujian Yu, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;"><em>ICML 2024</em></p>
    <p style="margin: 0;"><a href="https://proceedings.mlr.press/v235/zhou24a.html">Paper</a> | 
      <a href="https://arxiv.org/abs/2405.08779">arXiv</a> |
      <a href="https://github.com/ElleZWQ/JRNGC">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 40px;">
  <img src="images/paper/aaai-2024-pda.jpg" alt="PDA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Prompt-based Distribution Alignment for Unsupervised Domain Adaptation</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Shuanghao Bai</u></strong>, Min Zhang, Wanqi Zhou, Siteng Huang, Zhirong Luan, Donglin Wang, Badong Chen</p>
    <p style="margin: 0 0 10px 0;"><em>AAAI 2024</em></p>
    <p style="margin: 0;">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/27830">Paper</a> |
      <a href="https://arxiv.org/abs/2312.09553">arXiv</a> | 
      <a href="https://github.com/BaiShuanghao/Prompt-based-Distribution-Alignment">Code</a>
      </p>
  </div>
</div>


<img src="https://img.shields.io/badge/CoRL-2025-blue?style=flat-square"> 
Yiguo Fan<sup>*</sup>, Pengxiang Ding<sup>*</sup>, <strong><u>Shuanghao Bai<sup>*</sup></u></strong>, Xinyang Tong<sup>*</sup>, Yuyang Zhu, Hongchao Lu, Fengqi Dai, Wei Zhao, Yang Liu, Siteng Huang, Zhaoxin Fan, Badong Chen, Donglin Wang.  &quot;**Long-VLA: Unleashing Long-Horizon Capability of Vision Language Action Model for Robot Manipulation**&quot;.  [[arXiv](https://arxiv.org/abs/2508.19958)] [[Project](https://long-vla.github.io/)]

<img src="https://img.shields.io/badge/NN-2025-228B22?style=flat-square"> 
Wanqi Zhou, <strong><u>Shuanghao Bai</u></strong>, Qibin Zhao, Badong Chen.  &quot;**An Information-Theoretic Approach for Heterogeneous Differentiable Causal Discovery**&quot;.  [[Paper](https://www.sciencedirect.com/science/article/pii/S0893608025002965)] [[Code](https://github.com/ElleZWQ/MHCD)]

<img src="https://img.shields.io/badge/ICLR-2025-blue?style=flat-square"> 
Wei Zhao, Pengxiang Ding, Zhang Min, Zhefei Gong, <strong><u>Shuanghao Bai</u></strong>, Han Zhao, Donglin Wang.  &quot;**VLAS: Vision-Language-Action Model with Speech Instructions for Customized Robot Manipulation**&quot;.  [[arXiv](https://arxiv.org/abs/2502.13508)] [[Code](https://github.com/whichwhichgone/VLAS)]

<img src="https://img.shields.io/badge/ICASSP-2025-blue?style=flat-square"> 
Haoran Zhang<sup>*</sup>, <strong><u>Shuanghao Bai<sup>*</sup></u></strong>, Wanqi Zhou, Jingwen Fu, Badong Chen.  &quot;**PromptTA: Prompt-driven Text Adapter for Source-free Domain Generalization**&quot;.  [[Paper](https://ieeexplore.ieee.org/abstract/document/10888057)] [[arXiv](https://arxiv.org/abs/2409.14163)] [[Code](https://github.com/zhanghr2001/PromptTA)]

<img src="https://img.shields.io/badge/ICASSP-2024-blue?style=flat-square"> 
<strong><u>Shuanghao Bai</u></strong>, Wanqi Zhou, Zhirong Luan, Donglin Wang, Badong Chen.  &quot;**Improving Cross-domain Few-shot Classification with Multilayer Perceptron**&quot;.  [[Paper](https://ieeexplore.ieee.org/abstract/document/10447065/)] [[arXiv](https://arxiv.org/abs/2312.09589)] [[Code](https://github.com/BaiShuanghao/CDFSC-MLP)]


## Preprints & Under Submission

<img src="https://img.shields.io/badge/arXiv-2505.18770-B31B1B?style=flat-square">
Yuedi Zhang, <strong><u>Shuanghao Bai</u></strong>, Wanqi Zhou, Zhirong Luan, Badong Chen.  &quot;**Dual-Path Stable Soft Prompt Generation for Domain Generalization**&quot;.  [[arXiv](https://arxiv.org/abs/2505.18770)] [[Code](https://github.com/renytek13/Dual-Path-Stable-Soft-Prompt-Generation)]

<img src="https://img.shields.io/badge/arXiv-2505.03912-B31B1B?style=flat-square">
Can Cui, Pengxiang Ding, Wenxuan Song, <strong><u>Shuanghao Bai</u></strong>, Xinyang Tong, Zirui Ge, Runze Suo, Wanqi Zhou, Yang Liu, Bofang Jia, Han Zhao, Siteng Huang, Donglin Wang.  &quot;**Openhelix: A Short Survey, Empirical Analysis, and Open-source Dual-system VLA Model for Robotic Manipulation**&quot;.  [[arXiv](https://arxiv.org/abs/2505.03912)] [[Code](https://github.com/OpenHelix-robot/OpenHelix)] [[Project](https://openhelix-robot.github.io/)]

<img src="https://img.shields.io/badge/arXiv-2404.19287-B31B1B?style=flat-square">
Wanqi Zhou<sup>*</sup>, <strong><u>Shuanghao Bai<sup>*</sup></u></strong>, Danilo Mandic, Qibin Zhao, Badong Chen.  &quot;**Revisiting the Adversarial Robustness of Vision Language Models: a Multimodal Perspective**&quot;.  [[arXiv](https://arxiv.org/abs/2404.19287)] [[Code](https://github.com/ElleZWQ/MMCoA)]



# 📖 Research Experience
* [Beijing Academy of Artificial Intelligence (BAAI)](https://www.baai.ac.cn/): Aug. 2025 - Now
  * Research Intern
  * Research Direction: Embodied Multimodal Foundation Models, e.g. VLA models.
  * Advisor: [Chi Cheng](https://chicheng123.github.io/)
  * Co-Advisor: [Shanghang Zhang](https://pku-hmi-lab.github.io/HMI-Web/leader.html)

* Westlake University - [MiLab](https://milab.westlake.edu.cn/index.html): Sept. 2024 – Mar. 2025
  * Visiting Student
  * Research Direction: Robotics.
  * Advisor: [Donglin Wang](https://scholar.google.com/citations?user=-fo6wdwAAAAJ&hl=zh-CN)



# 🏅 Honors and Awards
* National Scholarship, 2024
* Outstanding Undergraduate Thesis of College of Automation, Chongqing University, 2022
* National Scholarship, 2019
* Outstanding Student of Chongqing University, 2019

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->


<!-- <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=V1s6bHv5YoOUdWy_xe51WDGQ7ssAbRpDmruXR6D4I9Q&cl=ffffff&w=a"></script> -->

<!-- <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=V1s6bHv5YoOUdWy_xe51WDGQ7ssAbRpDmruXR6D4I9Q&w=150&h=150&t=light&cmo=#FF5588&cmn=#88FF55"></script> -->

<div style="display: flex; justify-content: center; align-items: center; height: 200px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=V1s6bHv5YoOUdWy_xe51WDGQ7ssAbRpDmruXR6D4I9Q&w=150&h=150&t=light&cmo=#FF5588&cmn=#88FF55"></script>
</div>



<!-- <hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/nn-2025-mee.jpg" alt="MEE" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">An Information-Theoretic Approach for Heterogeneous Differentiable Causal Discovery</h3>
    <p style="margin: 0 0 10px 0;">Wanqi Zhou, <strong><u>Shuanghao Bai</u></strong>, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">Neural Networks 2025</p>
    <p style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0893608025002965">Paper</a> |
      <a href="https://github.com/ElleZWQ/MHCD">Code</a>
      </p>
  </div>
</div> -->

<!-- <hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/iclr-2025-vlas.jpg" alt="VLAS" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">VLAS: Vision-Language-Action Model with Speech Instructions for Customized Robot Manipulation</h3>
    <p style="margin: 0 0 10px 0;">Wei Zhao, Pengxiang Ding, Zhang Min, Zhefei Gong, <strong><u>Shuanghao Bai</u></strong>, Han Zhao, Donglin Wang</p>
    <p style="margin: 0 0 10px 0;">ICLR 2025</p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2502.13508">arXiv</a> |
      <a href="https://github.com/whichwhichgone/VLAS">Code</a>
      </p>
  </div>
</div> -->

<!-- <hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icassp-2025-promptta.jpg" alt="PromptTA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">PromptTA: Prompt-driven Text Adapter for Source-free Domain Generalization</h3>
    <p style="margin: 0 0 10px 0;">Haoran Zhang*, <strong><u>Shuanghao Bai*</u></strong>, Wanqi Zhou, Jingwen Fu, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">ICASSP 2025</p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/abstract/document/10888057">Paper</a> |
      <a href="https://arxiv.org/abs/2409.14163">arXiv</a> | 
      <a href="https://github.com/zhanghr2001/PromptTA">Code</a>
      </p>
  </div>
</div> -->

<!-- <hr /> -->

<!-- <div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/arxiv-2024-mmcoa.jpg" alt="MMCoA" style="width: 200px; height: 120px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Revisiting the Adversarial Robustness of Vision Language Models: a Multimodal Perspective</h3>
    <p style="margin: 0 0 10px 0;">Wanqi Zhou*, <strong><u>Shuanghao Bai*</u></strong>, Qibin Zhao, Badong Chen</p>
    <p style="margin: 0 0 10px 0;">arXiv 2024</p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2404.19287">arXiv</a> | 
      <a href="https://github.com/ElleZWQ/MMCoA">Code</a>
      </p>
  </div>
</div> -->

<!-- <hr /> -->

<!-- <div style="display: flex; align-items: center;margin-top: 30px; margin-bottom: 30px;">
  <img src="images/paper/icassp-2024-mlp.jpg" alt="MLP" style="width: 200px; height: 80px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Improving Cross-domain Few-shot Classification with Multilayer Perceptron</h3>
    <p style="margin: 0 0 10px 0;"></p>
    <p style="margin: 0 0 10px 0;">ICASSP 2024</p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/abstract/document/10447065/">Paper</a> |
      <a href="https://arxiv.org/abs/2312.09589">arXiv</a> | 
      <a href="https://github.com/BaiShuanghao/CDFSC-MLP">Code</a>  
      </p>
  </div>
</div> -->

<!-- <img src="https://img.shields.io/badge/arXiv-2024-%20red?style=flat-square">  -->