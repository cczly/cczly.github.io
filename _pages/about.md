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

<span class='anchor' id='-about-me'></span>

# 😃 About Me
I work at Suzhou Institute for advanced research, USTC as a Postdoctoral now in Suzhou. I am now working on audio-driven talking face generation, three-dimensional reconstruction and multi-modal large model. If you are seeking any form of academic cooperation, please feel free to email me at **cczly@ustc.edu.cn**. We are hiring interns!

My research interest includes Image/video generation, three-dimensional reconstruction and multi-modal large model. I have published in several journals, such as IEEE Transactions on Image Processing, IEEE Transactions on Multimedia, IEEE Transactions on Circuits and Systems for Video Technology, Pattern Recognition, and IEEE Transactions on Instrumentation and Measurement, and top conferences, such as CVPR, ICCV, AAAI, and ACM MM. I am nominated for the Shanghai Computer Society's Outstanding Doctoral Dissertation Award, received the honor of Outstanding Graduate Student of Shanghai, and was titled as an Outstanding Postdoctoral Fellow in Jiangsu Province, China.

<span class='anchor' id='-news'></span>

# 🔥 News
- **2024.06**: &nbsp;🎉 Received the Youth Fund from the Jiangsu Province Basic Research Program.
- **2024.06**: &nbsp;🎉 A journal article is accepted by IEEE TCSVT.
- **2024.01**: &nbsp;🎉 A journal article is accepted by IEEE TIP.
- **2023.12**: &nbsp;🎉 A conference paper is accepted by IEEE ICASSP2024.
- **2023.07**: &nbsp;🎉 Received the Special Fund of The China Postdoctoral Science Foundation. 

<span class='anchor' id='-honors-and-awards'></span>

# 🎖 Honors and Awards
- **2023**:&nbsp;🎉 Outstanding Postdoctoral Fellow in Jiangsu Province.
- **2022**:&nbsp;🎉 Outstanding Graduate Student of Shanghai. 
- **2022**:&nbsp;🎉 Shanghai Computer Society's Outstanding Doctoral Dissertation Award (Nominated).
- **2021**:&nbsp;🎉 Doctoral National Scholarship.
- **2020**:&nbsp;🎉 Doctoral National Scholarship.

<span class='anchor' id='-fundings'></span>

# 💴 Fundings
- **2024.07**: &nbsp;🎉🎉 Youth Fund of Jiangsu Provincial Basic Research Program (Natural Science Foundation).
- **2023.07**: &nbsp;🎉🎉 Special Fund of The China Postdoctoral Science Foundation. 
- **2023.06**: &nbsp;🎉🎉 General Fund of The China Postdoctoral Science Foundation. 
- **2023.06**: &nbsp;🎉🎉 The Jiangsu Funding Program for Excellent Postdoctoral Talent.

<span class='anchor' id='-research-highlights'></span>

# 🔍Research Highlights
- **Face Analysis and Synthesis**: &nbsp; Including face alignment, age estimation, talking face synthesis, video re-dubbing, etc.
- **Physics-informed Visual Computing**: &nbsp; Including 3D reconstruction, novel view synthesis, dynamic rendering, etc.
- **Knowledge Compression of Visual Language Models**: &nbsp; Including low-rank learning of large models, mixture of expert systems, reflective learning, etc.

<span class='anchor' id='-publications'></span>

