---
title: "<center><font size=6>NSNet: Non-saliency Suppression Sampler for Efficient Video Recognition</font></center>"
collection: projects
permalink: /publication/nsnet
excerpt: A sampler with a $4\times$ faster practical speed than SOTA methods.
date: July 2020
venue: ECCV2022 (19.9$\%$ acceptance rate)
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<!-- This paper is about the number 1. The number 2 is left for future work. -->
<!-- <div style="padding-top: 5pt;" class="title" id="lang"> -->
<!-- </div> --> 
<p style="text-align:center;font-size: 15pt;">European Conference on Computer Vision (ECCV) 2022</p>
<div style="text-align:center;font-size: 15pt;"><span>
    <a href="https://lawrencexia2008.github.io" target="_blank">Boyang Xia</a><sup>1</sup>*,&nbsp;&nbsp;
    <a href="https://whwu95.github.io">Wenhao Wu</a><sup>2,3$\dagger$</sup>*,&nbsp;
    <a href="#">Haoran Wang</a><sup>3</sup>,&nbsp;
    <a href="#">Rui Su</a><sup>4</sup>,&nbsp;
    <a href="#">Dongliang He</a><sup>4</sup>,&nbsp;
    <a href="#">Haosen Yang</a><sup>5</sup>,&nbsp;
    <a href="#">Xiaoran Fan</a><sup>1</sup>,&nbsp;
    <a href="https://wlouyang.github.io" target="_blank">Wanli Ouyang</a><sup>4,3</sup>&nbsp;
</span></div>

<!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->

<center>
<sup>1</sup>Institute of Computing Technology &nbsp;
<sup>2</sup>The University of Sydney&nbsp;
<sup>3</sup>Shanghai AI Laboratory <br />
<sup>4</sup>Baidu Inc. &nbsp;
<sup>5</sup>Harbin Institute of Technology
</center>
<div style="text-align:center;font-size: 16pt;"><span>
    <a href="https://lawrencexia2008.github.io/projects/nsnet">Webpage</a> | <a href="https://lawrencexia2008.github.io/projects/nsnet">Paper</a>
</span></div>

<br />
<div align=center>
<img src="../images/projects/nsnet.png" width="700"/>
</div>
<!-- <img src="images/projects/nsnet.png" alt="drawing" width="200"/> -->

To accelerate the video recognition architectures, one typically build a lightweight video key frame sampler to firstly sample a few salient frames and then evoke a recognizer on them, to reduce temporal redundancies. However, existing methods neglect the discrimination between non-salient frames and salient ones in training objectives. We introduced a novel multi-granularity supervision scheme to suppress the non-salient frames and achieved SOTA accuracy with very low GFLOPs and wall-clock time (*$4\times$* faster than SOTA methods) on 4 video recognition benchmarks. 

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->