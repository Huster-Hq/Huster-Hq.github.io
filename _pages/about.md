---
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

<span class='anchor' id='about-me'></span>
I am a currently a first-year (2025.09-) Ph.D. candidate at the Huazhong University of Science and Technology (HUST), advised by <a href='https://andysis.github.io/'>Zhiwei Wang</a> and <a href='http://faculty.hust.edu.cn/liqiang15/zh_CN/index.htm'>Qiang Li</a>. Before that, I recieved my Bachelor Engineering degree at the HUST in 2022.

My research interests foucs on algorithms for Health Examination in Endoscopy images/videos, including segmentation, detection, classfication. Recently, I am exploring the  potential of visual-language models for endoscopy. If you are interested in my research, welcome to communicate with me!!!


<!-- # 🔥 News
- *2025.11*: &nbsp;🎉🎉 One paper ``PaGKD`` was accepted by AAAI 2026. Congratulations to the co-author Qimei Wang!
- *2025.05*: &nbsp;🎉🎉 Two papers ``ADD`` and ``DADA`` were ``early accepted`` by MICCAI 2025 (Top 9%). Congratulations to Qimei Wang and Gan Luo!
- *2024.12*: &nbsp;🎉🎉 One paper ``PSDNet`` was accepted by ICASSP 2025!
- *2024.12*: &nbsp;🎉🎉 One paper ``MonoBox`` was accepted by AAAI 2025!
- *2024.10*: &nbsp;🎉🎉 One paper was accepted by JBHI. Congratulations to Fang Peng!
- *2024.09*: &nbsp;🎉🎉 I won the ``National Scholarship for Master Students`` (HUST).
- *2024.09*: &nbsp;🎉🎉 Our paper ``SALI`` was invited as an ``Oral presentation`` (<3%) in MICCAI 2024. 
- *2024.06*: &nbsp;🎉🎉 One paper ``SALI`` was accepted by MICCAI 2024. Congratulations to the co-author Zhenyu Yi! -->


<style>
/* 定义滚动窗口的样式 */
.news-scroll {
    max-height: 280px;         /* 控制窗口的最大高度，你可以根据需要调整 */
    overflow-y: auto;          /* 当内容超出高度时自动显示垂直滚动条 */
    padding: 10px 15px;        /* 内部四周留白，让文字不贴边 */
    margin-bottom: 20px;       /* 与下方内容的间距 */
    border: 1px solid #eaecef; /* 添加一个浅灰色的边框，符合现有风格 */
    border-radius: 6px;        /* 边框加上微微的圆角，更现代美观 */
    background-color: transparent; 
}

/* 进一步美化滚动条，使其更符合极简风格 (适用于 Chrome, Edge, Safari) */
.news-scroll::-webkit-scrollbar {
    width: 6px;                /* 滚动条变细 */
}
.news-scroll::-webkit-scrollbar-track {
    background: transparent;   /* 轨道背景透明 */
}
.news-scroll::-webkit-scrollbar-thumb {
    background-color: #d1d5da; /* 滚动条的滑块颜色 */
    border-radius: 4px;        /* 滑块圆角 */
}
.news-scroll::-webkit-scrollbar-thumb:hover {
    background-color: #959da5; /* 鼠标悬停在滑块上时颜色加深 */
}
</style>

# 🔥 News
<div class="news-scroll" markdown="1">

- *2026.03*: &nbsp;🎉🎉 One paper was accepted by ICME. Congratulations to Hao Wang!
- *2026.02*: &nbsp;🎉🎉 One paper ``SAMIX`` was accepted by CVPR 2026. Congratulations to all co-authors!
- *2025.11*: &nbsp;🎉🎉 One paper ``PaGKD`` was accepted by AAAI 2026. Congratulations to the co-author Qimei Wang!
- *2025.05*: &nbsp;🎉🎉 Two papers ``ADD`` and ``DADA`` were ``early accepted`` by MICCAI 2025 (Top 9%). Congratulations to Qimei Wang and Gan Luo!
- *2024.12*: &nbsp;🎉🎉 One paper ``PSDNet`` was accepted by ICASSP 2025!
- *2024.12*: &nbsp;🎉🎉 One paper ``MonoBox`` was accepted by AAAI 2025!
- *2024.10*: &nbsp;🎉🎉 One paper was accepted by JBHI. Congratulations to Fang Peng!
- *2024.09*: &nbsp;🎉🎉 I won the ``National Scholarship for Master Students`` (HUST).
- *2024.09*: &nbsp;🎉🎉 Our paper ``SALI`` was invited as an ``Oral presentation`` (<3%) in MICCAI 2024. 
- *2024.06*: &nbsp;🎉🎉 One paper ``SALI`` was accepted by MICCAI 2024. Congratulations to the co-author Zhenyu Yi!

