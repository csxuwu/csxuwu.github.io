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

I am working towards a Ph.D. degree in Computer Vision Insitute, SZU, under the supervision of Prof.[Zhihui Lai](https://scholar.google.com/citations?hl=zh-CN&user=CkK6ULsAAAAJ). I have published several papers in journals/conferences, including Chinese Journal of Computers, Chinese Journal of Electronics, IEEE Transactions
on Emerging Topics in Computational Intelligence, etc.. I serve as a reviewer of journals, e.g., IEEE Transactions
on Emerging Topics in Computational Intelligence, International Journal of Machine Learning and Cybernetics, and IEEE/CAA Journal of Automatica Sinica. 
My research interests include contrastive learning, image processing, low-light image enhancment, low-light image semantic segmantation. My curriculum vitae can be found at [here](./CV_wuxu.pdf).


# 🔥 News
- *2023.02*: &nbsp;🎉🎉 Invited as a visiting student for University of Alberta.
- *2022.12*: &nbsp; One paper is submmitted to the IJCAI2023.
- *2022.12*: &nbsp;🎉🎉 2nd Prize, Award on China Post-Graduate Mathematic Contest in Modeling.
- *2021.09*: &nbsp;🎉🎉 **I join Computer Vision Insitute, SZU to pursue the Ph.D. degree under the supervision of Zhihui Lai!**

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Chinese Journal of Computers</div><img src='images/MR_VAE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Multi-Reconstruciton Variational AutoEncoder for Low-light Image Enhancement](https://kns.cnki.net/kcms2/article/abstract?v=3uoqIhG8C44YLTlOAiTRKibYlV5Vjs7i8oRR1PAr7RxjuAJk4dHXos_BuYfGFXVpmBdnj0gpB6SeN-FNUbuzCTM22HnKm5Mc&uniplatform=NZKPT)

Zetao Jiang, **Xu Wu**, Shaoqin Zhang
  
- Aiming at the low brightness, multi-noise, and blur of low illumination images, we propose Multiple Reconstruction-Variational AutoEncoder (MR-VAE) to gradually denoise and produce high-quality low illumination enhanced images from coarse to fine. MR-VAE consists of three modules: feature probability distribution capture, global reconstruction, and detail reconstruction. The core idea is to reconstruct the global features and local features in stages, and the global reconstruction module constructs the global features of the image and initially enhances the low illumination, to get a coarser image; the detail reconstruction module produces images with more realistic details, less noise, and more appropriate brightness based on the coarse image; In addition, this paper defines a multiple loss function replacement loss to guide the network to generate high-quality images. [**Code**](https://github.com/csxuwu/MR-VAE)
</div>
</div>



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCVW 2022</div><img src='images/demix.png' alt="sym" width="100%"></div></div>
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
 -->

### Selected Publication List

- Zetao Jiang, **Xu Wu**, Shaoqin Zhang, “Low-illumination Image Enhancement Based on MR-VAE”. Chinese Journal of Computers (计算机学报), 2020,43(07):1328-1339.
- Zetao Jiang, Yi Qian, **Xu Wu**, Shaoqin Zhang. “Low-light Image Enhancement Method Based on ARDGAN” Chinese Journal of Electronics (电子学报), 2021,49(11):2160-2165.
- **Xu Wu**, Zhihui Lai, Shiqi Yu, Jie Zhou, Zhuoqian Liang, Linlin Shen. “Coarse-to-Fine Low-light Image Enhancement with Light Restoration and Color Refinement”, IEEE Transactions on Emerging Topics in Computational Intelligence. Major revision.
- **Xu Wu**, Zhihui Lai, Xianxu Hou, Jiajun Wen, Linlin Shen. “Illumination Calibration and Scale-Aware Feature Learning for Low-light Image Enhancement”, IEEE Transactions on Industrial Informatics. Under review.
- 


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

# 💻 Professional Service

### Journals Reviewer 
- IEEE Transactions on Emerging Topics in Computational Intelligence
- International Journal of Machine Learning and Cybernetics
- IEEE/CAA Journal of Automatica Sinica. 

