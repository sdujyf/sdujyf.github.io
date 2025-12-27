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
  /* 全局变量定义 */
  :root {
    --primary-color: #2e6094; /* 经典学术蓝 */
    --accent-color: #e74c3c;
    --bg-light: #f8f9fa;
  }

  /* News 部分优化 */
  .news-container {
    background: var(--bg-light);
    padding: 15px 20px;
    border-radius: 10px;
    border-left: 5px solid var(--primary-color);
    max-height: 250px;
    overflow-y: auto;
    margin-bottom: 30px;
  }

  /* 论文卡片美化 */
  .paper-box {
    display: flex;
    margin-bottom: 25px;
    padding: 15px;
    border-radius: 12px;
    transition: all 0.3s ease;
    background: #ffffff;
  }

  .paper-box:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    background: #fafafa;
  }

  .paper-box-image {
    flex: 0 0 220px;
    margin-right: 20px;
  }

  .paper-box-image img {
    width: 100%;
    border-radius: 8px;
    border: 1px solid #eee;
  }

  .badge {
    display: inline-block;
    background: var(--primary-color);
    color: white;
    padding: 2px 10px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: 600;
    margin-bottom: 8px;
  }

  .paper-title {
    font-weight: bold;
    font-size: 1.1em;
    color: #333;
    display: block;
    margin-bottom: 5px;
  }

  /* 高亮自己的名字 */
  .me {
    color: var(--primary-color);
    font-weight: 700;
    text-decoration: underline;
  }

  /* 学术按钮 */
  .btn-pub {
    display: inline-block;
    padding: 3px 12px;
    margin: 5px 5px 0 0;
    font-size: 13px;
    color: var(--primary-color);
    border: 1px solid var(--primary-color);
    border-radius: 5px;
    text-decoration: none;
    transition: 0.2s;
  }

  .btn-pub:hover {
    background: var(--primary-color);
    color: white !important;
  }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋 About Me

I am **Yifan Jia**, a junior student at the School of Information Science and Engineering (Chongxin College), **Shandong University**. I am supervised by [Yuntao Du](https://scholar.google.com/citations?user=your_id).

My research journey focuses on the intersection of **Multimodal Learning**, **Generative Models**, and **Interpretability**. I am particularly interested in how MLLMs handle knowledge conflicts and how data attribution can explain model behavior.

**🚀 I am actively seeking PhD/MPhil positions for Fall 2026!** If you're interested in collaborating, feel free to reach out via [2597077223jyf@gmail.com](mailto:2597077223jyf@gmail.com).

---

# 🔥 News 
<div class="news-container">
<ul>
  <li><strong>2025.11</strong> 🎉 One paper accepted by <strong>AAAI 2026 Oral</strong>!</li>
  <li><strong>2025.06</strong> 🎉 Our paper accepted by <strong>MICCAI 2025</strong>!</li>
  <li><strong>2024.07</strong> 📝 Paper accepted by <em>Neurocomputing</em>.</li>
  <li><strong>2024.04</strong> 📝 Paper accepted by CVIDL 2024.</li>
</ul>
</div>

# 📝 Selected Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">AAAI 2026 Oral</div><img src='images/mmkc.png' alt="paper thumbnail"></div>
  </div>
  <div class='paper-box-text'>
    <a class="paper-title">Benchmarking Multimodal Knowledge Conflict for Large Multimodal Models</a>
    <span class="me">Yifan Jia</span>, Kailin Jiang, Yuyang Liang, Qihan Ren, Yi Xin, et al. <br>
    <a href="https://arxiv.org/pdf/2505.19509" class="btn-pub">PDF</a>
    <a href="#" class="btn-pub">Code</a>
    <a href="#" class="btn-pub">Project Page</a>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">Preprint</div><img src='images/sam.png' alt="paper thumbnail"></div>
  </div>
  <div class='paper-box-text'>
    <a class="paper-title">Attributing Data for Sharpness-Aware Minimization</a>
    Chenyang Ren*, <span class="me">Yifan Jia*</span>, Huanyi Xie, Zhaobin Xu, et al. <br>
    <a href="https://arxiv.org/pdf/2507.04059" class="btn-pub">PDF</a>
    <a href="#" class="btn-pub">Poster</a>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">MICCAI 2025</div><img src='images/MIC.png' alt="paper thumbnail"></div>
  </div>
  <div class='paper-box-text'>
    <a class="paper-title">BioD2C: A Dual-level Semantic Consistency Constraint Framework for Biomedical VQA</a>
    Zhengyang Ji, Shang Gao, Li Liu, <span class="me">Yifan Jia</span>, Yutao Yue <br>
    <a href="https://arxiv.org/pdf/2503.02476" class="btn-pub">PDF</a>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div><div class="badge">MICCAI 2025</div><img src='images/is.png' alt="paper thumbnail"></div>
  </div>
  <div class='paper-box-text'>
    <a class="paper-title">Interpreting Social Bias in LVLMs via Information Flow Analysis and Multi-Round Dialogue Evaluation</a>
    Zhengyang Ji*,  <span class="me">Yifan Jia*</span>, Shang Gao,Yutao Yue, Yutao Yue <br>
    <a href="https://arxiv.org/pdf/2503.02476" class="btn-pub">PDF</a>
  </div>
</div>
# 🎖 Honors and Awards
* **2023.09** Academic Scholarship, Shandong University
* **2024.12**  Third Prize, National Intelligent Car Competition
* **2023.04**  National Third Prize, Asia-Pacific Mathematical Modeling Competition
* **2024.07** Second prize of provincial level in mathematical Modeling Contest for college students

# 💻 Internships
* **2025.05 - 2025.06** AI Engineer @ **HUAWEI**
* **2025.07 - 2025.10** Research Intern @ **Westlake University**
* **2024.11 - 2025.05** Research Intern @ **HKUST (GZ)**

# 📊 Stats
![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Follow-blue?logo=google-scholar&style=flat-square) 