# 📝 Publications 
**Face Analysis and Synthesis**
<ul>
  <li><code class="language-plaintext highlighter-rouge">IEEE TCSVT</code> <a href="https://ieeexplore.ieee.org/abstract/document/10583942">Toward Quantifiable Face Age Transformation under Attribute Unbias</a>, Ling Lin, Tao Wang, Hao Liu, <strong>Congcong Zhu*</strong>, Jingrun Chen</li>
  <li><code class="language-plaintext highlighter-rouge">ICASSP2024</code> <a href="https://ieeexplore.ieee.org/abstract/document/10448304">Toward Quantifiable Face age Transformation</a>, Ling Lin, <strong>Congcong Zhu*</strong>, Lin Zhou, Jingrun Chen</li>
  <li><code class="language-plaintext highlighter-rouge">IEEE TIP</code> <a href="https://ieeexplore.ieee.org/abstract/document/10462910">HeadDiff: Exploring Rotation Uncertainty With Diffusion Models for Head Pose Estimation</a>, Yaoxing Wang, Hao Liu, Yaowei Feng, Zhendong Li, Xiangjuan Wu, <strong>Congcong Zhu</strong></li>
  <li><code class="language-plaintext highlighter-rouge">IEEE TIM</code> <a href="https://ieeexplore.ieee.org/abstract/document/10049177">A multi-scale feature fusion network with cascaded supervision for cross-scene crowd counting</a>, Xinfeng Zhang, Lina Han, Wencong Shan, Xiaohu Wang, Shuhan Chen, <strong>Congcong Zhu</strong>, Bin Li</li>
  <li><code class="language-plaintext highlighter-rouge">IEEE TMM</code> <a href="https://ieeexplore.ieee.org/abstract/document/9911664">Multi-Sourced Knowledge Integration for Robust Self-Supervised Facial Landmark Tracking</a>, <strong>Congcong Zhu</strong>, Xiaoqiang Li, Jide Li, Songmin Dai, Weiqin Tong </li>
  <li><code class="language-plaintext highlighter-rouge">Pattern Recognition</code> <a href="https://arxiv.org/pdf/2112.10087">Reasoning structural relation for occlusion-robust facial landmark localization</a>, <strong>Congcong Zhu</strong>, Xiaoqiang Li, Jide Li, Songmin Dai, Weiqin Tong </li>
  <li><code class="language-plaintext highlighter-rouge">CVPR2022</code> <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_Occlusion-Robust_Face_Alignment_Using_a_Viewpoint-Invariant_Hierarchical_Network_Architecture_CVPR_2022_paper.pdf">Occlusion-robust face alignment using a viewpoint-invariant hierarchical network architecture</a>, <strong>Congcong Zhu</strong>, Xintong Wan, Shaorong Xie, Xiaoqiang Li, Yinzheng Gu </li>
  <li><code class="language-plaintext highlighter-rouge">ICCV2021</code> <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Zhu_Improving_Robustness_of_Facial_Landmark_Detection_by_Defending_Against_Adversarial_ICCV_2021_paper.pdf">Improving robustness of facial landmark detection by defending against adversarial attacks</a>, <strong>Congcong Zhu</strong>, Xiaoqiang Li, Jide Li, Songmin Dai </li>
  <li><code class="language-plaintext highlighter-rouge">Pattern Recognition</code> <a href="https://www.sciencedirect.com/science/article/pii/S0031320320301576">Learning spatial-temporal deformable networks for unconstrained face alignment and tracking in videos</a>, Hongyu Zhu, Hao Liu, <strong>Congcong Zhu</strong>, Zongyong Deng, Xuehong Sun. </li>
  <li><code class="language-plaintext highlighter-rouge">ACM MM 2020</code> <a href="https://dl.acm.org/doi/abs/10.1145/3394171.3413993">Spatial-temporal knowledge integration: Robust self-supervised facial landmark tracking</a>, <strong>Congcong Zhu</strong>, Xiaoqiang Li, Jide Li, Guangtai Ding, Weiqin Tong. </li>
  <li><code class="language-plaintext highlighter-rouge">AAAI 2020</code> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/7011">Towards Omni-Supervised Face Alignment for Large Scale Unlabeled Videos</a>, <strong>Congcong Zhu</strong>, Hao Liu, Zhenhua Yu, Xuehong Sun. </li>
</ul>

# Acknowledgement
Thanks for this convenient [template](https://github.com/RayeRen/acad-homepage.github.io).
