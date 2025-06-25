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

I am working towards a Ph.D. degree in Computer Vision Insitute, SZU, under the supervision of Prof. [Zhihui Lai](https://scholar.google.com/citations?hl=zh-CN&user=CkK6ULsAAAAJ). I have published several papers in journals/conferences, including the Chinese Journal of Computers, the Chinese Journal of Electronics, IEEE Transactions on Emerging Topics in Computational Intelligence, etc. I serve as a reviewer of journals, e.g., IEEE Transactions
on Emerging Topics in Computational Intelligence, International Journal of Machine Learning and Cybernetics, and IEEE/CAA Journal of Automatica Sinica. 
My research interests include contrastive learning, image processing (low-light image enhancement, medical image enhancement), and low-light image semantic segmentation. 
<!-- My curriculum vitae can be found at [here](./CV_wuxu.pdf).!-->


# 🔥 News
- *2025.06*: &nbsp; 🎉 One paper has been accepted to the Neural Network (NN, Q1, IF: 6.3).
- *2025.06*: &nbsp; 🎉 One paper has been accepted to the IEEE Transaction on Image Processing (TIP, Q1, IF: 11.3).
- *2025.05*: &nbsp; 🎉 One paper has been accepted to the Engineering Applications of Artificial Intelligence (EAAI, Q1, IF: 7.5).
- *2024.05*: &nbsp; 🎉 One paper has been accepted to the ACM Transactions on Multimedia Computing Communications and Applications (TOMM, Q1, IF: 5.2).
- *2024.04*: &nbsp; As a Visiting Ph.D. student at Nanyang Technological University (NTU) for one year.
- *2023.10*: &nbsp; Excellent PhD Funding (**Rate<5%**)
- *2023.08*: &nbsp; One paper has been accepted to the IEEE Transactions on Emerging Topics in Computational Intelligence (TETCI, Q1, IF: 5.7).
<!-- - *2023.04*: &nbsp; One paper is accepted to the IJCNN 2023. !-->
<!-- - *2023.02*: &nbsp;🎉🎉 Invited as a visiting student for the University of Alberta.!-->
- *2022.12*: &nbsp;🎉🎉 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling.
- *2021.11*: &nbsp; Excellent PhD Funding (**Rate<5%**)
- *2021.09*: &nbsp;🎉🎉 **I joined Computer Vision Insitute, SZU to pursue the Ph.D. degree under the supervision of Zhihui Lai!**

# 📝 Publications 
<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI</div><img src='images/CodeEnhance.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CodeEnhance: A Codebook-Driven Approach for Low-Light Image Enhancement](http://arxiv.org/abs/2404.05253)

Xu Wu, XianXu Hou, Zhihui Lai$^{*}$, Jie Zhou, Ya-nan Zhang, Witold Pedrycz, Linlin Shen
  
- Low-light image enhancement (LLIE) aims to improve low-illumination images. However, existing methods face two challenges: (1) uncertainty in restoration from diverse brightness degradations; (2) loss of texture and color information caused by noise suppression and light enhancement. In this paper, we propose a novel enhancement approach, CodeEnhance, by leveraging quantized priors and image refinement to address these challenges. 
</div>
</div>

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETCI</div><img src='images/LRCR_Net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Coarse-to-Fine Low-light Image Enhancement with Light Restoration and Color Refinement

**Xu Wu**, Zhihui Lai, Shiqi Yu, Jie Zhou, Zhuoqian Liang, Linlin Shen 
  
- Low-light image enhancement aims to improve the illumination intensity while restoring color information. Although recent deep learning-based methods have achieved impressive results, they still suffer from over or under-light enhancement in complex illumination scenes and poor contrast and saturation recovery in dark regions. To address these drawbacks, we propose a novel pipeline (called LRCR-Net) to perform Light Restoration and Color Refinement in a coarse-to-fine manner.
</div>
</div>

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOMM</div><img src='images/LACR_VAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Light-Aware Contrastive Learning for Low-light Image Enhancement

**Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen 
  
- Low-light image Enhancement (LLIE) presents challenges due to texture information loss and uneven illumination, which can distort feature distribution and reduce the quality of the enhanced images. However, current deep learning methods for LLIE only use supervised information from clear images to extract low-light image features, while disregarding the negative information in low-light images (i.e., low illumination and noise). To address these challenges, we propose a novel LLIE method, LACR-VAE, by leveraging the negative information and considering the uneven illumination..
</div>
</div>

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Chinese Journal of Computers</div><img src='images/MR_VAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multi-Reconstruction Variational AutoEncoder for Low-light Image Enhancement](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7i8oRR1PAr7RxjuAJk4dHXos_BuYfGFXVpmBdnj0gpB6SeN-FNUbuzCTM22HnKm5Mc&uniplatform=NZKPT)

Zetao Jiang, **Xu Wu**, Shaoqin Zhang
  
- Aiming at the low brightness, multi-noise, and blur of low illumination images, we propose Multiple Reconstruction-Variational AutoEncoder (MR-VAE) to gradually denoise and produce high-quality low illumination enhanced images from coarse to fine. MR-VAE consists of three modules: feature probability distribution capture, global reconstruction, and detail reconstruction. The core idea is to reconstruct the global features and local features in stages, and the global reconstruction module constructs the global features of the image and initially enhances the low illumination, to get a coarser image; the detail reconstruction module produces images with more realistic details, less noise, and more appropriate brightness based on the coarse image; In addition, this paper defines a multiple loss function replacement loss to guide the network to generate high-quality images. [**Code**](https://github.com/csxuwu/MR-VAE)
</div>
</div>

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/ACEVAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Variational Autoencoder with Attention and Context Encoding for Low-light Image Enhancement

Zetao Jiang, **Xu Wu**, Rushi Lan, Zhuoqian Liang, Zhihui Lai
  
- The low-illumination image enhancement is a challenging task because color restoration, denoising, and light enhancement should all be taken into account. However, most previous works focus on light enhancement, which makes it difficult to generate high-quality enhanced images. To address this dilemma, a novel deep probabilistic framework that integrates both attention mechanism and context encoding into a unique variational autoencoder (ACE-VAE) is proposed.
</div>
</div>


### Selected Publication List
- Wencai Zhu, Zetao Jiang, **Xu Wu**. Key Features-Guided Multi-view Collaborative Network for Image Captioning[J]. Neural Network. 2025.
- Yanan Zhang, Qiufu Li, **Xu Wu**, Linlin Shen. A Wavelet-guided Deep Unfolding Network for Single Image Reflection Removal[J]. IEEE Transactions on Image Processing. 2025.
- **Xu Wu**, Xianxu Hou, Lai Zhihui, Jie Zhou, Witold Pedrycz, Linlin Shen. A Codebook-Driven Approach for Low-Light Image Enhancement[J]. Engineering Applications of Artificial Intelligence. 2025.
- **Xu Wu**, Z. Lai, Z. Jie, C. Gao, X. Hou, Y. N. Zhang, & L. Shen. "Low-Light Enhancement Effect on Classification and Detection: An Empirical Study". arXiv preprint arXiv:2409.14461, 2024.
- **Xu Wu**, Z. Lai, Z. Zhou,  et al, "Light-Aware Contrastive Learning for Low-light Image Enhancement," in ACM Transactions on Multimedia Computing Communications and Applications. 2024. (CCF B)
- **Xu Wu**, X. Hou, Z. Lai, et al, "CodeEnhance: A Codebook-Driven Approach for Low-Light Image Enhancement". arXiv preprint arXiv:2404.05253, 2024.
- **Xu Wu**, Z. Lai, S. Yu, J. Zhou, Z. Liang, and L. Shen, "Coarse-to-Fine Low-Light Image Enhancement With Light Restoration and Color Refinement," in IEEE Transactions on Emerging Topics in Computational Intelligence, doi: 10.1109/TETCI.2023.3314436.
- Zetao Jiang, **Xu Wu**, Shaoqin Zhang, “Low-illumination Image Enhancement Based on MR-VAE”. Chinese Journal of Computers (计算机学报), 2020,43(07):1328-1339.
- Zetao Jiang, Yi Qian, **Xu Wu**, Shaoqin Zhang. “Low-light Image Enhancement Method Based on ARDGAN” Chinese Journal of Electronics (电子学报), 2021,49(11):2160-2165.


# 🎖 Honors and Awards
- *2023* Excellent PhD Funding (**Rate<5%**)
- *2022* 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling (**Rate<0.02%**)
- *2021* Excellent PhD Funding (**Rate<5%**)
- *2021* Outstanding Master’s Degree Thesis Award (**Rate<0.05%**)
- *2020* National Scholarship, Ministry of Education, China (**Rate<0.02%**)
- *2020* Excellent Academic Scholarship, First Class 
- *2018* Outstanding Graduate Award of Hunan Province (**Rate<0.02%**)
- *2018* Outstanding Graduate Award (**Rate<5%**)
- *2017* National Scholarship, Ministry of Education, China (**Rate<0.02%**)
- *2017* Excellent Academic Scholarship, First Class 

# 📖 Research Experience

### Guangxi Key Laboratory of Image and Graphic Intelligent Processing, GUET
M.S. supervised by [Prof. Zetao Jiang](https://www.guet.edu.cn/people2/1130186.html)
- Proposed a multi-reconstruction variational autoencoder for low-light image enhancement, accepted by the Chinese Journal of Computers and open source.
- Proposed a variational autoencoder with attention and context encoding for low-light image enhancement.
- Proposed a multi-stage variational autoencoder for low-light image enhancement, which has been patented (Patent number: CN110163815B).
- Graduate Student Innovation Project of GUET. 

# 💻 Professional Service

### Journals/References Reviewer 
- IEEE Transactions on Multimedia
- IEEE Transactions on Emerging Topics in Computational Intelligence
- Neural Network
- Expert Systems with Applications
- Neurocomputing
- International Journal of Machine Learning and Cybernetics
- IEEE/CAA Journal of Automatica Sinica. 
- IJCNN 
- NeurIPS 

