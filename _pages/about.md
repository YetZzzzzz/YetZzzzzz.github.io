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

My name is <span class="accent-text">Yan Zhuang</span>. I am a Research Engineer at <i class="fas fa-building"></i> **Tencent**, where I work on <span class="primary-gradient-text">Large Multimodal Models (LMMs)</span> for <span class="primary-gradient-text">Healthcare Intelligence</span> and <span class="primary-gradient-text">Neural Search</span>. Previously, I received my Ph.D. in Computer Science and Technology from <i class="fas fa-university"></i> **University of Electronic Science and Technology of China (UESTC)**, advised by Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=eyLJ0fMAAAAJ" class="link-accent">Fuji Ren</a>. Before that, I obtained my M.S. in Computer Technology from **UESTC**, under the supervision of Prof. <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=6I1ytegAAAAJ" class="link-accent">Yanru Zhang</a>, and my B.S. in Information and Computing Science from <i class="fas fa-university"></i> **Anhui Science and Technology University**.

<div class="quote-accent">

My research focuses on <span class="primary-gradient-text">Large Multimodal Models (LMMs)</span> and their real-world applications. My interests include <span class="primary-gradient-text">Multimodal Affective Computing</span>, <span class="primary-gradient-text">Multimodal Mathematical Reasoning</span>, and <span class="primary-gradient-text">Healthcare Intelligence</span>. More broadly, I am interested in developing reliable, efficient, and trustworthy multimodal intelligent systems capable of understanding, reasoning, and interacting in complex real-world environments.

</div>


<div class="highlight-blocks">

  <div class="highlight-block floating-card">

    <h3>
      <i class="fas fa-brain"></i>
      Multimodal Affective Intelligence
    </h3>

<ul>

<li>
<span class="accent-text">Multimodal sentiment and emotion understanding</span>
</li>

<li>
Robust multimodal learning under
<span class="primary-gradient-text">missing, noisy, and incomplete modalities</span>
</li>

<li>
Representation learning, multimodal alignment, and efficient fusion
</li>

</ul>

  </div>

  <div class="highlight-block floating-card">

    <h3>
      <i class="fas fa-lightbulb"></i>
      Multimodal Reasoning & Foundation Models
    </h3>

<ul>

<li>
<span class="accent-text">Large multimodal models (LMMs)</span>
</li>

<li>
Multimodal mathematical reasoning and self-verifiable inference
</li>

<li>
Reasoning, planning, and reinforcement learning for multimodal agents
</li>

</ul>

  </div>

  <div class="highlight-block floating-card">

    <h3>
      <i class="fas fa-heartbeat"></i>
      Healthcare Intelligence
    </h3>

<ul>

<li>
<span class="accent-text">Medical multimodal intelligence</span>
</li>

<li>
Clinical decision support and healthcare applications with LMMs
</li>

</ul>

  </div>

</div>

# <i class="fas fa-fire"></i> Recent News

<small>
Recent research updates, publications, awards, and professional activities.
</small>
- **May 2026** · 🎉 **ReNoRD** has been accepted to **ACM International Conference on Multimedia Retrieval (ICMR 2026)**.
- **Apr. 2026** · 🎉 **DEJA** has been accepted to **ACL Main 2026**, marking our recent work on trustworthy reasoning for retrieval-augmented generation.
- **Mar. 2026** · 🎉 Our work **DHM** has been accepted by **Neurocomputing**.
- **Jan. 2026** · 🎉 **TMDC** has been accepted to **AAAI 2026**.
- **Sep. 2025** · 🎉 **HME** has been accepted to **NeurIPS 2025**.
- **Jul. 2025** · 🎉 **CMAD** has been accepted to **ICCV 2025**.
- **Apr. 2025** · 🎉 **FAME** has been accepted to **ACM Multimedia 2025**.
- **Mar. 2025** · 🎉 **IIE** has been accepted by **IEEE Transactions on Multimedia (TMM)**.

# <i class="fas fa-book-open"></i> Featured Publications
<small>(*denotes joint first-authors. Representative publications on multimodal representation learning, robust multimodal intelligence, large multimodal models, and trustworthy reasoning. Full publication list is available on <a href="https://scholar.google.com.hk/citations?user=DtOl0DkAAAAJ&hl=zh-CN" class="link-accent">Google Scholar</a>.)</small>


