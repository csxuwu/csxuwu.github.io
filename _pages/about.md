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

I am working towards a Ph.D. degree in Computer Vision Insitute, SZU, under the supervision of Prof.[Zhihui Lai](https://scholar.google.com/citations?hl=zh-CN&user=CkK6ULsAAAAJ). I have published several papers in journals/conferences, including Chinese Journal of Computers, Chinese Journal of Electronics, IEEE Transactions on Emerging Topics in Computational Intelligence, etc.. I serve as a reviewer of journals, e.g., IEEE Transactions
on Emerging Topics in Computational Intelligence, International Journal of Machine Learning and Cybernetics, and IEEE/CAA Journal of Automatica Sinica. 
My research interests include contrastive learning, image processing, low-light image enhancment, low-light image semantic segmantation. My curriculum vitae can be found at [here](./CV_wuxu.pdf).


# 🔥 News
- *2023.02*: &nbsp;🎉🎉 Invited as a visiting student for University of Alberta.
- *2022.12*: &nbsp; One paper is submmitted to the IJCAI2023.
- *2022.12*: &nbsp;🎉🎉 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling.
- *2021.11*: &nbsp; Received funding from the outstanding Ph.D. project.
- *2021.09*: &nbsp;🎉🎉 **I join Computer Vision Insitute, SZU to pursue the Ph.D. degree under the supervision of Zhihui Lai!**

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Chinese Journal of Computers</div><img src='images/MR_VAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multi-Reconstruciton Variational AutoEncoder for Low-light Image Enhancement](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7i8oRR1PAr7RxjuAJk4dHXos_BuYfGFXVpmBdnj0gpB6SeN-FNUbuzCTM22HnKm5Mc&uniplatform=NZKPT)

Zetao Jiang, **Xu Wu**, Shaoqin Zhang
  
- Aiming at the low brightness, multi-noise, and blur of low illumination images, we propose Multiple Reconstruction-Variational AutoEncoder (MR-VAE) to gradually denoise and produce high-quality low illumination enhanced images from coarse to fine. MR-VAE consists of three modules: feature probability distribution capture, global reconstruction, and detail reconstruction. The core idea is to reconstruct the global features and local features in stages, and the global reconstruction module constructs the global features of the image and initially enhances the low illumination, to get a coarser image; the detail reconstruction module produces images with more realistic details, less noise, and more appropriate brightness based on the coarse image; In addition, this paper defines a multiple loss function replacement loss to guide the network to generate high-quality images. [**Code**](https://github.com/csxuwu/MR-VAE)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/ACEVAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Variational Autoencoder with Attention and Context Encoding for Low-light Image Enhancement

Zetao Jiang, **Xu Wu**, Rushi Lan, Zhuoqian Liang, Zhihui Lai
  
- The low-illumination image enhancement is a challenging task because color restoration, denoising, and light enhancement should all be taken into accounts. However, most previous works focus on light enhancement, which is difficult to generate high quality enhanced images. To address this dilemma, a novel deep probabilistic framework that integrates both attention mechanism and context encoding into a unique variational autoencoder (ACE-VAE) is proposed.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TETCI</div><img src='images/LRCR2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Coarse-to-Fine Low-light Image Enhancement with Light Restoration and Color Refinement

**Xu Wu**, Zhihui Lai, Shiqi Yu, Jie Zhou, Zhuoqian Liang, Linlin Shen 
  
- Low-light image enhancement aims to improve the illumination intensity while restoring color information. Although recent deep learning-based methods have achieved impressive results, they still suffer from over or under light enhancement in complex illumination scenes, and poor contrast and saturation recovery in dark regions. To address these drawbacks, we propose a novel pipeline (called LRCR-Net) to perform Light Restoration and Color Refinement in a coarse-to-fine manner.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII</div><img src='images/SCSF2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Illumination Calibration and Scale-Aware Feature Learning for Low-light Image Enhancement

**Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen 
  
- Low-light image enhancement has made significant progress with deep neural networks in recent years. A typical framework is to learn nonlinear image-to-image mappings from low-light images and the corresponding normal light ones. However, these methods rarely consider the illumination relations between different regions and the diversity of regions in scale and shape, leading to over or under enhancement in uneven illumination. To address these issues, we propose a novel low-light image enhancement model that learns illumination relations and multi-scale information.
</div>
</div>



### Selected Publication List

- Zetao Jiang, **Xu Wu**, Shaoqin Zhang, “Low-illumination Image Enhancement Based on MR-VAE”. Chinese Journal of Computers (计算机学报), 2020,43(07):1328-1339.
- Zetao Jiang, Yi Qian, **Xu Wu**, Shaoqin Zhang. “Low-light Image Enhancement Method Based on ARDGAN” Chinese Journal of Electronics (电子学报), 2021,49(11):2160-2165.
- **Xu Wu**, Zhihui Lai, Shiqi Yu, Jie Zhou, Zhuoqian Liang, Linlin Shen. “Coarse-to-Fine Low-light Image Enhancement with Light Restoration and Color Refinement”, IEEE Transactions on Emerging Topics in Computational Intelligence. Major revision.
- **Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen. “Illumination Calibration and Scale-Aware Feature Learning for Low-light Image Enhancement”, IEEE Transactions on Industrial Informatics. Under review.



# 🎖 Honors and Awards
- *2022* 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling (**Rate<0.02%**)
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
- Proposed a multi-reconstruction variational autoencoder for low-light image enhancement, which is accepted by Chinese Journal of Computers and open source.
- Proposed a variational autoencoder with attention and vontext encoding for low-light image enhancement.
- Proposed a multi-stage variational autoencoder for low-light image enhancement, which has been patented (Patent number: CN110163815B).
- Graduate Student Innovation Project of GUET. 

# 💻 Professional Service

### Journals/References Reviewer 
- IEEE Transactions on Emerging Topics in Computational Intelligence
- International Journal of Machine Learning and Cybernetics
- IEEE/CAA Journal of Automatica Sinica. 
- MICCAI2023

