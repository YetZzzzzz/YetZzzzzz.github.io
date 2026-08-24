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

<style>
/* Compact spacing for Education, Honors and Awards, and Professional Activities */
#education + ul,
#honors-and-awards + ul,
#professional-activities + ul {
  margin-top: 0.35em;
  margin-bottom: 0.6em;
}

#education + ul li,
#honors-and-awards + ul li,
#professional-activities + ul li,
#professional-activities ~ ul li {
  margin-bottom: 0.2em;
  line-height: 1.35;
}

#education + ul li p,
#honors-and-awards + ul li p,
#professional-activities + ul li p {
  margin-bottom: 0.2em;
}
</style>

Dr. **Yan Zhuang** will join the **Department of Data Science and Artificial Intelligence (DSAI)** at [**The Hong Kong Polytechnic University (PolyU)**](https://www.polyu.edu.hk/), Hong Kong SAR, China, as a **Postdoctoral Fellow**, under the supervision of Dr. [Xingyu Wu](https://www.polyu.edu.hk/dsai/people/academic-staff/wu-xingyu/) and Prof. [Kay Chen Tan](https://www.polyu.edu.hk/dsai/people/academic-staff/tankaychen/). He will be fortunate to conduct research with the **MIND Lab**.

Before joining PolyU, he received his Ph.D. in Computer Science and Technology from the [**University of Electronic Science and Technology of China (UESTC)**](https://www.uestc.edu.cn/), advised by Prof. [Fuji Ren](https://scholar.google.com.hk/citations?hl=zh-CN&user=eyLJ0fMAAAAJ). He received his M.S. in Computer Technology from [**UESTC**](https://www.uestc.edu.cn/), under the supervision of Prof. [Yanru Zhang](https://scholar.google.com.hk/citations?hl=zh-CN&user=6I1ytegAAAAJ), and his B.S. in Information and Computing Science from [**Anhui Science and Technology University**](https://www.ahstu.edu.cn/).

His research interests encompass **multimodal intelligence** and **self-evolving large language and multimodal models**, with a particular focus on developing intelligent systems that can continuously reason, learn, adapt, and improve.

My research focuses on **self-evolving Large Multimodal Models (LMMs)** and their real-world applications, including **Multimodal Affective Computing**.

# &#x20;Recent News

- **Aug. 2026** · 🎉 **MAPS** has been accepted to **EMNLP Main 2026**.
- **Aug. 2026** · 🎉 **MF-CC** has been accepted by **Computers & Security**.
- **May 2026** · 🎉 **ReNoRD** has been accepted to **ACM International Conference on Multimedia Retrieval (ICMR 2026)**.
- **Apr. 2026** · 🎉 **DEJA** has been accepted to **ACL Main 2026**, marking our recent work on trustworthy reasoning for retrieval-augmented generation.
- **Mar. 2026** · 🎉 Our work **DHM** has been accepted by **Neurocomputing**.
- **Jan. 2026** · 🎉 **TMDC** has been accepted to **AAAI 2026**.
- **Sep. 2025** · 🎉 **HME** has been accepted to **NeurIPS 2025**.
- **Jul. 2025** · 🎉 **CMAD** has been accepted to **ICCV 2025**.
- **Apr. 2025** · 🎉 **FAME** has been accepted to **ACM Multimedia 2025**.
- **Mar. 2025** · 🎉 **IIE** has been accepted by **IEEE Transactions on Multimedia (TMM)**.

# &#x20;Featured Publications

(*denotes joint first-authors. Representative publications on multimodal representation learning, robust multimodal intelligence, large multimodal models, and trustworthy reasoning. Full publication list is available on [Google Scholar](https://scholar.google.com.hk/citations?user=DtOl0DkAAAAJ&hl=zh-CN).*)

ACL Main 2026

### &#x20;[Beyond Explicit Refusals: Soft-Failure Attacks on Retrieval-Augmented Generation](https://arxiv.org/pdf/2604.18663)

Wentao Zhang, **Yan Zhuang**, Zhuhang Zheng, Mingfei Zhang, Jiawen Deng, Fuji Ren

Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (**ACL Main 2026**)

Our work investigates previously overlooked soft-failure behaviors in retrieval-augmented generation systems and introduces a new benchmark for evaluating trustworthy multimodal reasoning.

[Paper](https://arxiv.org/pdf/2604.18663)

AAAI 2026

### [TMDC: A Two-Stage Modality Denoising and Complementation Framework for Multimodal Sentiment Analysis with Missing and Noisy Modalities](https://ojs.aaai.org/index.php/AAAI/article/view/37212)

**Yan Zhuang\***, Minhao Liu\*, Yanru Zhang, Jiawen Deng, Fuji Ren

In The 40th Annual AAAI Conference on Artificial Intelligence (AAAI 2026)

[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37212) &nbsp;&nbsp;&nbsp; [Code](https://github.com/YetZzzzzz/TMDC)

NeurIPS 2025

### [Hyper-Modality Enhancement for Multimodal Sentiment Analysis with Missing Modalities](https://proceedings.neurips.cc/paper_files/paper/2025/file/d079de28c5e3f22e3507db24e870126b-Paper-Conference.pdf)

**Yan Zhuang\***, Minhao Liu\*, Wei Bai, Yanru Zhang, Wei Li, Jiawen Deng, Fuji Ren

In The 38th Conference on Neural Information Processing Systems (NeurIPS 2025)

[Paper](https://proceedings.neurips.cc/paper_files/paper/2025/file/d079de28c5e3f22e3507db24e870126b-Paper-Conference.pdf) &nbsp;&nbsp;&nbsp; [Code](https://github.com/YetZzzzzz/HME)

ICCV 2025

### [CMAD: Correlation-Aware and Modalities-Aware Distillation for Multimodal Sentiment Analysis with Missing Modalities](https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html)

**Yan Zhuang**, Minhao Liu, Wei Bai, Yanru Zhang, Xiaoyue Zhang, Jiawen Deng, Fuji Ren

In The IEEE/CVF International Conference on Computer Vision (ICCV 2025)

[Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Zhuang_CMAD_Correlation-Aware_and_Modalities-Aware_Distillation_for_Multimodal_Sentiment_Analysis_with_ICCV_2025_paper.html) &nbsp;&nbsp;&nbsp; [Code](https://github.com/YetZzzzzz/CMAD)

IEEE TMM 2025

### [Intra-sample and Intra-modal Enhancement for Multimodal Sentiment Analysis with Missing Modalities](https://ieeexplore.ieee.org/abstract/document/11303977)

**Yan Zhuang**, Yanru Zhang, Jiawen Deng, Fuji Ren

IEEE Transactions on Multimedia (TMM 2025)

[Paper](https://ieeexplore.ieee.org/abstract/document/11303977) &nbsp;&nbsp;&nbsp; [Code](https://github.com/YetZzzzzz/IIE)

- ICMR 2026  **ReNoRD: Learning from Relations under Noisy Pseudo Labels via Relational Distillation for Multimodal Sentiment.** Tiantai Zhai, **Yan Zhuang**, Fuji Ren, Jiawen Deng, Liang Luo.
- Neurocomputing 2026  [**Decoupled Hypergraph Modeling for Multimodal Sentiment Analysis.**](https://www.sciencedirect.com/science/article/abs/pii/S092523122600576X) Yanping Huang, Jiawen Deng, **Yan Zhuang**, Jiali You, Qian Liu, Fuji Ren.
- ACM MM 2025 Grand Challenge  [**FAME: Fusion-Aware Multi-modal Ensemble for Social Media Popularity Prediction.**](https://dl.acm.org/doi/abs/10.1145/3746027.3763759) **Yan Zhuang**, Wei Bai, Yanru Zhang, Minhao Liu, Jiawen Deng, Fuji Ren.
- IEEE TAFFC 2025  [**Enhanced Emotion Recognition in Conversations through Hybrid Context Encoding and Latent Dependency Mining.**](https://ieeexplore.ieee.org/abstract/document/11134050) Zheng Hu, Jiawen Deng, Satoshi Nakagawa, **Yan Zhuang**, Xiaoyue Zhang, Shimin Cai, Fuji Ren.
- IEEE TMM 2025  [**Multi-Level Contrastive Learning for Multimodal Sentiment Analysis.**](https://ieeexplore.ieee.org/abstract/document/11175557) **Yan Zhuang**, Wei Bai, Yanru Zhang, Jiawen Deng, Zheng Hu, Xiaoyue Zhang, Fuji Ren.
- Research 2025  [**R3DG: Retrieve, Rank and Reconstruction with Different Granularities for Multimodal Sentiment Analysis.**](https://spj.science.org/doi/full/10.34133/research.0729) **Yan Zhuang**, Yanru Zhang, Jiawen Deng, Fuji Ren.
- WWW 2025  [**ETS-MM: A Multi-Modal Social Bot Detection Model Based on Enhanced Textual Semantic Representation.**](https://dl.acm.org/doi/abs/10.1145/3696410.3714551) Wei Li, Jiawen Deng, Jiali You, Yuanyuan He, **Yan Zhuang**, Fuji Ren.
- ACM MM 2024  [**GLoMo: Global-local modal fusion for multimodal sentiment analysis.**](https://dl.acm.org/doi/abs/10.1145/3664647.3681527) **Yan Zhuang**, Yanru Zhang, Zheng Hu, Xiaoyue Zhang, Jiawen Deng, Fuji Ren.
- IEEE TKDE 2024  [**Hierarchical denoising for robust social recommendation.**](https://ieeexplore.ieee.org/abstract/document/10771708/) Zheng Hu, Satoshi Nakagawa, **Yan Zhuang**, Jiawen Deng, Shimin Cai, Tao Zhou, Fuji Ren.

# &#x20;Professional Experience

My research experience spans both academia and industry, with a primary focus on **multimodal intelligence, large multimodal models, and self-evolving AI systems**.

### *Sep. 2026 – :* **Postdoctoral Fellow** in [The Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/)

Conduct research on **self-evolving large language models (LLMs), intelligent agents, and the integration of evolutionary algorithms with LLMs**, with a focus on developing adaptive and continuously improving intelligent systems.

### *Jan. 2026 – Sep. 2026:* **Research Engineer** in Tencent

Conducted research on **reinforcement learning for multimodal mathematical reasoning and trustworthy large multimodal models**, with applications to **healthcare intelligence and AI search**.

### *Jan. 2022 – Jun. 2022:* **Research Intern** in NetEase FUXI Laboratory

Conducted research on **large language model pre-training and efficient language representation learning**, laying the foundation for subsequent research on multimodal foundation models.

# &#x20;Education

- *Sep. 2022 – Jun. 2026:* **Ph.D. in Computer Science and Technology**  
  University of Electronic Science and Technology of China (UESTC), Advisor: Prof. Fuji Ren
- *Sep. 2019 – Jun. 2022:* **M.S. in Computer Technology**  
  University of Electronic Science and Technology of China (UESTC), Advisor: Prof. Yanru Zhang
- *Sep. 2015 – Jun. 2019:* **B.S. in Information and Computing Science**  
  Anhui Science and Technology University

# &#x20;Honors and Awards

### Academic Honors

- **UESTC Outstanding Graduate**, 2026
- **UESTC Academic Newcomer Award**, 2026
- **National Scholarship (Ph.D.)**, 2025
- **National Scholarship (B.S.)**, 2017

### Competition Awards

- **Best Performance Award**, ACM Multimedia 2025 Social Media Prediction Challenge (Image Track)
- **Silver Award**, China International College Students' "Internet+" Innovation and Entrepreneurship Competition, 2021
- **Second Prize**, China Postgraduate Mathematical Contest in Modeling (Huawei Cup), 2020

# &#x20;Professional Activities

### Journal Reviewing

- IEEE Transactions on Multimedia (TMM 2025–2026)
- IEEE Transactions on Affective Computing (TAFFC 2026)
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT 2026)
- Transactions on Machine Learning Research (TMLR 2026)
- Knowledge-Based Systems (KBS 2026)
- IEEE Transactions on Vehicular Technology (TVT 2023–2024)

### Conference Reviewing

- AAAI 2027
- NeurIPS 2026
- ICML 2026 (**Gold Reviewer Award, Top 25%**)
- CVPR 2026

---

Thank you for visiting my homepage.

I am always happy to discuss **research collaborations, academic exchanges, and opportunities** related to **multimodal intelligence and self-evolving large multimodal models**. Please feel free to contact me at [**delecisz@gmail.com**](mailto:delecisz@gmail.com).
