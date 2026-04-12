---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 全局右侧字体缩减 */
  .page__content {
    font-size: 0.88em; /* 整体缩放 */
    line-height: 1.5;
    color: #333;
  }

  html { scroll-behavior: smooth; }

  /* 标题样式缩小 */
  h1, h2 { 
    font-size: 1.3em !important; 
    margin-top: 1.5em !important;
    margin-bottom: 0.8em !important;
    border-bottom: 1px solid #eee;
    padding-bottom: 5px;
  }

  /* News 列表缩小 */
  .news-list {
    font-size: 0.95em;
    padding-left: 20px;
  }
  .news-list li {
    margin-bottom: 6px;
  }

  /* 论文卡片紧凑布局 */
  .pub-card {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    gap: 20px;
    margin-bottom: 25px;
    width: 100%;
  }

  .pub-img-container {
    flex: 0 0 35%; /* 稍微缩小图片比例 */
    position: relative;
  }

  .pub-img-container img {
    width: 100%;
    height: auto;
    border: 1px solid #eee;
    box-shadow: 2px 2px 8px rgba(0,0,0,0.08);
    display: block;
  }

  .pub-badge {
    position: absolute;
    top: 0;
    left: 0;
    background-color: #003d99;
    color: white;
    padding: 2px 6px;
    font-size: 0.7em;
    font-weight: bold;
    z-index: 10;
  }

  .pub-content {
    flex: 1;
  }

  .pub-title {
    font-size: 1.0rem !important; /* 论文标题缩小 */
    font-weight: 600;
    margin: 0 0 4px 0 !important;
    line-height: 1.2;
  }

  .pub-title a {
    color: #1a5dab;
    text-decoration: underline;
  }

  .pub-authors-links {
    font-size: 0.85rem; 
    color: #555;
    margin: 0 0 4px 0;
    line-height: 1.3;
  }

  .pub-links {
    display: inline;
    margin-left: 8px;
    font-weight: 500;
  }

  .pub-links a {
    color: #1a5dab;
    text-decoration: underline;
  }

  .pub-bullets {
    padding-left: 15px;
    margin: 4px 0 0 0;
    color: #666;
    font-size: 0.8rem; /* 列表文字进一步缩小 */
    line-height: 1.4;
  }

  @media (max-width: 768px) {
    .pub-card { flex-direction: column; gap: 15px; }
    .pub-img-container { width: 100%; }
  }
</style>

# About Me

I am currently a 1st-year PhD student at Nanjing University, supervised by Prof. [Wenbin Li](https://liwenbin.cn). Recently, I have focused on Continual Learning and Multi-modal Learning. 

I am a member of the [Reasoning and Learning Research Group](https://cs.nju.edu.cn/rl/), led by Professor [Yang Gao](https://cs.nju.edu.cn/gaoyang).

# News

<ul class="news-list">
  <li><b>[2025.11]</b> 🎉 Our paper <b>MoZO</b> was accepted by <b>AAAI 2026</b>!</li>
  <li><b>[2025.09]</b> 🎓 Started my Ph.D. journey at <b>Nanjing University</b>!</li>
  <li><b>[2025.06]</b> 🚀 Our paper <b>DMNSP</b> (Dynamic Multi-Layer Null Space Projection) was accepted by <b>ICCV 2025</b>!</li>
</ul>


<h1 id="publications">Selected Publications</h1>

<!-- 论文 1: DMNSP -->
<div class="pub-card">
  <div class="pub-img-container">
    <div class="pub-badge">ICCV 2025</div>
    <img src="/images/dmnsp_fig.png" alt="DMNSP Framework">
  </div>
  <div class="pub-content">
    <h3 class="pub-title">
      <a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Kang_Dynamic_Multi-Layer_Null_Space_Projection_for_Vision-Language_Continual_Learning_ICCV_2025_paper.pdf">Dynamic Multi-Layer Null Space Projection for Vision-Language Continual Learning</a>
    </h3>
    <p class="pub-authors-links">
      <strong>Borui Kang</strong>, Lei Wang, Zhiping Wu, Tao Feng, Yawen Li, Yang Gao, Wenbin Li
      <span class="pub-links">
        <a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Kang_Dynamic_Multi-Layer_Null_Space_Projection_for_Vision-Language_Continual_Learning_ICCV_2025_paper.pdf">Paper</a> / 
        <a href="https://github.com/RL-MIND/DMNSP">Code</a>
      </span>
    </p>
    <ul class="pub-bullets">
      <li>We propose DMNSP to mitigate the catastrophic forgetting caused by the different behaviors of two modalities in VLM-CL.</li>
      <li>Extensive experiments show that our method achieves superior performance on various VLCL benchmarks.</li>
    </ul>
  </div>
</div>

<!-- 论文 2: ZO Optimization (MoZO) -->
<div class="pub-card">
  <div class="pub-img-container">
    <div class="pub-badge">AAAI 2026</div>
    <img src="/images/mozo_fig.png" alt="MoZO Framework">
  </div>
  <div class="pub-content">
    <h3 class="pub-title">
      <a href="https://arxiv.org/pdf/2506.12409">Branch, or Layer? Zeroth-Order Optimization for Continual Learning of Vision-Language Models</a>
    </h3>
    <p class="pub-authors-links">
      Ziwei Liu*, <strong>Borui Kang</strong>*, Wei Li, Hangjie Yuan, Yanbing Yang, Wenbin Li, Jun Luo, Yifan Zhu, Tao Feng
      <span class="pub-links">
        <a href="https://arxiv.org/pdf/2506.12409">Paper</a>
      </span>
      <br>
      <span style="font-size: 0.9em; color: #888; font-style: italic;">(* Equal Contribution)</span>
    </p>
    <ul class="pub-bullets">
      <li>Explores Zeroth-Order optimization to solve the instability issues in VLM continual learning.</li>
      <li>Achieves a modality-aware stabilized ZO strategy for improved robustness.</li>
    </ul>
  </div>
</div>
