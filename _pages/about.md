---
permalink: /
title: "About Me"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second-year graduate student at the [Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)](http://www.ict.cas.cn/jssgk/jssjj/), supervised by [Ke Gao](https://teacher.ucas.ac.cn/~0038308). Previously, I received my B.E. degree from [Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/bygk/zjby/xxjj.htm) with honors of the Outstanding Bachelor Thesis Award in 2020. I am focusing on computer vision, especially on video understanding and multimodality learning. I'm dedicated to developing more robust, efficient and explainable AI models, to pushing them towards practical applications in daily lifes. 

Research & Projects
===
### Multi-granularity Video Frame Sampler for Efficient Video Recognition  
<!-- During internship in the Computer Vision Technology Department of Baidu. Inc. -->
A sampler with a *<font color="Red">$4\times$ faster</font> practical speed than SOTA methods.*
<!-- <img src="images/projects/nsnet.png" width="500" > -->
<div align=center>
<img src="images/projects/nsnet.png" width="500"/>
</div>
<!-- <img src="images/projects/nsnet.png" alt="drawing" width="200"/> -->
To accelerate the video recognition architectures, one typically build a lightweight video key frame sampler to firstly sample a few salient frames and then evoke a recognizer on them, to reduce temporal redundancies. However, existing methods neglect the discrimination between non-salient frames and salient ones in training objectives. We introduced a novel multi-granularity supervision scheme to suppress the non-salient frames and achieved SOTA accuracy with very low GFLOPs and wall-clock time (*$4\times$* faster than SOTA methods) on 4 video recognition benchmarks. 

### Multi-modal Video Frame Sampler for Efficient Video Recognition
<!-- During internship in the Computer Vision Technology Department of Baidu. Inc. -->
*The <font color="Red">first work</font> to introduce multimodal prior knowledge to temporal sampling frameworks.*
<div align=center>
<img src="images/projects/tsqnet.png" width="600"/>
</div>
A human can precisely elect the most informative frames with the aid of prior knowledge about the probable category
of the video. Inspired by this intuition, we pioneeringly cast frame sampling as a query-response task to introduce category prior knowledge from both visual and textual modalities in temporal sampling framework. Experimental results show the efficacy of our method on both and practical speed.

Undergraduate Works
===
### Subtle Appearance Anomaly Detection Based on Deep Learning
A weakly-supervised product counterfeit detection framework with <font color="Red">70$\%+$</font> annotation savings, appeared as Outstanding Bachelor Thesis Award.  
<div align=center>
<!-- <img src="images/projects/bishe.png" width="450" height="200"/><img src="images/projects/secoo.jpg" width="160" height="230"/> -->
<img src="images/projects/bishe.png" align="center" width="450" style="display:inline;margin:10px 10px 10px 10px;"/><img src="images/projects/secoo.jpg" align="center" width="155" style="display:inline;margin:2px 2px 2px 5px;"/>
</div>
An efficient and effective framework for product counterfeit detection based on learnable informative region crop. It is notesworthy that the framework only use image-level annotations, without region-level annotions. This work won the honors of the Outstanding Bachelor Thesis Award of BUPT in 2020.

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
1. **Boyang Xia**, et al. NSNet: Non-saliency Suppression Sampler for Efficient Video Recognition (Accepted by ECCV22)
2. **Boyang Xia**, et al. Temporal Saliency Query Network for Efficient Video Recognition (Accepted by ECCV22)
3. Li, L., Gao, K., Cao, J., Huang, Z., Weng, Y., Mi, X., ... & **Xia, B**. (2021). Progressive Domain Expansion Network 
for Single Domain Generalization. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern 
Recognition (pp. 224-233).
4. Yang, H., Wu, W., Wang, L., Jin, S., **Xia, B.**, Yao, H., & Huang, H. (2021) Temporal Action Proposal 
Generation with Background Constraint (Accepted by AAAI2022)
5. **Xia B Y**, Cao C, Han Y H, et al. Universal photonic three-qubit quantum gates with two degrees of 
freedom assisted by charged quantum dots inside single-sided optical microcavities[J]. Laser Physics, 
2018, 28(9): 095201.


