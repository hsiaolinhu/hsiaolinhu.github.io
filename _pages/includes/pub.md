
# 📝 Publications 
## 🎙 Federated Learning Generalization

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/zo-dsgd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stability and Generalization of Zeroth-Order Decentralized Stochastic Gradient Descent with Changing Topology]() \\
**Xiaolin Hu**, Zixuan Gong, Gengze Xu, Wei Liu, Jian Luan, Bin Wang, Yong Liu

<!-- [**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong> -->
  
- This paper provides the first generalization analysis of ZO-DSGD with changing topology.  
- The obtained generalization bounds align with SGD in (strongly) convex cases and with DSGD in non-convex cases.
- The results reflect the impact of client count, sample size, and topology on generalization performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/fl-gen.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalization Bounds for Federated Learning: Fast Rates, Unparticipating Clients and Unbounded Losses](https://openreview.net/forum?id=-EHqoysUYLx) \\
**Xiaolin Hu**, Shaojie Li, Yong Liu

[**Video**](https://www.bilibili.com/video/BV1Wk4y1i7Xv?t=565.5) <strong><span class='show_paper_citations' ></span></strong>

<!-- [**Video**](https://www.bilibili.com/video/BV1Wk4y1i7Xv?t=565.5) <strong><span class='show_paper_citations' data='6CSzbVEAAAAJ:KlAtU1dfN6UC'></span></strong> -->
  
- We present a theoretical analysis of the generalization error for non-participating clients in federated learning.
- The obtained generalization bounds in high probability form capture the performance of a single trial, rather than the average over multiple trials. 
- We derive generalization bounds for heavy-tail losses, applicable to federated learning with unbounded losses, such as cross-entropy. 
</div>
</div>

## 🧑‍🎨 Large Language Models


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/icl-svd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing In-Context Learning with just SVD-Based Pruning: A Theoretical Perspective](https://arxiv.org/abs/2406.03768) \\
Xinhao Yao, **Xiaolin Hu**, Shenzhi Yang, Yong Liu

<!-- [**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong> -->
  
- We show an exciting phenomenon that SVD-based weight pruning can enhance In-Context Learning (ICL) performance. 
- we conduct theoretical analysis by presenting the implicit gradient descent (GD) of ICL and giving generalization bounds of ICL. 
- We further propose a simple, derivative-free algorithm to enhance ICL. Experiments demonstrate its effectiveness.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2025</div><img src='images/pmss.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PMSS: Pretrained Matrices Skeleton Selection for LLM Fine-tuning](https://arxiv.org/abs/2409.16722) \\
Qibin Wang, **Xiaolin Hu**, Weikai Xu, Wei Liu, Jian Luan, Bin Wang

<!-- [**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong> -->

- We propose PMSS, enabling high-rank updates at low costs by selecting skeletons from pre-trained weights.
- PMSS overcomes LoRA’s low-rank limitations and optimizes initialization to utilize semantic and linguistic information.
- Experiments show PMSS outperforms LoRA and excels in tasks like DROP and math reasoning with fewer trainable parameters.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">KDD 2024</div><img src='images/ir-bias.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Retrievers are Biased Towards LLM-Generated Content](https://arxiv.org/abs/2310.20501) \\
Sunhao Dai, Yuqi Zhou, Liang Pang, Weihao Liu, **Xiaolin Hu**, Yong Liu, Xiao Zhang, Gang Wang, Jun Xu

<!-- [**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong> -->

- We explore how LLM-generated texts influence IR systems, revealing a source bias where neural models favor LLM-generated documents.
- We use information theory to explain this bias, showing it arises from the focused semantics of LLM-generated content.
</div>
</div>

## 🧬 AI+Science

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APMC 2020</div><img src='images/waveguide-pinn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Deep Learning Framework for Solving Rectangular Waveguide Problems](https://ieeexplore.ieee.org/document/9331654) \\
**Xiaolin Hu**, Nicholas E. Buri, **APMC 2020** <span style="color:red">(Oral)</span> \| [![](https://img.shields.io/github/stars/xiaulinhu/pinn-pytorch?style=social&label=Code+Stars)](https://github.com/xiaulinhu/pinn-pytorch)

[**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' ></span></strong>
  - We employ Physics Informed Neural Networks (PINNs) to solve rectangular waveguide problems.
  - We successfully apply PINNs to the task of solving electric and magnetic fields, which can be described by partial differential equations (PDEs).
  - We also show the applicability of the framework for predicting the unknown parameters such as wavenumber.
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">档案学研究</div><img src='images/dangan.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- [Transformation of Archival Work in the AI Era: Opportunities, Challenges, and Strategies]() \\
Xiaoting Chen(陈晓婷), Yongjun Xu(徐拥军), Xiaolin Hu(胡啸林) -->

<!-- [**Project**](https://github.com/xiaulinhu/pinn-pytorch) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>  -->
  
<!-- - In collaboration with the School of Information Resource Management at RUC, this study explores the transformation of archival work in the era of AI.
- AI offers diverse applications and scenarios in archival work, significantly enhancing the automation and intelligence across various operational stages.
- AI also poses security risks to archival management, introducing new challenges for archival professionals. It is essential to implement risk regulation measures. -->

<!-- </div>
</div> -->


- ``APMC 2019`` [Capacity Estimation of MIMO Systems via Support Vector Regression](https://ieeexplore.ieee.org/abstract/document/9038838) \\
  **Xiaolin Hu**, Nicholas E. Buri, **APMC 2019** <span style="color:red">(Oral)</span>
  
- ``APMC 2020`` [Multiple Signal DoA Estimation with Unknown Electromagnetic Coupling using Gaussian Process](https://ieeexplore.ieee.org/document/9506234) \\
  Qifeng Wang, Nicholas E. Buris, **Xiaolin Hu**, **APMC 2020**


## 🚍 Others
- ``ICIP 2021`` [3D Grid Transformation Network For Point Cloud Completion](https://ieeexplore.ieee.org/document/9506234) \\
  Xiaobao Deng, **Xiaolin Hu**, Nicholas E. Buris, Ping An, Yilei Chen, **ICIP 2021**
- [Wavelength-tunable Q-switched fiber laser based on a 45 tilted fiber grating](https://www.oejournal.org/article/doi/10.12086/oee.2018.170741?viewType=HTML) \\
  **Xiaolin Hu**, Zhijun Yan, Qianqian Huang, Chuanhang Zou, Tianxing Wang, Chengbo Mou, **Opto-Electronic Engineering 2018**



