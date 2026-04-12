---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a 1st-year PhD student at Nanjing University, supervised by Prof. [Wenbin Li](https://liwenbin.cn). Recently, I have focused on Computer Learning and Multi-modal Learning. 

I am a member of the [Reasoning and Learning Research Group](https://cs.nju.edu.cn/rl/), led by Professor [Yang Gao](https://cs.nju.edu.cn/gaoyang).

News
======
* **[2024.09]** Started my PhD journey at [Your University]!
* **[2024.xx]** Our project on *Genshin Impact Action Detection* is now open-sourced on GitHub.

<style>
  .pub-card {
    display: flex;
    flex-direction: row;
    align-items: flex-start; /* 改回顶部对齐，通过缩小文字来对齐高度 */
    gap: 25px;
    margin-bottom: 35px;
    width: 100%;
  }
    /* 左侧图片：稍微缩小一点 */
  .pub-img-container {
    flex: 0 0 38%; 
    position: relative;
  }

  .pub-img-container img {
    width: 100%;
    height: auto;
    border: 1px solid #eee;
    box-shadow: 3px 3px 10px rgba(0,0,0,0.1); /* 参考图中的柔和阴影 */
    display: block;
  }

  /* 调小标签字号 */
  .pub-badge {
    position: absolute;
    top: 0;
    left: 0;
    background-color: #003d99;
    color: white;
    padding: 2px 8px;
    font-size: 0.7em;
    font-weight: bold;
    z-index: 10;
  }

  /* 右侧内容：全面调小字号 */
  .pub-content {
    flex: 1;
  }

  /* 标题：1.05em，深蓝色下划线，模拟参考图 */
  .pub-title {
    font-size: 1.05em; 
    font-weight: 600;
    margin: 0 0 4px 0;
    line-height: 1.2;
  }

  .pub-title a {
    color: #1a5dab;
    text-decoration: underline;
  }

  /* 作者：0.85em，收紧行高 */
  .pub-authors {
    font-size: 0.85em; 
    color: #555;
    margin: 0 0 8px 0;
    line-height: 1.3;
  }

  /* 链接：0.9em，去掉加粗，更清爽 */
  .pub-links {
    margin-bottom: 8px;
    font-size: 0.9em;
  }

  .pub-links a {
    color: #1a5dab;
    text-decoration: underline;
    margin-right: 12px;
  }

  /* 列表：0.82em，非常紧凑 */
  .pub-bullets {
    padding-left: 15px;
    margin: 0;
    color: #666;
    font-size: 0.82em; 
    line-height: 1.4;
  }

  @media (max-width: 768px) {
    .pub-card { flex-direction: column; gap: 15px; }
    .pub-img-container { width: 100%; }
  }
</style>

# Selected Publications

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
    <p class="pub-authors">
      <strong>Borui Kang</strong>, Lei Wang, Zhiping Wu, Tao Feng, Yawen Li, Yang Gao, Wenbin Li
    <div class="pub-links">
      <a href="https://github.com/RL-MIND/DMNSP">Code</a>
    </div>
    <ul class="pub-bullets">
      <li>We propose DMNSP to mitigate the catastrophic forgetting caused by the different behaviors of two modalities in VLM-CL.</li>
      <li>Extensive experiments show that our method achieves superior performance on various VLCL benchmarks.</li>
    </ul>
  </div>
</div>


<!-- 论文 2: ZO Optimization -->
<div class="pub-card">
  <div class="pub-img-container">
    <div class="pub-badge">AAAI 2026</div>
    <img src="/images/mozo_fig.png" alt="VLCL Framework">
  </div>
  <div class="pub-content">
    <h3 class="pub-title">
      <a href="https://arxiv.org/pdf/2506.12409">Branch, or Layer? Zeroth-Order Optimization for Continual Learning of Vision-Language Models</a>
    </h3>
    <p class="pub-authors">
      Ziwei Liu*, <strong>Borui Kang</strong>*, Wei Li, Hangjie Yuan, Yanbing Yang, Wenbin Li, Jun Luo, Yifan Zhu, Tao Feng
      <br>
      <span style="font-size: 0.85em; color: #888;">(* Equal Contribution)</span>

    <ul class="pub-bullets">
      <li>Explores Zeroth-Order optimization to solve the instability issues in VLM continual learning.</li>
      <li>Achieves a modality-aware stabilized ZO strategy for improved robustness.</li>
    </ul>
  </div>
</div>