</div>


# 📝 Publications 
### (Note: <span style="color:#0D6EFD">&#42;</span>: Co-first author, <span style="color:#FFA500">&#8224;</span>: Corresponding author)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 </div><img src='images/SAMIX.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SAMIX: Reinforcing SAM2 with Semantic Adapter and Reference Selecting Policy for Mix-Supervised Segmentation]()

**Qiang Hu**, Jiajie Wei, Zhenyu Yi, Zhifen Yan, Yingjie Guo, Hongkuan Shi, Ge-Peng Ji, Qiang Li, and Zhiwei Wang<span style="color:#FFA500">&#8224;</span>;

[**Code**]()
[**Paper**]()
- SAMIX is a RL-empowered in-context segmenter comprising two core components: SA-SAM2 and SPNet. SA-SAM2 leverages a lightweight semantic adapter to transform the vanilla SAM2 into an in-context segmenter, enabling cross-image semantic tracking capabilities. Meanwhile, SPNet is trained via GRPO with customized verifiable rewards to retrieve valuable visual contexts from a data pool for the query image, effectively empowering SA-SAM2.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 </div><img src='images/PaGKD-500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pairing-free Group-level Knowledge Distillation for Robust Gastrointestinal Lesion Classification in White-Light Endoscopy](https://arxiv.org/abs/2601.09209)

**Qiang Hu**<span style="color:#0D6EFD">&#42;</span>, Qimei Wang<span style="color:#0D6EFD">&#42;</span>, Yingjie Guo, Qiang Li, and Zhiwei Wang<span style="color:#FFA500">&#8224;</span>;

