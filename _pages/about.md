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

I am working towards a Ph.D. degree in AI Initiative, KAUST, under the supervision of Prof.[Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en). I have published several papers in top-tier journals/conferences, including CVPR, ICCV, ECCV, AAAI, MICCAI, IEEE Trans on Image Processing, etc.. I serve as a reviewer of top-tier conferences, e.g., CVPR'2023,  CVPR'2022, ICML'2022, ECCV'2022, and MICCAI'2022. 
Previously, I interned at Jarvis Lab, Tencent, and was a visiting student at NBL, NTNU. My research interests include regularization, self-supervised learning, adversarial learning, and reinforcement learning. My curriculum vitae can be found at [here](./haozheliu.pdf).


# 🔥 News
- *2023.02*: &nbsp;🎉🎉 Two papers are accepted by CVPR'2023!.
- *2023.02*: &nbsp; Invited as a reviewer for ICCV'2023.
- *2022.11*: &nbsp;🎉🎉 One paper is accepted by AAAI'2023 (Oral).
- *2022.11*: &nbsp; Invited as a reviewer for CVPR'2023.
- *2022.08*: &nbsp;🎉🎉 **I join AI Initiative, KAUST to pursue the Ph.D. degree under the supervision of Juergen Schmidhuber!**
- *2022.08*: &nbsp;🎉 Our team reaches to the 4th/40 in [NICO challenge](https://nicochallenge.com/) (Invited Workshop Paper in ECCV'2022).
- *2022.07*: &nbsp;🎉 One paper is accepted by ECCV'2022! 
- *2022.06*: &nbsp;🎉 Two papers are accepted by MICCAI'2022!
- *2022.05*: &nbsp;[Our method (Group-wise Inhibition)](https://github.com/LinusWu/TENET_Training) is merged into the official benchmark of [ImageNet-C](https://github.com/hendrycks/robustness)!  
- *2022.04*: &nbsp; Invited as a reviewer for ICML'2022, ECCV'2022 and MICCAI'2022.  
- *2021.10*: &nbsp; Invited as a reviewer for CVPR'2022.
- *2021.07*: &nbsp;🎉 One paper is accepted by ICCV'2021!

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023 (Oral)</div><img src='images/gan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Combating Mode Collapse in GANs via Manifold Entropy Estimation](https://arxiv.org/pdf/2208.12055.pdf)

**Liu, H.**, Li, B., Wu, H., Liang, H., Huang, Y., Li, Y., ... & Zheng, Y.
  
- In this paper, we propose a novel training pipeline to address the mode collapse issue of GANs. Different from existing methods, we propose to generalize the discriminator as feature embedding and maximize the entropy of distributions in the embedding space learned by the discriminator. [**Project Page**](https://haozheliu-st.github.io/MEE/) [**Code**](https://github.com/HaozheLiu-ST/MEE)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCVW 2022</div><img src='images/demix.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Decoupled Mixup for Out-of-Distribution Visual Recognition.](https://arxiv.org/pdf/2210.14783.pdf)

**Liu, H.**, Zhang, W., Xie J., Wu, H., Li, B., Zhang, Z., Li, Y., Huang, Y., Ghanem, B., Y. Zheng.
  
- We propose a novel ”Decoupled-Mixup” method to train CNN models for OOD visual recognition. Different from previous work combining pairs of images homogeneously, our method decouples each image into discriminative and noise-prone regions, and then heterogeneously combine these regions of image pairs to train CNN models. [**Code**](https://github.com/HaozheLiu-ST/NICOChallenge-OOD-Classification)  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/pad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Effective Presentation Attack Detection Driven by Face Related Task](https://link.springer.com/chapter/10.1007/978-3-031-20065-6_24)

Zhang, W.\*, **Liu, H.**\*, Liu, F., Ramachandra, R., & Busch, C. (**\* Equal Contribution**)
  
- Unlike this specific PAD task, other face related tasks trained by huge amount of real faces (e.g. face recognition and attribute editing) can be effectively adopted into different application scenarios. Inspired by this, we propose to trade position of PAD and face related work in a face system and apply the free acquired prior knowledge from face related tasks to solve face PAD, so as to improve the generalization ability in detecting PAs. [**Project Page**](https://wentianzhang-ml.github.io/pad/) [**Code**](https://github.com/WentianZhang-ML/FRT-PAD)  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/pbc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Point Beyond Class: A Benchmark for Weakly Semi-Supervised Abnormality Localization in Chest X-Rays](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_24)

Ji, H.\*, **Liu, H.**\*, Li, Y.\*, Xie J., He, N., Huang, Y., Dong, W., Chen, X., Shen L. & Zheng, Y. (**\* Equal Contribution**)
 
- We propose to train the CXR abnormality localization framework via a weakly semi-supervised strategy, termed Point Beyond Class (PBC), which utilizes a small number of fully annotated CXRs with lesion-level bounding boxes and extensive weakly annotated samples by points. Such a point annotation setting can provide weakly instance-level information for abnormality localization with a marginal annotation cost. [**Code**](https://github.com/HaozheLiu-ST/Point-Beyond-Class)   
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/group.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Group-wise Inhibition based Feature Regularization for Robust Classification](https://openaccess.thecvf.com/content/ICCV2021/html/Liu_Group-Wise_Inhibition_Based_Feature_Regularization_for_Robust_Classification_ICCV_2021_paper.html)

**Liu, H.**, Wu, H., Xie, W., Liu, F., & Shen, L.

- CNN pays more attention to the most discriminative regions, but ignores the auxiliary features when learning, leading to the lack of feature diversity for final judgment. In our method, we propose to dynamically suppress significant activation values of CNN by group-wise inhibition, but not fixedly or randomly handle them when training. The feature maps with different activation distribution are then processed separately to take the feature independence into account. CNN is finally guided to learn richer discriminative features hierarchically for robust classification according to the proposed regularization. [**Code**](https://github.com/LinusWu/TENET_Training) 
</div>
</div>


### Selected Publication List

- **Liu, H.**, Li, B., Wu, H., Liang, H., Huang, Y., Li, Y., ... & Zheng, Y. Combating Mode Collapse in GANs via Manifold Entropy Estimation.  _AAAI'2023 Oral_.

- **Liu, H.**, Ji, H., Li, Y., He, N., Wu, H., Liu, F., Shen, L. & Zheng, Y. (2022). Robust Representation via Dynamic Feature Aggregation. _Arxiv Preprint_

- **Liu, H.**, Zhang, W., Xie J., Wu, H., Li, B., Zhang, Z., Li, Y., Huang, Y., Ghanem, B., Y. Zheng. Decoupled Mixup for Out-of-Distribution Visual Recognition. _ECCV'2022 Workshop_ 

- Ji, H.\*, **Liu, H.**\*, Li, Y.\*, Xie J., He, N., Huang, Y., Dong, W., Chen, X., Shen L. & Zheng, Y. Point Beyond Class: A Benchmark for Weakly Semi-Supervised Abnormality Localization in Chest X-Rays.  _MICCAI'2022_. (**\* Equal Contribution**)

- Zhang, W.\*, **Liu, H.**\*, Liu, F., Ramachandra, R., & Busch, C. Effective Presentation Attack Detection Driven by Face Related Task. _ECCV'2022_ (**\* Equal Contribution**)

- **Liu, H.**, Wu, H., Xie, W., Liu, F., & Shen, L. Group-wise Inhibition based Feature Regularization for Robust Classification. _ICCV'2021_ 

- **Liu, H.**, Zhang, W., Liu, F., Wu, H.,& Shen, L. (2021). Fingerprint Presentation Attack Detector Using Global-Local Model. _IEEE T-CYB_.

- Liu, F., **Liu, H**., Zhang, W., Liu, G., & Shen, L. (2021). One-Class Fingerprint Presentation Attack Detection Using Auto-Encoder Network. _IEEE T-IP, 30, 2394-2407_.

# 🎖 Honors and Awards
- *2022* Outstanding Graduate Award (**Rate<5%**)
- *2021* China National Scholarship (**Rate<0.02%**)
- *2020* Excellent Academic Scholarship, First Class 
- *2019* Excellent Academic Scholarship, Second Class 
- *2018* National University Big Data Application Innovation Competition in Northwest, First Place

# 📖 Research Experience

### AI Initiative (KAUST) 
 PhD Candidate supervised by Prof. [Juergen Schmidhuber](https://scholar.google.com/citations?user=gLnCTgIAAAAJ&hl=en).

- Research Field includes Video based Decision System, especially focusing on the extraction of the subgoal in a trajectory.

---

### Jarvis Lab (Tencent) 
Internship supervised by Mentor: [Dr. Yawen Huang](https://yawen-hwang.github.io/), [Dr. Nanjun He](https://scholar.google.ch/citations?user=w3iS1G0AAAAJ&hl=en) & [Dr. Yuexiang Li](https://scholar.google.com/citations?user=WsKu4EMAAAAJ&hl=en) and Director: [Dr. Yefeng Zheng](https://scholar.google.ch/citations?user=vAIECxgAAAAJ&hl=en) 
  
- Proposed Dynamic Feature Aggregation to improve the robustness against adversarial attacks.

- Proposed offline entropy estimation to combat mode collapse, which is accepted **AAAI'2023**. (This project is cooperated with AI Initiative, KAUST.)  
- Proposed Point Beyond Class to reduce the annotation cost for medical object detection, which is accepted by **MICCAI'2022**.

- Participate to NICO Challenge (ECCV'2022 workshop), our team reach to 5th/40 in both tracks at Phase I, and 4th in Track 2 at Final Phase. 

---

### Norwegian Biometrics Laboratory (NTNU)
Visiting student supervised by  [Prof. Raghavendra Ramachandra](https://scholar.google.com/citations?user=OIYIrmIAAAAJ&hl=en) and [Prof. Christoph Busch](https://scholar.google.com/citations?user=qsopcXIAAAAJ&hl=en)

- Proposed a self-supervised learning based method for face and fingerprint presentation attack detection, which is accepted by **IEEE TNNLS**.
- Proposed a face presentation attack detector based on the taskonomy features, which is accepted by **ECCV'2022**.

---

### Computer Vision Insitute (SZU)
M.S. supervised by [Prof. Feng Liu](https://scholar.google.com/citations?hl=zh-CN&user=45uLWocAAAAJ) and [Prof. Linlin Shen](https://scholar.google.com/citations?hl=zh-CN&user=AZ_y9HgAAAAJ)
- Proposed a regularization method to imporve the robustness of CNN based models, which is accepted by **ICCV'2021** and open source.
- Proposed a Manifold-preserved GANs to mitigate the mode collapse and gradient exploding.
- Collected a famous presentation attack dataset based on OCT and **for the first time** established a one-class framework for OCT based PAD. This work is accepted by **IEEE TIP**
- Proposed a presentation attack detector using Global-Local model, which reaches over 90% in terms of TDR@FDR=1% on LivDet2017 **for the first time**. (Accepted by **IEEE TCYB**)

# 💻 Professional Service

### Conference Reviewer 
- CVPR: 2022, 2023
- ECCV: 2022
- ICCV: 2023
- ICML: 2022
- MICCAI: 2022
