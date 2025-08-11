---
permalink: /
title: ""
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

<span class='anchor' id='about-me'></span>

He is currently a 2nd-year PhD student of [AIM Lab](http://aim-nercms.whu.edu.cn/) at [National Engineering Research Center for Multimedia Software(国家多媒体软件工程技术研究中心)](http://multimedia.whu.edu.cn/) and [Wuhan University (武汉大学)](https://www.whu.edu.cn/), advised by [Prof. Zheng Wang](https://wangzwhu.github.io/home/). 
He is currently a visiting Ph.D. supervised by [Basura Fernando](https://basurafernando.github.io/) in [Agency for Science, Technology and Research (A*STAR) Singapore](https://www.a-star.edu.sg/).
<!-- and cooperates with [Prof. SHOU, Zheng Mike](https://sites.google.com/view/showlab) in National University of Singapore (新加坡国立大学). -->
He received his Master's and Bachelor's degrees from [Wuhan University of Technology](http://english.whut.edu.cn/), School of Computer Science and Artificial Intelligence, under the supervision of [Prof. Xian Zhong](http://cst.whut.edu.cn/xygk/szdw/201505/t20150527_876884.shtml).

His research interests include causal inference, computer vision, and retrieval. He has published over 10 papers at the top international conferences and journals (<a href='https://scholar.google.com/citations?user=xKVIwtEAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) such as CVPR, ACM MM.
<!-- with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a>  -->
He has also served as a reviewer of multiple conferences and journals, including CVPR, IJCAI, ICANN, ACM MM, TIP, TMM, and JEI. 

If you are seeking any form of **academic cooperation** on person reidentification, cross-modality retrieval, please feel free to email at [yzw_aim@whu.edu.cn](mailto:yzw_aim@whu.edu.cn).

# 🔥 News
- *2025.07*: &nbsp;🎉🎉 One paper is accepted by IJCV journal！
- *2025.07*: &nbsp;🎉🎉 One co-authored paper is accepted by TIFS journal！
- *2025.07*: &nbsp;🎉🎉 One co-authored paper is accepted by ACM MM 2025!
- *2025.06*: &nbsp;🎉🎉 One co-authored paper is accepted by ICCV 2025!
- *2025.04*: &nbsp;🎉🎉 One co-authored paper is accepted by SIGIR 2025!
- *2025.02*: &nbsp;🎉🎉 One co-authored paper is accepted by CVPR 2025!
- *2024.12*: &nbsp;🎉🎉 One co-authored paper is accepted by AAAI 2025!
- *2024.11*: &nbsp;🎉🎉 He finish his visiting at A*STAR
- *2024.07*: &nbsp;🎉🎉 One co-authored paper is accepted by ECCV 2024!
- *2024.04*: &nbsp;🎉🎉 One co-authored paper is accepted by IJCAI 2024!
- *2023.11*: &nbsp;🎉🎉 He begins his visting at A*STAR in Singapore!
- *2023.07*: &nbsp;🎉🎉 Two co-authored papers are accepted by ACM MM 2023!
- *2023.05*: &nbsp;🎉🎉 One paper is accepted by TIP!
- *2022.04*: &nbsp;🎉🎉 One co-authored paper is accepted by TITS!
- *2023.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2023!
- *2022.06*: &nbsp;🎉🎉 One co-authored paper is accepted by ACM MM 2022!
- *2022.03*: &nbsp;🎉🎉 One paper is accepted by ICME 2022!
- *2021.03*: &nbsp;🎉🎉 One paper is accepted by ICME 2021!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/IJCV25.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Clothing Purification with Causality Meets Vision-Language Pretraining Models](https://link.springer.com/article/10.1007/s11263-025-02548-7?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=nonoa_20250811&utm_content=10.1007/s11263-025-02548-7)

**Zhengwei Yang\***, Huilin Zhu\*, Nan Lei, Basura Fernando, Zheng Wang

[**Code**]() <strong><span class='show_paper_citations' data='xKVIwtEAAAAJ:Y0pCki6q_DkC'></span></strong>
-  This work constructs a clothing indication VLP pipeline to efficiently capture clothing semantics and employs causality analysis to purify the relationship between learned visual features and intrinsic identity representation from two causal aspects.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/CVPR23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Good is Bad: Causality Inspired Cloth-debiasing for Cloth-changing Person Re-identification](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Good_Is_Bad_Causality_Inspired_Cloth-Debiasing_for_Cloth-Changing_Person_Re-Identification_CVPR_2023_paper.pdf)

**Zhengwei Yang**, Meng Lin, Xian Zhong, Yu Wu, Zheng Wang

[**Code**](https://github.com/BoomShakaY/AIM-CCReID) <strong><span class='show_paper_citations' data='xKVIwtEAAAAJ:Y0pCki6q_DkC'></span></strong>
-  The first work introduces causality to cloth-changing person ReID, and proposes a causality-based Auto-Intervention Model (AIM) to mitigate clothing bias for robust cloth-changing person ReID.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2023</div><img src='images/TIP23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Win-Win by Competition: Auxiliary-Free Cloth-Changing Person Re-Identification](https://ieeexplore.ieee.org/document/10130745)

**Zhengwei Yang**, Xian Zhong, Zhun Zhong, Hong Liu, Zheng Wang, Shin'Ichi Satoh

[**Code**](https://github.com/BoomShakaY/Win-CCReID) <strong><span class='show_paper_citations' data='xKVIwtEAAAAJ:Tyk-4Ss8FVUC'></span></strong>
-  This paper introduces an Auxiliary-free Competitive IDentification (ACID) model. It achieves a win-win situation by enriching the identity-preserving information conveyed by the appearance and structure features while maintaining holistic efficiency. 

</div>
</div>
- [Contrastive-Generative-Contrastive: NeutralizeSubjectivity in Sketch Re-identification](), Zechao Hu, **Zhengwei Yang**, Hao Li, Zheng Wang, **TIFS 2025**
- [From Language to Instance: Generative Visual Prompting for Zero-shot Camouflaged Object Detection](), Zihou Zhang, Hao Li, **Zhengwei Yang**, Zechao Hu, Liang Li, Zheng Wang, **ACM MM 2025**
- [Cross-Category Subjectivity Generalization for Style-Adaptive Sketch Re-ID](), Zechao Hu, **Zhengwei Yang**, Hao Li, Yixiong Zou, Zheng Wang, **ICCV 2025**
- [Unified Category and Style Generalization for Instance-Level Sketch Retrieval](), Zechao Hu, **Zhengwei Yang**, Hao Li, Yixiong Zou, Fengbin Zhu, Zheng Wang, **SIGIR 2025**
- [CCIN: Compositional Conflict Identification and Neutralization for\\Composed Image Retrieval](), Likai Tian, Jian Zhao, Zechao Hu, **Zhengwei Yang**, Hao Li, Lei Jin, Zheng Wang, Xuelong Li, **CVPR 2025**
- [VEGAS: Towards Visually Explainable and Grounded Artificial Social Intelligence](), Hao Li, Hao Fei, Zechao Hu, **Zhengwei Yang**, Zheng Wang, **AAAI 2025**
- [Zero-shot Object Counting with Good Exemplars](https://arxiv.org/abs/2407.04948)[code](https://github.com/HopooLinZ/VA-Count), Huilin Zhu\*, Jingling Yuan, **Zhengwei Yang\***, Yu Guo, Xian Zhong, Zheng Wang, Shengfeng He, **ECCV 2024**
- [Expressiveness is Effectiveness: Self-supervised Fashion-aware CLIP for Video-to-Shop Retrieval](https://doi.org/10.24963/ijcai.2024/148), Likai Tian\*, **Zhengwei Yang\***, Zechao Hu, Li Hao, Yifang Yin, Zheng Wang, **IJCAI 2024**
- [Striking a balance: Unsupervised cross-domain crowd counting via knowledge diffusion](https://dl.acm.org/doi/abs/10.1145/3581783.3611797), Haiyang Xie\*, **Zhengwei Yang\***, Huilin Zhu, Zheng Wang, **ACM MM 2023**
- [DAOT: Domain-Agnostically Aligned Optimal Transport for Domain-Adaptive Crowd Counting](https://dl.acm.org/doi/abs/10.1145/3581783.3611793), Huilin Zhu, Jingling Yuan, Xian Zhong, **Zhengwei Yang**, Zheng Wang, Shengfeng He, **ACM MM 2023**
- [Visual Exposes You: Pedestrian Trajectory Prediction Meets Visual Intention](https://ieeexplore.ieee.org/abstract/document/10103218/), Xian Zhong\*, Xu Yan, **Zhengwei Yang\***, Wenxin Huang, Kui Jiang, Ryan Wen Liu, Zheng Wang, **TITS 2023**
- [Fine-Grained Fragment Diffusion for Cross Domain Crowd Counting](https://dl.acm.org/doi/abs/10.1145/3503161.3548298), Huilin Zhu, Jingling Yuan, **Zhengwei Yang\***, Xian Zhong\*, Zheng Wang,  **ACM MM 2022**
- [Attentive decoupling network for cloth-changing re-identification](https://ieeexplore.ieee.org/abstract/document/9859851/), **Zhengwei Yang**, Xian Zhong, Hong Liu, Zhun Zhong, Zheng Wang, **ICME 2022**
- [Auxiliary bi-level graph representation for cross-modal image-text retrieval](https://ieeexplore.ieee.org/abstract/document/9428380/), Xian Zhong\*, **Zhengwei Yang\***, Mang Ye, Wenxin Huang, Jingling Yuan, Chia-Wen Lin, **ICME 2021**


# 🎖 Honors and Awards
- *2023.10* He won a national scholarship at Wuhan University
- *2022.09* He was awarded the Outstanding Graduate Student and Outstanding Master’s Thesis of Wuhan University of Technology

# 📖 Educations
- *2022.09 - 2025.04 (now)*, Doctoral, Wuhan University, Wuhan.
- *2019.09 - 2022.06*, Master, Wuhan University of Technology, Wuhan.
- *2015.09 - 2019.06*, Bachelor, Wuhan University of Technology, Wuhan.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internshipss
- *2023.11 - 2024.11*, Visiting Ph.D., Centre for Frontier AI Research (CFAR), Agency for Science, Technology and Research (A*STAR), Singapore
