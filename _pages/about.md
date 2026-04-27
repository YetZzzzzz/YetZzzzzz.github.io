---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is <span class="accent-text">Yan Zhuang</span>. I am a Ph.D. candidate in the [Affective Computing and Advanced Intelligence Laboratory](https://www.scse.uestc.edu.cn/info/1028/15498.htm) and [Intelligame Lab](https://intelligame.github.io/) at <i class="fas fa-university"></i> **University of Electronic Science and Technology of China (UESTC)**, advised by Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=eyLJ0fMAAAAJ" class="link-accent">Fuji Ren</a>. I earned my Master's degree in Computer Technology from UESTC under the guidance of Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=6I1ytegAAAAJ" class="link-accent">Yanru Zhang</a>, and my Bachelor's degree in Information and Computing Science from <i class="fas fa-university"></i> **Anhui Science and Technology University**.

<div class="quote-accent">
My research focuses on <span class="primary-gradient-text">Multimodal Learning and Reasoning</span>, with an emphasis on advancing emotion perception and classification in scenarios where textual, visual, and audio modalities are available, either fully or partially.
</div>

Feel free to reach out if you'd like to discuss research or explore potential collaboration!

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> Multimodal Alignment & Fusion</h3>
    <ul>
      <li>Multigranular alignment & hierarchical <span class="accent-text">contrastive learning</span></li>
      <li>Fusion strategies leveraging <span class="primary-gradient-text">Mixture-of-Experts (MoE)</span></li>
      <li>Publications at <span class="accent-text">NeurIPS</span>, <span class="accent-text">ICCV</span>, <span class="accent-text">AAAI</span>, <span class="accent-text">ACL</span></li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-shield-alt"></i> Multimodal Robustness</h3>
    <ul>
      <li>Robust representation under <span class="accent-text">modality missing</span></li>
      <li>Handling <span class="primary-gradient-text">corruption & noise</span> conditions</li>
      <li>Knowledge distillation for incomplete modalities</li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-brain"></i> LLM-based Understanding</h3>
    <ul>
      <li><span class="accent-text">Affective understanding</span> and reasoning</li>
      <li>Self-verifiable multimodal <span class="primary-gradient-text">math reasoning (K9)</span></li>
      <li>Reinforcement learning for reasoning</li>
    </ul>
  </div>
</div>

# <i class="fas fa-file-alt"></i> Selected Publications

<small>(*denotes joint first-authors, <a href="https://scholar.google.com.hk/citations?user=DtOl0DkAAAAJ&hl=zh-CN" class="link-accent">Google Scholar</a>)</small>

<div class='paper-box floating-card'>
  <div class='paper-box-text'>
    <h3><a href="https://ojs.aaai.org/index.php/AAAI/article/view/37212" style="color: inherit; text-decoration: none;">TMDC: A Two-Stage Modality Denoising and Complementation Framework for Multimodal Sentiment Analysis with Missing and Noisy Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang*</strong>, Minhao Liu*, Yanru Zhang, Jiawen Deng, Fuji Ren</div>
    <div class="venue">AAAI 2026</div>
    <div class="links">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/37212" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/TMDC" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-text'>
    <h3><a href="https://openreview.net/pdf?id=mPOQZMBKaN" style="color: inherit; text-decoration: none;">Hyper-Modality Enhancement for Multimodal Sentiment Analysis with Missing Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang*</strong>, Minhao Liu*, Wei Bai, Yanru Zhang, Wei Li, Jiawen Deng, Fuji Ren</div>
    <div class="venue">NeurIPS 2025</div>
    <div class="links">
      <a href="https://openreview.net/pdf?id=mPOQZMBKaN" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/HME" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-text'>
    <h3><a href="https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html" style="color: inherit; text-decoration: none;">CMAD: Correlation-Aware and Modalities-Aware Distillation for Multimodal Sentiment Analysis with Missing Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang</strong>, Minhao Liu, Wei Bai, Yanru Zhang, Xiaoyue Zhang, Jiawen Deng, Fuji Ren</div>
    <div class="venue">ICCV 2025</div>
    <div class="links">
      <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/CMAD" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-text'>
    <h3><a href="https://dl.acm.org/doi/abs/10.1145/3746027.3763759" style="color: inherit; text-decoration: none;">FAME: Fusion-Aware Multi-modal Ensemble for Social Media Popularity Prediction</a></h3>
    <div class="authors"><strong>Yan Zhuang</strong>, Wei Bai, Yanru Zhang, Minhao Liu, Jiawen Deng, Fuji Ren</div>
    <div class="venue">ACM MM 2025</div>
    <div class="links">
      <a href="https://dl.acm.org/doi/abs/10.1145/3746027.3763759" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
    </div>
  </div>
</div>

- **ReNoRD: Learning from Relations under Noisy Pseudo Labels via Relational Distillation for Multimodal Sentiment.** Tiantai Zhai, **Yan Zhuang**, Fuji Ren, Jiawen Deng, Liang Luo. *ICMR 2026*.
- **Beyond Explicit Refusals: Soft-Failure Attacks on Retrieval-Augmented Generation.** Wentao Zhang, **Yan Zhuang**, Zhuhang Zheng, Mingfei Zhang, Jiawen Deng, Fuji Ren. *ACL Main 2026*.
- **Decoupled Hypergraph Modeling for Multimodal Sentiment Analysis.** Yanping Huang, Jiawen Deng, **Yan Zhuang**, Jiali You, Qian Liu, Fuji Ren. [*Neurocomputing 2026*](https://www.sciencedirect.com/science/article/abs/pii/S092523122600576X).
- **Intra-sample and Intra-modal Enhancement for Multimodal Sentiment Analysis with Missing Modalities.** **Yan Zhuang**, Yanru Zhang, Jiawen Deng, Fuji Ren. [*IEEE Transactions on Multimedia (TMM) 2025*](https://ieeexplore.ieee.org/abstract/document/11303977). [\[code\]](https://github.com/YetZzzzzz/IIE)
- **Multi-Level Contrastive Learning for Multimodal Sentiment Analysis.** **Yan Zhuang**, Wei Bai, Yanru Zhang, Jiawen Deng, Zheng Hu, Xiaoyue Zhang, Fuji Ren. [*IEEE Transactions on Multimedia (TMM) 2025*](https://ieeexplore.ieee.org/abstract/document/11175557). [\[code\]](https://github.com/YetZzzzzz/MLCL)
- **R3DG: Retrieve, Rank and Reconstruction with Different Granularities for Multimodal Sentiment Analysis.** **Yan Zhuang**, Yanru Zhang, Jiawen Deng, Fuji Ren. [*Research 2025*](https://spj.science.org/doi/full/10.34133/research.0729). [\[code\]](https://github.com/YetZzzzzz/R3DG)
- **Enhanced Emotion Recognition in Conversations through Hybrid Context Encoding and Latent Dependency Mining.** Zheng Hu, Jiawen Deng, Satoshi Nakagawa, **Yan Zhuang**, Xiaoyue Zhang, Shimin Cai, Fuji Ren. [*IEEE Transactions on Affective Computing (TAFFC) 2025*](https://ieeexplore.ieee.org/abstract/document/11134050).
- **ETS-MM: A Multi-Modal Social Bot Detection Model Based on Enhanced Textual Semantic Representation.** Wei Li, Jiawen Deng, Jiali You, Yuanyuan He, **Yan Zhuang**, Fuji Ren. [*WWW 2025*](https://dl.acm.org/doi/abs/10.1145/3696410.3714551).
- **GLoMo: Global-local modal fusion for multimodal sentiment analysis.** **Yan Zhuang**, Yanru Zhang, Zheng Hu, Xiaoyue Zhang, Jiawen Deng, Fuji Ren. [*ACM MM 2024*](https://dl.acm.org/doi/abs/10.1145/3664647.3681527). [\[code\]](https://github.com/YetZzzzzz/GLoMo/tree/main)
- **Hierarchical denoising for robust social recommendation.** Zheng Hu, Satoshi Nakagawa, **Yan Zhuang**, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren. [*IEEE TKDE 2024*](https://ieeexplore.ieee.org/abstract/document/10771708/).
- **Yet at the FinNLP-2022 ERAI Task: Modified models for evaluating the Rationales of Amateur Investors.** **Yan Zhuang**, Fuji Ren. [*EMNLP 2022 Workshop*](https://aclanthology.org/2022.finnlp-1.17/).
- **Yet@smm4h'22: Improved bert-based classification models with rdrop and polyloss.** **Yan Zhuang**, Yanru Zhang. [*COLING 2022 Workshop*](https://aclanthology.org/2022.smm4h-1.28/).
- **Yet at Memotion 2.0 2022: Hate speech detection combining bilstm and fully connected layers.** **Yan Zhuang**, Yanru Zhang. [*AAAI 2022 Workshop*](https://ceur-ws.org/Vol-3199/paper14.pdf).
- **Yet at Factify 2022: Unimodal and bimodal roberta-based models for fact checking.** **Yan Zhuang**, Yanru Zhang. [*AAAI 2022 Workshop*](https://ceur-ws.org/Vol-3199/paper8.pdf).

# <i class="fas fa-graduation-cap"></i> Educations
- *2022 - Present*: &nbsp;Ph.D. in Computer Science and Technology, <span class="primary-gradient-text">University of Electronic Science and Technology of China</span>. Advisor: Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=eyLJ0fMAAAAJ" class="link-accent">Fuji Ren</a>.
- *2019 - 2022*: &nbsp;M.S. in Computer Technology, <span class="primary-gradient-text">University of Electronic Science and Technology of China</span>. Advisor: Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=6I1ytegAAAAJ" class="link-accent">Yanru Zhang</a>.
- *2015 - 2019*: &nbsp;B.S. in Information and Computing Science, <span class="primary-gradient-text">Anhui Science and Technology University</span>.

# <i class="fas fa-laptop-code"></i> Professional Experiences
- *Spring 2026*: &nbsp;Intern, **Tencent**: Self-Verifiable Multimodal Mathematical Reasoning (K9) using RL.
- *Spring 2022*: &nbsp;Research Intern, **NetEase FUXI Laboratory**: LLM pre-training.

# <i class="fas fa-trophy"></i> Honors and Awards
- *2025*: &nbsp;ACM MM 2025 Social Media Prediction (SMP) Challenge - Image Track: <a href="https://smp-challenge.com/2025/leaderboard.html" class="link-accent">Best Performance Award</a>.
- *2025*: &nbsp;<span class="accent-text">National Scholarship (Ph.D.)</span>.
- *2021*: &nbsp;The 7th China International College Students' "Internet+" Innovation and Entrepreneurship Competition: Silver Award.
- *2020*: &nbsp;"Huawei Cup" The 17th China Post-Graduate Mathematical Contest in Modeling (GMCM): Second Prize.
- *2017*: &nbsp;<span class="accent-text">National Scholarship (B.S.)</span>.

# <i class="fas fa-users"></i> Professional Service
- **Journal Reviewer:** IEEE Transactions on Multimedia (T-MM), IEEE Transactions on Circuits and Systems for Video Technology (T-CSVT), IEEE Transactions on Vehicular Technology (T-VT)
- **Conference Reviewer:** CVPR 2026, ICML 2026
