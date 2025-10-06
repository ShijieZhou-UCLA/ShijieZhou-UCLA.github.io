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

<p style="text-align: justify;">
I am a final-year Ph.D. candidate in Electrical and Computer Engineering at University of California, Los Angeles (UCLA), gratefully advised by <a href="https://samueli.ucla.edu/people/achuta-kadambi/">Prof. Achuta Kadambi</a>. Previously, I obtained my M.S. in Electrical Engineering from Columbia University in 2021, where I was fortunate to be advised by <a href="https://www.columbia.edu/~jw2966/">Prof. John Wright</a>. I received my B.E. in Electronic Information Engineering from University of Electronic Science and Technology of China (UESTC) in 2019.
</p>

<!-- My research interests include 3D computer vision, vision language models and generative AI. Currently, my research focuses on exploring spatial intelligence, including 3D/4D scene reconstruction (Gaussian Splatting), generation (diffusion models), understanding (vision foundation models), reasoning (vision language models), and interaction (agentic AI). -->
<!-- My research focuses on 3D computer vision and multimodal generative AI, especially advancing world models with spatial intelligence to integrate geometry, semantics, and dynamics. My work spans 3D/4D scene reconstruction (Gaussian Splatting), generation (diffusion models), understanding (vision foundation models), reasoning (vision language models), and interaction (agentic AI) in real-world environments. -->
<p style="text-align: justify;">
My research focuses on 3D computer vision and multimodal generative modeling, advancing world models with spatial intelligence that integrate geometry, semantics, dynamics, and interactivity. My recent work extends visual reconstruction, generation, and reasoning from 2D into the 3D/4D domain, enabling physically grounded spatial intelligence through coherent scene representation and multimodal modeling for applications in mixed reality, robotics, and agentic AI.
During my Ph.D., I also had the privilege of collaborating with <a href="https://profiles.stanford.edu/leonidas-guibas">Prof. Leonidas Guibas</a> at Stanford University and <a href="https://www.ece.utexas.edu/people/faculty/atlas-wang">Prof. Atlas Wang</a> at the University of Texas at Austin.

<!-- During my PhD, I was also actively working with <a href="https://profiles.stanford.edu/leonidas-guibas">Prof. Leonidas Guibas</a> at Stanford University and <a href="https://www.ece.utexas.edu/people/faculty/atlas-wang">Prof. Atlas Wang</a> at University of Texas at Austin. -->
</p>

<!-- I am currently a Research Intern at <img src="images/Apple.svg" alt="Apple" style="height: 15px; margin-bottom: 6px;"/> Apple, and I was a Student Researcher at <img src="images/Google_logo.png" alt="Google" style="height: 18px;"/> in 2024. 
<!-- <span style="color: red;">I am actively seeking full-time research scientist opportunities starting in 2026 :)</span> -->
<!-- **I will be on the job market and actively seeking full-time research scientist/engineer opportunities starting in 2026.** --> 
<!-- I am currently a Research Intern at <img src="images/Apple.svg" alt="Apple" style="height: 15px; margin-bottom: 6px;"/> Apple, and I was a Student Researcher at <img src="images/Google_logo.png" alt="Google" style="height:18px; vertical-align:middle;"/> in 2024.  -->

<p style="text-align: justify;">
I am currently a Research Intern at <img src="images/Apple.svg" alt="Apple" style="height: 15px; margin-bottom: 6px;"/> Apple, was a Student Researcher at <img src="images/Google_logo.png" alt="Google" style="height:18px; vertical-align:middle;"/> in 2024, and led a research collaboration with <a href="https://www.microsoft.com/en-us/research/publication/vlm4d-towards-spatiotemporal-awareness-in-vision-language-models/" target="_blank"><img src="images/microsoft.png" alt="Microsoft" style="height: 18px; margin-bottom: 3px;"/></a> in 2025. <strong style="color: red;">I am on the job market and actively seeking full-time research scientist/engineer opportunities starting in 2026.</strong>
</p>

