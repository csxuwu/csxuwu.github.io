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
My research interests include contrastive learning, image processing (low-light image enhancement, medical image enhancement), and low-light image semantic segmentation. My curriculum vitae can be found at [here](./CV_wuxu.pdf).


# 🔥 News
- *2024.04*: &nbsp; Visiting Ph.D. student at Nanyang Technological University (NTU).
- *2023.10*: &nbsp; Excellent PhD Funding (**Rate<5%**)
- *2023.08*: &nbsp; One paper is accepted to the TETCI.
<!-- - *2023.04*: &nbsp; One paper is accepted to the IJCNN 2023. !-->
<!-- - *2023.02*: &nbsp;🎉🎉 Invited as a visiting student for the University of Alberta.!-->
- *2022.12*: &nbsp;🎉🎉 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling.
- *2021.11*: &nbsp; Excellent PhD Funding (**Rate<5%**)
- *2021.09*: &nbsp;🎉🎉 **I joined Computer Vision Insitute, SZU to pursue the Ph.D. degree under the supervision of Zhihui Lai!**

# 📝 Publications 
<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/MR_VAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CodeEnhance: A Codebook-Driven Approach for Low-Light Image Enhancement

Xu Wu, XianXu Hou, Zhihui Lai$^{*}$, Jie Zhou, Ya-nan Zhang, Witold Pedrycz, Linlin Shen
  
- Low-light image enhancement (LLIE) aims to improve low-illumination images. However, existing methods face two challenges: (1) uncertainty in restoration from diverse brightness degradations; (2) loss of texture and color information caused by noise suppression and light enhancement. In this paper, we propose a novel enhancement approach, CodeEnhance, by leveraging quantized priors and image refinement to address these challenges. In particular, we reframe LLIE as learning an \textbf{image-to-code} mapping from low-light images to discrete codebook, which has been learned from high-quality images. To enhance this process, a Semantic Embedding Module (SEM) is introduced to integrate semantic information with low-level features, and a Codebook Shift (CS) mechanism, designed to adapt the pre-learned codebook to better suit the distinct characteristics of our low-light dataset. Additionally, we present an Interactive Feature Transformation (IFT) module to refine texture and color information during image reconstruction, allowing for interactive enhancement based on user preferences. Extensive experiments on both real-world and synthetic benchmarks demonstrate that the incorporation of prior knowledge and controllable information transfer significantly enhances LLIE performance in terms of quality and fidelity. The proposed CodeEnhance exhibits superior robustness to various degradations, including uneven illumination, noise, and color distortion.
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

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETCI</div><img src='images/LRCR2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Coarse-to-Fine Low-light Image Enhancement with Light Restoration and Color Refinement

**Xu Wu**, Zhihui Lai, Shiqi Yu, Jie Zhou, Zhuoqian Liang, Linlin Shen 
  
- Low-light image enhancement aims to improve the illumination intensity while restoring color information. Although recent deep learning-based methods have achieved impressive results, they still suffer from over or under-light enhancement in complex illumination scenes, and poor contrast and saturation recovery in dark regions. To address these drawbacks, we propose a novel pipeline (called LRCR-Net) to perform Light Restoration and Color Refinement in a coarse-to-fine manner.
</div>
</div>

<!-- -------------------------------------------------------- !-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII</div><img src='images/SCSF2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Illumination Calibration and Scale-Aware Feature Learning for Low-light Image Enhancement

**Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen 
  
- Low-light image enhancement has made significant progress with deep neural networks in recent years. A typical framework is to learn nonlinear image-to-image mappings from low-light images and the corresponding normal-light ones. However, these methods rarely consider the illumination relations between different regions and the diversity of regions in scale and shape, leading to over or under-enhancement in uneven illumination. To address these issues, we propose a novel low-light image enhancement model that learns illumination relations and multi-scale information.
</div>
</div>



### Selected Publication List

- Zetao Jiang, **Xu Wu**, Shaoqin Zhang, “Low-illumination Image Enhancement Based on MR-VAE”. Chinese Journal of Computers (计算机学报), 2020,43(07):1328-1339.
- Zetao Jiang, Yi Qian, **Xu Wu**, Shaoqin Zhang. “Low-light Image Enhancement Method Based on ARDGAN” Chinese Journal of Electronics (电子学报), 2021,49(11):2160-2165.
- **Xu Wu**, X. Wu, Z. Lai, S. Yu, J. Zhou, Z. Liang, and L. Shen, "Coarse-to-Fine Low-Light Image Enhancement With Light Restoration and Color Refinement," in IEEE Transactions on Emerging Topics in Computational Intelligence, doi: 10.1109/TETCI.2023.3314436.
- **Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen. “Illumination Calibration and Scale-Aware Feature Learning for Low-light Image Enhancement”, IEEE Transactions on Industrial Informatics. Under review.



# 🎖 Honors and Awards
- *2023* Excellent PhD Funding (**Rate<5%**)
- *2022* 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling (**Rate<0.02%**)
- *2021* Excellent PhD Funding (**Rate<5%**)
- *2021* Outstanding Master’s Degree Thesis Award (**Rate<0.05%**)
- *2020* China National Scholarship (**Rate<0.02%**)
- *2020* Excellent Academic Scholarship, First Class 
- *2018* Outstanding Graduate Award of Hunan Province (**Rate<0.02%**)
- *2018* Outstanding Graduate Award (**Rate<5%**)
- *2017* China National Scholarship (**Rate<0.02%**)
- *2017* Excellent Academic Scholarship, First Class 

# 📖 Research Experience

### Guangxi Key Laboratory of Image and Graphic Intelligent Processing, GUET
M.S. supervised by [Prof. Zetao Jiang](https://www.guet.edu.cn/people2/1130186.html)
- Proposed a multi-reconstruction variational autoencoder for low-light image enhancement, which is accepted by the Chinese Journal of Computers and open source.
- Proposed a variational autoencoder with attention and context encoding for low-light image enhancement.
- Proposed a multi-stage variational autoencoder for low-light image enhancement, which has been patented (Patent number: CN110163815B).
- Graduate Student Innovation Project of GUET. 

# 💻 Professional Service

### Journals/References Reviewer 
- IEEE Transactions on Emerging Topics in Computational Intelligence
- International Journal of Machine Learning and Cybernetics
- IEEE/CAA Journal of Automatica Sinica. 
- IJCNN2024

