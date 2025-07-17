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

I am currently a visiting student at ShanghaiTech University, conducting research in the [AMNR group](https://www.amnrlab.org/) under the joint supervision of [Prof. Song Liu](https://sist.shanghaitech.edu.cn/liusong/main.htm), who is expert in the field of ultrasonic robotics, micro/nano robotics in the ShanghaiTech Automation and Robotics Center, and [Prof. Hu Su](https://people.ucas.edu.cn/~suhu), who is expert in the field of machine vision, robotic control and non-contact manipulation Institute of Automation, Chinese Academy of Sciences). I received my B.E. degree from Chongqing University of Posts and Telecommunications, advised by [Prof. Jun Liu](https://faculty.cqupt.edu.cn/junliu/zh_CN/index.htm), who is expert in the field of computer vision, blockchain, and big data security.

## Research interests

My research interests include computer vision, embodied intelligence, and multimodal large models. My earlier work focused on low-level vision tasks (e.g., low-light image enhancement), while my current research explores 3D reconstruction and embodied intelligence.


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/paper/LMV.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  Real-time Tear Film Break-up Measurement Based on Multi-task Collaborative System for Dry Eye Instrument (under revirew)

  **Guangrong Wan**, Jun Liu, Tang Tang, Lianghao Shi

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/paper/mtk.webp' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  A Novel Multi-modal Sentiment Analysis Based on Multiple Kernel Learning with Margin-Dimension Constraint

  Jun Liu, Zhihao Wang, **Guangrong Wan**, Jianbo Liu 

  [**Paper**](https://link.springer.com/article/10.1007/s44196-024-00624-3)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/paper/tf_review.jpg' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  A Review of Dry Eye Detection Algorithms Based on Computer Vision

  Jun Liu, Zhi Zhang, **Guangrong Wan**, Mingwei Lin

  [**Paper**](https://kns.cnki.net/kcms2/article/abstract?v=-f9lWFCLl9Borcrte8UiKJjWGMr-2AARVYXfLd9WG-8o6gADUTyUp8xBVy2cWGCdgqhrqKr1YH-6sEbN8Tz7uRGy9hA2LbLCeHWuJiLhn2AsNUqv4wpvcdXncQRM2K8YN9l0wYHFBJN2dseALLcSNCDfT4VuDBWLYWNuP1k8Z4A=&uniplatform=NZKPT)

  </div>
</div>



# 🎖 Project
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/project/LLIELib.webp' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **LLIE Library** [**Code**](https://github.com/glory-wan/LLIE-Lib)

  A Python library that integrates multiple traditional low-light enhancement methods, written in Pytorch, is a flexible and expandable Python library that integrates traditional low-light enhancement methods.
  - Currently supported algorithms include: HE series (HE/CLAHE/RCLAHE), gamma correction, log transformation, DarkChannel...
  - The currently supported color Spaces include: RGB, HSV, HLS, LAB, and YUV
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/project/LLIEWeb.webp' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **LLIE Web** [**Code**](https://github.com/glory-wan/LLIE-web)

  Low-illumination image enhancement algorithm platform developed based on LLIE Lib.
  A visual user interface for low-light image enhancement algorithms is provided by using the java backend and VUE, and it is deployed and launched on Alibaba Cloud servers.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/project/project2.webp' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **face detection and tracking** [**Code**](https://github.com/glory-wan/face-detection-and-tracking)

  Face/object recognition and tracking are achieved by using Dlib and haar cascaded classifiers.
  - The supported models include: frontal_face_detector, face_landmarks, haarcascade series...
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/project/tobacco.webp' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  **Tobacco Recognition** [**Code**](https://github.com/glory-wan/face-detection-and-tracking)

  A cloud-based tobacco recognition interface implemented based on Ultralytics and Django.
  The tobacco recognition interface was implemented by jointly using the Django framework and the API of Ultralytics. Finally, it was deployed to the cloud using the Alibaba Cloud ESC server.

  - It has now been taken over by the Chongqing Tobacco Bureau Corporation and actual business cooperation has begun
  </div>
</div>

# 📖 Educations
- *2021.09 - 2025.06*, Undergraduate, Chongqing University of Posts and Telecommunications

# 💻 Internship
- *2025.03 - Present*, Visiting Student, Automation and Robotics Centerm, ShanghaiTech University.
- *2021.09 - 2025.03*, Laboratory Member, Engineering Laboratory of Network and Information Security Chongqing.



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

