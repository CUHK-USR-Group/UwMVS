---
permalink: /
title: ""
excerpt: "About the paper"
author_profile: false
redirect_from:
    /about/
    /about.html
---

<h1 style="text-align: center; font-size: 36px; font-family: 'system-ui';">End-to-End Underwater Multi-View Stereo for Dense Scene Reconstruction</h1>
<h2  style="text-align: center; font-size: 18px; font-family: 'Sama Devanagari';">
    Submitted to 2024 IEEE International Conference on Robotics and Automation
</h2>
<div style=" text-align: center; font-size: 17px;">
Guidong Yang†, Junjie Wen†, Benyun Zhao, Qingxiang Li, Yijun Huang, <br> Xi Chen, Alan Lam, and Ben M. Chen∗
</div>
<div  style="text-align: center; font-size: 17px;" >
The Chinese University of Hong Kong, Hong Kong SAR, China

</div>
<div style="display: flex; flex-direction: row; margin: 10px auto; justify-content: center"> 

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px;border: none; border-radius: 5px;">
<a href="../files/End-to-End Underwater Multi-View Stereo for Dense Scene Reconstruction.pdf" style="color: white; text-decoration: none;">Paper</a>
</button>

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px; border: none; border-radius: 5px;">
<a href="https://github.com/CUHK-USR-Group/UW-MVS" style="color: white; text-decoration: none;">Code</a>
</button>

<button style="background-color: #000000; color: white;margin-right: 15px; padding: 10px 15px; border: none; border-radius: 5px;">
<a href="../files/Appendix_End-to-End Underwater Multi-View Stereo for Dense Scene Reconstruction.pdf" style="color: white; text-decoration: none;">Appendix</a>
</button>

</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Abstract</h2>
</div>
<div style="text-align: justify; text-justify:inter-ideograph;">

Multi-view stereo (MVS) has been widely used for 3D reconstruction in various applications. However, existing MVS methods often struggle in underwater environments due to the unique challenges posed by water, such as light attenuation, scattering, and color distortion. In this paper, we propose an end-to-end underwater MVS framework that addresses these challenges and achieves dense scene reconstruction in underwater environments. Our framework consists of three main components: (1) an <b>underwater image enhancement module</b> that restores the degraded underwater images, (2) a <b>multi-scale feature extraction and matching module</b> that captures both local and global information for robust feature correspondence, and (3) a <b>depth map refinement module</b> that improves the accuracy and consistency of the reconstructed 3D model. We evaluate our method on both synthetic and real-world underwater datasets, demonstrating its superior performance compared to state-of-the-art MVS methods in terms of reconstruction accuracy and completeness. Furthermore, we showcase the practical applications of our framework in underwater archaeology and marine ecosystem monitoring.

</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Proposed Method</h2>
</div>

<div class="image-container"  style="margin: 40px auto; text-align: center; font-weight: 400;">
    <img src="images/workflow.png" alt="" width="100%">
<div style="text-align: justify; font-size: 14px;  text-justify:inter-ideograph;">
<p style="text-align: justify; font-size: 14px;  text-justify:inter-ideograph;">
Overview of our proposed end-to-end underwater MVS framework. The framework consists of three main components: (1) <b>Underwater Image Enhancement Module</b>, which restores the degraded underwater images; (2) <b>Multi-scale Feature Extraction and Matching Module</b>, which captures both local and global information for robust feature correspondence; and (3) <b>Depth Map Refinement Module</b>, which improves the accuracy and consistency of the reconstructed 3D model.</p>
</div>
</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Demo Video</h2>
</div>

<div style="text-align: center;">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

<div style="text-align: center; font-family: 'American Typewriter'; font-weight: 400; "> 
<h2>Acknowledgements</h2>
</div>

<div style="text-align: justify">This work was supported by the InnoHK of the Government of the Hong Kong Special Administrative Region via the Hong Kong Centre for Logistics Robotics.
<br> <br>
We sincerely thank all the ICRA reviewers for their time and efforts.
</div>
