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
  /* 增加一些局部样式，让页面更精致 */
  .pub-card {
    display: flex; 
    flex-direction: row; 
    align-items: flex-start; 
    margin-bottom: 40px; 
    gap: 25px;
    padding: 15px;
    border-radius: 8px;
    transition: background-color 0.3s ease;
  }
  .pub-card:hover {
    background-color: #fcfcfc; /* 鼠标悬停时有轻微底色 */
  }
  .pub-img {
    flex: 1; 
    min-width: 280px;
    max-width: 320px;
  }
  .pub-img img {
    width: 100%; 
    border-radius: 5px; 
    box-shadow: 0 4px 12px rgba(0,0,0,0.08); /* 更柔和的投影 */
    border: 1px solid #f0f0f0;
  }
  .pub-content {
    flex: 2;
  }
  .pub-title {
    margin: 0 0 10px 0; 
    font-size: 1.2em; 
    font-weight: 700;
    line-height: 1.3;
  }
  .pub-title a {
    color: #0056b3;
    text-decoration: none;
  }
  .pub-title a:hover {
    text-decoration: underline;
  }
  .pub-authors {
    margin: 8px 0; 
    font-size: 0.95em; 
    color: #444;
  }
  .pub-venue {
    margin: 5px 0;
    font-weight: 600;
    color: #d9534f; /* 专业学术红/蓝 */
    font-style: italic;
  }
  .pub-links {
    margin: 12px 0;
  }
  .pub-btn {
    display: inline-block;
    padding: 2px 12px;
    margin-right: 8px;
    border: 1px solid #0056b3;
    border-radius: 15px;
    font-size: 0.85em;
    color: #0056b3;
    text-decoration: none;
    transition: all 0.3s;
  }
  .pub-btn:hover {
    background-color: #0056b3;
    color: #fff;
  }
  .pub-bullets {
    margin-top: 10px;
    padding-left: 20px;
    font-size: 0.9em;
    color: #555;
    line-height: 1.6;
  }
</style>

# Selected Publications

<!-- 论文 1: DMNSP -->

<div class="pub-card">
  <div class="pub-img">
    <img src="/images/dmnsp_fig.png" alt="DMNSP Framework">
  </div>
  <div class="pub-content">
    <h3 class="pub-title">
      <a href="#">Dynamic Multi-Layer Null Space Projection for Vision-Language Continual Learning</a>
    </h3>
    <p class="pub-authors">
      <strong>Borui Kang</strong>, Lei Wang, Zhiping Wu, Tao Feng, Yawen Li, Yang Gao, Wenbin Li
    </p>
    <p class="pub-venue">ICCV 2025</p>
    <div class="pub-links">
      <a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Kang_Dynamic_Multi-Layer_Null_Space_Projection_for_Vision-Language_Continual_Learning_ICCV_2025_paper.pdf" class="pub-btn">Paper</a>
      <a href="https://github.com/RL-MIND/DMNSP" class="pub-btn">Code</a>
    </div>
    <ul class="pub-bullets">
      <li>We propose <b>DMNSP</b> to mitigate the catastrophic forgetting caused by the different behaviors of two modalities in VLM-CL.</li>
      <li>Extensive experiments show that our method achieves superior performance on various VLCL benchmarks.</li>
    </ul>
  </div>
</div>

<!-- 论文 2: ZO Optimization (此处作为美观对比) -->

<div class="pub-card">
  <div class="pub-img">
    <img src="/images/mozo_fig.png" alt="VLCL Framework">
  </div>
  <div class="pub-content">
    <h3 class="pub-title">
      <a href="https://arxiv.org/pdf/2506.12409">Branch, or Layer? Zeroth-Order Optimization for Continual Learning of Vision-Language Models</a>
    </h3>
    <p class="pub-authors">
      Ziwei Liu*, <strong>Borui Kang</strong>*, Wei Li, Hangjie Yuan, Yanbing Yang, Wenbin Li, Jun Luo, Yifan Zhu, Tao Feng
   	<br>
      <span style="font-size: 0.85em; color: #666; font-style: italic;">(* Equal Contribution)</span>                    
    </p>
    <p class="pub-venue">AAAI 2026</p>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2506.12409" class="pub-btn" style="color:#888; border-color:#888;">Paper</a>
    </div>
    <ul class="pub-bullets">
      <li>Explores Zeroth-Order optimization to solve the instability issues in VLM continual learning.</li>
      <li>Achieves a modality-aware stabilized ZO strategy for improved robustness.</li>
    </ul>
  </div>
</div>

