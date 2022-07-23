---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second-year graduate student at the [Key Lab of Intelligent Information Processing of Chinese Academy of Sciences (CAS),
Institute of Computing Technology, CAS](https://iip.ict.ac.cn/), supervised by [Ke Gao](https://teacher.ucas.ac.cn/~0038308) and [Dongbo Bu](https://people.ucas.edu.cn/~dbu?language=en). Previously, I received my B.E. degree from [Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/bygk/zjby/xxjj.htm) with honors of the Outstanding Bachelor Thesis Award in 2020. I am focusing on artificial intelligence, especially on computer vision and time series analysis. I'm dedicated to developing more robust, efficient and explainable AI models, to pushing them towards practical applications in daily lifes. 

Research & Projects
===
### NSNet: Non-saliency Suppression Sampler for Efficient Video Recognition  
*Accepted by European Conference on Computer Vision 2022 <font color="firebrick">(ECCV'22, 19.9$\%$ acceptance rate).</font>*<br /><font color="red">A sampler with a $4\times$ faster practical speed than SOTA methods.</font>
[<a href="https://arxiv.org/abs/2207.10388" target="_blank">Paper</a>]|[<a href="https://lawrencexia2008.github.io/projects/nsnet" target="_blank">Project</a>]
<!-- During internship in the Computer Vision Technology Department of Baidu. Inc. -->
<!-- <img src="images/projects/nsnet.png" width="500" > -->
<div align=center>
<img src="images/projects/nsnet.png" width="500"/>
</div>
<!-- <img src="images/projects/nsnet.png" alt="drawing" width="200"/> -->
To accelerate the video recognition architectures, one typically build a lightweight video key frame sampler to firstly sample a few salient frames and then evoke a recognizer on them, to reduce temporal redundancies. However, existing methods neglect the discrimination between non-salient frames and salient ones in training objectives. We introduced a novel multi-granularity supervision scheme to suppress the non-salient frames and achieved SOTA accuracy with very low GFLOPs and wall-clock time (*$4\times$* faster than SOTA methods) on 4 video recognition benchmarks. 

### Temporal Saliency Query Network for Efficient Video Recognition
*Accepted by European Conference on Computer Vision 2022 <font color="firebrick">(ECCV'22, 19.9$\%$ acceptance rate).</font>*<br /><font color="red">The first work to model temporal sampling as a query-response task.</font>
[<a href="https://arxiv.org/abs/2207.10379" target="_blank">Paper</a>]|[<a href="https://lawrencexia2008.github.io/projects/tsqnet" target="_blank">Project</a>]
<!-- During internship in the Computer Vision Technology Department of Baidu. Inc. -->
<div align=center>
<img src="images/projects/tsqnet.png" width="600"/>
</div>
A human can precisely elect the most informative frames with the aid of prior knowledge about the probable category
of the video. Inspired by this intuition, we pioneeringly cast frame sampling as a query-response task to introduce category prior knowledge from both visual and textual modalities in temporal sampling framework. Experimental results show the efficacy of our method on both and practical speed.

### Time Series Anomaly Detection with Memory-Enhanced Composite Neural Networks
*Technical report.*
<br /><font color="red">An effective framework for multivariate unsupervised time series anomaly detection.</font>
[<a href="https://lawrencexia.github.io/files/time_series.pdf" target="_blank">Paper</a>]|[<a href="https://github.com/anomalydetector/MCCED" target="_blank">code</a>]
<!-- During internship in the Computer Vision Technology Department of Baidu. Inc. -->
<div align=center>
<img src="images/projects/timeseries.png" width="300"/>
</div>
Low discrimination between normal and abnormal data is an important challenge for reconstruction based unsupervised anomaly detection methods. This is because model learns trivial patterns brought by sensor noise in training data inevitably. We solve this problem by a memory mechanism, where non-trivial normal patterns are stored in a memory matrix and time series representation are cleaned after attentional memory addressing. Extensive experiments on two industrial control systems (ICS) cybersecurity datasets demonstrate the effectiveness of our approach.

Undergraduate Works
===
### Subtle Appearance Anomaly Detection Based on Deep Learning
*With the honors of <font color="firebrick">Outstanding Bachelor Thesis Award (Top 2$\%$)</font>  in 2020.*<br /><font color="red">A weakly-supervised product counterfeit detection framework with 70$\%+$ annotation savings.</font>
<div align=center>
<!-- <img src="images/projects/bishe.png" width="450" height="200"/><img src="images/projects/secoo.jpg" width="160" height="230"/> -->
<img src="images/projects/bishe.png" align="center" width="450" style="display:inline;margin:10px 10px 10px 10px;"/><img src="images/projects/secoo.jpg" align="center" width="155" style="display:inline;margin:2px 2px 2px 5px;"/>
</div>
An efficient and effective framework for product counterfeit detection based on learnable informative region crop. It is notesworthy that the framework only use image-level annotations, without region-level annotions.

Competitions
===
### Contest of Automatic Identification of Butterflies In the Wild in 2020  
*Object detection task, with small-object, longtail and occlusion challenges.*  
CCF $\times$ BCDI  
Rank <font color="Red">3/1004</font>

### POI Name Generation Contest in 2021  
*Text generation with multimodality (image and text) information.*  
CCF $\times$ Amap. Inc.  
Rank <font color="Red">3/1107</font>

### Global AI Innovation Contest in 2022
*Image-text matching of key attributes of e-commerce.*  
Chinese Association of Artificial Intelligence $\times$ JD.COM    
Rank <font color="Red">7/1300+</font>

Publications
===
1. **Boyang Xia**, et al. NSNet: Non-saliency Suppression Sampler for Efficient Video Recognition (Accepted by ECCV'2022)
2. **Boyang Xia**, et al. Temporal Saliency Query Network for Efficient Video Recognition (Accepted by ECCV'2022)
3. Li, L., Gao, K., Cao, J., Huang, Z., Weng, Y., Mi, X., ... & **Xia, B**. Progressive Domain Expansion Network 
for Single Domain Generalization. (Accepted by CVPR'2021)
4. Yang, H., Wu, W., Wang, L., Jin, S., **Xia, B.**, Yao, H., & Huang, H. Temporal Action Proposal 
Generation with Background Constraint (Accepted by AAAI'2022)
5. Wang, H., He, D., Wu, W., **Xia, B.**, Yang, M., Li, F., Yu, Y., Ji, Z., Ding, E., Wang, J. CODER: Coupled Diversity-Sensitive Momentum Contrastive Learning for Image-Text Retrieval (Accepted by ECCV'2022)
6. **Xia B Y**, Cao C, Han Y H, et al. Universal photonic three-qubit quantum gates with two degrees of 
freedom assisted by charged quantum dots inside single-sided optical microcavities. (Published in Laser Physics, 2018 (SCI District 3))