# 🔥 News
- *2025.06*: One paper accepted to ICCV 2025.
- *2025.05*: Awarded Dissertation Year Award from UCLA.
- *2025.04*: [X-Dyna](https://x-dyna.github.io/xdyna.github.io/) was selected as a Highlight paper at CVPR 2025 (2.98% of 13008 submissions)! 🎉 
- *2025.02*: Two papers accepted to CVPR 2025.
- *2025.02*: [4K4DGen](https://4k4dgen.github.io/) (4D version of [DreamScene360](https://dreamscene360.github.io/)) was selected as a Spotlight at ICLR 2025 (5.1% of 11565 submissions)! 🎉 
- *2025.01*: One paper accepted to ICLR 2025.
- *2024.10*: Awarded J.B. Fourier Scholar in Vision and Graphics from UCLA.
- *2024.09*: One paper accepted to NeurIPS 2024.
- *2024.07*: One paper accepted to ECCV 2024.
- *2024.04*: [Feature 3DGS](https://feature-3dgs.github.io/) was selected as a Highlight paper at CVPR 2024 (2.8% of 11532 submissions)! 🎉 
- *2024.02*: One paper accepted to CVPR 2024.
- *2023.02*: One paper accepted to CVPR 2023. 
- *2021.09*: Awarded Graduate Dean's Scholar Award from UCLA.
- *2020.06*: Awarded MS Honors Student from Columbia University.

# 📝 Selected Publications
\* indicates equal contribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/vlm4d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## VLM4D: Towards Spatiotemporal Awareness in Vision Language Models

**Shijie Zhou**\*, Alexander Vilesov\*, Xuehai He\*, Ziyu Wan, Shuwang Zhang, Aditya Nagachandra, Di Chang, Dongdong Chen, Xin Eric Wang, Achuta Kadambi

[**Paper**](https://www.arxiv.org/pdf/2508.02095) | [**Project**](https://vlm4d.github.io/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose the first benchmark explicitly designed to rigorously evaluate the spatiotemporal reasoning capabilities of Vision-Language Models (VLMs).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/feature4x.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Feature4X: Bridging Any Monocular Video to 4D Agentic AI with Versatile Gaussian Feature Fields

**Shijie Zhou**\*, Hui Ren\*, Yijia Weng, Shuwang Zhang, Zhen Wang, Dejia Xu, Zhiwen Fan, Suya You, Zhangyang Wang, Leonidas Guibas, Achuta Kadambi

[**Paper**](https://arxiv.org/pdf/2503.20776) | [**Project**](https://feature4x.github.io/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Building 4D interactive scenes with agentic AI from monocular videos, by dynamically distilling model-conditioned
features and integrating 2D foundation models with LLMs in feedback loops.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/dreamscene360.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting

**Shijie Zhou**\*, Zhiwen Fan\*, Dejia Xu\*, Haoran Chang, Pradyumna Chari, Tejas Bharadwaj, Suya You, Zhangyang Wang, Achuta Kadambi

[**Paper**](https://arxiv.org/pdf/2404.06903.pdf) | [**Project**](https://dreamscene360.github.io/)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We introduce a 3D scene generation pipeline that creates immersive scenes with full 360$^{\circ}$ coverage from text prompts of any level of specificity.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/feature_3dgs_teaser.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Feature 3DGS: Supercharging 3D Gaussian Splatting to Enable Distilled Feature Fields

**Shijie Zhou**, Haoran Chang\*, Sicheng Jiang\*, Zhiwen Fan, Zehao Zhu, Dejia Xu, Pradyumna Chari, Suya You, Zhangyang Wang, Achuta Kadambi

[**Paper**](https://arxiv.org/pdf/2312.03203.pdf) | [**Project**](https://feature-3dgs.github.io/) (<span style="color: red;">CVPR 2024 Highlight</span>)<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Feature 3DGS 🪄, distills feature fields from 2D foundation models, opening the door to a brand new semantic, editable, and promptable explicit 3D scene representation.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/alto.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## ALTO: Alternating Latent Topologies for Implicit 3D Reconstruction

Zhen Wang\*, **Shijie Zhou**\*, Jeong Joon Park, Despoina Paschalidou, Suya You, Gordon Wetzstein, Leonidas Guibas, Achuta Kadambi

[**Paper**](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_ALTO_Alternating_Latent_Topologies_for_Implicit_3D_Reconstruction_CVPR_2023_paper.pdf) | [**Project**](https://visual.ee.ucla.edu/alto.htm/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Rethinking latent topologies for fast and detailed implicit 3D reconstructions.
</div>
</div>

<li>
  <span style="background-color:#0036A0; color:white; padding:3px 5px; border-radius:0px; font-size: 0.75em; font-weight:bold; margin-right:6px;">
    ICLR 2025
  </span>
  <strong><a href="https://4k4dgen.github.io/" target="_blank" style="text-decoration: none; color:black;">
  4K4DGen: Panoramic 4D Generation at 4K Resolution,
  </a></strong>
  Renjie Li, Panwang Pan, Bangbang Yang, Dejia Xu, <strong>Shijie Zhou</strong>, Xuanyang Zhang, Zeming Li, Achuta Kadambi, Zhangyang Wang, Zhengzhong Tu, Zhiwen Fan (<span style="color: red;">Spotlight</span>)
</li>

<li>
  <span style="background-color:#0036A0; color:white; padding:3px 2.9px; border-radius:0px; font-size: 0.75em; font-weight:bold; margin-right:6px;">
    CVPR 2025
  </span>
  <strong><a href="https://x-dyna.github.io/xdyna.github.io/" target="_blank" style="text-decoration: none; color:black;">
  X-Dyna: Expressive Dynamic Human Image Animation,
  </a></strong>
  Di Chang, Hongyi Xu, You Xie, Yipeng Gao, Zhengfei Kuang, Shengqu Cai, Chenxu Zhang, Guoxian Song, Chao Wang, Yichun Shi, Zeyuan Chen, <strong>Shijie Zhou</strong>, Linjie Luo, Gordon Wetzstein, Mohammad Soleymani (<span style="color: red;">Highlight</span>)
</li>

<li>
  <span style="background-color:#0036A0; color:white; padding:3px 2.9px; border-radius:0px; font-size: 0.75em; font-weight:bold; margin-right:6px;">
  NeurIPS 2024
  </span>
  <strong><a href="https://largespatialmodel.github.io/" target="_blank" style="text-decoration: none; color:black;">
  Large Spatial Model: End-to-end Unposed Images to Semantic 3D,
  </a></strong>
  Zhiwen Fan, Jian Zhang, Wenyan Cong, Peihao Wang, Renjie Li, Kairun Wen, <strong>Shijie Zhou</strong>, Achuta Kadambi, Zhangyang Wang, Danfei Xu, Boris Ivanovic, Marco Pavone, Yue Wang
</li>

# 🎖 Honors and Awards
- *2025* Dissertation Year Award, UCLA
- *2024* J.B. Fourier Scholar in Vision and Graphics, UCLA
- *2021* Graduate Dean’s Scholar Award, UCLA
- *2020* MS Honors Student, Columbia University
- *2019* Outstanding Graduate, University of Electronic Science and Technology of China
- *2018* James Watt Scholar, University of Glasgow

# 💻 Work Experience
- *2025.04 - now*, Research Intern at <img src="images/Apple.svg" alt="Apple" style="height: 15px; margin-bottom: 6px;"/> Apple
- *2024.06 - 2024.11*, Student Researcher at <img src="images/Google_logo.png" alt="Google" style="height: 18px;"/> 
- *2023.06 - 2023.09*, Visiting Academic at USC Institute for Creative Technologies

# 📖 Teaching
- Teaching Assistant @ UCLA: ECE188 Computer Vision, ECE113 Digital Signal Processing 
- Teaching Assistant @ Columbia: EECS6690 Statistical Learning, ELEN6885 Reinforcement Learning
- Teaching Assistant @ UoG & UESTC: 1008 Microelectronic Systems, 3010 Team Design Project and Skills

# 🖋️ Service
- Conference Reviewer: <br>
  SIGGRAPH 2025, SIGGRAPH Asia 2025, CVPR 2025, ICCV 2025, ECCV 2024, NeurIPS 2025/2024, ICLR 2025, ICML 2025, 3DV 2025
- Journal Reviewer: <br>
  International Journal of Computer Vision, IEEE Transactions on Image Processing, IEEE Transactions on Multimedia, Pattern Recognition
- Workshop Reviewer: <br>
  End-to-End 3D Learning @ ICCV 2025, AI for 3D Generation @ CVPR 2024, AI for 3D Content Creation @ ICCV 2023