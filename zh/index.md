---
layout: default
permalink: /zh/
title: ""
excerpt: ""
author_profile: true
---

<style>
  .zh-page {
    color: #3f474f;
    font-size: 0.98em;
    line-height: 1.82;
  }

  .zh-page h1,
  .zh-page h2,
  .zh-page h3 {
    color: #1f2933;
    letter-spacing: 0;
  }

  .zh-page a {
    text-underline-offset: 0.18em;
  }

  .zh-intro {
    padding: 0 0 1.35em;
    border-bottom: 1px solid #dce2e8;
  }

  .zh-intro h1 {
    margin: 0 0 0.5em;
    font-size: 1.8em;
    line-height: 1.25;
  }

  .zh-lead {
    color: #2f3740;
    font-size: 1.05em;
  }

  .zh-section {
    padding: 1.45em 0 1.35em;
    border-bottom: 1px solid #e7ebef;
  }

  .zh-section__header {
    margin-bottom: 0.8em;
  }

  .zh-section__header h2 {
    margin: 0;
    font-size: 1.28em;
    line-height: 1.35;
  }

  .zh-section__summary {
    margin: -0.15em 0 1em;
    color: #65717c;
  }

  .zh-timeline,
  .zh-awards,
  .publication-list {
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .zh-timeline li {
    display: grid;
    grid-template-columns: 5.6em minmax(0, 1fr);
    gap: 0.9em;
    padding: 0.42em 0;
    border-top: 1px dashed #e1e6eb;
  }

  .zh-timeline li:first-child {
    border-top: 0;
  }

  .zh-timeline time,
  .zh-awards strong {
    color: #1d4f8f;
    font-weight: 700;
    white-space: nowrap;
  }

  .zh-awards {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.65em 1.2em;
  }

  .zh-awards li {
    display: grid;
    grid-template-columns: 4em minmax(0, 1fr);
    gap: 0.65em;
    padding: 0.52em 0;
    border-top: 1px dashed #e1e6eb;
  }

  .zh-research-list {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.9em;
  }

  .zh-research-list article {
    padding: 0.85em 0.95em;
    border: 1px solid #dfe5eb;
    border-radius: 6px;
    background: #fafbfc;
  }

  .zh-research-list h3 {
    margin: 0 0 0.35em;
    font-size: 0.98em;
  }

  .zh-research-list p {
    margin: 0;
    color: #56616c;
    font-size: 0.94em;
    line-height: 1.7;
  }

  .publication-list {
    counter-reset: publication;
  }

  .publication-list li {
    position: relative;
    padding: 0.75em 0 0.85em 2.25em;
    border-top: 1px solid #e7ebef;
  }

  .publication-list li::before {
    counter-increment: publication;
    content: counter(publication);
    position: absolute;
    left: 0;
    top: 0.92em;
    width: 1.45em;
    height: 1.45em;
    border-radius: 999px;
    background: #eef3f8;
    color: #365a7d;
    font-size: 0.76em;
    font-weight: 700;
    line-height: 1.45em;
    text-align: center;
  }

  .authors {
    color: #5b6570;
  }

  .pub-badge,
  .pub-link {
    display: inline-block;
    margin: 0 0.28em 0.22em 0;
    padding: 0.12em 0.48em;
    border-radius: 4px;
    font-size: 0.78em;
    font-weight: 700;
    line-height: 1.45;
    white-space: nowrap;
  }

  .pub-badge {
    background-color: #0b2d4d;
    color: #fff;
  }

  .pub-link {
    background-color: #eef0f2;
  }

  .pub-link a {
    color: #3b4cc0;
  }

  @media (max-width: 720px) {
    .zh-awards,
    .zh-research-list {
      display: block;
    }

    .zh-research-list article {
      margin-bottom: 0.75em;
    }

    .publication-list li {
      padding-left: 0;
    }

    .publication-list li::before {
      display: none;
    }
  }
</style>

<div class="zh-page">
  <span class="anchor" id="-about-me"></span>

  <header class="zh-intro">
    <h1>朱聪聪</h1>
    <p class="zh-lead">
      我目前在中国科学技术大学苏州高等研究院任副研究员、硕士生导师。研究方向包括具身人工智能、多模态内容生成与理解、物理先验视觉计算等。
    </p>
    <p>
      如果您希望开展学术合作，或正在寻找博士生、硕士生、科研实习等机会，欢迎邮件联系：
      <strong>cczly@ustc.edu.cn</strong>。
    </p>
  </header>

  <section class="zh-section" aria-labelledby="news-heading">
    <span class="anchor" id="-news"></span>
    <div class="zh-section__header">
      <h2 id="news-heading">最新动态</h2>
    </div>
    <ol class="zh-timeline">
      <li><time>2026.05</time><span>一篇会议论文被 ICML 2026 接收。</span></li>
      <li><time>2026.02</time><span>一篇期刊论文被 TNNLS 接收。</span></li>
      <li><time>2025.11</time><span>一篇会议论文被 AAAI 2026 接收。</span></li>
      <li><time>2025.05</time><span>论文被 ICME 2025 选为 Oral。</span></li>
      <li><time>2025.05</time><span>获得华为 Spark 奖。</span></li>
      <li><time>2025.05</time><span>一篇会议论文被 ICML 2025 接收。</span></li>
      <li><time>2025.04</time><span>本科实习生完成的一篇论文被 IEEE IJCNN 2025 接收。</span></li>
      <li><time>2025.03</time><span>一篇会议论文被 IEEE ICME 2025 接收。</span></li>
      <li><time>2025.01</time><span>晋升为副研究员、硕士生导师。</span></li>
    </ol>
  </section>

  <section class="zh-section" aria-labelledby="honors-heading">
    <span class="anchor" id="-honors-and-awards"></span>
    <div class="zh-section__header">
      <h2 id="honors-heading">荣誉奖励</h2>
    </div>
    <ul class="zh-awards">
      <li><strong>2025</strong><span>华为 Spark 奖</span></li>
      <li><strong>2023</strong><span>江苏省优秀博士后</span></li>
      <li><strong>2022</strong><span>上海市优秀毕业生</span></li>
      <li><strong>2022</strong><span>上海市计算机学会优秀博士学位论文提名</span></li>
      <li><strong>2021</strong><span>博士研究生国家奖学金</span></li>
      <li><strong>2020</strong><span>博士研究生国家奖学金</span></li>
    </ul>
  </section>

  <section class="zh-section" aria-labelledby="research-heading">
    <span class="anchor" id="-research-highlights"></span>
    <div class="zh-section__header">
      <h2 id="research-heading">研究方向</h2>
    </div>
    <div class="zh-research-list">
      <article>
        <h3>具身人工智能</h3>
        <p>视觉-语言-动作模型、场景生成、动态渲染等。</p>
      </article>
      <article>
        <h3>物理先验视觉计算</h3>
        <p>新视角合成、物理先验动态建模、数据驱动反问题等。</p>
      </article>
      <article>
        <h3>多模态内容生成与理解</h3>
        <p>人体动作生成、视频生成、大模型低秩学习和专家混合系统等。</p>
      </article>
    </div>
  </section>

  <section class="zh-section" aria-labelledby="publications-heading">
    <span class="anchor" id="-publications"></span>
    <div class="zh-section__header">
      <h2 id="publications-heading">代表成果</h2>
    </div>
    <p class="zh-section__summary">以下列出部分近期代表性成果，完整论文列表请参考英文主页。</p>

    <ol class="publication-list">
      <li>
        <span class="pub-badge">TNNLS</span>
        <a href="https://ieeexplore.ieee.org/abstract/document/11373586/">A2Net: Affiliation Alignment Networks for Whole-Body Pose Estimation With Vision-Language Models</a>.
        <span class="authors">Ling Lin, Yaoxing Wang, <strong>Congcong Zhu*</strong>, Jingrun Chen.</span>
      </li>
      <li>
        <span class="pub-badge">AAAI 2026</span>
        <span class="pub-link"><a href="https://github.com/SCAILab-USTC/Physics-Informed-Deformable-Gaussian-Splatting">Code</a></span>
        <a href="https://arxiv.org/abs/2511.06299">Physics-Informed Deformable Gaussian Splatting: Towards Unified Constitutive Laws for Time-Evolving Material Field</a>.
        <span class="authors"><strong>Haoqin Hong</strong>, <strong>Ding Fan</strong>, Fubin Dou, Zhi-Li Zhou, Haoran Sun, <strong>Congcong Zhu*</strong>, Jingrun Chen*.</span>
      </li>
      <li>
        <span class="pub-badge">ICML 2025</span>
        <span class="pub-link"><a href="https://github.com/SCAILab-USTC/PITA">Code</a></span>
        <a href="https://arxiv.org/pdf/2505.10930">Physics-informed Temporal Alignment for Auto-regressive PDE Foundation Models</a>.
        <span class="authors"><strong>Congcong Zhu</strong>, <strong>Xiaoyan Xu</strong>, Jiayue Han, Jingrun Chen*.</span>
      </li>
      <li>
        <span class="pub-badge">IJCNN 2025</span>
        <a href="https://vimeo.com/1095993656">Toward Invisible Region Restoration for Single-View 3D Face Reconstruction</a>.
        <span class="authors">Zhijing Cheng, YuQing Wen, <strong>Congcong Zhu*</strong>, Rui Du*.</span>
      </li>
      <li>
        <span class="pub-badge">ICME 2025 Oral</span>
        <span class="pub-link"><a href="https://github.com/SCAILab-USTC/STSA">Code</a></span>
        <a href="https://arxiv.org/abs/2503.23039">STSA: Spatial-Temporal Semantic Alignment for Visual Dubbing</a>.
        <span class="authors">Zijun Ding, Mingdie Xiong, <strong>Congcong Zhu*</strong>, Jingrun Chen.</span>
      </li>
      <li>
        <span class="pub-badge">IEEE TCSVT</span>
        <a href="https://ieeexplore.ieee.org/abstract/document/10583942">Toward Quantifiable Face Age Transformation under Attribute Unbias</a>.
        <span class="authors">Ling Lin, Tao Wang, Hao Liu, <strong>Congcong Zhu*</strong>, Jingrun Chen.</span>
      </li>
      <li>
        <span class="pub-badge">IEEE TIP</span>
        <a href="https://ieeexplore.ieee.org/abstract/document/10462910">HeadDiff: Exploring Rotation Uncertainty With Diffusion Models for Head Pose Estimation</a>.
        <span class="authors">Yaoxing Wang, Hao Liu, Yaowei Feng, Zhendong Li, Xiangjuan Wu, <strong>Congcong Zhu</strong>.</span>
      </li>
      <li>
        <span class="pub-badge">CVPR 2022 Oral</span>
        <a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_Occlusion-Robust_Face_Alignment_Using_a_Viewpoint-Invariant_Hierarchical_Network_Architecture_CVPR_2022_paper.pdf">Occlusion-robust face alignment using a viewpoint-invariant hierarchical network architecture</a>.
        <span class="authors"><strong>Congcong Zhu</strong>, Xintong Wan, Shaorong Xie, Xiaoqiang Li, Yinzheng Gu.</span>
      </li>
    </ol>
  </section>
</div>