<div class='paper-box floating-card'>
<div class='paper-box-image'>
<div class="badge pulse-accent">
ACL Main 2026
</div>
<img src='images/acl_main_2026.png'
alt="DEJA Framework"
width="100%">
</div>
<div class='paper-box-text'>
<h3>
<a href="https://arxiv.org/pdf/2604.18663"
style="color:inherit;text-decoration:none;">
Beyond Explicit Refusals: Soft-Failure Attacks on Retrieval-Augmented Generation
</a>
</h3>
<div class="authors">
Wentao Zhang,<strong>Yan Zhuang</strong>,Zhuhang Zheng,Mingfei Zhang,Jiawen Deng,Fuji Ren
</div>
<div class="venue">
Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics
(<strong>ACL Main 2026</strong>)
</div>
<div class="paper-summary">
Our work investigates previously overlooked soft-failure behaviors in retrieval-augmented generation systems and introduces a new benchmark for evaluating trustworthy multimodal reasoning.
</div>
<div class="links">
<a href="https://arxiv.org/pdf/2604.18663"
class="btn-accent">
<i class="fas fa-file-alt"></i>
Paper
</a>
</div>
</div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">AAAI 2026</div>
    <img src='images/aaai_26.png' alt="TMDC Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3><a href="https://ojs.aaai.org/index.php/AAAI/article/view/37212" style="color: inherit; text-decoration: none;">TMDC: A Two-Stage Modality Denoising and Complementation Framework for Multimodal Sentiment Analysis with Missing and Noisy Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang*</strong>, Minhao Liu*, Yanru Zhang, Jiawen Deng, Fuji Ren</div>
    <div class="venue">In The 40th Annual AAAI Conference on Artificial Intelligence (AAAI 2026)</div>
    <div class="links">
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/37212" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/TMDC" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">NeurIPS 2025</div>
    <img src='images/neurips_25.png' alt="HME Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3><a href="https://proceedings.neurips.cc/paper_files/paper/2025/file/d079de28c5e3f22e3507db24e870126b-Paper-Conference.pdf" style="color: inherit; text-decoration: none;">Hyper-Modality Enhancement for Multimodal Sentiment Analysis with Missing Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang*</strong>, Minhao Liu*, Wei Bai, Yanru Zhang, Wei Li, Jiawen Deng, Fuji Ren</div>
    <div class="venue">In The 38th Conference on Neural Information Processing Systems (NeurIPS 2025)</div>
    <div class="links">
      <a href="https://proceedings.neurips.cc/paper_files/paper/2025/file/d079de28c5e3f22e3507db24e870126b-Paper-Conference.pdf" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/HME" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ICCV 2025</div>
    <img src='images/iccv_25.png' alt="CMAD Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3><a href="https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html" style="color: inherit; text-decoration: none;">CMAD: Correlation-Aware and Modalities-Aware Distillation for Multimodal Sentiment Analysis with Missing Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang</strong>, Minhao Liu, Wei Bai, Yanru Zhang, Xiaoyue Zhang, Jiawen Deng, Fuji Ren</div>
    <div class="venue">In The IEEE/CVF International Conference on Computer Vision (ICCV 2025)</div>
    <div class="links">
      <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/CMAD" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">IEEE TMM 2025</div>
    <img src='images/tmm_25.png' alt="IIE Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3><a href="https://ieeexplore.ieee.org/abstract/document/11303977" style="color: inherit; text-decoration: none;">Intra-sample and Intra-modal Enhancement for Multimodal Sentiment Analysis with Missing Modalities</a></h3>
    <div class="authors"><strong>Yan Zhuang</strong>, Yanru Zhang, Jiawen Deng, Fuji Ren</div>
    <div class="venue">IEEE Transactions on Multimedia (TMM 2025)</div>
    <div class="links">
      <a href="https://ieeexplore.ieee.org/abstract/document/11303977" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/YetZzzzzz/IIE" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

