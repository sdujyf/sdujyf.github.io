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

Here is Yifan Jia.

I am a junior student studying in the School of Information Science and Engineering(Chongxin College), Shandong University in China,supervised by Prof. Zhi Liu. 
My primary research interest lies in the domain of Trustworthy AI and Multi-modal learning.

Specifically, I focus on CBM for explainable AI. My focus is on how CBM can be used to achieve the interpretability of effective AI systems. In addition, I am interested in multimodal learning, which includes the modal missing task and knowledge conflicts for multimodal large models.

Looking to the future, I am currently applying for the PHD/Mphil program of 26Fall. If you are interested in any aspect of me that I would like to chat about and collaborate with, please email me at sdujyf[at]mail.sdu.edu.cn

# 🔥 News 
- *2024.04.19*: &nbsp;🎉🎉 Our paper  has been accepted by 2024 5th International Conference on Computer Vision, Image and Deep Learning (CVIDL)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive H&E-IHC information fusion staining framework based on feature extractor](https://arxiv.org/pdf/2502.20156)

**Yifan Jia**, **Xingda Yu**, Zhengyang Jia, Songning Lai,Yutao Yue

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Immunohistochemistry (IHC) staining plays a significant role
in the evaluation of diseases such as breast cancer. The H&E-to-IHC
transformation based on generative models provides a simple and costeffective method for obtaining IHC images. Although previous models
can perform digital coloring well, they still suffer from (i) coloring only
through the pixel features that are not prominent in HE, which is easy
to cause information loss in the coloring process; (ii) The lack of pixelperfect H&E-IHC groundtruth pairs poses a challenge to the classical
L1 loss.To address the above challenges, we propose an adaptive information enhanced coloring framework based on feature extractors. We
first propose the VMFE module to effectively extract the color information features using multi-scale feature extraction and wavelet transform convolution, while combining the shared decoder for feature fusion. The high-performance dual feature extractor of H&E-IHC is trained
by contrastive learning, which can effectively perform feature alignment
of HE-IHC in high latitude space. At the same time, the trained feature encoder is used to enhance the features and adaptively adjust the
loss in the HE section staining process to solve the problems related
to unclear and asymmetric information.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/MIC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BioD2C: A Dual-level Semantic Consistency
Constraint Framework for Biomedical VQA](https://arxiv.org/pdf/2503.02476)

Zhengyang Ji,  Shang Gao, Li Liu,  Yifan Jia,Yutao Yue

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
Biomedical visual question answering (VQA) has been widely
studied and has demonstrated significant application value and potential
in fields such as assistive medical diagnosis. Despite their success, current
biomedical VQA models perform multimodal information interaction
only at the model level within large language models (LLMs), leading to
suboptimal multimodal semantic alignment when dealing with complex
tasks. To address this issue, we propose BioD2C: a novel
Dual-level Semantic Consistency Constraint Framework for Biomedical VQA, which
achieves dual-level semantic interaction alignment at both the model
and feature levels, enabling the model to adaptively learn visual features
based on the question. Specifically, we firstly integrate textual features
into visual features via an image-text fusion mechanism as feature-level
semantic interaction, obtaining visual features conditioned on the given
text; and then introduce a text-queue-based cross-modal soft semantic
loss function to further align the image semantics with the question semantics. Specifically, in this work, we establish a new dataset, BioVGQ,
to address inherent biases in prior datasets by filtering manually-altered
images and aligning question-answer pairs with multimodal context, and
train our model on this dataset. Extensive experimental results demonstrate that BioD2C achieves state-of-the-art (SOTA) performance across
multiple downstream datasets, showcasing its robustness, generalizability, and potential to advance biomedical VQA research. The source code
of this work and the BioVGQ dataset can be accessed through code and
dataset.

</div>
</div>


# 🎖 Honors and Awards
- *2023.09* Academic Scholarship from Shandong University 
- *2024.12* Third prize in the National Intelligent Car Competition
- *2023.4* National Third Prize in the Asia-Pacific Mathematical Modeling Competition
- *2024.7* Second prize of provincial level in mathematical Modeling Contest for college students

# 📖 Educations
- *2024.11 - now*,  HKUST(GZ) (Intern)
- *2022.09 - now*,Shandong University 
"


# 💻 Internships
- *2024.05 - 2025.02*,Initial Certification for the Taichu Yuanqi AI Competition.