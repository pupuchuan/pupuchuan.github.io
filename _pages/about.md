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

I received my Ph.D. training at the  <a href="https://www.smu.edu.cn/english/">Southern Medical University (SMU)</a> under the supervision of Prof.  <a href="https://scholar.google.com/citations?user=Br-t_8cAAAAJ&hl">Wei Yang </a> , and was also a visiting Ph.D. student at the <a href="https://www.nus.edu.sg/">National University of Singapore</a> supervised by Prof. <a href="https://yuemingjin.github.io/">Yueming Jin</a>. My research interests include medical image synthesis, medical image segmentation, and prognosis analysis. My work has been published in leading conferences and journals in medical image analysis, including MedIA, TMI, CVPR, MICCAI and ISBI.

<span class='anchor' id='publications'></span>

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2026</div><img src='images/MICCAI2026.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Physics-driven Cold Diffusion with Severity-aware Sampling and Adaptive Degradation Estimation for MRI Motion Artifact Removal

**Chuanpu Li**, Jinlong Zhang, Yuan Yang, Yueming Jin, Wei Yang

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a physics-driven cold diffusion framework for MRI motion artifact removal, where the diffusion process is modeled as an acquisition-consistent k-space degradation rather than Gaussian noising.
- We introduce severity-aware sampling and adaptive degradation estimation to guide deterministic restoration across diverse motion patterns and artifact levels.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2025</div><img src='images/MICCAI2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Boosting Medical Image Synthesis via Registration-guided Consistency and Disentanglement Learning

**Chuanpu Li∗**, Zeli Chen∗, Yiwen Zhang, Liming Zhong, Wei Yang

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a registration-guided consistency framework for medical image synthesis, which enforces geometry-preserving synthesis by aligning the outputs of synthesis-before-registration and synthesis-after-registration branches.
- We introduce anatomy consistency disentanglement learning to separate anatomical content from modality-specific styles.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMI 2024</div><img src='images/TMI2024.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DoseDiff: Distance-aware Diffusion Model for Dose Prediction in Radiotherapy

Yiwen Zhang∗, **Chuanpu Li∗**, Liming Zhong, Zeli Chen, Wei Yang, Xuetao Wang

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose DoseDiff, a distance-aware conditional diffusion model for radiotherapy dose prediction, which leverages physical-space signed distance maps to capture spatial relationships between targets, OARs, and surrounding tissues.
- We design a multi-encoder and multi-scale fusion network to effectively integrate CT and distance-aware features, achieving superior dose prediction performance with improved visual quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMI 2023</div><img src='images/TMI2023.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Breath-Hold CBCT-Guided CBCT-to-CT Synthesis via Multimodal Unsupervised Representation Disentanglement Learning

Yiwen Zhang∗, **Chuanpu Li∗**, Zhenhui Dai, Liming Zhong, Xuetao Wang, Wei Yang

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We introduce breath-hold CBCT as training guidance and decompose breast CBCT-to-CT synthesis into motion artifact reduction and intensity correction, improving synthesis from free-breathing CBCT.
- We propose a multimodal unsupervised representation disentanglement framework to separate content, style, and artifact representations, preserving structural consistency while achieving superior synthetic CT quality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Cancer Imaging</div><img src='images/cancer imaging.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A deep learning model to enhance the classification of primary bone tumors based on incomplete multimodal images in X-ray, CT, and MRI

Liwen Song∗, **Chuanpu Li∗**, Lilian Tan∗, Menghong Wang, Xiaqing Chen, Qiang Ye, Shisi Li, Rui Zhang, Qinghai Zeng, Zhuoyao Xie, Wei Yang, Yinghua Zhao

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a Transformer-based fusion model to classify primary bone tumors using incomplete multimodal images from X-ray, CT, and MRI, enabling robust diagnosis when certain imaging modalities are missing in real-world clinical scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISBI 2022</div><img src='images/ISBI2022.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

SPA-ResUnet: Strip Pooling Attention ResUnet for Multi-class Segmentation of Vertebrae and intervertebral Discs

**Chuanpu Li**, Tianbao Liu, Zeli Chen, Shumao Pang, Liming Zhong, Qianjin Feng, Wei Yang

# <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose SPA-ResUNet, a strip-pooling attention based residual U-Net for multi-class segmentation of vertebrae and intervertebral discs, effectively capturing long-range spinal dependencies and improving segmentation of challenging top structures and the sacral crest.
</div>
</div>

# 🎖 Honors and Awards
- *2023.10* I won the dual-track championship in the SynthRAD2023 Grand Challenge at MICCAI 2023, ranking 1st in both MRI-to-CT and CBCT-to-CT synthesis tracks.
- *2022.09* I won the championship in the INSTANCE 2022 Challenge at MICCAI 2022 for intracranial hemorrhage segmentation.
- *2019.11* I won the China National Scholarship for Undergraduate Students.

# 💻 Services
- PC for Conference:

  ECCV, MICCAI, ISBI
  
- PC for Journal:

  IEEE TMI/TNNLS/TMM
  KBS, ESWA, AIIM, CMIG, CMPB

# 📖 Educations
- *2025.08 - now*, Visiting PhD Student @ <a href="https://www.nus.edu.sg/">National University of Singapore</a>, supervised by Prof. <a href="https://yuemingjin.github.io/">Yueming Jin</a>
- *2023.09 - now*, PhD Student @ <a href="https://www.smu.edu.cn/english/">Southern Medical University</a>, supervised by Prof. <a href="https://scholar.google.com/citations?user=Br-t_8cAAAAJ&hl">Wei Yang</a>
- *2021.09 - 2023.08*, Master Student @ <a href="https://www.smu.edu.cn/english/">Southern Medical University</a>, supervised by Prof. <a href="https://scholar.google.com/citations?user=Br-t_8cAAAAJ&hl">Wei Yang</a>