[**Code**](https://github.com/Huster-Hq/PaGKD)
[**Paper**](https://arxiv.org/abs/2601.09209)
- PaGKD proposes the Group-level Distillation strategy, achieving reliable knowledge transfer between unpaired cross-modal data, i.e., from Narrow-Band Imaging (NBI, the dominant modality) to White-Light Imaging (WLI), and improving the gastrointestinal lesions diagnostic performance in WLI domain.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 </div><img src='images/MonoBox-500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MonoBox: Tightness-free Box-supervised Polyp Segmentation using Monotonicity Constraint](https://arxiv.org/abs/2404.01188)

**Qiang Hu**, Zhenyu Yi, Ying Zhou, Fan Huang, Mei Liu, Qiang Li, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

[**Code**](https://github.com/Huster-Hq/MonoBox)
[**Paper**](https://arxiv.org/abs/2404.01188)
- MonoBox proposes a novel monotonicity constraint to liberate the training of existing MIL-based box-supervised segmentation methods from the user-unfriendly box-tightness assumption. It is plug-and-play and can improve the tolerance of any MIL-based box-supervised segmentation methods (e.g., BoxInst, BoxLevelSet, IBoxCLA, etc.) to tightness-free box annotations in any scenarios (e.g., common, medical, etc.).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025 <span style="color:red">(Early Accept)</span></div><img src='images/ADD-500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Holistic White-light Polyp Classification via Alignment-free Dense Distillation of Auxiliary Optical Chromoendoscopy](https://arxiv.org/abs/2505.19319)

**Qiang Hu**<span style="color:#0D6EFD">&#42;</span>, Qimei Wang<span style="color:#0D6EFD">&#42;</span>, Jia Chen, Xuantao Ji, Mei Liu, Qiang Li<span style="color:#FFA500">&#8224;</span>, and Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

[**Code**](https://github.com/Huster-Hq/ADD)
[**Paper**](https://arxiv.org/abs/2505.19319)
- We propose a novel holistic WLI polyp classification framework, which mainly prpose a novel module, Alignment-free Dense Distillation (ADD), to leverage NBI knowledge to assist holistic WLI polyp classifier without requiring geometric priors (e.g., polyp locations).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025 </div><img src='images/PSDNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[First-frame Supervised Video Polyp Segmentation via Propagative and Semantic Dual-teacher Network](https://arxiv.org/abs/2412.16503)

**Qiang Hu**, Mei Liu, Qiang Li, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

[**Code**](https://github.com/Huster-Hq/PSDNet)
[**Paper**](https://arxiv.org/abs/2412.16503)
- PSDNet greatly reduces the labeling costs of training video segmentation models, which require only one frame of annotation on each video, regardless of the length. It benefits from the existing powerful fundamental video segmentation models (e.g., XMem and SAM 2).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2024 <span style="color:red">(Oral)</span></div><img src='images/SALI-500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SALI: Short-Term Alignment and Long-Term Interaction Network for Colonoscopy Video Polyp Segmentation](https://link.springer.com/chapter/10.1007/978-3-031-72089-5_50)

**Qiang Hu**<span style="color:#0D6EFD">&#42;</span>, Zhenyu Yi<span style="color:#0D6EFD">&#42;</span>, Ying Zhou, Fang Peng, Mei Liu, Qiang Li<span style="color:#FFA500">&#8224;</span>, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

[**Code**](https://github.com/Scatteredrain/SALI)
[**Paper**](https://arxiv.org/abs/2406.13532)
- SALI, a hybrid of Short-term Alignment Module (SAM) and Long-term Interaction Module (LIM), achieves the SOTA performance on the SUN-SEG dataset (currently the largest video polyp segmentation dataset).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025 <span style="color:red">(Early Accept)</span></div><img src='images/DADA.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Targeted False Positive Synthesis via Detector-guided Adversarial Diffusion Attacker for Robust Polyp Detection](https://arxiv.org/abs/2506.18134)

Quan Zhou<span style="color:#0D6EFD">&#42;</span>, Gan Luo<span style="color:#0D6EFD">&#42;</span>, **Qiang Hu**<span style="color:#FFA500">&#8224;</span>, Qingyong Zhang, Yinjiao Tian, Qiang Li, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

[**Code**](https://github.com/Huster-Hq/DADA)
[**Paper**](https://arxiv.org/abs/2506.18134)
- To reduce false positive predictions of polyp detectors in clinical applications, we propose a novel image synthesis method, namely DADA, that integrates diffusion models with adversarial attacks, focusing on generating high-value negative samples capable of effectively misleading polyp detectors.
</div>
</div>


- ``JBHI 2024`` [Fine-Grained Temporal Site Monitoring in EGD Streams Via Visual Time-Aware Embedding and Vision-Text Asymmetric Coworking](https://ieeexplore.ieee.org/abstract/document/10738274), Fang Peng<span style="color:#0D6EFD">&#42;</span>, Hongkuan Shi<span style="color:#0D6EFD">&#42;</span>, Shiquan He<span style="color:#0D6EFD">&#42;</span>, **Qiang Hu**, Ting Li, Fan Huang, Xinxia Feng, Mei Liu, Jiazhi Liao, Qiang Li<span style="color:#FFA500">&#8224;</span>, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

- ``ICME 2026`` [Moving Light Adaptive Colonoscopy Reconstruction via Illumination-Attenuation-Aware 3D Gaussian Splatting](), Hao Wang<span style="color:#0D6EFD">&#42;</span>, Ying Zhou<span style="color:#0D6EFD">&#42;</span>, Haoyu Zhao, Rui Wang, **Qiang Hu**, Xin Zhang, Qiang Li, Zhiwei Wang<span style="color:#FFA500">&#8224;</span>

# 🎖 Honors and Awards
- *2024.9* National Scholarship (Highest Scholarship from the Ministry of Education of China).

# 📖 Educations
- *2025.09 - (now)*, Ph.D. candidate, Huazhong University of Science and Technology (HUST), Wuhan.
- *2022.09 - 2025.06*, Master, Huazhong University of Science and Technology (HUST), Wuhan.
- *2018.09 - 2022.06*, Undergraduate, Huazhong University of Science and Technology (HUST), Wuhan.

# 💬 Invited Talks

# 💻 Internships