- <span class="accent-text">ICMR 2026 </span> **ReNoRD: Learning from Relations under Noisy Pseudo Labels via Relational Distillation for Multimodal Sentiment.** Tiantai Zhai, **Yan Zhuang**, Fuji Ren, Jiawen Deng, Liang Luo.
- <span class="accent-text">Neurocomputing 2026 </span> [**Decoupled Hypergraph Modeling for Multimodal Sentiment Analysis.**](https://www.sciencedirect.com/science/article/abs/pii/S092523122600576X) Yanping Huang, Jiawen Deng, **Yan Zhuang**, Jiali You, Qian Liu, Fuji Ren.
- <span class="accent-text">ACM MM 2025 </span> [**FAME: Fusion-Aware Multi-modal Ensemble for Social Media Popularity Prediction.**](https://dl.acm.org/doi/abs/10.1145/3746027.3763759) **Yan Zhuang**, Wei Bai, Yanru Zhang, Minhao Liu, Jiawen Deng, Fuji Ren.
- <span class="accent-text">IEEE TAFFC 2025 </span> [**Enhanced Emotion Recognition in Conversations through Hybrid Context Encoding and Latent Dependency Mining.**](https://ieeexplore.ieee.org/abstract/document/11134050) Zheng Hu, Jiawen Deng, Satoshi Nakagawa, **Yan Zhuang**, Xiaoyue Zhang, Shimin Cai, Fuji Ren.
- <span class="accent-text">IEEE TMM 2025 </span> [**Multi-Level Contrastive Learning for Multimodal Sentiment Analysis.**](https://ieeexplore.ieee.org/abstract/document/11175557) **Yan Zhuang**, Wei Bai, Yanru Zhang, Jiawen Deng, Zheng Hu, Xiaoyue Zhang, Fuji Ren. <a href="https://github.com/YetZzzzzz/MLCL" style="text-decoration:none;color:#333;"><i class="fab fa-github"></i></a>
- <span class="accent-text">Research 2025 </span> [**R3DG: Retrieve, Rank and Reconstruction with Different Granularities for Multimodal Sentiment Analysis.**](https://spj.science.org/doi/full/10.34133/research.0729) **Yan Zhuang**, Yanru Zhang, Jiawen Deng, Fuji Ren. <a href="https://github.com/YetZzzzzz/R3DG" style="text-decoration:none;color:#333;"><i class="fab fa-github"></i></a>
- <span class="accent-text">WWW 2025 </span> [**ETS-MM: A Multi-Modal Social Bot Detection Model Based on Enhanced Textual Semantic Representation.**](https://dl.acm.org/doi/abs/10.1145/3696410.3714551) Wei Li, Jiawen Deng, Jiali You, Yuanyuan He, **Yan Zhuang**, Fuji Ren.
- <span class="accent-text">ACM MM 2024 </span> [**GLoMo: Global-local modal fusion for multimodal sentiment analysis.**](https://dl.acm.org/doi/abs/10.1145/3664647.3681527) **Yan Zhuang**, Yanru Zhang, Zheng Hu, Xiaoyue Zhang, Jiawen Deng, Fuji Ren. <a href="https://github.com/YetZzzzzz/GLoMo/tree/main" style="text-decoration:none;color:#333;"><i class="fab fa-github"></i></a>
- <span class="accent-text">IEEE TKDE 2024 </span> [**Hierarchical denoising for robust social recommendation.**](https://ieeexplore.ieee.org/abstract/document/10771708/) Zheng Hu, Satoshi Nakagawa, **Yan Zhuang**, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren.

# <i class="fas fa-project-diagram"></i> Research Projects

<small>
My research has evolved around three interconnected directions: multimodal representation learning, robust multimodal intelligence, and large multimodal models for reasoning and real-world applications.
</small>

<div class="floating-card">
<h3><i class="fas fa-shield-alt"></i>Robust Multimodal Intelligence</h3>
<p>
Building robust multimodal learning frameworks capable of handling <strong>missing modalities</strong>, <strong>noisy observations</strong>, and incomplete multimodal information. This research line focuses on modality denoising, adaptive fusion, representation enhancement, and knowledge distillation.
</p>
<p>
Representative works:
<span class="accent-text">TMDC (AAAI 2026), HME (NeurIPS 2025), CMAD (ICCV 2025)
</span>
</p>
</div>

<div class="floating-card">
<h3><i class="fas fa-network-wired"></i>Multimodal Representation Learning</h3>
<p>
Developing effective multimodal representation learning methods through contrastive learning, cross-modal alignment, global-local interaction, and relational modeling to improve multimodal understanding.
</p>
<p>
Representative works: <span class="accent-text"> GLoMo (ACM MM 2024), MLCL (TMM 2025), IIE (TMM 2025), ReNoRD (ICMR 2026)
</span>
</p>
</div>

<div class="floating-card">
<h3><i class="fas fa-robot"></i>Large Multimodal Models</h3>
<p>
Exploring reasoning, verification, and practical deployment of large multimodal models, with applications to mathematical reasoning, healthcare intelligence, and trustworthy AI systems.
</p>
<p>
Current topics include: <span class="accent-text"> RLVR, Medical LMMs, Trustworthy Reasoning
</span>
</p>
</div>

# <i class="fas fa-briefcase"></i> Professional Experience

<small>
My research experience spans both academia and industry, with a primary focus on multimodal intelligence, large multimodal models, and real-world AI systems.
</small>

### *Jul. 2026 – Present* **Research Engineer**: <i class="fas fa-building"></i> Tencent 
Working on large multimodal models for healthcare intelligence and next-generation AI search systems. My current research focuses on multimodal reasoning, trustworthy AI, reinforcement learning for reasoning, and practical deployment of multimodal foundation models in real-world applications.

### *Jan. 2026 – Jun. 2026* **Research Intern**: <i class="fas fa-building"></i> Tencent
Conducted research on reinforcement learning for multimodal mathematical reasoning and trustworthy large multimodal models, with applications to healthcare intelligence.

### *Jan. 2022 – Jun. 2022* **Research Intern**: <i class="fas fa-gamepad"></i> NetEase FUXI Laboratory
Conducted research on large language model pre-training and efficient language representation learning, laying the foundation for subsequent research on multimodal foundation models.

# <i class="fas fa-graduation-cap"></i> Education

- *Sep. 2022 – Jun. 2026*  **Ph.D. in Computer Science and Technology**  
  University of Electronic Science and Technology of China (UESTC), Advisor: Prof. Fuji Ren  
  
- *Sep. 2019 – Jun. 2022* **M.S. in Computer Technology**  
  University of Electronic Science and Technology of China (UESTC),Advisor: Prof. Yanru Zhang  
   
- *Sep. 2015 – Jun. 2019* **B.S. in Information and Computing Science**  
  Anhui Science and Technology University  
  
# <i class="fas fa-graduation-cap"></i> Honors and Awards
### Academic Honors
- **UESTC Outstanding Graduate**, 2026
- **UESTC Academic Newcomer Award**, 2026
- **National Scholarship (Ph.D.)**, 2025
- **National Scholarship (B.S.)**, 2017

### Competition Awards
- **Best Performance Award**, ACM Multimedia 2025 Social Media Prediction Challenge (Image Track)
- Silver Award, China International College Students' "Internet+" Innovation and Entrepreneurship Competition, 2021
- Second Prize, China Postgraduate Mathematical Contest in Modeling (Huawei Cup), 2020

# <i class="fas fa-users"></i> Professional Activities
### Journal Reviewing
- IEEE Transactions on Multimedia (TMM 2025-2026)
- IEEE Transactions on Affective Computing (TAFFC 2026)
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT 2026)
- Transactions on  Machine Learning Research (TMLR 2026)
- Knowledge-Based Systems (KBS 2026)
- IEEE Transactions on Vehicular Technology (TVT 2023-2024)


### Conference Reviewing
- CVPR 2026
- ICML 2026 (<span class="accent-text">Gold Reviewer Award, Top 25%</span>)
- NeurIPS 2026

---

<div align="center">

Thank you for visiting my homepage.

I am always happy to discuss research collaborations, academic exchanges, and opportunities related to multimodal intelligence, large multimodal models, and trustworthy AI.

</div>
