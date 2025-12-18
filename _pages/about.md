---
permalink: /
title: "Greetings! 😆"
excerpt: "Homepage"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Welcome to my website!

I am a third-year PhD student in the Sun Yat-sen University's Master-Doctor combined program, supervised by [Guang Tan](https://scholar.google.com/citations?hl=zh-CN&user=JerZls4AAAAJ&view_op=list_works&sortby=pubdate) and [Chao Gou](https://scholar.google.com/citations?user=_0ad79AAAAAJ&hl=en). 

Since June 2024, I have been honored to be a visiting Ph.D at [MMLab](https://mmlab.ie.cuhk.edu.hk/people.html), CUHK, under the supervision of Prof. [Tianfan Xue](https://tianfan.info/).

My research interests center around 3D consistent video generation/world modeling, 3D generation/reconstruction, and 4D generation. I am open to collaboration and welcome further discussions if you are interested in my research.<br />


   
🔥 News 🔥
----- 
**∙** [2025.12] 🌟🌟 Our new work, ReCamDriving, is released! Check it out via [here](https://recamdriving.github.io/).<br />
**∙** [2025.10] 🌟🌟 Our new work, DynamicTree, is released! Check it out via [here](https://dynamictree-dev.github.io/DynamicTree.github.io/).<br />
**∙** [2025.10] 🎉🎉 One paper is accepted to PR 2025<br />
**∙** [2025.07] 🎉🎉 One paper is accepted to ICCV 2025<br />
**∙** [2024.12] 🎉🎉 One paper is accepted to AAAI 2025<br />
**∙** [2024.11] 🎉🎉 One paper is accepted to ESWA 2025<br />
**∙** [2023.11] 🎉🎉 One paper is accepted to IJCV 2024<br /> 

📑 Selected Publications 
-----
<style>
  .pub-item {
    display: flex;
    align-items: flex-start; /* 改为顶部对齐，防止图片被拉伸变形 */
    margin-bottom: 30px;
    background-color: transparent;
  }
  
  .pub-item img {
    margin-right: 20px;   /* 图片与文字的间距 */
    width: 220px;         /* 缩小图片宽度，使其高度更容易与简短的文字对齐 */
    height: auto;         /* 确保图片按比例缩放，不被裁剪或拉伸 */
    flex-shrink: 0;       /* 防止图片被 flex 容器挤压 */
    border-radius: 4px;
    object-fit: contain;  /* 确保内容完整 */
  }

  /* 右侧内容容器 */
  .pub-content {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  /* 论文标题：调小字体 */
  .pub-item h3 {
    margin-top: 0;
    margin-bottom: 5px;
    font-size: 1.0rem;    /* 与正文 H3 接近，或设为 1.05rem */
    line-height: 1.3;
  }
  
  /* 作者、期刊信息：调小字体，与上面 News 字体大小一致 */
  .pub-item p {
    line-height: 1.4;     /* 增加行高，让文字占据的空间稍微变大，匹配图片高度 */
    font-size: 0.85rem;   /* 这里的 0.85-0.9rem 通常是标准正文的大小 */
    margin: 0;
    color: #333;
  }

  /* 描述文字 */
  .pub-desc {
    margin-top: 5px !important;
    margin-bottom: 8px !important;
    color: #555;
    font-style: italic;
    font-size: 0.85rem !important; /* 保持一致的小号字体 */
    line-height: 1.4 !important;
  }

  /* 链接颜色 */
  .pub-content a {
    font-size: 0.85rem;
  }

  .pub-divider {
    border: none;
    border-top: 1px solid #eee;
    margin: 20px 0;
  }
</style>

<div class="pub-item">
  <img src="../images/paper_teasers/recamdriving.gif">
  <div class="pub-content">
    <h3>ReCamDriving: LiDAR-Free Camera-Controlled Novel Trajectory Video Generation</h3>
    <p>
      <strong><u>Yaokun Li</u></strong>, Shuaixian Wang, Mantang Guo, Jiehui Huang, Taojun Ding, Mu Hu, Kaixuan Wang, Shaijie Shen, Guang Tan<br>
      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We introduce ReCamDriving, a vision-only framework for camera-controlled video generation, and ParaDrive, a large-scale dataset comprising 110K parallel-trajectory video pairs.
    </p>
    <p>
      <a href="https://recamdriving.github.io/">Project</a> |
      <a href="https://arxiv.org/abs/2512.03621">Paper</a> |
      <a href="https://github.com/Iron-LYK/ReCamDriving">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="https://dinglihe.github.io/images/fullpart.png">
  <div class="pub-content">
    <h3>FullPart: Generating each 3D Part at Full Resolution</h3>
    <p>
      Lihe Ding*, Shaocong Dong*, <strong><u>Yaokun Li</u></strong>, Chenjian Gao, Xiao Chen, Rui Han, Yihao Kuang, Hong Zhang, Bo Huang, Zhanpeng Huang, Zibin Wang, Dan Xu†, Tianfan Xue†<br>
      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      Fullpart generates each 3d part at full resolution. We also present PartVerse-XL, the largest human annotated 3d part dataset.
    </p>
    <p>
      <a href="https://fullpart3d.github.io/">Project</a> |
      <a href="https://arxiv.org/abs/2510.26140">Paper</a> |
      <a href="https://github.com/hkdsc/fullpart">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


<div class="pub-item">
  <img src="../images/paper_teasers/DynamicTree.gif">
  <div class="pub-content">
    <h3>DynamicTree: Interactive Real Tree Animation via Sparse Voxel Spectrum</h3>
    <p>
      <strong><u>Yaokun Li</u></strong>, Lihe Ding, Xiao Chen, Guang Tan, Tianfan Xue<br>
      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We propose DynamicTree, the first framework that can generate long-term, interactive animation of 3D Gaussian Splatting trees.
    </p>
    <p>
      <a href="https://dynamictree-dev.github.io/DynamicTree.github.io/">Project</a> |
      <a href="https://arxiv.org/abs/2510.22213">Paper</a> |
      <a href="https://github.com/Iron-LYK/DynamicTree">Code</a> |
      <a href="https://github.com/Iron-LYK/DynamicTree">Data</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


<div class="pub-item">
  <img src="../images/paper_teasers/copart.gif">
  <div class="pub-content">
    <h3>From One to More: Contextual Part Latents for 3D Generation</h3>
    <p>
      Shaocong Dong*, Lihe Ding*, Xiao Chen, <strong><u>Yaokun Li</u></strong>, Yuxin Wang, Yucheng Wang, Qi Wang, Jaehyeok Kim, Chenjian Gao, Zhanpeng Huang, Zibin Wang, Tianfan Xue†, Dan Xu†<br>
      <strong style="display:inline-block; margin:6px 0;">ICCV 2025</strong>
    </p>
    <p class="pub-desc">
      Copart generates 3d parts from contextual part latents and supports various applications, such as articulation modeling.
    </p>
    <p>
      <a href="https://hkdsc.github.io/project/copart/">Project</a> |
      <a href="https://arxiv.org/abs/2507.08772">Paper</a> |
      <a href="https://github.com/hkdsc/copart">Code</a> |
      <a href="https://huggingface.co/datasets/dscdyc/partverse/tree/main">Data</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/paper_teasers/FDEP.png">
  <div class="pub-content">
    <h3>Rethinking Infrared Small Target Detection: A Foundation-Driven Efficient Paradigm</h3>
    <p>
      Chuang Yu, Jinmiao Zhao, Yunpeng Liu, <strong><u>Yaokun Li</u></strong>, Xiujun Shu, Yuanhao Feng, Bo Wang, Yimian Dai, Xiangyu Yue<br>
      <strong style="display:inline-block; margin:6px 0;">arXiv Preprint, 2025</strong>
    </p>
    <p class="pub-desc">
      We propose FDEP, a foundation-driven efficient paradigm for single-frame infrared small target detection, alongside HSE, a holistic evaluation metric for fair model comparison.
    </p>
    <p>
      <a href="https://arxiv.org/pdf/2512.05511">Paper</a> |
      <a href="https://github.com/YuChuang1205/FDEP-Framework">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


<div class="pub-item">
  <img src="../images/paper_teasers/aaai25.png">
  <div class="pub-content">
    <h3>Exploiting Continuous Motion Clues for Vision-Based Occupancy Prediction</h3>
    <p>
      Haoran Xu, Peixi Peng, Xinyi Zhang, Guang Tan, <strong><u>Yaokun Li</u></strong>, Shuaixian Wang, Luntong Li<br>
      <strong style="display:inline-block; margin:6px 0;">AAAI 2025</strong>
    </p>
    <p class="pub-desc">
    We propose CMOP, a continuous motion-aware occupancy prediction framework that leverages historical propagation and dynamic tracking modules to address object occlusions in real-world scenarios.
    </p>
    <p>
      <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32958">Paper</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/paper_teasers/ID-NeRF.png">
  <div class="pub-content">
    <h3>ID-NeRF: Indirect Diffusion-Guided Neural Radiance Fields for Generalizable View Synthesis</h3>
    <p>
      <strong><u>Yaokun Li</u></strong>, Shuaixian Wang, Guang Tan<br>
      <strong style="display:inline-block; margin:6px 0;">ESWA 2025</strong>
    </p>
    <p class="pub-desc">
    We propose ID-NeRF, a generalizable novel view synthesis framework that addresses sub-optimal reprojected features by indirectly distilling pre-trained diffusion priors into an imaginative latent space for feature refinement.
    </p>
    <p>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S095741742402935X">Paper</a>
    </p>
  </div>
</div>
<hr class="pub-divider">

<div class="pub-item">
  <img src="../images/paper_teasers/pr.png">
  <div class="pub-content">
    <h3>Learning hierarchical uncertainty from hybrid representations for neural active reconstruction</h3>
    <p>
      Shuaixian Wang, <strong><u>Yaokun Li</u></strong>, Chenhui Guo, Guang Tan<br>
      <strong style="display:inline-block; margin:6px 0;">PR 2025</strong>
    </p>
    <p class="pub-desc">
    We propose a neural active reconstruction system that leverages hierarchical uncertainty across hybrid implicit representations to optimize next-best-view planning and high-fidelity 3D reconstruction.
    </p>
    <p>
      <a href="https://www.sciencedirect.com/science/article/pii/S0031320325011562">Paper</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


<div class="pub-item">
  <img src="../images/paper_teasers/CIT.png">
  <div class="pub-content">
    <h3>Cascaded Iterative Transformer for Jointly Predicting Facial Landmark, Occlusion Probability and Head Pose</h3>
    <p>
      <strong><u>Yaokun Li</u></strong>, Guang Tan, Chao Gou<br>
      <strong style="display:inline-block; margin:6px 0;">IJCV 2024</strong>
    </p>
    <p class="pub-desc">
    We propose CIT, a cascaded iterative transformer that explicitly exploits task dependencies for facial analysis, along with MERL-RAV-FLOP, the first dataset providing joint annotations for landmarks, occlusion, and pose.
    </p>
    <p>
      <a href="https://doi.org/10.1007/s11263-023-01935-2">Paper</a> |
      <a href="https://github.com/Iron-LYK/CIT">Code</a>
    </p>
  </div>
</div>
<hr class="pub-divider">


🏆 Awards 
----- 
∙ \(2019\) China National Scholarship<br /> 
∙ \(2020\) Polytechnic Youth Top Ten Students<br /> 
∙ \(2022\) Honorable mention in HACKPKU 2022<br /> 
∙ \(2023\) Third Prize of 2023 "Huawei Cup" National Graduate Student Mathematical Modeling Competition<br /> 




📝 Academic Service 
----- 
Reviewer:<br /> 
∙ Conference Reviewer: CVPR, ECCV, AAAI, ...<br /> 
∙ Journal Reviewer: IJCV, TCSVT, PR, ...<br /> 



📖 Teaching 
----- 
∙ Teaching Assistant: IERG4190-IEMS5707 Multimedia Coding and Processing, CUHK, 2024R2 
∙ Teaching Assistant: ISE3111 Pattern Recognition & Machine Learning, SYSU, 2022 Fall 


😻 My Hobbies
----- 
🏃‍♂️ 🏀 🏋 🎧 📷 ...
