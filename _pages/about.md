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
He is currently a visiting Ph.D supervised by [Basura Fernando](https://basurafernando.github.io/) in [Agency for Science, Technology and Research (A*STAR) Singapore](https://www.a-star.edu.sg/) and cooperate with [Prof. SHOU, Zheng Mike](https://sites.google.com/view/showlab) in National University of Singapore (新加坡国立大学) . 
He received his Master's and Bachelor's degrees from [Wuhan University of Technology](http://english.whut.edu.cn/), School of Computer Science and Artificial Intelligence, under the supervision of [Prof. Xian Zhong](http://cst.whut.edu.cn/xygk/szdw/201505/t20150527_876884.shtml).

His research interests include causal inference, computer vision, and retrieval. He has published over 10 papers at the top international conferences and journals (<a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) such as CVPR, ACM MM.
<!-- with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a>  -->
He has also served as a reviewer of multiple conferences and journals, including CVPR, IJCAI, ICANN, ACM MM, TIP, TMM, and JEI. 

If you are seeking any form of **academic cooperation** on person reidentification, cross-modality retrieval, please feel free to email at [yzw_aim@whu.edu.cn](mailto:yzw_aim@whu.edu.cn).

# 🔥 News
- *2023.11*: &nbsp;🎉🎉 He begins his visting at A*STAR in Singapore!
- *2023.07*: &nbsp;🎉🎉 Two co-authored papers are accepted by ACM MM 2023!
- *2023.05*: &nbsp;🎉🎉 One paper is accepted by TIP!
- *2022.04*: &nbsp;🎉🎉 One co-authore paper is accepted by TITS!
- *2023.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2023!
- *2022.06*: &nbsp;🎉🎉 One co-authored paper is accepted by ACM MM 2022!
- *2022.03*: &nbsp;🎉🎉 One paper is accepted by ICME 2022!
- *2021.03*: &nbsp;🎉🎉 One paper is accepted by ICME 2021!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/CVPR23.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Good is Bad: Causality Inspired Cloth-debiasing for Cloth-changing Person Re-identification](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_Good_Is_Bad_Causality_Inspired_Cloth-Debiasing_for_Cloth-Changing_Person_Re-Identification_CVPR_2023_paper.pdf)

**Zhengwei Yang**, Meng Lin, Xian Zhong, Yu Wu, Zheng Wang

[**Code**](https://github.com/BoomShakaY/AIM-CCReID) <strong><span class='show_paper_citations' data='xKVIwtEAAAAJ:Y0pCki6q_DkC'></span></strong>
-  The first work introduces casality in to cloth-changing person ReID, and proposed a causality-based Auto-Intervention Model (AIM) to mitigate clothing bias for robust cloth-changing person ReID.

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

- [Striking a balance: Unsupervised cross-domain crowd counting via knowledge diffusion](https://dl.acm.org/doi/abs/10.1145/3581783.3611797), Haiyang Xie\*, **Zhengwei Yang\***, Huilin Zhu, Zheng Wang, **ACM MM 2023**
- [DAOT: Domain-Agnostically Aligned Optimal Transport for Domain-Adaptive Crowd Counting](https://dl.acm.org/doi/abs/10.1145/3581783.3611793), Huilin Zhu, Jingling Yuan, Xian Zhong, **Zhengwei Yang**, Zheng Wang, Shengfeng He, **ACM MM 2023**
- [Visual Exposes You: Pedestrian Trajectory Prediction Meets Visual Intention](https://ieeexplore.ieee.org/abstract/document/10103218/), Xian Zhong\*, Xu Yan, **Zhengwei Yang\***, Wenxin Huang, Kui Jiang, Ryan Wen Liu, Zheng Wang, **TITS 2023**
- [Implicit Attention-Based Cross-Modal Collaborative Learning for Action Recognition](https://ieeexplore.ieee.org/abstract/document/10222496), Jianghao Zhang, Xian Zhong, Wenxuan Liu, Kui Jiang, **Zhengwei Yang**, Zheng Wang, **ICIP 2023**
- [Fine-Grained Fragment Diffusion for Cross Domain Crowd Counting](https://dl.acm.org/doi/abs/10.1145/3503161.3548298), Huilin Zhu, Jingling Yuan, **Zhengwei Yang\***, Xian Zhong\*, Zheng Wang,  **ACM MM 2022**
- [Global Temporal Attention Optimization for Human Trajectory Prediction](https://ieeexplore.ieee.org/abstract/document/9945387/), Xu Yan, Xian Zhong, **Zhengwei Yang**, Rui Zhang, Wenxin Huang, Zheng Wang, **ISMC 2022**
- [Attentive decoupling network for cloth-changing re-identification](https://ieeexplore.ieee.org/abstract/document/9859851/), **Zhengwei Yang**, Xian Zhong, Hong Liu, Zhun Zhong, Zheng Wang, **ICME 2022**
- [Subspace enhancement and colorization network for infrared video action recognition](https://link.springer.com/chapter/10.1007/978-3-030-89370-5_24), Lu Xu, Xian Zhong, Wenxuan Liu, Shilei Zhao, **Zhengwei Yang**, Luo Zhong, **PRICAI 2021**
- [Auxiliary bi-level graph representation for cross-modal image-text retrieval](https://ieeexplore.ieee.org/abstract/document/9428380/), Xian Zhong\*, **Zhengwei Yang\***, Mang Ye, Wenxin Huang, Jingling Yuan, Chia-Wen Lin


# 🎖 Honors and Awards
- *2023.10* He won a national scholarship at Wuhan University
- *2022.09* He was awarded the Outstanding Graduate Student and Outstanding Master’s Thesis of Wuhan University of Technology

# 📖 Educations
- *2022.09 - 2024.03 (now)*, Doctoral, Wuhan University, Wuhan.
- *2019.09 - 2022.06*, Master, Wuhan University of Technology, Wuhan.
- *2015.09 - 2029.06*, Bachelor, Wuhan University of Technology, Wuhan.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internshipss
- *2023.11 - 2024.11*, Visiting Ph.D, Centre for Frontier AI Research (CFAR), Agency for Science, Technology and Research (A*STAR), Singapore